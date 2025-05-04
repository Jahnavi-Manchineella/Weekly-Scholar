# Weekly-Scholar
Weekly Scholar 🎓
Race through your syllabus, week by week!

Weekly Scholar is an AI-powered tool designed to simplify study planning. By uploading a syllabus or topic PDF and specifying a timeline, users receive a customized weekly roadmap with clear objectives and short study notes. It’s the perfect companion for students aiming to stay consistent and focused in their academic journey.

🚀 Features
AI-Generated Weekly Roadmaps
Automatically divides your syllabus into weekly segments with actionable learning objectives.

PDF Upload Support
Users can upload any syllabus or topic in PDF format for roadmap generation.

Personalized Plans
Tailors study plans to the number of weeks entered by the user.

Elegant UI/UX
A clean and modern interface ensures a user-friendly experience.

Dynamic Output
Displays weekly study cards with:

Topics for the week

Learning objectives

Study notes

🌟 How It Works
Upload: Provide your syllabus or topic in PDF format.

Set Timeline: Enter the number of weeks to complete your study.

Generate Roadmap: Weekly Scholar processes the input and generates a personalized roadmap.

Review Output: The roadmap is displayed as interactive cards, breaking down weekly tasks.

🛠️ Tech Stack
Frontend: Built with Lovable for a dynamic web experience.

Backend: n8n for workflow automation and Groq API for AI-powered text processing.

AI Engine: LLaMA3-8B-8192 for generating human-like responses and study notes.

📖 Project Structure
pgsql
Copy
Edit
.
├── frontend/
│   ├── components/
│   ├── pages/
│   └── styles/
├── backend/
│   ├── webhook/
│   └── pdf-parser/
├── assets/
│   ├── images/
│   └── icons/
├── roadmap-generator/
│   └── AI-engine/
└── README.md
🧩 Future Enhancements
Integrate progress tracking for students.

Provide free resources (videos, articles) linked to weekly topics.

Add note-taking functionality under each week.

Synchronize roadmaps with calendar reminders.

Include quiz generators for periodic reviews.

🖼️ Screenshots
Landing Page

Weekly Roadmap

🛠️ Setup Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/weekly-scholar.git
Navigate to the project directory:

bash
Copy
Edit
cd weekly-scholar
Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm run dev
📝 Contributing
We welcome contributions! Please follow these steps:

Fork the repository.

Create a new branch:

bash
Copy
Edit
git checkout -b feature-name
Commit your changes:

bash
Copy
Edit
git commit -m "Add feature-name"
Push the branch:

bash
Copy
Edit
git push origin feature-name
Open a pull request.

🤝 License
This project is licensed under the MIT License.
