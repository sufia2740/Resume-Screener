# Advanced NLP-Powered Resume-Screener
An AI-driven application that leverages cutting-edge NLP technologies to streamline the recruitment process by accurately matching resumes to job descriptions. This project incorporates BERT-based models for candidate-job matching and utilizes AWS Lambda for scalable, efficient processing.

![image](https://github.com/user-attachments/assets/c00e6670-d020-42f9-b492-69464fcb44d9)

## Project Overview
This project uses advanced natural language processing (NLP) techniques to automate and enhance resume screening. By integrating BERT models and cloud-based automation, the screener achieves high accuracy in candidate-job matching and significantly reduces recruitment processing time.

### Key Highlights
* AI-Powered Matching: Utilized BERT-based models to achieve 96% accuracy in matching resumes to job descriptions.
* Automated Scoring: Implemented AWS Lambda functions to automate recruitment scoring, reducing processing time by 60%.
* Scalability: Built using Flask for deployment, with AWS Lambda ensuring seamless scalability.

## Tools & Technologies
* Python: Core programming language for model integration and backend logic.
* Hugging Face Transformers: Utilized pre-trained BERT models for semantic matching.
* Flask: Developed a lightweight and efficient web application.
* AWS Lambda: Enabled serverless automation of scoring functions.
* NLP Models: Fine-tuned transformer models for resume and job description analysis.

## Features
1. Resume Parsing: Extracts relevant information from resumes for analysis.
2. Job Description Analysis: Breaks down job descriptions to identify key skills and requirements.
3. Semantic Matching: Matches candidates to jobs using contextual embeddings from BERT.
4. Automated Scoring: Assigns a compatibility score to each resume-job pair using AWS Lambda.
5. Web Interface: A user-friendly interface built with Flask for uploading resumes and job descriptions.

## Project Achievements 
* High Accuracy: Achieved 96% candidate-job matching accuracy using advanced NLP techniques.
* Efficiency Gains: Reduced processing time by 60%, improving recruitment workflows.
* Scalable Deployment: Leveraged AWS Lambda for scalable and cost-effective scoring automation.

## How It Works
1. Input: User uploads resumes and job descriptions via the Flask web interface.
2. Processing:
   * Resumes and job descriptions are parsed.
   * Semantic matching is performed using BERT-based models.
   * AWS Lambda calculates compatibility scores.
3. Output: The system returns ranked candidates based on their scores.

## Future Enhancements
* Extend support for multi-language resumes and job descriptions.
* Incorporate additional models for specialized industries.
* Enable real-time updates with live data integration.

## Sample Output
* Ranked list of candidates with compatibility scores.
* Visual summaries of skill matches and mismatches.



