HAproxy 1.5 RPM
===============

This is an RPM for building HAproxy 1.5 on EL6 systems. This RPM is based on 
the Fedora 17 SPEC from the Fedora project, retrieved on July 11th 2013

http://pkgs.fedoraproject.org/cgit/haproxy.git/log/?h=f17

This SPEC file builds OpenSSL 1.0.1e and then staticly links HAproxy 1.5 
against it. This gives us some of the newer OpenSSL features such as NPN and 
TLS 1.2 which are not availible in the stock Enterprise Linux RPMs.

License
=======

This code is licensed under the MIT license per the Fedora default licensing 
agreement that is outlined below

https://fedoraproject.org/wiki/Licensing:Main?rd=Licensing#License_of_Fedora_SPEC_Files
