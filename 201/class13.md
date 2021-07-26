## Local Storage

***Persistent local storage is one of the areas where native client applications have held an advantage over web applications.***

For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. 

**These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.**


1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over  
2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)


What we really want is

 - a lot of storage space
 - on the client
 - that persists beyond a page refresh
 - and isn’t transmitted to the server


**So what is HTML5 Storage?** Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser.
Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.



### HTML Web Storage Objects
HTML web storage provides two objects for storing data on the client:  

1. window.localStorage - stores data with no expiration date
2. window.sessionStorage - stores data for one session (data is lost when the browser tab is closed) ### Before using web storage, check browser support for localStorage and sessionStorage:


```
if (typeof(Storage) !== "undefined") {
  // Code for localStorage/sessionStorage.
} else {
  // Sorry! No Web Storage support..
}
```