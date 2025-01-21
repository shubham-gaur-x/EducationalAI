Generative AI Education Assistant Project
This project explores the use of Generative AI (ChatGPT) to create an interactive and personalized education assistant. The assistant helps a hypothetical 10th-grade student, Alex, strengthen their skills in algebra and physics through tailored learning profiles, study plans, quizzes, and chatbot simulations.

Features
Learning Profile Generation:

Creates a detailed learning profile for Alex, highlighting strengths, areas for improvement, and preferred learning methods.
Provides actionable recommendations for study strategies and resources.
Personalized Study Plan:

Designs a 4-week study plan targeting Alex’s academic goals in algebra and physics.
Includes daily objectives, tasks, and recommended tools like Khan Academy and PhET Interactive Simulations.
Quiz Generation:

Generates subject-specific quizzes in algebra and physics.
Ensures questions are challenging yet appropriate for a 10th-grade student.
Chatbot Simulation:

Simulates an interactive chatbot to guide Alex in solving linear equations step-by-step.
Iterative improvements enhance the chatbot’s engagement, clarity, and motivational tone.
Files and Structure
src/
learning_profile.py: Generates the learning profile.
study_plan.py: Creates the personalized study plan.
quiz_generation.py: Generates algebra and physics quizzes.
chatbot_simulation.py: Simulates a chatbot for math guidance.
assets/
prompts.md: Prompts used for the AI models.
outputs/: Generated outputs from each stage.
README: Project documentation.
requirements.txt: Python dependencies.
.env: Environment variables (e.g., OpenAI API key).
Prerequisites
Python 3.7 or higher
OpenAI Python SDK
dotenv package for environment variables
Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/genai-education-assistant.git
cd genai-education-assistant
Set Up the Environment:

Create a .env file in the root directory:
makefile
Copy
Edit
OPENAI_API_KEY=your-api-key-here
Install Dependencies:

Copy
Edit
pip install -r requirements.txt
Usage
Generate Learning Profile:

bash
Copy
Edit
python src/learning_profile.py
Create a Study Plan:

bash
Copy
Edit
python src/study_plan.py
Generate Quizzes:

bash
Copy
Edit
python src/quiz_generation.py
Run Chatbot Simulation:

bash
Copy
Edit
python src/chatbot_simulation.py
Key Learnings and Challenges
Prompt Engineering: Iteratively refined prompts to ensure high-quality, contextually appropriate outputs.
Balancing Clarity and Engagement: Strived to make interactions concise, engaging, and student-friendly.
Token Limit Management: Handled token limits in API calls to avoid truncation and ensure completeness.
Interactive Design: Enhanced chatbot interactions across iterations to improve motivation and understanding.
Future Enhancements
Include more diverse quizzes (e.g., real-world problems).
Integrate alternative problem-solving approaches (e.g., graphical solutions).
Expand functionality to support additional subjects.
Use a database to store and analyze Alex’s progress over time.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or suggestions, feel free to reach out:

Name: Shubham Gaur
Email: your.email@example.com
GitHub: yourusername
