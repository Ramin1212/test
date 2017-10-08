# COM3502/4502/6502

## SPEECH PROCESSING

- Lecture 1
- Introduction

## The Course

### Speech

- speaking and hearing
-	acoustics and sound
-	the nature of speech
-	sounds and symbols
-	phonetics
-	phonology
-	prosody


###	Speech Processing

-	signals and spectra
-	sampling
-	waveform processing
-	the Fourier transform
-	filters and linear prediction
-	cepstral analysis

Note: 'Pd-extended' is available on the University Managed Desktop

## Recommended Text Books

- Introducing Phonetic Science
- Designing sound
- Speech Synethesis


## Logistics

Lectures

-	2x per week (Tue 16:00-16:50 + Thur 16:00-16:50)
-	reading week (week 6)

Practical Sessions

-	introduction to Pd (weeks 2-5 Mon 13:00-13:50 DIA-CR3)
-	drop-in sessions (weeks 6-11 Mon 13:00-13:50 Lewin Lab.)

Assessment

-	introduction to Pd lab exercise (pass/fail, worth 5%)
-	2x Pd programming assignments (worth 25% and 35%)
-	2x invigilated MOLE quizzes (worth 15% and 20%)

Feedback

-	in-class exercises + practical sessions + assignments
-	office hours (room 142 - book an appointment at 
http://www.dcs.shef.ac.uk/~roger/contact.html)

Lecture notes (these slides + MP3 recordings)

-	on-line (MOLE) asap after each lecture


## What is Speech Processing ?

> "..... the study of speech signals and the processing methods of these signals"

> "..... a special case of digital signal processing applied to speech signals"

http://en.wikipedia.org/wiki/Speech_processing


## What is Speech Processing For?

![1876 -> 2](figures/figure.jpg)

Figure 1 (Slide 6)

![2017 -> 7,000,000,000](figures/figure.jpg) 

Figure 2 (Slide 6)

## Speech Processing Technologies

- Automatic Speech Recognition
- Digital Speech Coding
- Spoken Language Dialogue Systems
- Text-to-Speech Synthesis


## Extracting Information from Speech

![Speaker conveys several levels of information. In addition to the message being spoken (words) there is also information about the language and the speaker. The aim in all automatic speech processing techniques is to extract these levels of information for further processing (database query, info for synthesis, etc.) Although shown as independent extraction paths, knowledge gained from the different levels of information can be used together for different application goals. 
](figures/L1_03.jpg)

Figure 3 (Slide 8)

Slide courtesy of Doug Reynolds, MIT Lincoln Lab.

## Why Speech Processing ?

Lots of applications...especially in Science Fiction !

Video (Slide 9)

## Why use Speech ?

> "Speech is the 'natural' way to interact with your computer."

WRONG!

Speech may be a more **intuitive** way of accessing information, controlling things and communicating **but** there may be viable alternatives

## Why use Speech ?

Some alternatives can be problematic...

> "...If you'd like to hear all your options again, press 49. If you've forgotten why you called in the first place, press 50."

Copyright: 1999 Randy Glasbergen. www.glasbergen.com

## The Advantages of Speech

- hands-free
- eyes-free
- fast (Audio; Slide 12)
- intuitive

> "You have been learning since birth the only skill needed to operate our equipment."

## Markets & Applications

- Medicine
- Transport
- Army
- Office

![Figure (Slide 13)](figures/L1_04.jpg) 

## Toys & Games

- KINECT XBOX 360
- Game Commander 2
- Dog robot

![Figure (Slide 14)](figures/L1_05.jpg) 

## At Home and Mobile

- Google home
- Amazon echo
- Siri
- Cortana

![Figure (Slide 15)](figures/L1_06.jpg) 

## Robots

- Pepper
- Jibo
- Echo look

![Figure (Slide 16)](figures/L1_07.jpg) 

## Types of Application

> $'C^3I^2PS'$ ...

-	 **C**ommand & **C**ontrol
-	 **C**ommunications
-	 **I**nformation
-	 **I**ntelligence
-	 **P**rocessing
-	 **S**torage

Interactive vs non-interactive

-	conversational human-machine interface (A)
-	monitoring speech communications (B)

Real-time vs non real-time

-	'live' speech transcription (B)
-	speech data mining (C)
-	telephone (A)
-	voicemail (D)


![Figure (Slide 18)](figures/L1_08.jpg) 

---

- Intelligence
- Information
- Command, control & communications
- Processing & storage

![Figure (Slide 19)](figures/L1_09.jpg) 


## Question...

What current or future applications of speech processing can you think of ?

## Speech Processing Application

Describe your proposed application...


Place an 'X' on this diagram that corresponds to your application.


Figure (Slide 21)

Name: _______________


_____________________________



Example by Roger Moore.

Describe your proposed application.

*Being able to search the voice recordings made durin these lectures*

Place an 'X' on this diagram that corresponds to your application.

Name: __Roger Moore__


# Some real applications

### Command & Control: *Vehicle*

Video (Slide 24)

Robust Speaker-Independent Small-Vocabulary Automatic Speech Recognition

## Command & Control: *Multimedia*

ASR + TTS

http://www.amuletdevices.com


## Command & Control: *Reading Aid*

Video (Slide 26)

## Information: *Dictation*

Speaker-Dependent Large-Vocabulary Continuous Speech Recognition

Figure (Slide 27)

## Information: *Dictation*

Figure (Slide 28)

## Information: *Speech Output*

Text-to-Speech Synthesis

Video (Slide 29)

## Information: *Interactive Voice Resonse (IVR) Services*

Audio (Slide 30)

- Telephone-Based
- Speaker-Independent
- Medium-Vocabulary
- Spoken Language
- Dialogue System

## Information: *Voice Search*

Google voice search

## Information: *Conversational Search*

Speech Recognition -> Natural Language

Understanding -> Natural Language

Generation -> Speech Synthesis


## Communications: *Speech-to-Speech (S2S) Translation*

Example: VoiceTra by NiCT

Speech Recognition -> Text

Translation -> Speech Synthesis

## Intelligence: *Live Captioning*

Video (Slide 34)

AT&T Advanced Speech Products Group

## Intelligence: *Voice Stress Analysis*

www.nemesysco.com

## Processing: *Special Effects*

Audio 1 (Slide 36)

Audio of robot voice (Slide 36)

## Processing: *Audio Alignment*

Example of software by SYNCHROARTS

## Summary

![Figure Slide 38](figures/L1_10.jpg)

Non-real time and Interactive

- SPEECH STORE &FORWARD
      - productivity enhancement
      - automation

- SPEECH DATA MINING
      - productivity enhancement
      - automation
      - service model applicable
      
- SPEECH DATA MONITORING
      - productivity enhancement
      - automation

- SPEECH INPUT OR OUTPUT
      - hand or eyes-free
      - workload reduction

## This lecture has covered

- What speech processing is
- What speech processing is for
- Speech processing technologies
- The advantages of speech
- Types of application

## Any Questions?

## Next time

Sound
