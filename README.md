<h1>CubePilot - Cube Detection and Navigation</h1> 
 <p>Cube Pilot is a Python project that leverages OpenCV and the Cozmo SDK to enable the Cozmo robot to detect the color of a cube and navigate towards it, stopping within a specified distance for interaction..</p>

<h2>Features</h2>

- <b>Color detection:</b> Utilizes OpenCV for real-time color detection of green and yellow cubes.
- <b>Precise stopping:</b> Stops the robot within a given distance from the cube for interaction.
- <b>Autonomous navigation:</b> Cozmo robot autonomously navigates towards the detected cube.

<h2>Color Detection Procedure</h2>

- <b>Capture image & remove noise:</b> The program captures an image from the Cozmo robot's camera in the RGB color space. Image smoothing techniques are applied to remove noise and improve the quality of the image.
- <b>Convert to HSV color space:</b> The RGB image is converted to the HSV (Hue, Saturation, Value) color space, which is more suitable for color-based image processing.
- <b>Filter by color & detect blobs:</b> Color filtering is applied to isolate regions in the image that match the specified color ranges for green and yellow cubes. Blob detection algorithms are used to identify and locate the detected colored regions (blobs) in the image.


<h2>Challenges</h2>
The color detection process is the most challenging aspect of this project due to variations in lighting conditions across different environments. Varying lighting conditions can impact the accuracy of color detection algorithms, requiring careful calibration and tuning for optimal performance.
 

<h2>Requirements</h2>
<li>Python 3.5.1 or later</li>
<li> OpenCV</li>
<li>Cozmo SDK</li>

<h2>Screenshots</h2>
<div><img src="https://imgur.com/cDrIpVY.png" width=45% height=45% align="right"/> </div>
