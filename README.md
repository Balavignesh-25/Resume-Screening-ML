# Resume Screening Project

## Overview
This project is a Resume Screening System designed to help HR professionals and recruiters efficiently filter resumes based on given criteria using machine learning algorithms. The system automates the process of screening resumes to make recruitment faster and more efficient.

## Features
- **Text Extraction**: Extracts text from resumes in PDF or DOCX format.
- **Skill Matching**: Matches specific skills from the resume with job requirements.
- **Candidate Scoring**: Uses machine learning models to assign a score to each resume based on how well it matches the job description.
- **User Interface**: Interactive interface to upload resumes and get results using Gradio.
- **Data Visualization**: Visualize the distribution of candidate scores with charts.

## Dependencies
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computations.
- **scikit-learn**: Machine learning models.
- **matplotlib**: Plotting library for data visualization.
- **seaborn**: Data visualization library for statistical graphics.
- **gradio**: Library to create an easy-to-use interface.

## Usage
1. Install the required dependencies using the command mentioned above.
2. Upload a resume (PDF or DOCX format) using the Gradio interface.
3. The system will process the resume, match skills with the job description, and display a score based on the match.

## How It Works
- **Data Collection**: The system collects the resume data and job description.
- **Text Preprocessing**: It preprocesses the resume by removing stop words and performing tokenization.
- **Feature Extraction**: Extracts features like skills, experience, and education.
- **Model Prediction**: The resume is scored using a machine learning model that classifies the relevance of the resume to the job description.
- **Results**: The results are displayed on a Gradio interface with visual representations.

## Example Usage
To use the resume screening tool, simply run the `app.py` script and upload resumes. Here's an example:
1. Upload a resume file.
2. View the candidate’s score based on how closely the resume matches the job requirements.
3. View the skill-based analysis and visualization of the candidate’s performance.

## Contribution
If you'd like to contribute to this project, feel free to fork the repository and make improvements. Pull requests are always welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.
