# 🚀 AI Summary for Articles – Chrome Extension
This Chrome Extension allows you to instantly summarize any article you are reading using Google's Gemini AI. You can choose between Brief, Detailed, or Bullet Point summaries. Ideal for researchers, students, or anyone wanting quick insights from online content.

## 🧠 Features
1. 🔍 Extracts article text from any webpage

2. 🤖 Summarizes content using Gemini 1.5 Flash API

3. 🧵 Three summary modes:

  ->Brief (2-3 lines)

  ->Detailed
 
  ->Bullet Points (5–7 bullets)

4. 📋 One-click Copy to Clipboard

5. 🔐 Stores your Gemini API key securely using chrome.storage.sync

6. ⚙️ Easy API key setup via an Options page

## 🛠 Installation & Setup
### 1. Clone or Download This Repo
git clone https://github.com/yourname/ai-summary-extension.git
Or download the ZIP and extract it.

### 2. Get a Gemini API Key
Visit Google AI Studio

Generate an API key

Copy it for use in the next step

### 3. Add the Extension to Chrome
Open Chrome

Go to chrome://extensions/

Enable Developer mode (top right)

Click "Load unpacked"

Select the folder containing the project (ai-summary-extension)

### 4. Set Up Your API Key
Click the extension icon

Click the gear/settings icon or open the Options page manually

Paste your Gemini API key

Click Save Settings

## 💡 How It Works


When you click "Summarize", it:

Collects the article content

Sends it to Gemini via their API

Displays the summarized response


## ⚠️ Notes
Summaries are limited to 20,000 characters to ensure quick performance

Only works on pages with accessible text (some sites block content access)

Requires internet access to connect with Gemini API


