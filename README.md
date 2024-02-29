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

3. Physical Interface: Have a functional prototype that makes it possible for the user to interact with the functionalities of the glasses.

4. Cloud: Have a running server on the cloud that can either host AI models or make API calls to existing models to receive, process and return data through the user's phone and to the glasses.

5. Phone: A mobile app (or similar) that can handle communication between the glasses and the main server.

1. Object Detection:

* Research and choose an appropriate object detection framework (e.g., YOLO, SSD, Faster R-CNN).
* Collect and preprocess a diverse dataset of images for training the object detection model.
* Train the object detection model on the dataset using GPU resources.
* Optimize the trained model for real-time performance on the glasses.
* Integrate the object detection model into the glasses' software pipeline.
* Test the object detection functionality in various real-world scenarios and refine as necessary.

2. Virtual Assistant:

* Research and select a suitable Natural Language Processing (NLP) model (e.g., GPT, BERT).
* Fine-tune the chosen NLP model on a corpus of conversational data and task-specific commands.
* Implement a dialogue management system to handle conversations and execute commands.
* Develop mechanisms for the virtual assistant to access and interact with other system components (e.g., object detection, reminders).
* Integrate the virtual assistant into the glasses' software architecture.
* Conduct thorough testing and debugging of the virtual assistant's capabilities.

3. Physical Interface:

* Design the physical form factor of the glasses, considering ergonomics and usability.
* Prototype the physical interface components, including buttons, touch panels, or gesture recognition sensors.
* Develop the electronic circuitry to connect the interface components to the glasses' mainboard.
* Implement firmware to manage user inputs and control the glasses' functionalities.
* Conduct user testing and iterate on the design based on feedback.
* Finalize the physical interface design for mass production.

4. Cloud:

* Choose a cloud service provider and set up an account.
* Design the cloud architecture to host AI models, handle communication with the glasses, and store user data securely.
* Select a suitable database technology for storing user data (e.g., SQL, NoSQL).
* Develop a schema for the database to organize and manage user information efficiently.
* Implement mechanisms for securely storing and accessing user data, including encryption and access control.
* Integrate the database into the cloud infrastructure, ensuring compatibility with other system components.
* Implement backup and disaster recovery procedures to safeguard user data against loss or corruption.
* Conduct thorough testing of the cloud infrastructure, including scalability, reliability, and security.
* Ensure compliance with relevant data protection regulations and user privacy preferences.
* Document the cloud architecture and procedures for future maintenance and updates.

5. Phone:

* Select a mobile development framework (e.g., Flutter, React Native).
* Design the user interface for the mobile app to communicate with the glasses and cloud server.
* Implement communication protocols (e.g., Bluetooth, Wi-Fi, REST API) between the glasses and mobile app.
* Integrate features for configuring settings, managing notifications, and accessing additional functionalities.
* Conduct extensive testing on different mobile devices and operating systems.
* Publish the mobile app on relevant app stores and ensure compatibility with future updates.
