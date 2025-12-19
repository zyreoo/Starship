# Starship Hackathon Website

The official website for Starship - the biggest 24-hour hackathon for high school students in Cluj, Romania.

🌐 **Live Site:** [starshipcluj.ro](https://starshipcluj.ro)

## 🚀 About

Starship is a 24-hour marathon where high school students learn to create projects (games, websites, applications, hardware) alongside their friends! This website serves as the main landing page for the event, providing information about the hackathon, schedule, FAQ, and registration.

## ✨ Features

- **Responsive Design**: Fully optimized for both desktop and mobile devices
- **Interactive Elements**: 
  - Animated astronaut that follows scroll path
  - Registration button linking to sign-up form
  - Schedule modal with event timeline
- **Sections**:
  - Hero section with call-to-action
  - "What is Starship?" information section
  - Event schedule with interactive modal
  - FAQ section with cloud-based Q&A
  - Sponsor showcase
  - Contact footer

## 🛠️ Technologies

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with responsive design
- **JavaScript**: Interactive functionality and animations
- **Google Fonts**: Sour Gummy font family

## 📁 Project Structure

```
Starship/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and responsive design
├── script.js           # JavaScript for interactivity and animations
├── images/             # All images and assets
│   ├── Logo.png/webp
│   ├── Background.png/webp
│   ├── Background-mobile.png/webp
│   └── ... (other assets)
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites

No special prerequisites needed! Just a modern web browser.

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Starship
```

2. Open `index.html` in your web browser, or use a local server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Then visit http://localhost:8000
```

### For Mobile Testing

1. Start a local server (see above)
2. Find your local IP address:
   ```bash
   # On macOS/Linux
   ifconfig | grep "inet " | grep -v 127.0.0.1
   ```
3. Access from your mobile device on the same Wi-Fi network:
   ```
   http://YOUR_IP_ADDRESS:8000
   ```

## 📱 Responsive Breakpoints

- **Desktop**: Default styles for screens > 700px
- **Tablet**: 700px - 900px
- **Mobile**: < 700px (optimized layout with stacked elements)

## 🎨 Key Features Explained

### Animated Astronaut
The rocket/astronaut image follows a custom scroll path, creating an engaging visual experience as users scroll through the page.

### Schedule Modal
Click the "Vezi Programul" (View Schedule) button to see the full event timeline in a beautiful modal popup.

### FAQ Clouds
Interactive cloud-based FAQ section with questions and answers about the event, including:
- Who can participate?
- What to bring?
- Is programming experience required?
- Cost information
- Past events
- And more!

## 📝 Customization

### Changing Colors
Main colors are defined in `styles.css`:
- Primary blue: `#4b87f7` / `#4897ff` (mobile)
- Dark blue: `#011a5e`
- Light blue: `#c7d6fc`
- Gold accent: `#c8a500`

### Updating Content
- Edit `index.html` for text content
- Modify schedule in the modal section (lines 178-243)
- Update sponsor images in the `images/` folder

## 🤝 Contributing

This is the official website for Starship Hackathon. For updates or contributions, please contact the Starship team.

## 📧 Contact

For questions or inquiries:
- **Email**: contact@starship.ro
- **Website**: [starshipcluj.ro](https://starshipcluj.ro)

## 📄 License

This project is proprietary and belongs to the Starship Hackathon organization.

---

Made with ❤️ by the Starship Team 🚀✨🌙⭐
