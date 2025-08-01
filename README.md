# 🚨 GA Castro Emergency Support Chat

**24/7 Emergency Roofing Support with Aurora IA**

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com)

## 🎯 Project Overview

Emergency support chat system for GA Castro Construction featuring Aurora IA assistant. Provides instant 24/7 assistance for roofing emergencies, storm damage, and urgent home repairs.

### ✨ Key Features

- **🤖 Aurora IA Assistant** - Intelligent chat support available 24/7
- **📱 Mobile-First Design** - Optimized for emergency situations on any device
- **⚡ Instant Response** - Immediate connection to support system
- **🔄 Auto-Retry Logic** - Robust error handling with automatic reconnection
- **📞 Emergency Fallback** - Phone number displayed if chat fails
- **🎨 Branded Experience** - Full GA Castro branding and colors

## 🚀 Live Demo

**Production URL:** [https://ga-chat.onrender.com](https://ga-chat.onrender.com)

## 📱 WhatsApp Integration

Share the emergency chat directly via WhatsApp:

```
https://wa.me/?text=🚨%20*EMERGENCIA%20DE%20TECHO?*%20🚨%0A%0A👋%20Conecta%20AHORA%20con%20Aurora%20IA%0A✅%20Respuesta%20automática%20inmediata%0A✅%20Evaluación%20instantánea%20de%20daños%0A✅%20Disponible%2024/7%0A%0A🔗%20*CHAT%20DIRECTO:*%20https://ga-chat.onrender.com%0A%0A⚡%20*¡Conecta%20directamente%20con%20Aurora%20IA!*
```

## 🛠️ Technology Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript ES6+
- **Chat Engine:** n8n Chat Widget v2.x
- **Backend:** n8n Webhook (Aurora IA Integration)
- **Hosting:** Render Static Site
- **Deployment:** GitHub → Render Auto-Deploy

## 📁 Project Structure

```
ga-chat/
├── index.html          # Main chat application
├── package.json        # Node.js dependencies and scripts
├── README.md          # Project documentation
└── .gitignore         # Git ignore rules
```

## 🔧 Development Setup

### Prerequisites

- Node.js 18.x or higher
- Git
- Modern web browser

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/benitocabrerar/ga-chat.git
   cd ga-chat
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start development server:**
   ```bash
   npm start
   ```

4. **Open browser:**
   ```
   http://localhost:3000
   ```

## 🚀 Deployment

### Render Deployment

1. **Connect GitHub to Render:**
   - Go to [render.com](https://render.com)
   - Click "New" → "Static Site"
   - Connect your GitHub repository

2. **Configure Build Settings:**
   ```
   Build Command: npm install
   Publish Directory: .
   ```

3. **Deploy:**
   - Click "Create Static Site"
   - Automatic deployment on every GitHub push

## ⚙️ Configuration

### Chat Settings

Key configuration in `index.html`:

```javascript
const CONFIG = {
    webhookUrl: 'https://g-tqf1.onrender.com/webhook/aurora-chat-webhook/chat',
    timeout: 20000,
    retryAttempts: 3,
    version: '1.0.0'
};
```

### Emergency Contact

Update emergency phone number in error fallback:
```html
📞 <strong>(800) 838-8186 Ext 1</strong>
```

## 📊 Analytics & Monitoring

### Built-in Logging

- Console logging for debugging
- Performance timing measurement
- Error tracking and retry attempts
- User interaction events

## 🔒 Security

- **HTTPS Only:** Enforced by Render
- **CORS Protection:** Configured in n8n webhook
- **No Sensitive Data:** No API keys in frontend code

## 📱 Mobile Optimization

- **Responsive Design:** Works on all screen sizes
- **Touch Optimization:** Large tap targets for mobile
- **Fast Loading:** Optimized for mobile networks

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