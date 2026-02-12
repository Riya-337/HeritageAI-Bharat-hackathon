HeritageAI Bharat
AI-powered dual-output platform for artisan heritage preservation and education.

Overview
HeritageAI Bharat is an innovative web application that transforms a single artisan documentation session (voice interview + photos) into two valuable outputs: authentic marketplace stories for direct sales and culturally relevant STEM lessons for students. Built on AWS serverless infrastructure, it empowers rural Indian artisans economically while providing free, NCERT-aligned educational content to students. The platform addresses dual national crises: artisan income disparity (up to 90% captured by intermediaries) and STEM education gaps (200M students struggling with abstract concepts).

This project is designed for solo hackathon MVP with AWS free tier constraints (₹0-1,000 budget, 2-week timeline), focusing on scalability, low-bandwidth optimization, and self-sustaining revenue.

Key Features
Dual-Output Pipeline: One documentation generates marketplace listings and educational lessons.
AI-Powered Generation: Uses AWS Transcribe, Rekognition, and Bedrock (Claude 3.5 Sonnet) for speech-to-text, image analysis, and content creation.
Multilingual Support: Hindi, English, Tamil for inclusive access.
Self-Sustaining Model: Marketplace revenue (85% to artisans) funds free education.
Low-Bandwidth Optimized: Works on 256 Kbps connections with compression and caching.
Privacy-Focused: Encrypts data, obtains consent, stores minimal personal info.

Tech Stack
Frontend: Streamlit (Python-based for rapid MVP development).
Backend: AWS Lambda (serverless compute), S3 (storage), DynamoDB (database).
AI Services: AWS Transcribe (speech-to-text), Rekognition (image analysis), Bedrock (content generation), Translate (multilingual support).
Languages: Python, C, JavaScript; DSA in C++ for algorithms.
Deployment: AWS EC2 t2.micro (free tier) or local for MVP

Files
Requirements: Detailed functional and non-functional requirements, user stories, acceptance criteria, and MVP scope.
Design: System architecture, components, data models, error handling, and testing strategy.

Documentation Overview
This repository contains the core documentation for the HeritageAI Bharat platform, submitted for Round 1 ideation in the hackathon. It includes requirements, design specs, and a presentation deck to demonstrate the concept's feasibility and impact. No prototype code is included yet—this is for concept evaluation only. If selected for Round 2, the prototype will be built based on these docs.

Solo Developer
Riya Aggarwal | 2nd Year B.E. CSE, RVCE (9.05 CGPA) | Technical Foundation: Proficient in Python, C, OOPS; Web Stack (HTML/CSS/JS); DSA in C++; Exploring AWS Serverless for social impact projects.

License
This project is for educational and hackathon purposes. All rights reserved.

For questions or contributions, contact: riyaaggarawal98473@gmail.com.

