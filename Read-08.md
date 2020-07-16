"The past present and future of Local Storage for Web Applications"
    -Persistent local storage is one of the area where native client applications have held an advantage over web applications.
    -Potentially dealbreaking downsides to cookies are: cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your enture web application is served over SSl) . Cookies are limited to about 4 KB of data, enough to slow down your application (see above), but not enough to be terribly useful
    - We really want a lot of storage space, on the client, that persists beyond a page refresh and isn't transmitted to the server
    -Before HTML 5 all attemps to solve the cookie problem were unsatisfactory.
    -HTML 5 storage is a specification named Web storage. It is also known as local storage or DOM storage.
    -HTML 5 storage is a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies this data persists even after you navigate away from the web site, or close your browser tab. 
    -Unlike cookies this data is never transmitted to the remote web server.
    -The latest version of pretty much every browser supports HTML 5 storage, even internet explorer.
    -HTML 5 storage is based on named key/value pairs, you store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by javascript, including strings, Booleans, integers or floats. However the data is actually stored as a string. If you are storing and retreiving anything other than strings you will need to use functions like parseInt or parseFloat to coerce your retrieved data into the expected JavaScript datatype.
    -If you want to keep track programatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem removeItem or clear is called and actually changes something.
    -The storage event is supported everywhere the localStorage object is supported, which includes internet explorer 8.
    