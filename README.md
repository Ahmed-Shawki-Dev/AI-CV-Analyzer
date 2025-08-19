# 📄 AI CV Analyzer  

Web app that analyzes CVs using **Google Gemini AI**.  
Built with **Vite + React + Chakra UI** (frontend) and **Strapi** (backend).  

---

## 🔥 How to Run  

```bash
# 1. Clone the repo
git clone https://github.com/Ahmed-Shawki-Dev/AI-CV-Analyzer.git
cd AI-CV-Analyzer

# 2. Install dependencies
npm install

# 3. Start Vite dev server
npm run dev
````

App runs on:

```
http://localhost:5173
```

---

## ⚙️ Config

* Get an API key from [Google AI Studio](https://ai.google.dev/).
* Add it in the code:

```ts
const ai = new GoogleGenAI({ apiKey: "YOUR_API_KEY" });
```

---

## ✨ Features

* Upload PDF CV and extract text with `pdfjs-dist`.
* Analyze using **Google Gemini AI**.
* Authentication + Protected Routes.
* Responsive design with Chakra UI.
* Strapi backend for content management.

---

## 📜 License

MUC © Projects

```

عايز أبسطها أكتر وأخليها **سطرين بس** (زي introduction + installation) ولا كده مناسب؟
```
