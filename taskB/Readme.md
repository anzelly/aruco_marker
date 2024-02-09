# Task B

To place the given 4 aruco-marker images on the boxes of “CVTask.png” image as given below :
<pre>
 Box Color-----Marker ID
  Green-----------1
  Orange----------2
  Black-----------3
  Pink-Peach------4
</pre>

The marker should exactly be placed on the squares only, even the orientation of the
squares should be kept in mind.

# Solution
### Contour Detection
The contours of the squares in the task images were obtained to determine the sizes of Aruco markers needed and also obtain their bounding rectangles.
### Aruco Detection
Aruco markers were identified. The markers were resized and oriented the correct way so as to fit into the rectangles in the task image.

### Bitmask Manipulation
The aruco markers were placed onto the task image rectangles one at a time by using bitmasks.
