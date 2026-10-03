# 🤖 AI Quiz Generator

An AI-powered quiz application built using **HTML, CSS, JavaScript and Google Gemini API**.

The application lets users type any topic pick a difficulty level and get a multiple-choice quiz using **Google Gemini 2.5 Flash**.

---

## ✨ Features

* 🤖 AI-generated quiz questions

* 📝 Custom topic input

* 🎯 Easy, Medium and Hard difficulty levels

* ❓ 5 questions per quiz

* 🔘 4 multiple-choice options for each question

* Automatic answer evaluation

* 📊 Final score and percentage

* 📈 Quiz progress indicator

* 🔄 Try button

* ⚠️ Error handling for API issues

* 🔑 Bring Your Own API Key (BYOK)

* 📱 Responsive design

* 💻 Runs in any web browser

* 🚫 No backend server needed

---

## 🧠 How It Works

1. Type the topic you want to be tested on.

2. Pick a difficulty: Easy, Medium or Hard.

3. Enter your Google Gemini API key.

4. Click **Generate Quiz**.

5. Gemini creates 5 multiple-choice questions based on the topic and difficulty.

6. Answer each question one by one.

7. The app automatically calculates your score.

8. See your score and percentage.

---

## 🛠️ Technologies Used

* **HTML5**

* **CSS3**

* **JavaScript**

* **Google Gemini API**

* **Gemini 2.5 Flash**

No frameworks, libraries or build tools are used. The project is straightforward and easy to follow.

---

## 📂 Project Structure

```text

AI-QUIZ-GENERATOR-

│

├── index.html

└── README.md

```

The project is kept simple so beginners can understand, modify and run it without trouble.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash

git clone https://github.com/nilaynayyar/AI-QUIZ-GENERATOR-.git

```

### 2. Open the Project

Go into the project folder:

```bash

cd AI-QUIZ-GENERATOR-

```

Then open:

```text

index.html

```

in a web browser.

### 3. Enter Your Gemini API Key

The app uses a **Bring Your API Key (BYOK)** method.

You must enter your Google Gemini API key when you generate a quiz.

**Never store your API key in the source code. Upload it to GitHub.**

---

## 🔑 Gemini API

This project uses Google’s Gemini API to create quiz questions.

Official Gemini API documentation:

https://ai.google.dev/gemini-api/docs

The app sends the topic and difficulty level to Gemini. Asks for a set of multiple-choice questions in a structured format.

---

## 🔐 API Key Security

This project **does not include** any API key.

Important security rules:

* Do not hardcode the API key in `index.html`.

* Do not commit API keys to GitHub.

* Do not share API keys in screenshots.

* Users must input their key when using the app.

* The key is stored in the browser’s memory not saved anywhere.

> **Never publish a Gemini API key on GitHub or share it publicly.**

---

## 📋 Example

### Topic

```text

Python

```

### Difficulty

```text

Medium

```

### Result

The AI generates:

* 5 Python questions

* 4 options for each

* 1 answer for each

After answering all the app shows the final score and percentage.

---

## ⚠️ Error Handling

The app handles issues and shows messages for:

* Missing API key

* Invalid API key

* Failed API request

* Rate limits

* Invalid AI response

* Missing questions

* Response format

This helps users understand what went wrong instead of letting the app crash silently.

---

## 🎓 Purpose of the Project

The goal is to show how **Generative AI can be used in tools**.

Than using a fixed set of questions this app creates quizzes on the fly based on what the user wants.

It also teaches skills like:

* Integrating AI APIs

* Getting structured AI responses

* Handling user input

* Validating JSON data

* Building web pages

* Automatic scoring

* Error handling

* Responsive design

---

## 🔮 Future Improvements

Possible updates include:

* ⏱️ Time-limited quizzes

* 📚 subject categories

* 🧩 More question types (true/false fill-in, etc.)

* 📈 Quiz history tracking

* 🏆 Leaderboards

* 📊 Performance analysis

* 💾 Export quiz results

* 🔊 Text-to-speech for questions

* 🌐 language support

* 🔐 Backend protection for API keys

---

## 👨‍💻 Author

**Nilay Nayyar**

GitHub:

https://github.com/nilaynayyar

---

## 📄 License

This project is, for ** learning purposes**.
