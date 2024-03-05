# AI-Glasses
AI powered glasses aimed to assist blind or partially blind people in their day to day activities.

---

The main objective of this project is to develop a pair of AI-powered glasses. The glasses are aimed to be used by visually impaired individuals and will have the following features:

* A microphone, a speaker and a camera.
* An AI voice assistant that can answer any question, have a long conversation and also perform tasks such as placing reminders, helping you with directions or perform an action on your phone.
* The capacity to understand its surroundings through the microphone and the camera and be able to describe the surroundings as well as some added capabilities such as warn the user of any potential dangers.


The development of the project will consist of five main pillars, each one addresing a specific objective for the development of the glasses.

1. Object Detection: Create a pipeline that can take real time images from the camera and give information about the images.
2. Virtual Assistant: Natural Language Processing models such as LLMs that can also execute commands or perform additional tasks.
3. Cloud: Have a running server on the cloud that can either host AI models or make API calls to existing models to receive, process and return data through the user's phone and to the glasses.
4. Physical Interface: Have a functional prototype that makes it possible for the user to interact with the functionalities of the glasses.

1. Object Detection:
*  Define the tasks that we're interested in e.g. OCR, obstacle detection, trail following, etc...
*  The model will be collectiong information but will only process it when the user asks for it.
*  Use motion detection models to detect changes in the image.

2. Virtual Assistant:
* Should be able to understand what the user is asking for and call the appropiate model to perform the action.

3. Cloud:
* Chroma DB database
* Deploy models in a cloud environment


4. Physical Interface:

   TBD

