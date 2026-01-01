CareerConnect – Resume–Job Matching Platform

CareerConnect is a web-based application that streamlines the process of matching candidate resumes with job descriptions using advanced Natural Language Processing (NLP) techniques. It provides an efficient and user-friendly interface for both candidates and companies.

🚀 Features
🔹 Main Menu & Navigation

Clean and intuitive user interface

Easy navigation to Login, Registration, About, and Articles sections

🔐 User Authentication

Secure user registration and login

Encrypted password storage

👤 User Roles
Candidate Registration & Login

Candidates can securely register and log in

Upload resumes in PDF format after authentication

Company Registration & Login

Companies can register and log in

Post job descriptions and search for matching resumes

📄 For Candidates

Resume Upload:
Candidates can upload their resumes in PDF format, which are securely stored in the database.

🏢 For Companies

Job Description Entry:
Companies can enter job descriptions to find the most suitable candidates.

Resume Matching (Core Feature):

A fine-tuned spaCy English model (en_core_web_sm) is used to extract technical and skill-based keywords.

Extracted keywords from job descriptions are matched with skills identified in candidate resumes stored in MongoDB.

Candidates are ranked based on the highest overlap of skills.

Candidates with no relevant skill overlap are excluded.

Companies can view and download matched resumes.

📌 Matching Logic Examples

Candidates with the highest skill overlap appear first.

Candidates without matching skills are not listed.

🛠️ Tech Stack
Back-End

Flask: Python-based micro web framework for application logic

MongoDB: NoSQL database for storing user data and resumes

spaCy: NLP library used for fine-tuning the base model to extract technical keywords

Front-End

HTML5: Structure and content

CSS3: Styling and layout

Infrastructure

GitHub: Version control and collaborative development

✅ Conclusion

CareerConnect is a powerful recruitment support platform that automates resume–job matching using NLP. Its secure authentication system, structured workflow, and intelligent ranking mechanism help recruiters identify the most relevant candidates efficiently, while providing job seekers with a smooth and secure experience.

🤝 Contributing

Contributions are welcome!
You can contribute by:

Enhancing existing features

Improving documentation

Adding new functionality
