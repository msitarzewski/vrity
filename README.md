# vrity
Open platform that facilitates server side rendering for VR applications.

vrity.app

1. What is it?

It moves all storage and rendering to the cloud to make AAA experiences available to anyone with a VR headset and a high bandwidth, low latency internet connection.

2. Which platforms will be supported?

All VR headsets should be supported. The delivery to the headset is a VR 180° SBS video. Anything that can render that stream is compatible.

3. What about optics? How will vrity handle the different specifications for each headset?

The client side application will send the headset’s specifications in the initial handshake. From then on, the server side services can customize the stream to that headset. This includes server side foveated rendering, and IPD adjustments.

4. Will it support 6 degrees of freedom? Lighthouses? Tracking towers?

Yes, all of these data points can be captured and sent to the server in realtime. The application will respond and return stream that reflect the input.

5. That's not possible.

Well, maybe. Let's see. Latency will be the primary driver of the success of the application. While the product is designed to work on all platforms and headsets, the reality is that it will take a very special internet connection to provide the best experience.

6. It's open source?

Yes, the protocols and rendering systems will be open. At some point in the future, layers of service may be provided. For example, anyone can connect to the service and can expect at least 60 frames per second at the equivalent of 1080p. Additional paid service may include 75 frames, 90, and 120 frames per second at 4K equivalent resolution.

To be clear, you should be able to play any AAA title on any quality of headset given the bandwidth and latency are sufficient. That may be 10 people, or it could be millions with the release and ubiquity of 5G. Cable internet is perfectly adequate to stream 4K video (25Mbps). This will be slightly higher than that.
