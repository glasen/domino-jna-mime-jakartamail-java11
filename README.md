# Domino JNA for Java 11 - Mime-Module with Jakarta Mail as dependency

This is a fork of Karsten Lehmann brilliant Java-library "Domino JNA":

https://github.com/klehmann/domino-jna

I've using this library in my company for quite a while in a data processing pipeline. I've "ported" the library to Java 11 (Mainly by providing Glassfish CORBA which is needed for Java 11).
I also cleaned up the code (I only forked the directory "domino-jna") a little bit and ported it from Maven to Gradle.

Contains a copy of Apache Commons Email moved to the package "com.mindoo.domino.jna.mime.internal.jakarta"
to avoid classloader conflicts.
Apache Commons Email has also been tweaked to work with the new jakarta.mail instead of javax.mail.

https://commons.apache.org/proper/commons-email/

Copyright The Apache Software Foundation
Apache 2.0 license
