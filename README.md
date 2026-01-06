# Fleet Manager Website

Official website for Fleet Manager - a lightweight fleet management SaaS solution designed for small businesses and micro fleets with fewer than 10 vehicles.

## 🌐 Live Website

- **Main Website**: [https://www.carsmanager.net](https://www.carsmanager.net)
- **SaaS Application**: [https://app.carsmanager.net](https://app.carsmanager.net)

## ✨ Features

- **Multi-language Support**: Available in English and Chinese (Simplified)
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **SEO Optimized**: Complete with meta tags, Open Graph, Twitter Cards, and Schema.org structured data
- **Fast Loading**: Lightweight static HTML/CSS with no JavaScript dependencies
- **Accessibility**: Semantic HTML structure with proper ARIA labels

## 📋 Pages

### English Pages
- [Home](index.html) - Landing page with product overview
- [Features](features.html) - Detailed feature descriptions
- [Roadmap](roadmap.html) - Future development plans
- [Contact](contact.html) - Contact information and support
- [Privacy Policy](privacy.html) - Data protection policy
- [Terms of Service](terms.html) - User agreement

### Chinese Pages (中文页面)
- [首页](zh/index.html) - 产品介绍主页
- [产品亮点](zh/features.html) - 功能详细说明
- [未来规划](zh/roadmap.html) - 产品发展路线图
- [联系我们](zh/contact.html) - 联系方式和支持
- [隐私政策](zh/privacy.html) - 数据保护政策
- [服务条款](zh/terms.html) - 用户协议

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom styles with responsive design
- **No JavaScript Frameworks**: Pure HTML/CSS for maximum performance
- **Schema.org**: Structured data for SEO

## 📁 Project Structure

```
fm_siteweb/
├── index.html              # English homepage
├── features.html           # English features page
├── contact.html            # English contact page
├── roadmap.html            # English roadmap page
├── privacy.html            # English privacy policy
├── terms.html             # English terms of service
├── styles.css              # Main stylesheet
├── robots.txt              # Search engine directives
├── zh/                     # Chinese version
│   ├── index.html
│   ├── features.html
│   ├── contact.html
│   ├── roadmap.html
│   ├── privacy.html
│   └── terms.html
└── README.md               # This file
```

## 🚀 Getting Started

### Prerequisites
- A web browser (Chrome, Firefox, Safari, Edge)
- A web server (optional, for production deployment)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fm_siteweb.git
   cd fm_siteweb
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local web server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **View the website**
   - Navigate to `http://localhost:8000`

### Deployment

This is a static website that can be deployed to any static hosting service:

**GitHub Pages**
```bash
# Push to GitHub and enable GitHub Pages in repository settings
```

**Netlify**
```bash
# Drag and drop the folder to Netlify
# Or use Netlify CLI
npm install -g netlify-cli
netlify deploy
```

**Vercel**
```bash
# Install Vercel CLI
npm install -g vercel
vercel
```

**AWS S3 + CloudFront**
```bash
# Upload files to S3 bucket and configure CloudFront
```

**Traditional Web Hosting**
- Upload all files to your web server's public directory (e.g., `/var/www/html`)

## 🌍 Language Switching

The website automatically detects the user's browser language and redirects to the appropriate version:
- English users → English version
- Chinese users → Chinese version

Users can also manually switch languages using the language toggle in the header.

## 🔧 Customization

### Update Contact Information

Replace `chulu365@hotmail.com` with your actual email address in all HTML files.

### Update Domain Names

Replace `www.carsmanager.net` and `app.carsmanager.net` with your actual domain names.

### Update Baidu Site Verification

Replace `code-verify-key` with your actual Baidu site verification code in Chinese pages.

### Modify Colors

Edit the color variables in `styles.css`:
```css
/* Primary color */
#667eea

/* Hover color */
#5568d3
```

## 📊 SEO Features

The website includes comprehensive SEO optimization:

- **Meta Tags**: Title, description, keywords, author
- **Open Graph**: Facebook and LinkedIn sharing
- **Twitter Cards**: Twitter sharing
- **Canonical URLs**: Prevent duplicate content issues
- **Schema.org**: Structured data for rich snippets
- **Robots.txt**: Search engine crawling directives
- **Semantic HTML**: Proper heading hierarchy and structure

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

For questions or support:
- Email: [chulu365@hotmail.com](mailto:chulu365@hotmail.com)
- Website: [https://www.carsmanager.net](https://www.carsmanager.net)

## 🙏 Acknowledgments

- Built with pure HTML and CSS for maximum performance
- Responsive design for all devices
- SEO best practices implementation

---

Made with ❤️ by Fleet Manager Team
