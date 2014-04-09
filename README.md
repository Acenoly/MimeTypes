Apache Mime Types and Extensions
================================

A text template to generate a static class with access to the mime types and extensions provided by
[The Apache Software Foundation](http://www.apache.org)
found at <http://svn.apache.org/repos/asf/httpd/httpd/trunk/docs/conf/mime.types>

###Apache's Header Information 
This file maps Internet media types to unique file extension(s).
Although created for httpd, this file is used by many software systems
and has been placed in the public domain for unlimited redisribution.

The table below contains both registered and (common) unregistered types.
A type that has no unique extension can be ignored -- they are listed
here to guide configurations toward known types and to make it easier to
identify "new" types.  File extensions are also commonly used to indicate
content languages and encodings, so choose them carefully.

Internet media types should be registered as described in RFC 4288.
The registry is at <http://www.iana.org/assignments/media-types/>.

####Other Projects 
Particularly inspired by <https://github.com/cymen/ApacheMimeTypesToDotNet>

TODO: Extend usage based on <https://github.com/broofa/node-mime>
