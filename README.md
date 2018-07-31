# OpenCV
Face,eye and smile detection in python

This is a basic usage of OpenCV and Haarcascade classifier's to identify eyes,face, and smile.
In background Haar features i.e edge,line,square classifiers work and tries to identify the face ,eye and smile of a person in real time.
Process :
1: Imported OpenCV
2: Detect Function with color and frame as inputs
3: For loop to detect Faces
  3.1 defined faces = face_cascade detectMultiScale classifier
  3.2 given specific rectangle sizes ---> X with width and Y with height
  3.3 Similarly for EYES and SMILE
4: Integrated the video saving code into this.
  4.1 : Assigned 'Q' Key to exit i.e to stop and save the VIDEO
5: STOP
