# Sign Language Examination Evaluator

An automated system for evaluating sign language examinations using NLP and computer vision technologies.

## Overview

Sign language examinations typically consist of two components:
- **Written Component**: Tests theoretical knowledge of sign language and related topics (ethics, deaf culture, etc.)
- **Practical Component**: Evaluates the candidate's ability to perform hand signs and gestures

Traditional manual evaluation methods are time-consuming, costly, and logistically complex. This project aims to automate both components using AI technologies.

## Solution Architecture

### Written Component Evaluation
- **Technology**: Natural Language Processing (NLP)
- **Approach**: Semantic analysis to compare candidate answers with model responses
- **Process**:
  1. Pre-stored model answers for each question
  2. Semantic comparison between candidate and model answers
  3. Automated scoring based on semantic similarity

### Practical Component Evaluation
- **Technology**: Object Detection with Artificial Neural Networks (ANN)
- **Approach**: Real-time hand gesture recognition and classification
- **Process**:
  1. Webcam input capture using OpenCV
  2. Hand gesture detection and preprocessing
  3. ANN-based classification of hand signs
  4. Automated scoring based on gesture accuracy

## Technologies Used

- **Natural Language Processing**: For semantic analysis of written responses
- **Artificial Neural Networks**: For hand gesture classification
- **Computer Vision**: OpenCV for image processing and webcam integration
