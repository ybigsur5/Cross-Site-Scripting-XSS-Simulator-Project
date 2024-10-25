# 🛡️ XSS Simulator with Sandbox

A web-based Cross-Site Scripting (XSS) simulator with sandbox functionality for educational purposes. This tool allows safe testing and understanding of XSS vulnerabilities in a controlled environment.

## ✨ Features

- 🔍 Real-time XSS payload testing
- 🛡️ Sandboxed environment for safe execution
- 📝 Input validation demonstration
- 🔒 Isolated iframe implementation
- 💻 Simple and intuitive interface

## 📋 Prerequisites

- 🌐 Modern web browser
- 📝 Basic understanding of HTML/JavaScript
- 🔒 Local development environment

## 🚀 Installation

1. Clone this repository:
```bash
git clone https://github.com/ybigsur5/xss-simulator.git
```

2. Navigate to project directory:
```bash
cd xss-simulator
```

3. Open in your preferred browser:
```bash
# For Python simple server
python -m http.server 8000

# For PHP
php -S localhost:8000
```

## 💻 Usage

1. Access the simulator:
```
http://localhost:8000
```

The simulator provides:
- 📝 Text area for XSS payload input
- 🔄 Real-time simulation button
- 📊 Output display section
- 🛡️ Sandboxed iframe for safe testing

## 🔒 Security Features

- ⚠️ Sandboxed execution environment
- 🛡️ Isolated iframe implementation
- 🔐 Content Security Policy (CSP)
- 📝 Input validation demonstration

## ⚠️ Limitations

- 👑 Browser security restrictions apply
- 🌐 Local testing environment only
- 🔌 Some XSS vectors may be blocked

## 📝 Code Structure

Basic Version:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>XSS Simulator</title>
    <!-- Basic styling and setup -->
</head>
<body>
    <textarea id="payload"></textarea>
    <button onclick="simulateXSS()">Simulate XSS</button>
    <div id="output"></div>
</body>
</html>
```

Sandboxed Version:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>XSS Simulator with Sandbox</title>
    <!-- Enhanced security features -->
</head>
<body>
    <textarea id="payload"></textarea>
    <button onclick="simulateXSS()">Simulate XSS</button>
    <iframe id="sandbox" sandbox="allow-scripts"></iframe>
</body>
</html>
```

## 🚀 Future Enhancements

1. Add payload validation options
2. Implement advanced sandboxing features
3. Include common XSS payload templates
4. Add result logging functionality
5. Enhance security controls

## 👨‍💻 Author

**Vira**
- 🌐 GitHub: [@ybigsur5](https://github.com/ybigsur5)
- 📧 Email: vira.cehoscp@gmail.com

## 🙏 Acknowledgments

- 📚 OWASP XSS Prevention Cheat Sheet
- 🛡️ Web Security Community
- 👥 Security Researchers

## ⚠️ Disclaimer

This tool is for educational purposes only. Do not use XSS payloads on production systems or without proper authorization. Always practice responsible security testing.
