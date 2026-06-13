ThriftLab - Streetwear E-Commerce Web Application

1. Project Description
ThriftLab is a responsive web application prototype designed for a modern thrift store specializing in curated streetwear. The project demonstrates advanced web design principles, including responsive layouts, interactive content management, and data visualization. The application serves as both a customer-facing storefront and an administrative dashboard. It features a seamless user experience across devices, from browsing products to managing sales data. The design aesthetic reflects the "Built From The Streets" brand identity, utilizing a minimalist, urban color palette and typography.

2. Features Included
   
User Interface (Front-End):

Responsive Navigation: A consistent navigation bar across all pages that collapses into a "hamburger menu" on mobile devices.

Hero Section: An engaging landing page with an animated text mask effect and background video integration.

Product Catalog (Shop Page): A grid-based layout displaying products with hover effects, pricing, and "Add to Cart" functionality.

Interactive Gallery: A CSS grid image gallery on the page that adjusts columns based on screen size (mobile vs. desktop).

About Us Page: A detailed company profile featuring video embeds, team member cards with modal popups, and a timeline of milestones.

Functional Components

Authentication System:

Login: A functional login page that validates credentials against localStorage.

Registration: A registration form that saves user credentials locally for persistent testing.

Dashboard:

Data Visualization: Includes interactive Bar and Doughnut charts (powered by Chart.js) to display sales trends and category distribution.

Data View: A responsive table displaying recent transaction records.

Summary Cards: Key performance indicators (Total Sales, Orders, etc.) presented in a clean card layout.

Shopping Cart Logic: A JavaScript-based cart system that allows users to add items, view the total price in a modal, and remove items dynamically.

3. Instructions to Test Login

To test the authentication flow, follow these steps:

Open the Website: Launch index.html in your web browser.

Navigate to Login: Click the User Icon (top right) in the navigation bar.

Test Registration:

Click "Create account" on the login screen.

Fill in the details (e.g., Email: test@user.com, Password: 123).

Click "Create". You will be redirected back to the login page.

Login:

Enter Email and Password

Verify Access: Upon successful login, you will be automatically redirected to the Dashboard Page (dashboard.html).

4. Frameworks & Libraries Used

HTML5 & CSS3: Core structure and styling, including Flexbox and Grid layouts for responsiveness.

Bootstrap 5.3.3: Used for the responsive grid system, navigation bar components, modals, and utility classes.

Chart.js: A JavaScript library used to render the interactive data visualization charts on the Dashboard page.

Google Fonts: Utilized Poppins for main body text, Manufacturing Consent for branding, and Cabin Condensed for hero sections.

FontAwesome (Implicit): Icons used for UI elements (via image assets in this specific build).
