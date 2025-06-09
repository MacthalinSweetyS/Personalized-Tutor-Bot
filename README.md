```markdown
# Personalized Tutor Bot

**Personalized Tutor Bot** is an AI-powered interactive learning platform designed to assess users’ learning capacity, recommend personalized career paths, and provide detailed performance feedback. This project includes modules for:

- **Learning Capacity Analysis**  
- **Goal Selection & Recommendation**  
- **Final Assessment & Performance Feedback**  
- **Interactive Chat Bot**  
- **Personal Notes with File Uploads**

---

## Features

- **User Authentication:**  
  Users can **sign up** and **log in** with a modern, responsive interface.

- **Profile Management:**  
  After logging in, users can manage their profiles. Students choose their education level (School, College, or Graduated), while Working Professionals and Others enter relevant information. This data is used to tailor quizzes and recommendations.

- **Adaptive Assessments:**  
  The Learning Capacity Test is generated dynamically according to the user's profile. The platform adapts question difficulty in real time and displays a detailed result with an animated pie chart.

- **Personalized Study Paths:**  
  Based on the user's goals and quiz performance, the Goal Selection module creates a customized learning path with targeted resources and recommendations.

- **Final Exam & Feedback:**  
  The Final Exam delivers tailored questions in a scrollable container, complete with a running timer. Detailed, formatted feedback is provided post-assessment.

- **Interactive Chat Bot:**  
  Users can interact with an AI-powered chat bot using an enhanced messaging interface with square send/mic buttons.

- **Progress Tracking:**  
  A progress bar is fixed at the left center of the dashboard to provide a visual indicator of overall progress.

---

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/YourUsername/PersonalizedTutorBot.git
   cd PersonalizedTutorBot
   ```

2. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use: venv\Scripts\activate
   ```

3. **Install Dependencies**

   Install required packages using:

   ```bash
   pip install -r requirements.txt
   ```

   If you don’t have a `requirements.txt`, install these manually:
   
   - Flask ([Flask Docs](https://flask.palletsprojects.com/))
   - openai

4. **Project Structure**

   Ensure your project structure resembles the following:
   ```
   PersonalizedTutorBot/
   ├── app.py
   ├── users.json          # Initialized with {}
   ├── notes.json          # Initialized with {}
   ├── uploads/            # Directory for file uploads
   ├── templates/
   │     └── index.html
   └── static/
         ├── styles.css
         ├── home_icon.png
         ├── avatar.png
         ├── robot.gif
         └── tutor_bot.png
   ```

5. **Configure API Key**

   In **app.py**, replace the placeholder API key (`sk-or-v1-dff1e`) with your valid OpenAI API key.

6. **Run the Application**

   ```bash
   python app.py
   ```

   Open your browser and navigate to [http://localhost:5000](http://localhost:5000).

---

## Usage

- **Sign Up / Log In:**  
  Users must sign up or log in before accessing any of the platform’s features.

- **Profile Management:**  
  Once logged in, update your profile with your educational or professional details to receive personalized quizzes and recommendations.

- **Learning Capacity Test:**  
  Take the adaptive quiz to assess your learning capacity. Detailed results and animated visual feedback are provided upon completion.

- **Goal Selection & Final Exam:**  
  Define your career goal to generate a personalized study plan. Then, complete the final exam to receive in-depth feedback and recommendations.

- **Interactive Chat Bot:**  
  Use the chat bot for immediate assistance and personalized advice.

- **Personal Notes:**  
  Save your study notes or upload files for later reference.

---

## Contributing

Contributions are always welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes. For more details, see our [CONTRIBUTING.md](https://github.com/YourUsername/PersonalizedTutorBot/blob/main/CONTRIBUTING.md).

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://opensource.org/licenses/MIT) file for details.

---

## Resources & References

- **[Flask Documentation](https://flask.palletsprojects.com/)**  
- **[OpenAI API Documentation](https://platform.openai.com/docs/)**  
- **[Chart.js](https://www.chartjs.org/)**  
- **[Tippy.js](https://atomiks.github.io/tippyjs/)**

---

## Acknowledgements

Special thanks to the open-source community for their contributions and support.

