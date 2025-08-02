# 🏗️ GA Castro Construction AI

**Professional ChatGPT-Style Interface for Construction Services**

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com)

## 🎯 Project Overview

Professional construction support chat system for GA Castro Construction featuring Aurora AI assistant. Provides instant assistance for roofing, siding, storm damage, and construction services with a sophisticated ChatGPT-inspired interface.

### ✨ Key Features

- **🤖 Aurora AI Assistant** - Intelligent chat support powered by Aurora IA
- **� ChatGPT-Style Interface** - Modern, minimalist design inspired by ChatGPT
- **🌐 Bilingual Support** - Full English/Spanish language switching
- **📱 Responsive Design** - Optimized for desktop and mobile devices
- **⚡ Real-time Chat** - Instant messaging with typing indicators
- **🏢 Company Integration** - Branch locations, hours, and emergency contact
- **🎨 Professional Branding** - Clean design with GA Castro branding

## 🚀 Live Demo

**Production URL:** [https://ga-chat.onrender.com](https://ga-chat.onrender.com)

## 🏢 Company Information

**GA Castro Construction** - 25+ Years in Connecticut

### Branch Locations:
- **Stamford Office**: 1200 Summer St Suite 203, Stamford, CT 06905
- **Guilford Office**: 1300 Boston Post Rd, Guilford, CT 06437

### Services:
- 🌧️ **Roof Repair** - Free inspections and insurance claims
- 🏡 **Siding & Exterior** - Professional installation and repair
- ⚡ **Storm Damage** - Complete assessment and assistance
- 💰 **Free Estimates** - Pricing for all services

### Emergency Contact: 🆘 (800) 838-8186

## 📱 WhatsApp Integration

Share the construction chat directly via WhatsApp:

```
https://wa.me/?text=🏗️%20*GA%20CASTRO%20CONSTRUCTION*%20🏗️%0A%0A👋%20Connect%20with%20our%20AI%20Assistant%0A✅%20Instant%20roofing%20support%0A✅%20Free%20damage%20assessment%0A✅%20Available%2024/7%0A%0A🔗%20*CHAT%20NOW:*%20https://ga-chat.onrender.com%0A%0A⚡%20*Professional%20construction%20services%20in%20Connecticut!*
```

## 🛠️ Technology Stack

- **Frontend:** Pure HTML5, CSS3 Variables, Vanilla JavaScript ES6+
- **UI Framework:** Custom ChatGPT-inspired design system
- **Chat Engine:** Direct webhook integration (no external dependencies)
- **Backend:** Aurora IA via n8n webhook integration
- **Hosting:** Render Static Site
- **Deployment:** GitHub → Render Auto-Deploy

## 📁 Project Structure

```
ga-chat/
├── index.html                 # Main ChatGPT-style application
├── aurora-ai-elegant-6.html   # Development/backup version
├── package.json              # Node.js configuration
├── README.md                 # Project documentation
└── .gitignore               # Git ignore rules
```

## 🔧 Development Setup

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Git for version control
- Text editor (VS Code recommended)

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/benitocabrerar/ga-chat.git
   cd ga-chat
   ```

2. **Open directly in browser:**
   ```bash
   # Open index.html in your browser
   # No build process required - pure vanilla implementation
   ```

3. **For local server (optional):**
   ```bash
   # Python 3
   python -m http.server 3000
   
   # Node.js
   npx serve .
   ```

## 🚀 Deployment

### Render Deployment

1. **Connect GitHub to Render:**
   - Go to [render.com](https://render.com)
   - Click "New" → "Static Site"
   - Connect your GitHub repository

2. **Configure Build Settings:**
   ```
   Build Command: (leave empty)
   Publish Directory: .
   ```

3. **Deploy:**
   - Click "Create Static Site"
   - Automatic deployment on every GitHub push

## ⚙️ Configuration

### Chat Settings

Key configuration in `index.html`:

```javascript
const WEBHOOK_URL = 'https://g-tqf1.onrender.com/webhook/aurora-chat-webhook/chat';
let sessionId = 'session-' + Date.now() + '-' + Math.random().toString(36).substr(2, 9);
let currentLanguage = 'en';
```

### Bilingual Support

Language switching is handled via data attributes:
```html
<span data-en="New conversation" data-es="Nueva conversación">New conversation</span>
```

### Emergency Contact

Update emergency phone number:
```html
<span data-en="🆘 EMERGENCY: (800) 838-8186" data-es="🆘 EMERGENCIAS: (800) 838-8186">
```

## 🎨 Design System

### CSS Variables

Modern design system using CSS custom properties:
```css
:root {
    --bg-primary: #ffffff;
    --bg-secondary: #f9fafb;
    --accent-primary: #1e40af;
    --text-primary: #1f2937;
    --shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.1);
}
```

### ChatGPT-Inspired Components

- **Sidebar navigation** with chat history placeholder
- **Message bubbles** with user/AI avatars
- **Typing indicators** with animated dots
- **Input area** with auto-resize textarea
- **Suggestion cards** for quick actions

## 📊 Analytics & Monitoring

### Built-in Features

- Session ID tracking for conversation continuity
- Error handling with bilingual fallback messages
- Console logging for debugging
- Performance optimized with minimal dependencies

## 🔒 Security

- **HTTPS Only:** Enforced by Render hosting
- **No External CDNs:** All code self-contained
- **Webhook Security:** Direct Aurora IA integration
- **No API Keys:** Secure server-side processing

## 📱 Mobile Optimization

- **Responsive Layout:** Sidebar hidden on mobile
- **Touch-Friendly:** Large tap targets and buttons
- **Performance:** Zero external dependencies for fast loading
- **Accessibility:** ARIA labels and semantic HTML

## 🌐 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Support

### Emergency Contact
- **Phone:** (800) 838-8186 Ext 1
- **Available:** 24/7

### Technical Support
- **Repository Issues:** [GitHub Issues](https://github.com/benitocabrerar/ga-chat/issues)

## 📄 License

Copyright © 2024 GA Castro Construction. All rights reserved.

---

**Last Updated:** January 2025  
**Version:** 1.0.0  
**Status:** 🟢 Production Ready