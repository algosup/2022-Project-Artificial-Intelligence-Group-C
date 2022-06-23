# Technical Specification

---

<details>

<summary> Table of Contents</summary>
  
- [Technical Specification](#technical-specification)
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

## 1. Front matter

The Project name is **Project Artificial Intelligence**

This Project is created by a team composed of

- Mathieu Chaput
- Maxime Pages
- Robin Debry
- Paul Nowak
- Florent Hureaux  

## 2. Introduction

### a. Overview

For this project we need to programm in **Python** for the beginning for :

- Recovering the dataset with mozilla Common voice
- Extracting the data
- Separating the data between train and test
- Transforming audio into images
- Creating a model
- Saving the model create before importing it 

After that, we have an Arduino Board that we need to programm in **C++** to put the model in the board.
With this board we have some LEDs to indicate the speech spoken.

### b. Terminology

This project is based on the AI so they are many words that people who arent't developper don't know. This misunderstanding can block you for the developping so we are explaining some technical terms
| Words | Meaning |
|-|-|
|AI| The Artificial intelligence is the theory and development of computer systems able to perform tasks normally requiring human intelligence, such as visual perception, speech recognition, decision-making, and translation between languages.

### c. Product and Technical Requirements

| Technical | Using |
|-|-|
|Python| We code in Python because it's the language that we were learning at this time. |
|OS| This library can be used on Mac and Windows as we have these two different operating systems in our groups.|
|Google Colab |We use Google Colab for this project because it's less complicated to work on it in Python with the model. |
|Arduino |We use Arduino to display with LEDs the result when we speak. |
|Arduino Nano 33 BLE Sense |It's the type of arduino board we use to make this project. |

### d. Out of Scope

For this project we can make an another model for three languages for example French/English/German and we can make the same system for the LEDs: Red for English, Green for French, and Blue for German.

## e. Future Goals

For the future version we can add

- a raspberryPi to have more place.
- a LCD screen to have the informations of accuracy and which language is detected.

## 3. Solution

### a. Existing Solution

There is a solution on github that allows us to make a similar AI to the one we want to get. Indeed, it does the same thing with different languages, and allows us to detect between English and German.

### b. Test Plan

For this project, we opted for the Google Colab to train and test the model, before testing it with the arduino board.

## 8. End Matter

### a. References

**Google Colab :**
<https://colab.research.google.com>
**Github for language recognition between german and english :**
<https://github.com/fraunhofer-iais/language-recognition>
**Documentation of Arduino for the nano 33 ble sense :**
<http://docs.arduino.cc/tutorials/nano-33-ble-sense/get-started-with-machine-learning>
