AI-Powered Resume Screening and Ranking System

The "AI-Powered Resume Screening and Ranking System" is an advanced automated solution designed to enhance the efficiency of the recruitment process. By leveraging state-of-the-art technologies, this system allows HR professionals and recruiters to quickly assess and rank resumes based on their relevance to specific job descriptions. The system processes resumes in PDF format and generates ranked results, offering a clear comparison with job descriptions using similarity scores.

Key Features:
- Upload multiple PDF resumes for processing.
- Input a job description to benchmark resumes against.
- Rank resumes using Term Frequency-Inverse Document Frequency (TF-IDF) and Cosine Similarity metrics.
- Display ranked resumes along with their similarity scores.

Project Structure:
resume_screening_app/
│── .venv/
│── app.py
│── requirements.txt
├── resume_ranking.ipynb
│── data/
│   ├── sample_resume.pdf
│── README.md
│── .gitignore


Installation & Setup:
1. Clone the repository to your local machine.
2. (Optional) Create a virtual environment:
3. Install the required dependencies:
4. Launch the application with Streamlit:
   
How It Works:
1. Upload resumes in PDF format using the file uploader.
2. Input the job description into the provided text box.
3. The system processes each resume, converting it into TF-IDF vectors for text comparison.
4. The job description is analyzed and compared to each resume using cosine similarity.
5. Resumes are ranked according to their similarity to the job description, and the results are displayed along with their respective similarity scores.

Deployment:
To deploy the application on Streamlit Cloud (Free Tier):
1. Push the project to your GitHub repository.
2. Log in to [Streamlit Cloud](https://streamlit.io/cloud).
3. Click **New App**, select your GitHub repository, and set `app.py` as the entry point.
4. Click **Deploy** to launch the app.

System Requirements:
- streamlit
- PyPDF2
- pandas
- scikit-learn
- numpy


Target Audience:
- HR Professionals & Recruiters – Automate the resume screening process, significantly improving the speed and accuracy of candidate evaluation.
- Hiring Managers – Quickly rank resumes to streamline the shortlisting process for open positions.
- Job Portals – Enhance the accuracy of resume-to-job matching, improving user experience and search relevance.
- AI Enthusiasts & Students – Gain practical experience with Natural Language Processing (NLP) techniques in the context of recruitment.

Future Enhancements:
- AI-Based Scoring – Integrate machine learning or deep learning models for a more sophisticated ranking algorithm.
- Advanced NLP Models – Utilize models like BERT or GPT for deeper text analysis and more accurate matches.
- Multi-Format Support – Extend the system to support other file formats, such as DOCX, TXT, and OCR-based image files.
- Automatic Skill Extraction – Incorporate skill extraction algorithms to enhance resume ranking and provide more granular analysis.
- API Integration – Develop API integrations to connect seamlessly with third-party job portals and HR systems.

Conclusion:
The AI-Powered Resume Screening and Ranking System offers a transformative solution to the challenges of manual resume screening. By utilizing advanced NLP techniques, including TF-IDF and Cosine Similarity, this system delivers fast, accurate, and unbiased candidate evaluations. With simple deployment via Streamlit and real-time resume ranking, this tool provides a powerful and scalable solution for HR professionals, recruiters, and job portals. The future enhancements outlined will further increase the system’s capabilities, providing deeper analysis and broader use cases in the recruitment process.

[Streamlit Cloud Deployment](https://ai-powered-resume-screening-and-ranking-system-6925.streamlit.app)

---

This revision maintains professionalism while clearly communicating the core aspects of the project. Let me know if you'd like any additional changes!
