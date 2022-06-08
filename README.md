# OSSLab_Final_VoiceAssistent
Voice Assistent with Rhasspy and Node-Red

# What does this project do

# Why is this project useful

# How to get started

## Table of Contents
1. [General Info](#general-info)
2. [Use and future extentions](#Use and future extentions)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)

### General Info
***
This project contains a basic version of a voice assistent like it is known from cmmercial companies. Popular ones are Alexa (Amazon), Cortana (Microsoft), Google Assistant (Google) and Siri (Apple). All these voice assistants have in common that they need an internet connection to work. However, this also has disadvantages. Especially in terms of data security. Based on this motivation, this offline-capable voice assistant is created, which does not require an internet connection for the evaluation of the received commands.

The voice assistent can handle the following commands in this version:

To request the time:
- what time is it
- tell me the time

To request the date:
- what's the date today
- tell me the date

To request the outside temperature
- what's the temperature
- how (hot | cold) is it




### Screenshot
![Image text](images/rhasspysettings.PNG)

## Use and future extentions
***
This project can be used to implement an own voice assistent on a raspberry pi. This raspberry pi can be placed in any room where it is usefull to ask for several daily things, like the weather or the time. Futhermore the current implemented commands can be extended. As described, this is just a basic version, but since this groundwork is already done, it is verry convinient to extend the functionalities now. For example: controlling the gpio-ports or switching the roomlight with voice-commands could be the next steps. However for performance reasons it is recomended to use at least a raspberry pi 3B+.

Because the equipment currently available has no microphone, this implementation is using a website which records the voice commands.


A list of technologies used within the project:
* [Technologie name](https://example.com): Version 12.3 
* [Technologie name](https://example.com): Version 2.34
* [Library name](https://example.com): Version 1234

## How to get started
### Installation
***
A little intro about the installation. 
```
$ git clone https://github.com/lbuetgit/OSSLab_Final_VoiceAssistent.git
$ cd OSSLab_Final_VoiceAssistent/.node-red
$ npm install
$ npm start
```



Side information: To use the application in a special environment use ```lorem ipsum``` to start

## Collaboration
***
Give instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> It should go over several rows?
> This is how you do it.

## FAQs
***
A list of frequently asked questions
1. **This is a question in bold**
Answer of the first question with _italic words_. 
2. __Second question in bold__ 
To answer this question we use an unordered list:
* First point
* Second Point
* Third point
3. **Third question in bold**
Answer of the third question with *italic words*.
4. **Fourth question in bold**

| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:--------------|:-------------:|--------------:|
| text-align left | text-align center | text-align right |
