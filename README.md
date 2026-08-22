# AI Resume & Cover Letter Tailor

Yeh ek lightweight **Turnkey AI Micro-SaaS** application hai jo job seekers ko unke resume ko kisi bhi Job Description (JD) ke hisaab se tailor karne me help karti hai. Yeh tool ATS (Applicant Tracking System) optimization ke liye missing keywords suggest karta hai aur ek tailored Cover Letter generate karke deta hai.

---

## 🌟 Key Features

* **Instant ATS Match Score**: Aapke resume aur Job Description ka match percentage dikhata hai.
* **Missing Keywords Identification**: Un important skills aur keywords ki list deta hai jo aapke resume me missing hain.
* **Automated Tailored Cover Letter**: Target job description ke according ready-to-use cover letter generate karta hai.
* **Turnkey & White-Label Friendly**: Easily customizable via `config.json` file.
* **Zero Backend Required**: Front-end single-page application jo directly client-side se OpenAI API consume karti hai.

---

## 🛠️ Tech Stack

* **HTML5 & CSS3**
* **Tailwind CSS** (via CDN) - Styling ke liye
* **Alpine.js** (via CDN) - Lightweight reactivity aur state management ke liye
* **OpenAI API** (`gpt-3.5-turbo`) - Resume analysis aur content generation ke liye

---

## 📁 Project Structure

```text
├── index.html     # Main UI application code (Tailwind + Alpine.js)
├── config.json    # App configurations (App name, description, default model)
