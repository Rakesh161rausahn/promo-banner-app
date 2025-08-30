# Promo Banner App

A Shopify theme app extension that allows store owners to easily add customizable promotional banners to their storefront.

## 📋 Overview

This app provides a simple way to display promotional messages, announcements, or special offers at the top of your Shopify store. Perfect for showcasing free shipping offers, sales announcements, or important store updates.

## ✨ Features

- **Easy Installation**: One-click installation through Shopify App Store
- **Customizable Text**: Edit banner message through theme customizer
- **Color Customization**: Change background and text colors to match your brand
- **Responsive Design**: Automatically adjusts to all screen sizes
- **Theme Integration**: Seamlessly integrates with any Shopify theme
- **No Coding Required**: Fully managed through Shopify's theme editor

## 🚀 Quick Start

### Installation

1. **Install the App**
   - Go to your Shopify admin panel
   - Navigate to Apps section
   - Install the Promo Banner App

2. **Add Banner to Theme**
   - Go to `Online Store > Themes`
   - Click `Customize` on your active theme
   - Click `Add section`
   - Look for "Promo Banner" in the Apps section
   - Add it to your theme (recommended: at the top)

3. **Customize Your Banner**
   - Click on the banner block in the theme editor
   - Edit the banner text
   - Choose your preferred background color
   - Adjust text color if needed
   - Save your changes

## 🎨 Customization Options

| Setting | Description | Default |
|---------|-------------|---------|
| **Banner Text** | The promotional message to display | "🎉 Free Shipping on All Orders! 🎉" |
| **Background Color** | Banner background color | Light Yellow (#fceabb) |
| **Text Color** | Color of the banner text | Black (#000000) |

## 📁 Project Structure

```
promo-banner-app/
├── extensions/
│   └── banner-extension/
│       ├── blocks/
│       │   └── banner.liquid          # Banner HTML/CSS template
│       └── shopify.extension.toml     # Extension configuration
├── web/                               # Backend application files
├── shopify.app.toml                   # App configuration
├── package.json                       # Node.js dependencies
└── README.md                          # This file
```

## 🛠️ Development

### Prerequisites

- Node.js (LTS version)
- Shopify CLI
- Shopify Partner account
- Development store

### Local Development

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Rakesh161rausahn/promo-banner-app.git
   cd promo-banner-app
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start Development Server**
   ```bash
   shopify app dev
   ```

### Deployment

1. **Deploy to Shopify**
   ```bash
   shopify app deploy
   ```

2. **Create App Version**
   - Follow the CLI prompts to create a new app version
   - The extension will be bundled and deployed

## 🎯 Use Cases

- **Promotional Campaigns**: Announce sales, discounts, or special offers
- **Shipping Information**: Display free shipping thresholds or delivery updates
- **Store Announcements**: Share important news or policy changes
- **Seasonal Messages**: Holiday greetings or seasonal promotions
- **Call-to-Actions**: Drive traffic to specific pages or products

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

### Built With

- **Shopify CLI**: For app development and deployment
- **Liquid**: Shopify's templating language
- **HTML/CSS**: For banner styling and layout
- **Node.js**: Backend application framework

### Extension Type

- **Theme App Extension**: Integrates directly with Shopify themes
- **Block Type**: `promo_banner`
- **Target**: Section-level integration

## 📊 Performance

- **Lightweight**: Minimal impact on page load times
- **Mobile Optimized**: Responsive design for all devices
- **SEO Friendly**: Semantic HTML structure

## 🔗 Live Demo

- **Development Store**: https://promobannerapp.myshopify.com
- **Backend API**: https://shopify-promo-banner-backend-qqlbq64lf.vercel.app
- **Backend Repository**: https://github.com/Rakesh161rausahn/shopify-promo-banner-backend

## 🤝 Support

For support, feature requests, or bug reports:

1. Check the Shopify Partner Dashboard
2. Review Shopify's theme extension documentation
3. Contact the app developer through Shopify

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🏗️ Version History

### v2.0.0 (Current)
- Deployed to production store: promobannerapp.myshopify.com
- Backend API integrated with Vercel deployment
- Banner displays "🎉 Free Shipping on All Orders! 🎉"
- Full theme integration completed
- Color and text customization available

## 🙏 Acknowledgments

- Shopify for the excellent CLI tools and documentation
- The Shopify developer community for best practices and examples

---

**Made with ❤️ for Shopify merchants**

For more information about Shopify app development, visit [Shopify Developer Documentation](https://shopify.dev/).
