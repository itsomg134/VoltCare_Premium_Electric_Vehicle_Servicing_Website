#  VoltCare Premium Electric Vehicle Servicing Website

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](#)

**VoltCare** is a modern, fully responsive front-end website designed for an electric vehicle (EV) servicing business. It showcases services, integrates a booking form, and provides a sleek user experience tailored to EV owners.

##  Features

- **Hero Section** – Engaging headline with key stats (EVs serviced, rating, express service)
- **Service Catalog** – Six core EV services with pricing (battery health, software updates, charging port repair, etc.)
- **Why Choose Us** – Highlights certified technicians, OEM tools, fast turnaround, eco-friendly approach
- **Booking Form** – Interactive form for service requests (client-side validation + success message)
- **Testimonials** – Social proof from real EV owners
- **Sticky Navigation** – Smooth scroll to different sections
- **Fully Responsive** – Works flawlessly on desktop, tablet, and mobile devices
- **Font Awesome Icons** – Clean, modern iconography
- **No External Dependencies** – Pure HTML/CSS/JS, ready to deploy

---

##  Screenshots

| Hero Section | Services Grid |
|--------------|---------------|
| <img width="1884" height="848" alt="image" src="https://github.com/user-attachments/assets/6964d3c1-3d26-4f6c-b05f-622b0b4e089d" />
 | ![Services](https://via.placeholder.com/400x250?text=Services) |

| Booking CTA | Mobile View |
|-------------|--------------|
| ![Booking](https://via.placeholder.com/400x250?text=Booking+Form) | ![Mobile](https://via.placeholder.com/400x250?text=Responsive) |

---

##  Technologies Used

- **HTML5** – Semantic markup
- **CSS3** – Flexbox, Grid, custom properties, animations
- **JavaScript (Vanilla)** – Form handling, validation, DOM interaction
- **Font Awesome 6** – Icons (CDN)
- **Google Fonts (Inter)** – Modern typography

---

##  Project Structure

```
voltcare-ev-website/
│
├── index.html          # Main website file (includes all styles & scripts)
├── README.md           # Project documentation
└── assets/ (optional)  # You can add images here if needed
```

> **Note:** This is a single-file front-end project. All CSS and JavaScript are embedded inside `index.html` for simplicity.

---

##  Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) Local web server for testing – but you can open the file directly

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/voltcare-ev-website.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd voltcare-ev-website
   ```

3. **Open the website**
   - Simply double-click `index.html`, or
   - Use a live server (e.g., VS Code Live Server extension)

4. **That’s it!** The website is ready to explore.

---

## Usage

- **Browse Services** – Scroll through the service cards to see EV-specific maintenance options.
- **Book a Service** – Fill out the booking form (name, email, phone, service type, preferred date) and submit. A JavaScript alert confirms the request.
- **Navigate** – Use the sticky header to jump between sections (Home, Services, Book Now, Contact).
- **Responsive Testing** – Resize your browser or use DevTools to see mobile adaptation.

 *The booking form does not send data to a backend in this demo; it’s a front-end simulation. For production, integrate with a form API (Formspree, Netlify Forms, etc.).*

---

##  Responsive Breakpoints

- **Desktop:** > 780px – Full layout with side-by-side elements
- **Tablet / Mobile:** ≤ 780px – Stacked layout, adjusted padding, smaller typography

---

##  Customization

You can easily modify the website to fit your brand:

1. **Change colors** – Edit CSS variables or inline styles (search for `#0b3b3f` and `#1c6d64`).
2. **Update services** – Add or remove `.service-card` divs in the services grid.
3. **Replace placeholder images** – The hero uses Font Awesome icons; swap with actual EV images if desired.
4. **Modify contact info** – Update email, phone, address in the footer section.
5. **Connect a real backend** – Replace the `alert()` in the `<script>` tag with an AJAX/fetch call.

---

##  Future Improvements

- Backend integration (Node.js / PHP) to store bookings in a database
- Email confirmation system for appointments
- Admin dashboard to manage service requests
- Live chat support widget
- Integration with Google Maps for location
- Customer login portal for service history

---

##  Contributing

Contributions are welcome! If you have ideas for improvements or find any bugs, feel free to open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

##  License

Distributed under the **MIT License**. See `LICENSE` file for more information (you can add a simple MIT license file if desired).
