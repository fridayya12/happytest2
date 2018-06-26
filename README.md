wat can i do if this error appears .

Preferred mode unavailable. Using binary translation instead.

This host supports Intel VT-x, but Intel VT-x is disabled.

Intel VT-x might be disabled if it has been disabled in the BIOS/firmware settings or the host has not been power-cycled since changing this setting.

(1) Verify that the BIOS/firmware settings enable Intel VT-x and disable 'trusted execution.'

(2) Power-cycle the host if either of these BIOS/firmware settings have been changed.

(3) Power-cycle the host if you have not done so since installing VMware Workstation.

(4) Update the host's BIOS/firmware to the latest version.





and then............


msgpack for C/C++ Version 3.0.0 Build Status Build status

It's like JSON but smaller and faster.

Overview MessagePack is an efficient binary serialization format, which lets you exchange data among multiple languages like JSON, except that it's faster and smaller. Small integers are encoded into a single byte and short strings require only one extra byte in addition to the strings themselves.

Features TCPConnection TCPServer

Usage
co { do { // create an echo server on localhost:8080 //let server = try TCPServer(host:"xhttp://192.168.70.149/main/", port: 8080) //let server = try TCPServer(host:"xhttp://139.99.16.161/main/", port: 8080) //let server = try TCPServer(host:"xhttp://192.168.70.150/main/", port: 8080) while true { // waits for an incoming connection, receives 1024 bytes, sends them back let connection = try server.accept() let data = try connection.receive(upTo: 1024) try connection.send(data) } } catch { print(error) } }

nap(for: 100.milliseconds)

// create a connection to server at localhost:8080 let connection = try TCPConnection(host: "0.0.0.0", port: 8080) // opens the connection, sends "hello" try connection.open() try connection.send("hello") // waits for a message, prints it out let data = try connection.receive(upTo: 1024) print(data) Installation import PackageDescription

let package = Package( dependencies: [ .Package(url: "https://github.com/VeniceX/Zewo.git", majorVersion: 0, minor: 14) ] ) Support If you need any help you can join our Slack and go to the #help channel. Or you can create a Github issue in our main repository. When stating your issue be sure to add enough details, specify what module is causing the problem and reproduction steps.

Community Slack

The entire Zewo code base is licensed under MIT. By contributing to Zewo you are contributing to an open and engaged community of brilliant Swift programmers. Join us on Slack to get to know us!

License This project is released under the MIT license. See LICENSE for details.
