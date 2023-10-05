# Face-recognition-using-Mobilenet
# Project Description
This project aims to develop a face recognition mechanism to detect faces and markup attendance for NREGA beneficiaries. The project uses a Convolutional Neural Network (CNN), MobileNet V2, Python, and Flask.
# Motivation
The National Rural Employment Guarantee Act (NREGA) is a social welfare program in India that provides employment to rural households on demand. However, there are challenges in tracking the attendance of NREGA beneficiaries, as they often work in remote locations and may not have access to smartphones or other devices.
# Solution
This project proposes a face recognition mechanism to address the challenges of tracking NREGA beneficiary attendance. The system uses a CNN, MobileNet V2, to detect faces in images and videos. Once a face is detected, the system extracts features from the face and compares them to a database of known faces. If a match is found, the system marks the beneficiary's attendance.
# Implementation
The system is implemented using Python and Flask. The CNN model is trained on a dataset of face images. Once the model is trained, it is deployed to a Flask server. The Flask server provides a REST API that can be used to detect faces in images and videos and mark attendance.
# How to Use
Clone the repository:<br>
git clone https://github.com/8122harishravichandra/Face-Recognition-Mechanism-using-MobileNet.git<br>
Install the required dependencies:<br>
**pip install -r requirements.txt**<br>
Start the Flask server:<br>
**flask run**<br>
Open a web browser and navigate to<br> http://localhost:5000/<br>

Click on the "Upload Image" button and select an image containing one or more faces.<br>
The system will detect the faces in the image and display the names of the beneficiaries, if they are in the database.
<br>
To mark attendance for a beneficiary, click on the "Mark Attendance" button next to their name.
# Contributing
**If you would like to contribute to this project, please feel free to fork the repository and create a pull request. We welcome contributions from all skill levels.**
# Conclusion
This project is a face recognition mechanism to detect faces and mark attendance for NREGA Beneficiaries. It is developed using CNN, MobileNet v2, Python, and Flask for the Smart India Hackathon 2022. The system is designed to be used by NREGA officials to mark attendance for beneficiaries in a fast and efficient manner.















