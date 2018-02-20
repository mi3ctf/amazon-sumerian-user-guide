# The Amazon Sumerian VR Camera Rig Component<a name="entities-vrcamerarig"></a>

The VR camera rig component configures a virtual reality headset and controllers for use in VR mode during playback\. When a user has a supported headset, they can click the VR button to switch between the main camera and the head mounted display \(HMD\) camera that represents a VR headset\.

**Supported Hardware**

+ Oculus Rift

+ HTC Vive

Attach the VR camera rig component to an entity with child entities for the HMD camera and each VR controller\. The **CoreVR** asset pack in the Sumerian library contains a rig entity with an HMD camera and controllers for each supported headset\.

**Properties**

+ **Load gamepads** – uncheck to disable controllers\.

+ **Start at current camera** – uncheck to use the camera from its transform location, instead of swapping out the main camera for the VR rig when the user enters VR mode\.

+ **Current VR camera rig** – check to use this rig in VR mode\.