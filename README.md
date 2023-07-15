# Sign Language Assistive Device for the Hearing Impaired

This repository contains the source code and project documentation for a Sign Language Assistive Device designed to aid individuals with hearing impairments. The device utilizes a Raspberry Pi and leverages the capabilities of the Mediapipe library to interpret sign language gestures and predict the corresponding spoken words. By doing so, it enables communication between the hearing-impaired and others through audible speech.

## Project Overview

The primary objective of this project is to bridge the communication gap between the hearing-impaired and general population. By recognizing and interpreting sign language gestures, the device can convert them into spoken words, allowing those who do not understand sign language to comprehend the intended message.

## Tools Used

- Raspberry Pi: The heart of the system, responsible for running the sign language recognition script and generating audible speech output.
- Mediapipe: A powerful library for various AI-based applications, in this case, utilized for hand gesture recognition from video input.
- Additional hardware components: A camera module or USB camera is required to capture the user's sign language gestures.

## Programming Language (Python)

The entire project is implemented using Python due to its ease of use and extensive libraries available for artificial intelligence, computer vision, and Raspberry Pi integration.

## How to Use

To use the Sign Language Assistive Device, follow these steps:

1. **Set Up the Raspberry Pi**: Connect all the necessary hardware components, including the camera module or USB camera, to the Raspberry Pi board.

2. **Install Dependencies**: Install all the required dependencies, including Python libraries and Mediapipe framework. Use the provided requirements.txt file or follow the installation instructions in the project documentation.

3. **Clone the Repository**: Clone this repository to your Raspberry Pi by executing the following command in the terminal:
```shell
git clone https://github.com/your-username/your-repository.git
```
   
5. **Navigate to the Project Directory**: Change the working directory to the project folder:
```shell
cd your-repository
```

7. **Run the Sign Language Recognition Script**: Execute the Python script responsible for capturing and interpreting sign language gestures:
```python
python app.py
```

9. **Interact with the Device**: Place your hand in front of the camera and perform various sign language gestures. The script will process the video input and predict the corresponding spoken words. The audible speech output will be generated, allowing others to understand your message.

10. **Adjust Settings (Optional)**: Depending on the lighting conditions and hand size, you may need to adjust certain parameters in the script to achieve optimal results. Refer to the documentation for customization options.

11. **Communicate with Others**: Engage in meaningful conversations with people around you, even if they do not understand sign language. The Sign Language Assistive Device will help bridge the communication gap and foster inclusivity.

Please note that this project is intended for educational and experimental purposes. Its accuracy and performance may vary depending on environmental factors and complexity of sign language gestures. We encourage contributions and improvements from the open-source community to make it even more effective and accessible for users.


