# MATRIX Ecosystem Overview
<h5 style="padding-top:0; font-weight:500;">Objective: Hardware shouldn't be hard</h5>
The MATRIX Ecosystem was created to make powerful hardware projects very approachable for software developers. The pillars of MATRIX, computer vision, hardware interfaces, distributed internet communication, and data-driven end-user clients, are all programming disciplines which require years for an individual to master, or for a team to build a solution around.

<br/>
## Support & Resources
Feel free to visit our communities and projects for any suggestions and/or questions you may have!

<p><img src="./img/community.png" height="24px" width="24px"> Post questions or comments on <a href="https://community.matrix.one" target="_blank">community.matrix.one</a>.</p>

<p><img src="./img/docs.png" height="24px" width="24px"> 
Submit documentation issues or improvements to the <a href="https://github.com/matrix-io/matrix-documentation/issues" target="_blank">MATRIX Documentation Repository</a>.</p>

<p><img src="./img/hackster.png" height="24px" width="24px"> Check out our Hackster projects and guides on our <a href="https://hackster.io/matrix-labs/projects" target="_blank">Hackster Page</a>.</p>

<p><img src="./img/youtube.png" height="24px" width="24px"> Follow our live streams and tutorial videos on <a href="https://youtube.com/MATRIXLabs" target="_blank">YouTube</a>.</p>

<p><img src="./img/E14.svg" height="24px" width="24px"> View blog posts & project guides on our <a href="https://element14.com/community/people/matrixlabs/content" target="_blank">element14 page</a>.</p>

<p><img src="./img/Github.svg" height="24px" width="24px"> 
Alert issues on our <a href="https://github.com/matrix-io" target="_blank">GitHub</a> under the corresponding repository.</p>

<br/>
## Programming Layers

The MATRIX platform adds powerful capabilities to your Raspberry Pi, depending on your background and the kind of application you want to write, you may need to decide on which layer best fits your need. The documentation is organized according to these layers:

<h3 style="padding-top:0;">MATRIX Lite</h3>
**Languages:** JavaScript, Python, Go, & Ruby

A straightforward library that's aimed at users of all skill levels. This layer is an abstraction around MATRIX HAL and allows you to program your MATRIX Device with as little as one line of code.

[Read more about MATRIX Lite](matrix-lite/overview)

<h3 style="padding-top:0;">MATRIX HAL</h3>
**Language:** C++

Interacts with the kernel modules by using C++ drivers, enabling it to access available sensors and components on your device.

[Read more about MATRIX HAL](matrix-hal/overview)

<h3 style="padding-top:0;">MATRIX Core</h3>
**Languages:** Over 40 (Examples in JavaScript & Python)

Abstraction layer for **MATRIX HAL**. Hosts a ZeroMQ + Protobuf communication layer which makes device information accessible via high-level interfaces. Supports multiple different languages through Protocol Buffers: C++, Python, Ruby, PHP, Java, etc.<br/>

[Read more about MATRIX Core](matrix-core/overview)

<br/>
## Devices
> Each programming layer in the MATRIX platform is compatible with each MATRIX product, excluding specific components on the boards.

<h3 style="padding-top:0;">MATRIX Creator</h3>

<!-- ![](img/matrix-creator.png) -->
A fully-featured development board for the Raspberry Pi with various sensors and communication protocols such as a 3D Gyroscope, Accelerometer, an 8 Microphone Array, zigbee, Z-Wave, and more!

[Read more about the MATRIX Creator](matrix-creator/overview.md)

<h3 style="padding-top:0;">MATRIX Voice</h3>
<!-- ![](img/matrix-voice.png) -->
A voice and audio focused development board with an 8 microphone array that enables you to create your own audio driven applications or use voice assistants such as 
<a href="https://www.hackster.io/matrix-labs/matrix-voice-and-matrix-creator-running-alexa-c-version-9b9d8d" target="_blank">Amazon Alexa</a>, 
<a href="https://www.hackster.io/matrix-labs/matrix-voice-and-matrix-creator-running-google-assistant-e9751e" target="_blank">Google Assistant</a>, 
PocketSphinx, etc.

[Read more about the MATRIX Voice](matrix-voice/overview.md)

