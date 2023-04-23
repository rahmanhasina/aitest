DepthAITestbed
--------------


At the moment, I've just implemented an interface for stereo depth sensing
(only on macOS with Apple silicon). I confirmed that I can implement the plugin
without OpenCV dependency. That's not an easy task due to C++ dependency,
though...

I only tested it with [OAK-D-Lite]. I think it also works with other Luxonis
stereo depth cameras.

[OAK-D-Lite]: 
  https://www.kickstarter.com/projects/opencv/opencv-ai-kit-oak-depth-camera-4k-cv-edge-object-detection
