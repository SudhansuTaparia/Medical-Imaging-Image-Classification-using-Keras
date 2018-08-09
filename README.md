# Medical-Imaging-Image-Classification-using-Keras
When a patient has a CT scan taken, a special device uses X-rays to take measurements from a variety of angles which are then computationally reconstructed into a 3D matrix of intensity values. Each layer of the matrix shows one very thin "slice" of the patient's body. This data is saved in an industry-standard format known as DICOM, which saves the image matrix in a set binary format and then wraps this data with a huge variety of metadata tags.  Some of these fields (e.g. hardware manufacturer, device serial number, voltage) are usually correct because they are automatically read from hardware and software settings  The problem is that many important fields must be added manually by the technician and are therefore subject to human error factors like confusion, fatigue, loss of situational awareness, and simple typos.  A doctor scrutinizing image data will usually be able to detect incorrect metadata, but in an era when more and more diagnoses are being carried out by computers it is becoming increasingly important that patient record data is as accurate as possible.  This is where AI comes in. To improve the error checking for one single but incredibly important value: a field known as Image Orientation (Patient) which indicates the 3D orientation of the patient's body in the image.Some of these fields (e.g. hardware manufacturer, device serial number, voltage) are usually correct because they are automatically read from hardware and software settings

The problem is that many important fields must be added manually by the technician and are therefore subject to human error factors like confusion, fatigue, loss of situational awareness, and simple typos.
A doctor scrutinizing image data will usually be able to detect incorrect metadata, but in an era when more and more diagnoses are being carried out by computers it is becoming increasingly important that patient record data is as accurate as possi


Predict orientation labels for the images in test.

The orientation labels have the following meaning when the image is viewed on an upright, vertical surface like a computer screen:

0: Spine at bottom, patient facing up.

1: Spine at right, patient facing left.

2: Spine at top, patient facing down.

3: Spine at left, patient facing right.
