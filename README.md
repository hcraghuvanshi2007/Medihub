# MediHub - Your Trusted Healthcare Partner 🏥

A modern, fully responsive healthcare e-commerce website with integrated AI-powered chat support. Built with pure HTML, CSS, and JavaScript.

## ✨ Features

### 🎯 Main Website
- **Sticky Header Navigation** - Easy navigation with logo, menu, search, user account, cart, and prescription upload
- **Hero Section** - Eye-catching hero with search functionality and trust badges
- **Health Blog** - Latest health tips and wellness articles from expert doctors
- **Featured Products** - Popular health products with discounts and ratings
- **Category Browsing** - 8 healthcare categories (Medicines, Doctors, Lab Tests, Heart Care, Mental Wellness, Nutrition, Baby Care, Fitness)
- **Newsletter Subscription** - Email subscription for health tips and exclusive offers
- **Complete Footer** - Quick links, support, and contact information
- **Responsive Design** - Mobile-friendly layout that works on all devices

### 💬 Integrated Chat Widget
- **Smart Bot Responses** - AI-powered chatbot with keyword-based responses
- **Quick Reply Buttons** - Pre-configured replies for common queries
- **Minimize & Close** - Toggle chat widget functionality
- **Typing Indicator** - Realistic typing animation
- **Auto-Scrolling** - Messages auto-scroll to latest conversation
- **Mobile Responsive** - Optimized for all screen sizes
- **24/7 Support** - Always available chat support

### 📱 Responsive Breakpoints
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (640px - 767px)
- Small Mobile (below 640px)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, and CSS Variables
- **JavaScript (ES6+)** - Interactive features and chat functionality
- **No External Dependencies** - Pure vanilla JavaScript, no frameworks required

## 📁 Project Structure

.vscode/
├── 1.html              # Main HTML file with all content and styles
├── README.md              # Project documentation
└── images/                # Images and other assets (optional)

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)

### Installation

1. **Clone the repository**
git clone https://github.com/hcraghuvanshi2007/medihub.git
cd medihub

2. **Open in browser**
# Simply open the file in your browser
open index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000

## 💻 Usage

### Main Website Features

**Navigation**
- Click on menu items to smoothly scroll to sections
- Search bar for finding medicines and products
- Cart icon with item count badge
- Upload prescription button

**Browse Products**
- View featured products with discounts
- Click category cards to see available services
- Read health tips and wellness articles
- Subscribe to newsletter for updates

### Chat Widget

**Starting a Conversation**
1. Click the 💬 chat button at bottom-right
2. Choose a quick reply or type your message
3. Press Enter or click send button

**Chat Features**
- Minimize chat: Click − button to minimize
- Close chat: Click ✕ button to close
- Reopen: Click the floating 💬 button
- Pre-built responses for common queries

**Supported Chat Topics**
- Order tracking and status
- Delivery information
- Doctor consultations
- Pricing and discounts
- Payment methods
- Returns and refunds

## 🎨 Design System

### Color Palette
Primary Color: #1fa5a0 (Teal)
Primary Hover: #178a85 (Dark Teal)
Secondary Color: #e97856 (Coral)
Dark Background: #1f2937 (Dark Gray)
Light Background: #f9fafb (Off White)
Text Dark: #111827 (Near Black)
Text Light: #6b7280 (Gray)

### Typography
- Font Family: System fonts (-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto)
- Primary Heading: 3.5rem (56px)
- Secondary Heading: 2.5rem (40px)
- Body Text: 0.95rem - 1.1rem (15px - 18px)

### Spacing
- Base unit: 1rem (16px)
- Commonly used: 0.75rem, 1rem, 1.5rem, 2rem, 3rem, 4rem

## 📊 Sections Breakdown

### 1. Header
- Logo with gradient background
- Navigation menu
- Search and user icons
- Shopping cart with badge
- Prescription upload button

### 2. Hero Section
- Gradient background
- Headline: "Your Health, Our Priority"
- Search functionality
- Trust badges (1M+ customers)
- 3 feature highlights

### 3. Health Blog
- 3 article cards with images
- Author information
- Reading time
- Hover animations

### 4. Featured Products
- 4 product cards
- Discount badges (29-40% OFF)
- Star ratings
- Review counts
- Product categories

### 5. Browse Categories
- 8 category cards
- Icons and descriptions
- Hover effects
- Clickable for alerts (demo)

### 6. Newsletter
- Email input field
- Subscribe button
- Responsive layout

### 7. Footer
- Company logo and description
- Social media links
- Quick links
- Support section
- Contact information
- Copyright notice

### 8. Chat Widget
- Fixed position (bottom-right)
- Header with minimize/close buttons
- Message display area
- Input field with send button
- Quick reply buttons
- Typing indicator animation

## 🔧 Customization

### Change Colors
Edit CSS variables in the `:root` selector:
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* ... update other colors */
}

### Update Content
1. Replace placeholder text in HTML sections
2. Update product names and descriptions
3. Modify chat bot responses in JavaScript
4. Add real images (replace gradient backgrounds)

### Add Real Images
Replace gradient divs with actual images:
<!-- Old -->
<div style="background: linear-gradient(135deg, #7dd3c0, #5fc5b8)"></div>

<!-- New -->
<img src="path/to/image.jpg" alt="Product Image">

## 📱 Mobile Optimization

The site is fully responsive with breakpoints at:
- **1024px** - Desktop
- **768px** - Tablet
- **640px** - Mobile

All features work seamlessly on mobile devices:
- Touch-friendly buttons
- Optimized chat widget size
- Flexible grid layouts
- Readable text sizes

## 🤖 Chat Bot Logic

The chatbot responds based on keywords in user messages:

| Keyword | Response |
|---------|----------|
| order, medicine | Track order info |
| delivery, shipping | Delivery charges |
| doctor, consult | Doctor consultation |
| price, cost | Pricing info |
| payment, card | Payment methods |
| return, refund | Return policy |
| thank, thanks | Appreciation response |
| Other | Random helpful response |

## 🐛 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Performance

- **No external dependencies** - Faster load times
- **Optimized CSS** - Using CSS Grid and Flexbox for better rendering
- **Minimal JavaScript** - Only essential functionality
- **Smooth animations** - Hardware-accelerated transitions
- **Responsive images** - Gradient backgrounds instead of heavy image files

## 📈 Future Enhancements

- [ ] Backend API integration for real product data
- [ ] User authentication system
- [ ] Real database for orders and user profiles
- [ ] Advanced search functionality
- [ ] Product filters and sorting
- [ ] Payment gateway integration
- [ ] Order tracking system
- [ ] User reviews and ratings
- [ ] Real-time chat with human agents
- [ ] Mobile app version

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Himanchal Raghuvanshi**
- GitHub: [@hcraghuvanshi2007](https://github.com/hcraghuvanshi2007)
- LinkedIn: [hcraghuvanshi](https://www.linkedin.com/in/hcraghuvanshi/)

## 🙏 Acknowledgments

- Inspired by modern healthcare e-commerce platforms
- Icons from emoji unicode
- Design principles from Material Design and modern UX
- Community feedback and contributions

## 📞 Support

Have questions or found a bug? 

-- 📧 Email: support@medihub.com
- 🐛 GitHub Issues: [Report Issue](https://github.com/hcraghuvanshi2007/medihub/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/hcraghuvanshi2007/medihub/discussions)

---

**Made with ❤️ for healthcare accessibility**

⭐ If you found this helpful, please consider giving it a star!
