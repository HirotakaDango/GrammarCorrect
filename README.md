# GrammarCorrect

A fast, lightweight, and modern web application for grammar checking, text editing, AI-powered document summarization, and originality checking. Built with React, Tailwind CSS, and powered by Google Gemini and Gemma models.

<img width="1366" height="768" alt="GrammarCorrect Interface" src="https://github.com/user-attachments/assets/8a4ef5db-5c8a-470b-8c61-b10d392e57b7" />

## Features

- 📝 **Real-Time Grammar & Style Correction**: Highlights spelling errors, grammatical mistakes, and stylistic improvements directly in the editor with custom severity styles.
- 🎯 **Click-to-Navigate & Interactive Popovers**: Click on any highlighted text in the editor or suggestion card in the sidebar to view contextual explanations, apply edits, or navigate directly to the exact text position.
- ⚡ **Correct All**: Fix all identified issues across selected categories with a single click.
- 📊 **Dynamic Score Rating**: Overall text quality score dynamically recalculates in real-time as you accept or dismiss corrections.
- 📋 **Executive Summary Tab**: Generates high-level takeaways, key points, sentiment/tone analysis, and estimated reading time.
- 🛡️ **Originality & Plagiarism Checker**: Scans text to detect potentially derivative, unoriginal, or clichéd passages and generates an originality score.
- 🎛️ **Tone & Temperature Control**: Adjust writing tone settings (Professional, Casual, Academic, Creative) and model temperature/creativity sliders.
- 💾 **OPFS Local Storage**: Uses Origin Private File System (OPFS) with LocalStorage fallback to automatically save drafts locally.
- 🤖 **Multiple Model Support**: Switch seamlessly between various Google Gemini and Gemma models.
- 🌙 **Dark Mode**: Fully supports light and dark themes.
- 📱 **Responsive Design**: Mobile-friendly layout featuring collapsible sidebars, custom scrollbars, and touch-optimized controls.

## Supported Models

### Google Gemini Models
- Gemini 3.7 Flash
- Gemini 3.6 Flash
- Gemini 3.5 Flash
- Gemini 3.5 Flash-Lite *(Default)*
- Gemini 3.1 Pro (Preview)
- Gemini 3.1 Flash-Lite

### Google Gemma Models (AI Studio)
- Gemma 4 31B Instruct
- Gemma 4 12B Instruct
- Gemma 3 27B Instruct
- Gemma 3 4B Instruct
- Gemma 2 27B Instruct

## Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/GrammarCorrect.git
   cd GrammarCorrect
   ```

2. **Run locally:**
   Simply open `index.html` (or `ai_grammar_checker.html`) in any modern web browser. No complex build step or server setup required!

3. **API Key Setup:**
   Provide your Google Gemini API key in the top settings bar to start analyzing text with AI.

## Built With

- **HTML5 & CSS3** (2-space indentation standard)
- **Tailwind CSS** (via CDN for fast styling)
- **React 18** & **Babel** (In-browser JSX transformation)
- **Google Gemini API**

## License

MIT License. Feel free to use and modify for your own projects!
