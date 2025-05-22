<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Educational Institute</title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>
    <header>
        <h1>Educational Institute</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About Us</a>
            <a href="#courses">Courses</a>
            <a href="#admissions">Admissions</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="home" class="hero">
            <h2>Welcome to Educational Institute</h2>
            <p>Your journey to excellence begins here. Explore our courses and begin learning today!</p>
            <a href="#admissions" class="cta-btn">Apply Now</a>
        </section>

        <!-- About Us Section -->
        <section id="about">
            <h2>About Us</h2>
            <p>We are committed to providing high-quality education to help you achieve your career goals. Our
                institution has a legacy of excellence in teaching and innovation.</p>
        </section>

        <!-- Courses Section -->
        <section id="courses">
            <h2>Our Courses</h2>
            <div class="course-grid">
                <div class="course">
                    <h3>Computer Science</h3>
                    <p>Learn the fundamentals of programming, algorithms, and data structures.</p>
                </div>
                <div class="course">
                    <h3>Business Administration</h3>
                    <p>Explore key principles of management, marketing, and entrepreneurship.</p>
                </div>
                <div class="course">
                    <h3>Graphic Design</h3>
                    <p>Develop your creativity with our design principles and software skills.</p>
                </div>
            </div>
        </section>

        <!-- Admissions Section -->
        <section id="admissions">
            <h2>Admissions</h2>
            <p>Ready to join us? Apply for your desired course today!</p>
            <a href="#contact" class="cta-btn">Contact Admissions</a>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials">
            <h2>What Our Students Say</h2>
            <div class="testimonials">
                <blockquote>“This institution helped me gain the skills to succeed in my career.” – James L.
                </blockquote>
                <blockquote>“The courses are engaging and provide practical knowledge.” – Sarah T.</blockquote>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or need more information, don't hesitate to reach out to us.</p>
            <form>
                <input type="text" name="name" placeholder="Your Name" required />
                <input type="email" name="email" placeholder="Your Email" required />
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <div class="social-icons">
            <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">Instagram</a>
        </div>
        <p>&copy; 2025 Educational Institute. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>

</html>
