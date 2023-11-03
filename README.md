# Aruco_Marker_Detection
The objective is to use the OpenCV library to detect the id, center coordinates and orientation of all given ArUco markers
An image might contain more than one ArUco marker placed at different positions and orientations.
For each ArUco marker, the following parameters should be determined -

Marker ID: This is unique for each marker. Should be returned as an int value

Center coordinates: Both X and Y coordinates of the marker center combined should be printed as a list. Each co-ordinate should be of int type

Orientation: This is defined as the angle at which the marker is placed w.r.t to the vertical. Should be of int type

Corner Points: For each marker, the corner points should be added to a separate dictionary for plotting the figure
