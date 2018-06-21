
# Supplementary Data

## Manuscript title: Depth estimation with ego-motion assisted monocular camera

### Authors:
		* Mostafa Mansour
		* Pavel Davidson
		* Oleg Stepanov
		* Jukka-Pekka Raunio
		* Mohammad M. Aref
		* Robert Piché

---

### Data description:
		This folder contains 5 Matlab files used in the field test associated with the paper in review. These files are:
			* camera_intrinsic_matrix.mat
			* ground_truth.mat
			* angular_vel.mat
			* linear_vel.mat
			* image_points.mat.

	The content of each of the previous files is described in the following section.

---

### Files description:

	- camera_intrinsic_matrix.mat: This file contains the intrinsic calibration parameters of the camera in use.
			@params:
					(cx,cy):	Camera principal point measured in pixels.
					f: 			Camera focal length measured in pixels.

	- ground_truth.mat: This file contains the true feature point coordinates during the experiment. The coordinates are resolved in camera coordinate frame. It consists of three columns.
			@params:
					first column: 	X coordinate of the feature point resolved in camera coordinate frame.
					second column: 	Y coordinate of the feature points resolved in camera coordinate frame.
					third column: 	Z (depth) coordinate of the feature point resolved in camera coordinate frame.

	- angular_vel.mat: This file contains camera angular velocities (Gyro outputs) with their corresponding time stamps. The file consists of two columns.
			@params:
					first column:	Time stamps of the measured angular velocities.
					second column:	Measured angular velocities.

	- linear_vel.mat: This file contains camera linear velocities (Odometer output) with their corresponding time stamps. The file consists of two columns.
			@params:
					first column:	Time stamps of the measured linear velocities.
					second column:	Measured linear velocities.

	- image_points.mat: This files contains the image points (x,y) of the feature point with their corresponding time stamps. The file consists of three columns.
			@params:
					first column:	Time stamps of the received image points
					second column:	x coordinates of the image points measured in pixels.
					third column:	y coordinates of the image points measured in pixels.


