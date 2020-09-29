# NLI PROJECT



## Assignment

Define:

- The **domain** of the Home Project
- The **profiles** of yourself and the agent
- A sample dialogue that you want to conduct with the agent
  - Each turning point (change of speaker) should allow for several variants, among which one is chosen, depending on the previous dialogue and on the context.
  - The dialogue should not be too rich (keep in mind that you will need to implement it!).



## OPTION 1: Talk about movies (movie assistant)

Why?:

- It's always a good talk

- There are plenty of good API's where we can get lots of information about movies easily (I am using this one http://www.omdbapi.com/). 

  - If we can get many information of an specific subject easily (using the movie API) it is easier to get good answers after analizing what the user is asking or talking about.

    

### TEST1: Using Python

Just because Python is probably the easiest way to code nowadays. All datascience libraries needed can be found in Python. (Scikit-learn, Spicy, Word2vec...)

**Requirements**

```bash
pip install SpeechRecognition # importing speech recognition package from google api 
pip install playsound # to play saved mp3 file
pip install gTTS # google text to speech 
pip install requests # to get API responses
pip install PyAudio # to play saved mp3 file
sudo apt install python-gobject # to play saved mp3 file
sudo apt install python3-pyaudio # to play saved mp3 file
```



> Tested and working on Ubuntu 18.0.4. On MAC and Windows should be very similar



### Usage

Go to `scripts folder` and run from terminal:

```bash
python gtt_test.py
```



![](img/test1.png)
<<<<<<< HEAD

=======
>>>>>>> eab3ec2e6a5ec6da5c1c4bae6ba39b4ad74583a7
