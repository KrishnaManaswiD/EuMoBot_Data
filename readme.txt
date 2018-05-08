The data in this folder supports the paper titled
EuMoBot: Replicating Euglenoid Movement in a Soft Robot

Authors: Krishna Manaswi Digumarti, Andrew Conn and Jonathan Rossiter

This folder contains six files of csv type. They are as follows:

1. centroids_largeRobot - coordinates of centroids of the large robot recorded during multiple trials along with timestamp.
			  Each row is formatted as x1,y1,t1,x2,y2,t2,... for one data point, with the number indicating the trial that the data was recorded in.
			  Units for x and y cordinates are pixels. Multiply by 2.5 to get mm. Units for t are seconds.
2. centroids_smallRobot - coordinates of centroids of the small robot recorded during multiple trials along with timestamp.
			  Each row is formatted as x1,y1,t1,x2,y2,t2,... for one data point, with the number indicating the trial that the data was recorded in.
			  Units for x and y cordinates are pixels. Multiply by 2.5 to get mm. Units for t are seconds.
3. estimatedChamberArea - each row of this file is a triplet containing area of red, green and blue chamber of the small robot. 
			  Each row is one frame of recording. Units are squared pixels. Multiply by 6.25 to get squared mm.
4. fourierCoefficients_euglenoid - set of normalised Fourier coefficients computed from the shapes of the euglenoid.
				   Each row corresponds to one shape. Columns contain coefficients. Units are pixels.
5. fourierCoefficients_largeRobot - set of normalised Fourier coefficients computed from the shapes of the large robot.
				    Each row corresponds to one shape. Columns contain coefficients. Units are pixels.
6. fourierCoefficients_smallRobot - set of normalised Fourier coefficients computed from the shapes of the small robot.
				    Each row corresponds to one shape. Columns contain coefficients. Units are pixels.