<p align="center">
  <img src="https://via.placeholder.com/120x120/7c5cfc/ffffff?text=AI" width="120" style="border-radius:50%;" />
</p>

<h1 align="center">🎨 AI Image Generator</h1>

<p align="center">
  <strong>Generate stunning images from text prompts — instantly.</strong><br/>
  <a href="https://aimgen-web.onrender.com">🌐 Live Demo</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-online-brightgreen" />
  <img src="https://img.shields.io/badge/version-1.0.0-blue" />
  <img src="https://img.shields.io/badge/license-MIT-green" />
</p>

---

## 🚀 Features

- 🎨 **AI Image Generation** – Powered by Pollinations.ai (no API key needed)
- 🤖 **Smart Prompt Enhancer** – Automatically adds style keywords (cinematic, 8k, photorealistic)
- 📦 **JSON Prep Log** – Shows original prompt, enhanced prompt, and metadata
- 💫 **Loading Overlay** – Spinner + "Generating…" animation on top of image
- 📱 **Responsive** – Works on desktop, tablet, and mobile
- 🧊 **Pure Static** – No backend — just HTML, CSS, JS

---

## 🧠 How It Works

1. You type a prompt (e.g., *"a dragon flying over a castle"*)
2. The AI **enhances** it locally with style keywords
3. The **JSON preparation log** shows exactly what's being sent
4. Pollinations.ai generates the image on the fly
5. The image appears with a smooth loading animation

---

## 🏃‍♂️ Run Locally

```bash
git clone https://github.com/your-username/aimgen-web.git
cd aimgen-web
open public/index.html
Or use a local server:

bash
python3 -m http.server 8000
Then visit http://localhost:8000/public/

📂 Project Structure
text
aimgen-web/
├── public/
│   └── index.html   ← Main app (all-in-one)
└── README.md        ← This file
🌐 Deployment
Deployed on Render as a Static Site:

Setting	Value
Build Command	(empty)
Publish Directory	public
Auto-deploy	Yes (on push to main)
🛠️ Future Improvements
□ Save generated images to a gallery (localStorage)
□ Download button for each image
□ Random "Surprise Me" prompts
🙏 Credits
Pollinations.ai – Free image generation API

Render – Free static hosting

📄 License
MIT © Your Name — free to use, modify, and share.

<p align="center"> <sub>Made with ❤️ by DeepSeek</sub> </p> ```
✅ What's included
Badges – status, version, license (dynamic via shields.io)

Live Demo link – points to your Render URL

Clear sections – Features, How it works, Run locally, Deployment

No external dependencies – pure markdown + shields.io badges (which are standard)

Minimal but professional
