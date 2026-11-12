# CSCU9M6 - Natural Language Processing and Computer Vision (Spring 2023)
*University of Stirling*

---

## Project Overview

This repository contains the code, dataset structure, and experimental evaluation for the **Image Classification Project**, completed as part of the CSCU9M6 module at the University of Stirling. 

The primary objective of this project is to apply pattern recognition and computer vision techniques to design, train, evaluate, and deploy an image classification system across two distinct locations (Cities A and B: **Stirling** and **Tallinn**).

---

## Table of Contents
1. [Problem Definition](#1-problem-definition)
2. [Dataset Structure](#2-dataset-structure)
3. [Dataloader & Preprocessing](#3-dataloader--preprocessing)
4. [Proposed Solution & Architecture](#4-proposed-solution--architecture)
5. [Experimental Tests & Evaluation (E1)](#5-experimental-tests--evaluation-e1)
6. [Running the Code](#6-running-the-code)
7. [License & Acknowledgments](#7-license--acknowledgments)

---

## 1. Problem Definition
The project addresses an image classification task involving urban environments from two specific geographic locations:
* **City A:** Tallinn
* **City B:** Stirling

The study object focuses on classifying **cars** from image scenes collected via remote repositories and structured into training and testing partitions. 

---

## 2. Dataset Structure
The dataset comprises positive and negative samples for both cities, split equally into training (50%) and testing (50%) subsets. The directory structure is organized as follows:

```text
cars/
├── cars_stirling/
│   ├── train/
│   │   ├── 0/ (Negative / Class 0)
│   │   └── 1/ (Positive / Class 1)
│   └── test/
│       ├── 0/
│       └── 1/
└── cars_tallinn/
    ├── train/
    │   ├── 0/
    │   └── 1/
    └── test/
        ├── 0/
        └── 1/