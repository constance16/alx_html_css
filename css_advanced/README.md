# Smile School - Landing Page

This project is a simple landing page for Smile School, an educational platform that provides tutorials for enhancing your smile. The page is designed using HTML and basic CSS, utilizing Flexbox for layout and FontAwesome for icons. It includes a header with navigation links, multiple sections highlighting tutorials, and testimonials, and a footer with social media links.

## Features

- **Responsive Design**: The page layout adjusts to different screen sizes using Flexbox.
- **FontAwesome Integration**: Icons from FontAwesome are used throughout the page for rating stars and social media links.
- **Sections**:
  - **Header**: Contains a logo and navigation links for "COURSE", "PRICING", and "LOGIN".
  - **Main Section**:
    - A welcome message with a "REGISTER FOR FREE" button.
    - Featured tutorials with information on popular instructors.
    - Testimonials and quotes from satisfied learners.
  - **Popular Tutorials**: Displays several tutorial options with star ratings.
  - **Free Membership**: Encourages users to register for free access to tutorials.
  - **FAQ Section**: Frequently asked questions about the platform.
  - **Footer**: Contains social media icons and a copyright notice.

## Technologies Used

- **HTML**: Basic structure and content of the webpage.
- **CSS (Flexbox)**: Used for layout and responsive design.
- **FontAwesome**: For icons in the footer and ratings section.
- **Images**: Placeholder images are used for logos, instructors, and tutorials.

## How to Use

1. Clone the repository to your local machine.
2. Open the `index.html` file in any web browser.
3. Explore the various sections including featured tutorials, testimonials, and more.

## Sample Code - Header and Footer excluding the main

```html
<header>
    <nav>
         <img src="./Images/logo.png" alt="smiley">
        <ul>
            <li><a href="#">COURSE</a></li>
            <li><a href="#">PRICING</a></li>
            <li><a href="#">LOGIN</a></li>
        </ul>
    </nav>
</header>

 <footer>
        <div class="footer-content">
            <div class="footer-logo">
                <img src="./Images/logo.png" alt="smilesland" class=" footer-icon">
            </div>
            <div class="social-icons">
                <a href="#" title="Facebook" aria-label="Facebook"><i class="fa fa-facebook"></i></a>
                <a href="#" title="Twitter" aria-label="Twitter"><i class="fa fa-twitter"></i></a>
                <a href="#" title="LinkedIn" aria-label="LinkedIn"><i class="fa fa-linkedin"></i></a>
                <a href="#" title="Instagram" aria-label="Instagram"><i class="fa fa-instagram"></i></a>
            </div>
            <p>&copy; SmileSchool 2020</p>
        </div>
    </footer>
