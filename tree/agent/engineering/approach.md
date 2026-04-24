# Engineering Approach

## Overview
This project implements a deterministic reflection system using a structured decision tree.

## Part A: Reflection Tree
- The reflection process is designed as a connected tree of open-ended questions
- Each question leads to deeper thinking based on previous responses
- No multiple-choice questions are used

## Design Principles
- Non-judgmental questioning
- Encourages self-reflection
- Covers three axes:
  - Locus (internal vs external control)
  - Orientation (past vs future)
  - Valence (positive vs negative)

## Part B: AI Agent (Optional)
- The AI does not generate new questions
- It only selects the next question from the predefined tree

## Guardrails to Prevent Hallucination
- The system restricts outputs to predefined questions
- No external knowledge is introduced
- AI is only used for classification (tone and control)

## Conclusion
This approach ensures structured, meaningful, and safe reflection.
