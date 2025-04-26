# 🧠 React Quiz App

Welcome to **React Quiz**, a fun and interactive quiz application built with **React**! 🚀  
This project was developed as part of my journey through **Maximilian Schwarzmüller's React course** to practice core React concepts. 🌟

---

## 📚 Concepts Practiced

- 🧉 Deriving values from state
- ✍️ Outputting questions dynamically and registering user answers
- 🔀 Shuffling answers randomly
- 🔥 Implementing full quiz flow and logic
- ⏳ Adding countdown timers for questions
- ⚡ Using `useEffect` dependencies and optimizing with `useCallback`
- 🧹 Cleaning up side effects correctly
- 🔑 Resetting components using React `key` prop
- 🌟 Highlighting selected answers dynamically
- 💪 Splitting and organizing components properly
- 📦 Moving state and logic to the components that truly need them
- ⏱️ Setting different timers based on user interaction
- 🧾 Displaying a clean, detailed quiz result summary

---

## 🛠️ Project Structure

```
/src
 ├── /assets         # Static files (logo, images)
 ├── /components     # React components
 │    ├── Answers.jsx
 │    ├── Header.jsx
 │    ├── Question.jsx
 │    ├── QuestionTimer.jsx
 │    ├── Quiz.jsx
 │    └── Summary.jsx
 ├── questions.js     # Quiz questions data
 ├── App.jsx          # Main application component
 └── main.jsx         # React app entry point
```

---

## 🧙‍♂️ Main Components

| Component        | Description |
|------------------|-------------|
| **`Header.jsx`** 🖼️ | Displays the quiz logo and title. |
| **`Quiz.jsx`** 📜 | Manages the overall quiz flow (questions ➡️ summary). |
| **`Question.jsx`** ❓ | Displays individual questions and handles answer selection logic. |
| **`QuestionTimer.jsx`** ⏲️ | Controls the countdown timer and timeout behavior for each question. |
| **`Answers.jsx`** ✅❌ | Shows shuffled answer buttons with dynamic highlighting. |
| **`Summary.jsx`** 🏆 | Presents a detailed performance summary after the quiz ends. |

---

## 🧪 Key Features

- 🌟 **Instant feedback** after answering (correct/wrong/skipped)
- 🔀 **Randomized answers** for every new question
- ⏳ **Dynamic timers** based on user interactions
- 🧹 **Proper resource cleanup** using `useEffect`
- 🔄 **Resettable components** using the `key` prop
- ⚡ **Optimized rendering** with `useCallback` and `useRef`
- 🧲 **Detailed quiz result summary** at the end
- 🎨 **Responsive and clean UI design**

---

## 🚀 Live Demo

Check out the live project here:  
🔗 **[React Quiz Live](https://react-quiz-esmat.vercel.app/)**

---

## 🚪 How to Run Locally

Follow these steps to run the project locally on your machine:

1. **Clone the repository** 📂
   ```bash
   git clone https://github.com/Mohamed-Esmat/React-Quiz.git
   ```

2. **Navigate into the project directory** 📁
   ```bash
   cd React-Quiz
   ```

3. **Install project dependencies** 📦
   ```bash
   npm install
   ```

4. **Start the development server** ⚡
   ```bash
   npm run dev
   ```

5. **Open** [http://localhost:5173](http://localhost:5173) in your browser to see the app live! 🌐

---

## 📸 App Preview

| Question View | Timer Progress | Quiz Summary |
|:-------------:|:--------------:|:------------:|
| ![Question](![image](https://github.com/user-attachments/assets/6b6f1985-3bea-47aa-90c6-70e6732d304e)) | ![Timer](![image](https://github.com/user-attachments/assets/4ad203b1-820b-4567-80a0-264a1117912e)) | ![Summary](![image](https://github.com/user-attachments/assets/feefdcea-da85-4bbe-adf3-1720a2c797ba)) |

---

## 📜 License

This project is intended for **educational purposes** only 🧜‍♂️  
No commercial usage is permitted without permission.

---

## 👌 Acknowledgements

Special thanks to **Maximilian Schwarzmüller** 🎓 for his brilliant React tutorials and guidance.

---

## 🔗 Connect With Me

- 👨‍💻 [LinkedIn](https://www.linkedin.com/in/mohamed-esmat-abdalhafiz-frontend-developer/)
- 📧 Email: msmt0452@gmail.com

---

### 🌟 Keep Learning. Keep Building. Keep Growing. 🚀

