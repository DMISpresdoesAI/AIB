# Giving Voice to a Palm-leaf Manuscript
## Human-AI Collaboration for the Arts and Humanities Project

## Project Overview
This project explores how Human-AI collaboration can be used to interpret and communicate cultural heritage objects to a general audience. It focuses on a palm-leaf manuscript held in the University of Glasgow Archives and Special Collections.

The project transforms the manuscript from a static archival project into an interactive experience. Through a guided AI system, users can ask questions about the manuscript and receive responses presented in both text and audio form. This approach aims to make the project more accessible while maintaining respect for its material form, cultural context, and historical uncertainty.

## The Object
The selected object is a Burmese palm-leaf manuscript from the University of Glasgow Archives and Special Collections.

Palm-leaf manuscripts are traditionally made from long, narrow leaves with engraved text, often bound together with cords. They are commonly associated with Buddhist textual traditions and were used to preserve religious and cultural knowledge.

While the manuscript holds significant cultural value, it can be difficult for a general audience to engage with due to language barriers, unfamiliar material form, and limited contextual information. This project addresses these challenges through AI-assisted interpretation.

## Project Objective
The aim of this project is to:

- Make the manuscript more accessible to a general audience  
- Explore how AI can support interpretive engagement with archival objects  
- Demonstrate how Human–AI collaboration can enhance creative communication  

Rather than generating fictional narratives, the project focuses on producing grounded, informative descriptions that reflect known characteristics of the manuscript.

## Human-AI Collaboration
The project uses generative AI as a collaborative tool rather than an autonomous creator.

The **human role** involves:
- Designing prompts
- Defining constraints (e.g avoiding fiction)
- Selecting and refining outputs

The **AI role** involves:
- Generating responses based on prompts
- Exploring different ways of expressing information

A constrained system prompt will ensure that the responses remain accurate, cautious, and focused on the manuscript's material and cultural context.

## Interactive System
The final output is a Jupyter Notebook interface where users will be able to:
- Select from guided questions about the manuscript
- Receive AI-generated responses in first-person perspective
- Listen to responses through AI-generated audio

This creates a conversational experience that allows users to engage more directly with the object while maintaining historical and cultural integrity.

## Tools and Technologies
This project will use the following tools:

1. **Generative AI (text)** - ChatGPT will be used to produce the interpretive responses
2. **ElevenLabs API** - used for text-to-speech audio generation
3. **ipywidgets** - used to create the interactive interface in Jupyter Notebook
4. **Python (requests library)** - used to connect to external APIs

## Repository Structure
Project-folder (AIB)
- README.md
- 01_manuscript_interaction.ipynb # Final interactive system
- 02_prompt_design_and_exploration.ipynb # Process and experimentation
- requirements.txt

## Ethical Considerations
This project recognises the importance of representing cultural heritage objects responsibly.

- AI responses are constrained to avoid inventing historical details
- Uncertainty is acknowledged where information is unknown
- The manuscript is not fictionalised or given an imagined biography

## Notes
- An internet connection is required for audio generation via the ElevenLabs API
