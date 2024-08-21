# Introduction

This document serves as an extensive manual detailing our approach to the development of a boxing psychological state tracking system. It provides the reader with the system's blueprint, explaining the various components and their interactions. The document is organized into sections that address key aspects such as structure, subunits, interfaces, methodology, and implementation methods.

## System Overview

The primary objective of the system is to analyze the psychological state of the boxer over the course of a fight and identify how it impacts their performance. The system integrates survey data on various psychological factors such as self-confidence, anxiety, team identity, and opponent strength, along with physical indicators like cuts and knockdowns.

## Requirements and Design Considerations

- **Psychological Analysis and Action Recognition:**
  - The system should simultaneously analyze the psychological state of the boxer while performing action recognition and classification.

- **Dynamic Models:**
  - Implementation of dynamic models is required, allowing for parameter updates throughout the fight to enhance prediction accuracy.

- **Advanced Processing Techniques:**
  - Utilize deep learning algorithms for image processing and natural language processing (NLP) techniques for text analysis.

- **User Interface:**
  - Develop an intuitive UI that enables users to upload fight videos and subsequently view the analysis results.

- **Explainability:**
  - Incorporate LIME (Local Interpretable Model-agnostic Explanations) to explain the model's predictions, ensuring transparency and understandability.
