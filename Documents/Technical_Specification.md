<h1> Technical Specification</h1>

---

<details><summary>Table of Contents</summary>
  
- [1. Front matter](#1-front-matter)
- [2. Introduction](#2-introduction)
  - [a. Overview](#a-overview)
  - [b. Terminology](#b-terminology)
  - [c. Product and Technical Requirements](#c-product-and-technical-requirements)
  - [d. Out of Scope](#d-out-of-scope)
  - [e. Future Goals](#e-future-goals)
- [3. Solution](#3-solution)
  - [a. Existing Solution](#a-existing-solution)
  - [b. Test Plan](#b-test-plan)
- [8. End Matter](#8-end-matter)
  - [a. References](#a-references)

</details>

---

# 1. Front matter

The Project name is **Project Artificial Intelligence**

This Project is create by a team composed of

- Mathieu Chaput
- Maxime Pages
- Robin Debry
- Paul Nowak
- Florent Hureaux  

# 2. Introduction

## a. Overview

For this project we need to programm in **Python** for the beginning for :

- Recover the dataset with mozilla Common voice
- Extract the data
- Separate the data between train and test
- Transforme audio into images
- Create a model
- Save the model create before to import it after

After we have an arduino Board for this part we need to programm in **C++** to put the model in the board
With this board we have some LEDs to indicate the speech spoken.

## b. Terminology

This project is based on the AI so they have many words that people who arent't developper don't know. This misunderstanding can block you for the developping so we explain some technical terms
| Words | Meaning |
|-|-|
|AI| The Artificial intelligence the is theory and development of computer systems able to perform tasks normally requiring human intelligence, such as visual perception, speech recognition, decision-making, and translation between languages.

## c. Product and Technical Requirements

| Technical | Using |
|-|-|
|Python| We code in Python because it's the language that we learning at this time. |
|OS| This library can be used on Mac and Windows as we have these two different operating systems in our groups.|
|Google Colab |We use Google Colab for this project because it's less complicated to work on it in Python with the model |
|Arduino |We use Arduino to display with LEDs the result when we speak |
|Arduino Nano 33 BLE Sense |It's the type of arduino board we use to make this project |

## d. Out of Scope

For this project we can make an another model for three languages for example French/English/German and we can make the same system for the LEDs Red for english Green for french and blue for German

## e. Future Goals

For the future version we can add

- a raspberryPi to have more place
- a LCD screen to have the informations of accuracy and which language is on it.

# 3. Solution

## a. Existing Solution

there is a solution on github that allows to make a similar AI to the one we want to get because it does the same thing with different languages, it allows to do it between English and German.

## b. Test Plan

For this project we opted for the Google Colab to test and train the model and after we test it with the arduino board

# 8. End Matter

## a. References

https://colab.research.google.com
https://github.com/fraunhofer-iais/language-recognition<br>
http://docs.arduino.cc/tutorials/nano-33-ble-sense/get-started-with-machine-learning