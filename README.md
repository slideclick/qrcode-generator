qrcode-generator
================
1. copy jar to here
2. qrcode-generator\src\main\java\com\github\qrcode>javac -cp ".;qrcode-1.0.jar" *.java
3.You can't run at this dir SINCE code is in package: package com.github.qrcode
4. go to DIR where com.github in, copy jar to here
5.java -cp ".;qrcode-1.0.jar" com.github.qrcode.QrcodeGenerator
if Linux:  /java$ java -cp ".:qrcode-1.0.jar" com.github.qrcode.QrcodeGenerator

你如果加压那个jar文件，你到它的com的父目录里面去运行，不需要写-cp因为自带了org和google的库


[![Maven Central](https://img.shields.io/maven-central/v/com.github.javadev/qrcode-generator.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.github.javadev%22%20AND%20a%3A%22qrcode-generator%22)

The java/swing application to generate QR codes

[![Screen short](https://raw.github.com/javadev/qrcode-generator/master/qrcode.png)](https://github.com/javadev/qrcode-generator/)
