## Who are we? 🙋‍♀️
This organisation contains code developed in relation to work done by Thomas Bolander Ph.D., professor at The Technical University of Denmark (Research, Education and Outreach). Our research focuses on programmatic enhancements on the Pepper robots from Aldebaran.

![Alt Text](https://github.com/MAvis-DTU/.github/blob/722fa67c977b14d3091509da35598a84075461e9/images/what_we_do.jpeg)

## Research Focus
Our team is actively enganged in research and developement including, 
- Course work for 02182 Symbolic Artificial Intelligence
- False-belief tasks with robots.
- Outreach work with robot demonstrations (cloudspeech) for presentations
- Demonstration for DTU Research Evaluation 2023 showcasing a live-demo with Pepper working as a chatbot.
- General feature development on the Pepper robots 

## Repositories in the organisation
The following sections described are meant as brief summaries of what some of the more important repositories in this organisation contain.

**DO THIS**, for new repositories, add a new section with a brief description.

‼️Some of the repositories might not appear if they are private🔐. Contact organisation owner if you wish to gain access🔓.‼️

### 📂`02182-MAvis-Code-Handout`
This repository contains content for the MAvis assignments of the DTU course: Symbolic artificial intelligence - 02182, and is considered DTU property. It is updated and maintained by current and previous TAs as well as student assistents of Thomas Bolander.

It includes guides for setting up your own private downstream repository, installing the requirements, how to use the client and server, how to interface with the Pepper robots.

### 📂`R2DTU`
This repository is a collection of various projects made by Lasse Dissing Hansen and Thomas Bolander.

It contains code for the False Belief Demo often seen in videos related to the following two papers,

- [Implementing Theory of Mind on a Robot Using Dynamic Epistemic Logic](https://doi.org/10.24963/ijcai.2020/224)
- [DEL-based Epistemic Planning for Human-Robot Collaboration: Theory and Implementation](http://www.imm.dtu.dk/~tobo/main_kr21.pdf)

As well as a readme named `things-i-wish-i-had-known.md` containing the main takeaways by Lasse after having worked on the Pepper robots.

### 📂`cloudspeech`
This repository is a general demo of how the OpenAI GPT models can be combined with the Pepper robots to create an advanced humanoid chatbot.

`cloudspeech.py`is a Python script utilizing Google Cloud Speech-to-Text, OpenAI's GPT models, and ElevenLabs' voice synthesis for interactive voice-enabled applications with a Softbanks Robotics Pepper Robot. This script incorporates functionality to interface with Pepper, execute voice streaming with real-time response using AI models, and perform object detection leveraging MediaPipe (provided MediaPipe is configured in the environment).

It is the main repository used for out-reach.

### 📂`pyRobot`
The purpose of `pyRobot` is a sandbox/development repository, containing code from multiple explorative investigations. It is meant as a *temporary graveyard* for code that might be needed in the future.

The `pepper-camera-server` which after building with Docker, is the exeutable that initilises the camera server on the Pepper robot, has been placed in this repository with an *easy-to-follow* guide. 

### 📂`research-evaluation-2023`
During the research evaluation of DTU in 2023 the research group was tasked to create a demonstration showcasing a more informal site of what we do at DTU. The repository contains code for a chatbot-setup with our Pepper robots. It takes a camera feed utilising a RealSense depth-camera, and connects to the OpenAI gpt models to create chat features and gestures during chatting. It has a UI that displays the camera feed and the chat side-by-side as the chat progresses.



<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
