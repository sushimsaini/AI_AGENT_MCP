"
================================================================================
OPENAI IQ TEST GENERATOR
================================================================================

File:           iq_test_generator.py
Description:    Dual-stage OpenAI API interaction for IQ assessment generation
Author:         [Your Name]
Date:           [Current Date]

Workflow:
---------
1. INITIALIZATION
   - Load environment variables via python-dotenv
   - Initialize OpenAI client with API key

2. STAGE 1 - QUESTION GENERATION
   - Prompt: Request challenging IQ question
   - Model: gpt-4o-mini
   - Output: IQ test question

3. STAGE 2 - ANSWER GENERATION
   - Input: Generated question from Stage 1
   - Model: gpt-4o-mini  
   - Output: Answer to the question

4. PRESENTATION
   - Raw output printed to console
   - Formatted markdown display via IPython

API Calls:
----------
- Call 1: Generate question (temperature: default)
- Call 2: Generate answer (temperature: default)

Exit Codes:
----------
0: Success
1: API key missing

Example Output:
--------------
OpenAI API key exists and begins sk-12345678
IQ Question: [Generated question]
Answer: [Formatted answer in markdown]
"""
