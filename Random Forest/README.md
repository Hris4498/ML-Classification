Dataset Information:
The HAR70+ dataset features data from 18 older adult individuals, aged between 70 and 95 years, who wore two 3-axial Axivity AX3 accelerometers for approximately 40 minutes in a semi-structured free-living environment. Among these participants, five used walking aids during the recording session. One accelerometer was placed on the right front thigh, while the other was attached to the lower back. The data was captured at a sampling rate of 50Hz. Video footage from a chest-mounted camera was employed to meticulously annotate the activities performed by the participants, frame by frame.

Each subject's recordings are provided in a separate .csv file. One such .csv file contains the following columns:
1. timestamp: date and time of recorded sample
2. back_x: acceleration of back sensor in x-direction (down) in the unit g
3. back_y: acceleration of back sensor in y-direction (left) in the unit g
4. back_z: acceleration of back sensor in z-direction (forward) in the unit g
5. thigh_x: acceleration of thigh sensor in x-direction (down) in the unit g
6. thigh_y: acceleration of thigh sensor in y-direction (right) in the unit g
7. thigh_z: acceleration of thigh sensor in z-direction (backward) in the unit g
8. label: annotated activity code

The dataset contains the following annotated activities with the corresponding coding scheme:
1: walking	
3: shuffling
4: stairs (ascending)	
5: stairs (descending)	
6: standing	
7: sitting	
8: lying