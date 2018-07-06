# s2i-netcat
s2i-netcat
It tests source-to-build feature for Open Shift
https://blog.openshift.com/create-s2i-builder-image/

Instead of using a specific service, this image leverages netcat to listen on port 8080:

nc -l 8080
