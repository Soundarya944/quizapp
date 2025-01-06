# 📚 QuizApp

**QuizApp** is a ReactJS-based web application that allows users to take assessments by solving multiple-choice questions (MCQs). The app ensures a seamless user experience with interactive features such as validations, real-time scoring, and a final result display.

---

## ✨ Features

- **Interactive Quiz**:  
  Users solve MCQs presented one question at a time, ensuring focus and ease of use.

- **Option Selection Validation**:  
  Users cannot proceed to the next question without selecting an option, reducing errors and ensuring meaningful engagement.

- **Dynamic Scoring**:  
  Scores are calculated in real time using a dedicated state variable.

- **Final Score Display**:  
  Upon completing the quiz, users receive their total score along with a summary.

- **User-Friendly Interface**:  
  The app provides a smooth, intuitive interface, making it easy to navigate and take quizzes.

---

## 🛠️ How It Works

1. **Start the Quiz**  
   - The quiz begins with the first question displayed prominently on the screen.

2. **Option Selection**  
   - Users must select an option for each question to enable the **"Next"** button.  
   - If no option is selected, users are prompted to make a selection before proceeding.

3. **Score Calculation**  
   - The application updates the score dynamically based on the correctness of the user's selected answers.  

4. **Final Score**  
   - After completing all questions, users are presented with their final score, which is displayed as:  
     ```
     Your Score: [X]/[Total Questions]
     ```

---

## 💻 Technologies Used

- **ReactJS**: Frontend framework used to build the application.  
- **State Management**: Implemented using React's `useState` and `useEffect` hooks.  
- **CSS**: Custom styles to ensure a visually appealing and responsive design.  

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
Run the following command to clone the repository:
```bash
git clone https://github.com/your-username/quizapp.git
