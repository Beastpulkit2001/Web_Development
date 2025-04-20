<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>
<body>

  <h1>🌐 Web Development Project Repository</h1>
  <p>Welcome to my <strong>Web Development Repository</strong>! This repository contains two major frontend projects:</p>
  <ol>
    <li><strong>🛒 E-Commerce Website</strong></li>
    <li><strong>👨‍💻 Portfolio Website</strong></li>
  </ol>
  <p>Each project is fully responsive, modern, and built with best practices in mind. Below, you'll find detailed documentation for both projects.</p>

  <hr/>

  <h2>📁 Repository Structure</h2>
  <pre><code>web_development/
├── ecommerce-frontend/
│   └── (All files for e-commerce site)
├── portfolio-website/
│   └── (All files for personal portfolio)
└── README.html (This file)</code></pre>

  <hr/>

  <h2>🔹 E-Commerce Website</h2>

  <h3>💡 Features</h3>
  <ul>
    <li>Product listing, filtering, and searching</li>
    <li>Single product detail view</li>
    <li>Cart management & quantity control</li>
    <li>User authentication (Login/Register)</li>
    <li>Order placement</li>
    <li>Mobile-friendly responsive design</li>
  </ul>

  <h3>🛠 Tech Stack</h3>
  <ul>
    <li>React.js (or HTML/CSS/JS)</li>
    <li>React Router DOM</li>
    <li>Redux / Context API</li>
    <li>Tailwind CSS / Bootstrap</li>
    <li>Axios / Fetch API</li>
  </ul>

  <h3>📦 Setup Instructions</h3>
  <pre><code>cd ecommerce-frontend
npm install
npm start</code></pre>

  <h3>🌐 API Integration Example</h3>
  <pre><code>import axios from 'axios';
const API_URL = "https://api.example.com/products";

export const getProducts = async () => {
  const res = await axios.get(API_URL);
  return res.data;
};</code></pre>

  <h3>🧪 Optional Enhancements</h3>
  <ul>
    <li>Wishlist</li>
    <li>Payment gateway integration</li>
    <li>Admin panel</li>
    <li>Order tracking</li>
  </ul>

  <hr/>

  <h2>🔹 Portfolio Website</h2>

  <h3>💡 Features</h3>
  <ul>
    <li>Hero section with intro & call to action</li>
    <li>Skills and tech stack listing</li>
    <li>Highlighted projects</li>
    <li>Downloadable resume</li>
    <li>Contact form using EmailJS</li>
    <li>Animations on scroll (AOS)</li>
  </ul>

  <h3>🛠 Tech Stack</h3>
  <ul>
    <li>HTML / CSS / JS or React.js</li>
    <li>EmailJS for form submissions</li>
    <li>AOS / Animate.css for animations</li>
    <li>Responsive grid/flexbox layouts</li>
  </ul>

  <h3>📦 Setup Instructions</h3>
  <pre><code>cd portfolio-website
npm install
npm start</code></pre>

  <h3>📧 EmailJS Setup</h3>
  <p>Update <code>Contact.js</code> with your keys:</p>
  <pre><code>emailjs.sendForm(
  "YOUR_SERVICE_ID",
  "YOUR_TEMPLATE_ID",
  form.current,
  "YOUR_PUBLIC_KEY"
);</code></pre>

  <h3>🚀 Deployment</h3>
  <ul>
    <li>Netlify</li>
    <li>Vercel</li>
    <li>GitHub Pages</li>
  </ul>

  <hr/>

  <h2>🧠 Shared Best Practices</h2>
  <ul>
    <li>Semantic HTML & accessible components</li>
    <li>Optimized assets & lazy loading</li>
    <li>Mobile-first responsive design</li>
    <li>Reusable and clean components</li>
    <li>Proper folder structure for scalability</li>
  </ul>

  <hr/>

  <h2>🧑‍💻 Developed by</h2>
  <p><strong>Pulkit Sharma</strong><br/>
  <a href="https://your-portfolio-url.com">🌐 Portfolio</a> |
  <a href="https://linkedin.com/in/yourprofile">🔗 LinkedIn</a> |
  <a href="https://github.com/Beastpulkit2001">💻 GitHub</a></p>

  <hr/>

  <h2>📄 License</h2>
  <p>This repository is licensed under the MIT License. Feel free to fork, customize, and build on top of it.</p>

</body>
</html>
