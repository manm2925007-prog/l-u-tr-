Tôi sẽ giúp bạn xây dựng một website cá nhân cho Gia Man. Đây là một website portfolio hiện đại, responsive với thiết kế đẹp mắt.

## 1. **index.html** - Trang chính

```html
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gia Man - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-brand">
                <h2>Gia Man</h2>
            </div>
            <ul class="nav-menu">
                <li><a href="#home">Trang chủ</a></li>
                <li><a href="#about">Giới thiệu</a></li>
                <li><a href="#skills">Kỹ năng</a></li>
                <li><a href="#portfolio">Dự án</a></li>
                <li><a href="#contact">Liên hệ</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h1 class="hero-title">Xin chào, tôi là <span>Gia Man</span></h1>
                <p class="hero-subtitle">Web Developer & Designer</p>
                <p class="hero-description">
                    Đam mê sáng tạo và phát triển những giải pháp web độc đáo
                </p>
                <div class="hero-buttons">
                    <a href="#contact" class="btn btn-primary">Liên hệ với tôi</a>
                    <a href="#portfolio" class="btn btn-outline">Xem dự án</a>
                </div>
                <div class="social-links">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-linkedin"></i></a>
                    <a href="#"><i class="fab fa-github"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
            <div class="hero-image">
                <img src="https://via.placeholder.com/500x500" alt="Gia Man">
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">Giới thiệu về tôi</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Tôi là Gia Man</h3>
                    <p>
                        Một nhà phát triển web đầy đam mê với hơn 3 năm kinh nghiệm trong việc 
                        tạo ra các website đẹp mắt và hiệu quả. Tôi chuyên về Front-end Development 
                        và luôn cập nhật những công nghệ mới nhất.
                    </p>
                    <div class="about-info">
                        <div class="info-item">
                            <span class="info-label">Họ tên:</span>
                            <span>Gia Man</span>
                        </div>
                        <div class="info-item">
                            <span class="info-label">Email:</span>
                            <span>giaman@email.com</span>
                        </div>
                        <div class="info-item">
                            <span class="info-label">Điện thoại:</span>
                            <span>0123 456 789</span>
                        </div>
                        <div class="info-item">
                            <span class="info-label">Địa chỉ:</span>
                            <span>Hà Nội, Việt Nam</span>
                        </div>
                    </div>
                    <a href="#" class="btn btn-primary">Tải CV</a>
                </div>
                <div class="about-stats">
                    <div class="stat-item">
                        <h3>50+</h3>
                        <p>Dự án hoàn thành</p>
                    </div>
                    <div class="stat-item">
                        <h3>30+</h3>
                        <p>Khách hàng hài lòng</p>
                    </div>
                    <div class="stat-item">
                        <h3>3+</h3>
                        <p>Năm kinh nghiệm</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">Kỹ năng của tôi</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <i class="fab fa-html5"></i>
                    <h3>HTML5</h3>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 90%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-css3-alt"></i>
                    <h3>CSS3</h3>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 85%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-js"></i>
                    <h3>JavaScript</h3>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 80%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-react"></i>
                    <h3>React</h3>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 75%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-node-js"></i>
                    <h3>Node.js</h3>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 70%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fas fa-database"></i>
                    <h3>Database</h3>
                    <div class="skill-bar">
                        <div class="skill-progress" style="width: 65%"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2 class="section-title">Dự án của tôi</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/400x300" alt="Project 1">
                    <div class="portfolio-overlay">
                        <h3>Website Thương mại điện tử</h3>
                        <p>Xây dựng website bán hàng với React và Node.js</p>
                        <div class="portfolio-links">
                            <a href="#"><i class="fas fa-link"></i></a>
                            <a href="#"><i class="fab fa-github"></i></a>
                        </div>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/400x300" alt="Project 2">
                    <div class="portfolio-overlay">
                        <h3>App Quản lý công việc</h3>
                        <p>Ứng dụng quản lý task với MERN Stack</p>
                        <div class="portfolio-links">
                            <a href="#"><i class="fas fa-link"></i></a>
                            <a href="#"><i class="fab fa-github"></i></a>
                        </div>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/400x300" alt="Project 3">
                    <div class="portfolio-overlay">
                        <h3>Blog cá nhân</h3>
                        <p>Website blog với CMS tùy chỉnh</p>
                        <div class="portfolio-links">
                            <a href="#"><i class="fas fa-link"></i></a>
                            <a href="#"><i class="fab fa-github"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Liên hệ với tôi</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h3>Email</h3>
                            <p>giaman@email.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <div>
                            <h3>Điện thoại</h3>
                            <p>0123 456 789</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h3>Địa chỉ</h3>
                            <p>Hà Nội, Việt Nam</p>
                        </div>
                    </div>
                </div>
                <form class="contact-form">
                    <input type="text" placeholder="Họ tên" required>
                    <input type="email" placeholder="Email" required>
                    <input type="text" placeholder="Chủ đề">
                    <textarea placeholder="Nội dung tin nhắn" rows="5" required></textarea>
                    <button type="submit" class="btn btn-primary">Gửi tin nhắn</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Gia Man. All rights reserved.</p>
            <div class="footer-social">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```

## 2. **styles.css** - File CSS

```css
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #6C63FF;
    --secondary-color: #FF6B6B;
    --text-color: #333;
    --light-bg: #f8f9fa;
    --white: #ffffff;
    --gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: var(--text-color);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Navigation */
.navbar {
    background: var(--white);
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.navbar .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 20px;
}

.nav-brand h2 {
    color: var(--primary-color);
    font-size: 1.8rem;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-menu a {
    text-decoration: none;
    color: var(--text-color);
    font-weight: 500;
    transition: color 0.3s;
}

.nav-menu a:hover {
    color: var(--primary-color);
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background: var(--text-color);
    margin: 3px 0;
    transition: 0.3s;
}

/* Hero Section */
.hero {
    padding: 120px 0 80px;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    min-height: 100vh;
    display: flex;
    align-items: center;
}

.hero .container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
}

.hero-title {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: var(--text-color);
}

.hero-title span {
    color: var(--primary-color);
}

.hero-subtitle {
    font-size: 1.5rem;
    color: var(--secondary-color);
    margin-bottom: 1rem;
}

.hero-description {
    font-size: 1.1rem;
    color: #666;
    margin-bottom: 2rem;
}

.hero-buttons {
    display: flex;
    gap: 1rem;
    margin-bottom: 2rem;
}

.btn {
    padding: 12px 30px;
    text-decoration: none;
    border-radius: 30px;
    font-weight: 500;
    transition: all 0.3s;
    display: inline-block;
    border: 2px solid transparent;
}

.btn-primary {
    background: var(--primary-color);
    color: white;
}

.btn-primary:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(108, 99, 255, 0.3);
}

.btn-outline {
    border: 2px solid var(--primary-color);
    color: var(--primary-color);
}

.btn-outline:hover {
    background: var(--primary-color);
    color: white;
}

.social-links {
    display: flex;
    gap: 1rem;
}

.social-links a {
    width: 40px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: var(--white);
    border-radius: 50%;
    color: var(--primary-color);
    text-decoration: none;
    transition: all 0.3s;
}

.social-links a:hover {
    background: var(--primary-color);
    color: white;
    transform: translateY(-3px);
}

.hero-image img {
    width: 100%;
    border-radius: 20px;
    box-shadow: 0 20px 40px rgba(0,0,0,0.1);
}

/* About Section */
.about {
    padding: 80px 0;
    background: var(--white);
}

.section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    position: relative;
    color: var(--text-color);
}

.section-title::after {
    content: '';
    width: 80px;
    height: 4px;
    background: var(--primary-color);
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
}

.about-content {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 4rem;
    align-items: start;
}

.about-text h3 {
    font-size: 1.8rem;
    margin-bottom: 1rem;
    color: var(--primary-color);
}

.about-text p {
    margin-bottom: 2rem;
    color: #666;
    line-height: 1.8;
}

.about-info {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin-bottom: 2rem;
}

.info-item {
    display: flex;
    gap: 0.5rem;
}

.info-label {
    font-weight: 600;
    color: var(--text-color);
}

.about-stats {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.stat-item {
    text-align: center;
    padding: 1.5rem;
    background: var(--light-bg);
    border-radius: 10px;
    transition: transform 0.3s;
}

.stat-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.stat-item h3 {
    font-size: 2rem;
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

/* Skills Section */
.skills {
    padding: 80px 0;
    background: var(--light-bg);
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.skill-card {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
    transition: transform 0.3s;
}

.skill-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

.skill-card i {
    font-size: 3rem;
    color: var(--primary-color);
    margin-bottom: 1rem;
}

.skill-card h3 {
    margin-bottom: 1rem;
}

.skill-bar {
    background: #e0e0e0;
    height: 10px;
    border-radius: 5px;
    overflow: hidden;
}

.skill-progress {
    height: 100%;
    background: var(--gradient);
    border-radius: 5px;
    transition: width 2s ease;
}

/* Portfolio Section */
.portfolio {
    padding: 80px 0;
    background: var(--white);
}

.portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 2rem;
}

.portfolio-item {
    position: relative;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.portfolio-item:hover {
    transform: translateY(-10px);
}

.portfolio-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.portfolio-overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: linear-gradient(to top, rgba(0,0,0,0.9), transparent);
    padding: 2rem;
    transform: translateY(100%);
    transition: transform 0.3s;
}

.portfolio-item:hover .portfolio-overlay {
    transform: translateY(0);
}

.portfolio-overlay h3 {
    color: white;
    margin-bottom: 0.5rem;
}

.portfolio-overlay p {
    color: #ccc;
    margin-bottom: 1rem;
}

.portfolio-links a {
    display: inline-block;
    width: 40px;
    height: 40px;
    line-height: 40px;
    text-align: center;
    background: var(--primary-color);
    color: white;
    border-radius: 50%;
    margin-right: 0.5rem;
    transition: background 0.3s;
}

.portfolio-links a:hover {
    background: var(--secondary-color);
}

/* Contact Section */
.contact {
    padding: 80px 0;
    background: var(--light-bg);
}

.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
}

.contact-info {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.contact-item i {
    width: 50px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: var(--primary-color);
    color: white;
    border-radius: 50%;
    font-size: 1.2rem;
}

.contact-item h3 {
    margin-bottom: 0.3rem;
    color: var(--text-color);
}

.contact-item p {
    color: #666;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.contact-form input,
.contact-form textarea {
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-family: inherit;
    transition: border-color 0.3s;
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: none;
    border-color: var(--primary-color);
}

/* Footer */
.footer {
    background: var(--text-color);
    color: white;
    padding: 2rem 0;
    text-align: center;
}

.footer .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer-social {
    display: flex;
    gap: 1rem;
}

.footer-social a {
    color: white;
    font-size: 1.2rem;
    transition: color 0.3s;
}

.footer-social a:hover {
    color: var(--primary-color);
}

/* Responsive Design */
@media (max-width: 768px) {
    .hamburger {
        display: flex;
    }
    
    .nav-menu {
        position: fixed;
        left: -100%;
        top: 70px;
        flex-direction: column;
        background: white;
        width: 100%;
        text-align: center;
        transition: 0.3s;
        box-shadow: 0 10px 27px rgba(0,0,0,0.05);
        padding: 2rem 0;
    }
    
    .nav-menu.active {
        left: 0;
    }
    
    .hero .container {
        grid-template-columns: 1fr;
    }
    
    .hero-title {
        font-size: 2rem;
    }
    
    .about-content {
        grid-template-columns: 1fr;
    }
    
    .contact-content {
        grid-template-columns: 1fr;
    }
    
    .footer .container {
        flex-direction: column;
        gap: 1rem;
    }
}
```

## 3. **script.js** - File JavaScript

```javascript
// Hamburger Menu Toggle
const hamburger = document.querySelector('.hamburger');
const navMenu = document.querySelector('.nav-menu');

hamburger.addEventListener('click', () => {
    navMenu.classList.toggle('active');
});

// Close menu when clicking on a link
document.querySelectorAll('.nav-menu a').forEach(link => {
    link.addEventListener('click', () => {
        navMenu.classList.remove('active');
    });
});

// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Add scroll effect to navbar
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 100) {
        navbar.style.background = 'rgba(255, 255, 255, 0.95)';
        navbar.style.backdropFilter = 'blur(10px)';
    } else {
        navbar.style.background = 'white';
    }
});

// Animate skill bars on scroll
const observerOptions = {
    threshold: 0.5,
    rootMargin: '0px'
};

const observer = new IntersectionObserver(function(entries, observer) {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            const skillBars = entry.target.querySelectorAll('.skill-progress');
            skillBars.forEach(bar => {
                const width = bar.style.width;
                bar.style.width = '0';
                setTimeout(() => {
                    bar.style.width = width;
                }, 200);
            });
            observer.unobserve(entry.target);
        }
    });
}, observerOptions);

const skillsSection = document.querySelector('.skills');
if (skillsSection) {
    observer.observe(skillsSection);
}

// Form submission
const contactForm = document.querySelector('.contact-form');
if (contactForm) {
    contactForm.addEventListener('submit', (e) => {
        e.preventDefault();
        
        // Get form data
        const formData = new FormData(contactForm);
        const data = Object.fromEntries(formData);
        
        // Here you would typically send the data to a server
        console.log('Form submitted:', data);
        
        // Show success message
        alert('Cảm ơn bạn đã liên hệ! Tôi sẽ phản hồi sớm nhất có thể.');
        
        // Reset form
        contactForm.reset();
    });
}

// Add animation on scroll
const animateOnScroll = () => {
    const elements = document.querySelectorAll('.portfolio-item, .skill-card, .stat-item');
    
    elements.forEach(element => {
        const elementTop = element.getBoundingClientRect().top;
        const elementBottom = element.getBoundingClientRect().bottom;
        
        if (elementTop < window.innerHeight && elementBottom > 0) {
            element.style.opacity = '1';
            element.style.transform = 'translateY(0)';
        }
    });
};

// Initial setup for animations
document.addEventListener('DOMContentLoaded', () => {
    const elements = document.querySelectorAll('.portfolio-item, .skill-card, .stat-item');
    elements.forEach(element => {
        element.style.opacity = '0';
        element.style.transform = 'translateY(20px)';
        element.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    });
    
    animateOnScroll();
});

window.addEventListener('scroll', animateOnScroll);

// Typing effect for hero title
const heroTitle = document.querySelector('.hero-title span');
if (heroTitle) {
    const text = heroTitle.textContent;
    heroTitle.textContent = '';
    let index = 0;
    
    const typeWriter = () => {
        if (index < text.length) {
            heroTitle.textContent += text.charAt(index);
            index++;
            setTimeout(typeWriter, 100);
        }
    };
    
    // Start typing effect after page loads
    setTimeout(typeWriter, 500);
}
```

## Hướng dẫn sử dụng:

1. **Tạo cấu trúc thư mục:**
```
portfolio-giaman/
│
├── index.html
├── styles.css
├── script.js
└── images/
    └── (đặt ảnh của bạn ở đây)
```

2. **Tùy chỉnh nội dung:**
   - Thay thế thông tin cá nhân trong HTML
   - Thêm ảnh thật vào thư mục images
   - Cập nhật link mạng xã hội
   - Thêm các dự án thực tế vào phần Portfolio

3. **Tính năng nổi bật:**
   - Responsive design (tương thích mọi thiết bị)
   - Smooth scrolling
   - Animation khi scroll
   - Menu hamburger cho mobile
   - Form liên hệ
   - Hiệu ứng typing cho tên
   - Progress bars cho kỹ năng

4. **Để deploy website:**
   - Sử dụng GitHub Pages (miễn phí)
   - Netlify hoặc Vercel
   - Hosting riêng

Website này có thiết kế hiện đại, chuyên nghiệp và dễ dàng tùy chỉnh theo nhu cầu của Gia Man!
