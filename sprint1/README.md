<h5>Creating a Neural Network that can drive a car (autonomous car simulation)</h5>

Team Members:
Erim Keresteci

Summary:
The aim of this project is to understand the basics of the technology behind self driving cars. 
There isn’t exactly an audience for this project other than the people working on it. It’s moreso about the motivation behind this project which lies in my will to understand how things work. As the world slowly and inevitably transitions into an age of automation, I want make sure I don’t take for granted the technology around me and ensure I understand what’s actually happening behind the scenes. 

Resources:
This project would use Python as the primary programming language, however it’s possible it could end up being C# depending on the simulation environment I decide to use. I have not yet researched the optimal software/library to make the visual simulation of the autonomous car on, but Unity is a possibility if I go down the C# route. API’s that will be helpful include TensorFlow, keras, NumPy, and Pandas. There will definitely be more that are used however that depends on my research regarding the method of simulation. 

Useful articles:
https://neptune.ai/blog/self-driving-cars-with-convolutional-neural-networks-cnn
https://medium.com/asap-report/training-a-neural-network-for-driving-an-autonomous-rc-car-3906db91f3e

Products that I might want to purchase include an RC car of some sort along with sensors incase I want to simulate this in real life. A possible RC car to use would be the Nvidia JetBot https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetbot-ai-robot-kit/

Tasks:
Research how self driving cars work
Research the ideal programming language and simulation tool to conduct this project
Configure programming environment
Continue step 3
Create the simulation environment
Continue step 5
Program a system to change the “track” the car will be learning/following
Continue step 7
Research and plan out how the neural network should look (i.e. how many inputs, what kinds of inputs, maybe it’s a self-supervised model)
Create a system to record the distance a car travels along the track so that a replicable alpha population slowly forms and further evolves from the repeated test
Start programming the neural network
Continue step 11
Continue step 11
Continue step 11
Continue step 11
Run tests on the neural network
Continue step 16
Fix any issues 
Continue step 18
Continue step 18
Make the visual simulation of the self driving car with the neural network (pulling it all together)
Continue step 21
Continue step 21
Continue step 21
Test it all
Fix any issues
configure the NVIDIA JetBot 
Design tracks for the jetbot to learn 
Make the code work on the jetbot
Continue step 29
Continue step 29
Continue step 29
Test 
Fix errors
See how it performs on various tracks 
Try and train the virtual simulation and then upload the model to the jetbot to see if it can replicate the movement in an identical real-life version

Additional Notes:
None



Identity Recognition System

Team Members:
Erim Keresteci

Summary:
The aim of this project is to create software that can detect peoples’ voices and faces using machine learning. 
The audience for this project would be the people working on it, however the later stages of this project (possibly in another sprint) would be for other people who would test the program (malware). The motivation behind this project is to learn how to use machine learning with video and audio data and extract specific information from that data (i.e. a name). The long term goal with this project, stretching into other sprints, would be to create a malware that can collect data about a subject. 

Resources:
This project would use Python as the primary programming language. Libraries that would be useful include keras, TensorFlow, Pandas, NumPy, OpenCV, and an audio-processing library. There could very well be more libraries used, however for now this is what I can foresee. I can’t write a lot on the resources matter because this kind of project is very new to me, so I’m not sure what else I might need.  

Helpful articles:
https://www.datacamp.com/tutorial/face-detection-python-opencv
https://realpython.com/face-recognition-with-python/
https://www.geeksforgeeks.org/python-speech-recognition-module/
https://www.simplilearn.com/tutorials/python-tutorial/speech-recognition-in-python

There are no products I would like to purchase as of now. 

Tasks:
Research how facial recognition works
Work with OpenCV to create a video feed that receives input from webcam
Create a machine learning model that can detect a face on the video feed
Continue step 4
Continue step 4
Continue step 4
Modify the machine learning model to be able to detect facial expressions and features (i.e. smiling/frowning, eye color, etc)
Continue step 10
Continue step 10
Continue step 10
Continue step 10
Continue step 10
Modify the machine learning model to be able to detect and classify different faces as different people.
Continue step 13
Continue step 13
Continue step 13
Modify step 13 so that it can save these “profiles” to a datastore 
Continue step 17
Continue step 17
Continue step 17
Modify step 17 so that it can label faces it has detected in the past with the corresponding profiles upon re-detection
Continue step 21
Continue step 21
Research how speech recognition works
Work with an audio-processing library to be able to get a live audio feed from computer - possibly extracting it from the video feed even
Continue step 25
Continue step 25
Test to see if audio feed works
Create machine learning model to detect a specific persons voice
Continue step 29
Modify step 29 to be able to detect multiple voices at once and save them to profiles
Continue step 31
Continue step 31
Continue step 31
Modify step 21 so that the facial recognition model can detect when a person is speaking through mouth movements
Continue step 35
Combine step 31 and 35 so that voices and faces are matched to the same profiles
Continue step 37
Continue step 37
Test + bug fixes 

Additional Notes:
The follow-up project to this is a little unethical due to its potential uses so I am limiting myself to just the functionality portion and not doing anything malware related for now. 



Creating documentation/materials for a Dalton ML Class

Team Members:
Erim Keresteci

Summary:
The aim of this project is to design resources for a potential Dalton course regarding machine learning. 
The audience for this project would be strong CS students at Dalton who are interested in AI and machine learning. In this course they would understand the theory behind machine learning (not necessarily the math as that is beyond what the Dalton ‘2A’ math curriculum teaches) as well as how to create neural networks, what each component of a neural network does, and the different kinds of machine learning. 

Resources:
This project would use Python as the primary programming language and github to hold all the documentation and resourced needed for the course. All external websites would also be included in this github. API’s that would definitely be used include keras, TensorFlow, Pandas, NumPy. However, based on the depth to which the resources go, this list may grow. With regard to books and articles that are relevant to this project, I would include any GeeksForGeeks page as well as the TensorFlow and keras official tutorials, however with this project being aimed at creating class resources and documentation, I would limit what I take from outside. There are no products I would like to purchase as of now. 

Tasks:
Create and configure github repo to hold all of the resources
Do research to determine exactly what to include in this documentation
Continue step 2
Create subsections in the github repo to hold resources covering different topics
Start researching the first “unit” of the documentation in depth
Create materials including reference code, explanations, extra resources, practice problems/projects with answers and explanations
Continue step 6
Continue step 6
Continue step 6
Continue step 6
Continue step 6
Continue step 6
Start researching the second “unit” of the documentation in depth
Create materials including reference code, explanations, extra resources, practice problems/projects with answers and explanations
Continue step 14
Continue step 14
Continue step 14
Continue step 14
Continue step 14
Continue step 14
Continue researching and creating resources until all documentation is complete (unsure for now how many “units” there would be)
Go through all units and edit all explanations and references to make sure everything is clear and correct
Continue step 22
Continue step 22
Continue step 22
Work with Dalton CS dept and high school office to make a course available on ML with this github repo serving as the curriculum and resources for the class.

Additional Notes:
I feel it is important that those who are interested in ML have time to learn it in high school without it being done on their own time for no credit. 


