# personal-health-coach-scaledown
# Personal Health Coach – ScaleDown Challenge

## Overview
This project is part of the ScaleDown Challenge (Challenge 2).  
It focuses on compressing medical history and wellness data into concise, structured representations to reduce token usage while still enabling personalized health recommendations.

## Problem Statement
Health data is often verbose and redundant, leading to high processing costs when used with AI systems.  
The goal of this project is to design a lightweight health coaching agent that summarizes user data efficiently without losing critical context.

## Solution Approach
- Accepts medical history and lifestyle information as text input
- Compresses data into structured key-value summaries
- Removes redundancy and non-essential tokens
- Generates personalized, non-diagnostic health suggestions

## Example

### Input
- Medical history: Long text describing conditions, medications, habits
- Lifestyle data: Sleep, diet, exercise patterns

### Compressed Output
- Conditions: Hypertension
- Medications: Amlodipine
- Lifestyle: Low activity, irregular sleep
- Risk Flags: High BP

### Recommendations
- Increase daily physical activity
- Maintain consistent sleep schedule
- Monitor blood pressure regularly

## Token Reduction
The compressed format reduces input size significantly, lowering inference cost while preserving essential information.

## Tech Stack
- Python
- Rule-based compression
- Structured summarization logic

## Future Improvements
- Add real-time wellness tracking
- Improve compression using embeddings
- Integrate privacy-first local processing

## Disclaimer
This project is for educational purposes only and does not provide medical advice.
