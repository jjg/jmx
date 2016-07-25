# jmx
JSFS media extensions

#API
#GET
`GET` requests will attempt to return the resource at the requested URL in the media format specified by the `Accept` header.  If the requested format cannot be returned, an `HTTP 406` status is returned with a `Content-Type` of `text/html` and a text body describing what (if anything) can be done to allow the server to deliver the requested type.

#Supported Media Types
* `audio/mpeg`
* `audio/ogg`
* `audio/opus`
