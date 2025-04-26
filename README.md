# 🚀 AI Summary for Articles – Chrome Extension
This Chrome Extension allows you to instantly summarize any article you are reading using Google's Gemini AI. You can choose between Brief, Detailed, or Bullet Point summaries. Ideal for researchers, students, or anyone wanting quick insights from online content.

## 🧠 Features
🔍 Extracts article text from any webpage

🤖 Summarizes content using Gemini 1.5 Flash API

🧵 Three summary modes:

Brief (2-3 lines)

Detailed

Bullet Points (5–7 bullets)

📋 One-click Copy to Clipboard

🔐 Stores your Gemini API key securely using chrome.storage.sync

⚙️ Easy API key setup via an Options page

🛠 Installation & Setup
1. Clone or Download This Repo
bash
Copy
Edit
git clone https://github.com/yourname/ai-summary-extension.git
Or download the ZIP and extract it.

2. Get a Gemini API Key
Visit Google AI Studio

Generate an API key

Copy it for use in the next step

3. Add the Extension to Chrome
Open Chrome

Go to chrome://extensions/

Enable Developer mode (top right)

Click "Load unpacked"

Select the folder containing the project (ai-summary-extension)

4. Set Up Your API Key
Click the extension icon

Click the gear/settings icon or open the Options page manually

Paste your Gemini API key

Click Save Settings

💡 How It Works
The extension injects a content script to extract readable text from articles (<article> tag or <p> elements).

When you click "Summarize", it:

Collects the article content

Sends it to Gemini via their API

Displays the summarized response

📂 Project Structure
bash
Copy
Edit
ai-summary-extension/
│
├── background.js        # Opens settings on first install
├── content.js           # Extracts article content from pages
├── popup.html           # UI for summarizing & copying
├── popup.js             # Logic for summarizing & calling Gemini API
├── options.html         # Settings page for API key input
├── options.js           # Stores/retrieves Gemini API key
├── manifest.json        # Chrome extension configuration
├── icon.jpg             # Extension icon
🧪 Example Use
Navigate to a news article or blog post

Click the extension icon

Choose a summary type (Brief, Detailed, or Bullets)

Click Summarize

Copy with one click!

🛡 Permissions Used
activeTab: To access current tab content

scripting: To execute scripts on pages

storage: To save the Gemini API key

host_permissions: To allow content script on all URLs

⚠️ Notes
Summaries are limited to 20,000 characters to ensure quick performance

Only works on pages with accessible text (some sites block content access)

Requires internet access to connect with Gemini API

📬 Feedback & Contributions
If you'd like to improve the project, feel free to open a pull request or submit issues on GitHub.

Let me know if you want this in .md format or want me to help you publish it to the Chrome Web Store.




Get smarter responses, upload files and images, and more.

Log in

Sign up for free

