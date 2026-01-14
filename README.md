<p align="center">
  <img src="https://cdn1.sharemyimage.com/smi/2026/01/03/Logo-Printify-automation.png" alt="Printify Automation Logo" width="120" height="120">
</p>

<h1 align="center">🚀 Printify Automation</h1>

<p align="center">
  <strong>AI-Powered Chrome Extension for Automated POD Product Creation</strong>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#quick-start">Quick Start</a> •
  <a href="#pricing">Pricing</a> •
  <a href="#support">Support</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chrome">
  <img src="https://img.shields.io/badge/Manifest-V3-success?style=for-the-badge" alt="Manifest V3">
  <img src="https://img.shields.io/badge/AI-Powered-blueviolet?style=for-the-badge&logo=openai&logoColor=white" alt="AI Powered">
  <img src="https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge" alt="Version">
</p>

---

## 📋 Overview

**Printify Automation** is a powerful Chrome extension that revolutionizes how you create Print-on-Demand products on Printify. With AI-powered content generation, bulk upload capabilities, and smart pricing tools, you can scale your POD business 10x faster.

<p align="center">
  <img src="docs/screenshots/demo.gif" alt="Demo" width="600">
</p>

---

## ✨ Features

<table>
  <tr>
    <td align="center" width="33%">
      <h3>📤 Bulk Upload</h3>
      <p>Upload multiple designs via drag & drop, URL import, or CSV file</p>
    </td>
    <td align="center" width="33%">
      <h3>🤖 AI Content Generation</h3>
      <p>Generate SEO-optimized titles & descriptions using Gemini or OpenAI</p>
    </td>
    <td align="center" width="33%">
      <h3>🎨 Multi-Product Creation</h3>
      <p>Apply one design across multiple product types simultaneously</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <h3>🏪 Multi-Store Support</h3>
      <p>Push products to multiple Printify stores at once</p>
    </td>
    <td align="center" width="33%">
      <h3>🎯 Smart Pricing</h3>
      <p>Set profit margins & auto-calculate retail prices</p>
    </td>
    <td align="center" width="33%">
      <h3>🔧 Advanced Configuration</h3>
      <p>Customize colors, sizes, print providers & image scaling</p>
    </td>
  </tr>
</table>

### 🎭 AI Tone Options

Choose from multiple AI writing styles for your product listings:

| Tone | Description |
|------|-------------|
| 💼 **Professional** | Clean, business-appropriate language |
| 😊 **Casual** | Friendly, conversational tone |
| 😄 **Funny** | Playful with humor and puns |
| ✨ **Luxury** | Premium, elegant descriptions |
| 🌸 **Cute** | Kawaii style with emojis |
| 🔍 **SEO** | Keyword-optimized for search visibility |

---

## 📦 Installation

### From Chrome Web Store (Recommended)

1. Visit the [Chrome Web Store](https://chrome.google.com/webstore) (link coming soon)
2. Click **"Add to Chrome"**
3. Confirm the installation

### Manual Installation (Developer Mode)

```bash
# Clone the repository
git clone https://github.com/yourusername/printify-automation.git

# Open Chrome Extensions
# Navigate to: chrome://extensions/

# Enable "Developer mode" (top right)

# Click "Load unpacked"

# Select the cloned folder
```

---

## 🚀 Quick Start

### Step 1: Get Your Printify API Key

1. Log in to [Printify](https://printify.com)
2. Go to **Account Settings** → **Connections**
3. Scroll to **API** section
4. Click **Create new token**
5. Copy the API key

### Step 2: Get AI API Key (Optional)

**Gemini API (Free tier available):**
1. Go to [Google AI Studio](https://aistudio.google.com/apikey)
2. Click **Create API Key**
3. Copy the key

**OpenAI API (Alternative):**
1. Go to [OpenAI Platform](https://platform.openai.com/api-keys)
2. Create an account and add billing
3. Generate a new API key

### Step 3: Configure the Extension

1. Click the Printify Automation icon in Chrome
2. Go to **Settings** tab
3. Paste your API keys
4. Select your AI provider (Gemini/OpenAI)

### Step 4: Start Creating!

1. Upload your designs (drag & drop, URL, or CSV)
2. Select product types
3. Click **Generate** for AI titles/descriptions
4. Click **Create** or **Publish**

---

## 💰 Pricing

<table align="center">
  <tr>
    <th>Free</th>
    <th>Pro ⭐</th>
    <th>Enterprise 🏢</th>
  </tr>
  <tr>
    <td align="center"><h2>$0</h2><small>/month</small></td>
    <td align="center"><h2>$19</h2><small>/month</small></td>
    <td align="center"><h2>$49</h2><small>/month</small></td>
  </tr>
  <tr>
    <td>✅ 10 products/day</td>
    <td>✅ Unlimited products</td>
    <td>✅ Unlimited products</td>
  </tr>
  <tr>
    <td>✅ 100 products/month</td>
    <td>✅ Priority AI generation</td>
    <td>✅ Priority AI generation</td>
  </tr>
  <tr>
    <td>✅ AI content generation</td>
    <td>✅ All product types</td>
    <td>✅ All product types</td>
  </tr>
  <tr>
    <td>✅ 5 product types</td>
    <td>✅ Multi-store support</td>
    <td>✅ API access</td>
  </tr>
  <tr>
    <td>❌ Multi-store</td>
    <td>✅ Email support</td>
    <td>✅ Priority support</td>
  </tr>
  <tr>
    <td align="center"><a href="#">Get Started</a></td>
    <td align="center"><a href="#">Subscribe</a></td>
    <td align="center"><a href="#">Contact Us</a></td>
  </tr>
</table>

---

## 🛠️ Tech Stack

- **Chrome Extension** - Manifest V3
- **AI Integration** - Google Gemini, OpenAI GPT-4
- **API** - Printify REST API
- **Backend** - Node.js (optional server component)
- **Languages** - JavaScript, HTML, CSS

---

## 📁 Project Structure

```
printify-automation/
├── manifest.json          # Extension manifest
├── popup/                 # Side panel UI
│   ├── popup.html
│   ├── popup.css
│   └── popup.js
├── background/            # Service worker
│   └── background.js
├── lib/                   # Shared libraries
├── assets/                # Icons & images
├── docs/                  # Documentation
└── server/                # Backend server (optional)
```

---

## 🔒 Privacy & Security

- ✅ All API keys stored **locally** in your browser
- ✅ No tracking or analytics
- ✅ Images processed only when you initiate actions
- ✅ Open-source and transparent

Read our full [Privacy Policy](docs/privacy.html) and [Terms of Service](docs/terms.html).

---

## 🤝 Support

Having issues or questions?

- 📧 **Email:** [ken.d150212@gmail.com](mailto:ken.d150212@gmail.com)
- 📖 **Documentation:** [View Docs](docs/index.html)
- 🐛 **Bug Reports:** [GitHub Issues](https://github.com/yourusername/printify-automation/issues)

---

## 📄 License

This project is proprietary software. All rights reserved.

© 2026 Ken Dao

---

<p align="center">
  Made with ❤️ for POD Sellers
</p>
