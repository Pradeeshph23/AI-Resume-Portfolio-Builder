Got it—you want a **clean GitHub-style README using proper `#` headings** (no extras). Here’s a polished version 👇

---

# 🚀 AI Resume & Portfolio Builder

An AI-powered web application to **create, analyze, and optimize resumes and portfolio content** using advanced language models.

This project integrates **ATS analysis, resume parsing, and AI-driven content enhancement** into a single streamlined platform.

---

# 🌟 Features

* 🤖 AI Resume Builder – Generate resumes with intelligent suggestions
* 📊 ATS Analysis – Evaluate resumes for Applicant Tracking Systems
* ✍️ Content Optimization – Improve bullet points, metrics, and keywords
* 📄 PDF Parsing – Extract text using PyPDF2
* 📝 DOCX Generation – Export resumes using python-docx
* 🎯 Prompt-Based AI System – Modular prompt design
* ⚡ Interactive UI – Built with Streamlit

---

# 🛠️ Tech Stack

* **Frontend/UI:** Streamlit
* **Backend:** Python
* **AI Integration:** OpenAI API

**Libraries Used:**

* streamlit
* openai
* python-docx
* PyPDF2

---

# 📁 Project Structure

```
AI-Resume-Portfolio-Builder/
│
├── app.py
├── requirement.txt
│
├── OptiResume/
│   ├── main.py
│   └── utils.py
│
├── Prompts/
│   ├── ATS Analysis.txt
│   ├── ATS_Check.txt
│   ├── Bullet Point Analysis.txt
│   ├── Bullet_Prompt.txt
│   ├── Keyword_Prompt.txt
│   ├── Metric_Prompt.txt
│   └── Optimisation-Prompt.txt
│
├── static/
│   └── styles.css
```

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/Pradeeshph23/AI-Resume-Portfolio-Builder.git
cd AI-Resume-Portfolio-Builder/AI\ Resume\ \&\ Portfolio\ Builder
```

---

## 2. Install Dependencies

```bash
pip install -r requirement.txt
```

---

## 3. Set OpenAI API Key

```bash
export OPENAI_API_KEY=your_api_key_here
```

**Windows (PowerShell):**

```powershell
setx OPENAI_API_KEY "your_api_key_here"
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

Open in browser:
[http://localhost:8501](http://localhost:8501)

---
# ScreenShot

<img width="1907" height="979" alt="image" src="https://github.com/user-attachments/assets/fb74ff17-ca5d-4fa1-8bc0-4eeb1b129bb8" />


# 🧠 How It Works

1. Upload your resume (PDF)
2. Extracts and analyzes content
3. Uses AI prompts to:

   * Improve bullet points
   * Add measurable metrics
   * Optimize keywords
4. Generates enhanced resume output
5. Download or reuse for portfolio

---

# 📌 Modules Overview

## 🔹 OptiResume

* Core resume processing logic
* AI integration
* Content structuring

## 🔹 Prompts

* ATS analysis
* Bullet optimization
* Keyword enhancement
* Resume improvement

## 🔹 Static

* UI styling (CSS for Streamlit)

---

# 🚀 Future Enhancements

* Multi-template resume support
* ATS score dashboard
* Cover letter generator
* Portfolio website generator
* Cloud deployment

---

# 🤝 Contributing

```bash
git checkout -b feature-branch
git commit -m "Added new feature"
git push origin feature-branch
```

---

# 📄 License

This project is licensed under the MIT License.

---

# 🙌 Support

If you like this project:

* ⭐ Star the repo
* 🍴 Fork it
* 📢 Share it

---

# 👨‍💻 Author

**Pradeesh**
AI & Data Science Student

---
# 💡 Inspiration

Creating impactful resumes is difficult and time-consuming.
This project simplifies the process using AI to make resumes smarter, faster, and more effective.
