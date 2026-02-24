# iyf-s10-week1-emmanuelwachira45-spec
week one portfolio for IYF season10

---

## Task Completion Status

### Lesson 1: Web Development & Environment Setup

| Task | Description | Status | Assigned To |
|------|-------------|--------|-------------|
| 1.1 | Environment Setup (VS Code, Git, Extensions) | ✅ Complete | All Members |
| 1.2 | DevTools Exploration (devtools-exploration.md) | ✅ Complete | All Members |
| 1.3 | First Webpage (index.html) | ✅ Complete | **emmanuelwachira45-spec** |
| 1.4 | Deploy to GitHub Pages | ✅ Complete | britneymuthoni67 |

### Lesson 2: HTML Deep Dive & Accessibility

| Task | Description | Status | Assigned To |
|------|-------------|--------|-------------|
| 2.1 | Semantic HTML Conversion | ✅ Complete | wachira-45 |
| 2.2 | Contact Form (contact.html) | ✅ Complete | britneymuthoni67 |
| 2.3 | Accessibility Audit | ✅ Complete | All Members |
| 2.4 | Multi-Page Portfolio | ✅ Complete | All Members |

### Daily Challenges (emmanuelwachira45-spec)

| Day | Challenge | File | Status |
|-----|-----------|------|--------|
| Day 1 | Five Tags Challenge | daily-challenges/day1-five-tags.html | ✅ Complete |
| Day 2 | Navigation Menu | daily-challenges/day2-navigation.html | ✅ Complete |
| Day 3 | Contact Section | daily-challenges/day3-contact-section.html | ✅ Complete |
| Day 4 | Photo Gallery | daily-challenges/day4-photo-gallery.html | ✅ Complete |
| Day 5 | Blog Post Layout | daily-challenges/day5-blog-post.html | ✅ Complete |

---

## My Files (emmanuelwachira45-spec)

### 📄 index.html (Home Page)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emmanuel Wachira - Home</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Emmanuel Wachira</h1>
            <p>Aspiring Web Developer | IYF Season 10 Participant</p>
        </section>

        <section>
            <h2>About Me</h2>
            <p>Hello! I'm Emmanuel, a passionate learner exploring web development through IYF Season 10. I enjoy building clean, accessible websites and collaborating with amazing teammates.</p>
            <img src="https://placehold.co/400x300" alt="Emmanuel Wachira profile placeholder">
        </section>

        <section>
            <h2>My Hobbies</h2>
            <ul>
                <li>Coding and learning new technologies</li>
                <li>Reading tech blogs and articles</li>
                <li>Playing chess and strategy games</li>
            </ul>
        </section>

        <section>
            <h2>Favorite Website</h2>
            <p>Check out <a href="https://github.com" target="_blank">GitHub</a> - where I host all my projects!</p>
            <p>Email me: <a href="mailto:emmanuel.wachira@example.com">emmanuel.wachira@example.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Emmanuel Wachira. All rights reserved.</p>
    </footer>
day1-five-tags.html
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day 1: Five Tags Challenge - Emmanuel Wachira</title>
</head>
<body>
    <header>
        <h1>Five HTML Tags Challenge</h1>
        <nav>
            <a href="../index.html">Back to Home</a>
        </nav>
    </header>
    
    <main>
        <h2>Tags I Learned Today</h2>
        
        <section>
            <h3>1. &lt;abbr&gt; Tag</h3>
            <p>The <abbr title="HyperText Markup Language">HTML</abbr> is the standard markup language for web pages.</p>
        </section>
        
        <section>
            <h3>2. &lt;blockquote&gt; Tag</h3>
            <blockquote cite="https://www.example.com">
                <p>The only way to learn a new programming language is by writing programs in it.</p>
                <footer>— Dennis Ritchie</footer>
            </blockquote>
        </section>
        
        <section>
            <h3>3. &lt;mark&gt; Tag</h3>
            <p>Remember to <mark>commit your code</mark> regularly when using Git!</p>
        </section>
        
        <section>
            <h3>4. &lt;time&gt; Tag</h3>
            <p>Today's date is <time datetime="2026-02-24">February 24, 2026</time>.</p>
        </section>
        
        <section>
            <h3>5. &lt;details&gt; & &lt;summary&gt; Tags</h3>
            <details>
                <summary>Click to learn more about semantic HTML</summary>
                <p>Semantic HTML uses tags that describe their meaning, making websites more accessible and SEO-friendly.</p>
            </details>
        </section>
    </main>
    
    <footer>
        <p>© 2026 Emmanuel Wachira - IYF Season 10</p>
    </footer>
</body>
</html>
day2 navigation,html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day 2: Navigation Menu - Emmanuel Wachira</title>
</head>
<body>
    <header>
        <!-- Logo/site name on left -->
        <div style="float: left;">
            <h1>Emmanuel's Portfolio</h1>
        </div>
        
        <!-- 4 navigation links on right -->
        <nav style="float: right;">
            <ul style="list-style: none; display: flex; gap: 20px;">
                <li><a href="../index.html">Home</a></li>
                <li><a href="../about.html">About</a></li>
                <li><a href="../projects.html">Projects</a></li>
                <li><a href="../contact.html">Contact</a></li>
            </ul>
        </nav>
        <div style="clear: both;"></div>
    </header>
    
    <main>
        <h2>Day 2 Challenge: Navigation Menu</h2>
        <p>This page demonstrates a semantic navigation menu with logo on left and 4 links on right.</p>
    </main>
    
    <footer>
        <p>© 2026 Emmanuel Wachira</p>
    </footer>
</body>
</html>
day3-contact-section
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day 3: Contact Section - Emmanuel Wachira</title>
</head>
<body>
    <header>
        <nav>
            <a href="../index.html">Back to Home</a>
        </nav>
        <h1>Contact Section Challenge</h1>
    </header>
    
    <main>
        <section>
            <h2>Get in Touch</h2>
            
            <!-- Address using <address> tag -->
            <address>
                <strong>Emmanuel Wachira</strong><br>
                123 Developer Street<br>
                Nairobi, Kenya 00100<br>
                East Africa
            </address>
            
            <!-- Email link using mailto -->
            <p><strong>Email:</strong> <a href="mailto:emmanuel.wachira@example.com">emmanuel.wachira@example.com</a></p>
            
            <!-- Phone link using tel -->
            <p><strong>Phone:</strong> <a href="tel:+254700000000">+254 700 000 000</a></p>
            
            <!-- Social media links -->
            <h3>Follow Me</h3>
            <ul>
                <li><a href="https://github.com/emmanuelwachira45-spec" target="_blank">GitHub</a></li>
                <li><a href="https://linkedin.com/in/emmanuel-wachira" target="_blank">LinkedIn</a></li>
                <li><a href="https://twitter.com/emmanuelwachira" target="_blank">Twitter</a></li>
            </ul>
        </section>
    </main>
    
    <footer>
        <p>© 2026 Emmanuel Wachira</p>
    </footer>
</body>
</html>
Day4-photo-gallery
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day 4: Photo Gallery - Emmanuel Wachira</title>
</head>
<body>
    <header>
        <nav>
            <a href="../index.html">Back to Home</a>
        </nav>
        <h1>Photo Gallery Challenge</h1>
    </header>
    
    <main>
        <h2>My Favorite Places</h2>
        
        <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px;">
            <!-- Image 1 -->
            <figure>
                <img src="https://placehold.co/300x200/ff6b6b/white" alt="Sunset at the beach">
                <figcaption>Beautiful sunset at Diani Beach</figcaption>
            </figure>
            
            <!-- Image 2 -->
            <figure>
                <img src="https://placehold.co/300x200/4ecdc4/white" alt="Mountain landscape">
                <figcaption>Hiking in Mount Kenya</figcaption>
            </figure>
            
            <!-- Image 3 -->
            <figure>
                <img src="https://placehold.co/300x200/ffe66d/black" alt="City skyline">
                <figcaption>Nairobi city skyline</figcaption>
            </figure>
            
            <!-- Image 4 -->
            <figure>
                <img src="https://placehold.co/300x200/95e06c/white" alt="Forest path">
                <figcaption>Karura Forest walking trail</figcaption>
            </figure>
            
            <!-- Image 5 -->
            <figure>
                <img src="https://placehold.co/300x200/6c5ce7/white" alt="Coffee cup and laptop">
                <figcaption>My favorite coffee shop workspace</figcaption>
            </figure>
            
            <!-- Image 6 -->
            <figure>
                <img src="https://placehold.co/300x200/fab1a0/white" alt="Wildlife safari">
                <figcaption>Elephants in Amboseli National Park</figcaption>
            </figure>
        </div>
    </main>
    
    <footer>
        <p>© 2026 Emmanuel Wachira</p>
    </footer>
</body>
</html>
Day5-post-blog.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day 5: Blog Post - Emmanuel Wachira</title>
</head>
<body>
    <header>
        <nav>
            <a href="../index.html">Back to Home</a>
        </nav>
    </header>
    
    <main>
        <article>
            <!-- Article title and metadata -->
            <header>
                <h1>Getting Started with Web Development: My IYF Journey</h1>
                <p>
                    <strong>Published on:</strong> <time datetime="2026-02-24">February 24, 2026</time><br>
                    <strong>Author:</strong> Emmanuel Wachira
                </p>
            </header>
            
            <!-- Featured image -->
            <figure>
                <img src="https://placehold.co/800x400/4a90e2/white" alt="Laptop with code on screen">
                <figcaption>Setting up my development environment</figcaption>
            </figure>
            
            <!-- Multiple paragraphs with subheadings -->
            <section>
                <h2>Week 1: The Foundation</h2>
                <p>Starting the IYF Season 10 program has been an incredible experience. In our first week, we've been diving deep into HTML fundamentals, learning how to structure web pages semantically, and understanding the importance of accessibility.</p>
                
                <h3>Setting Up My Environment</h3>
                <p>The first task was getting all our tools ready. I installed VS Code along with essential extensions like Live Server and Prettier. Git was set up for version control, and I created my first repository: iyf-s10-week-01-emmanuelwachira45-spec.</p>
                
                <h3>Learning HTML Semantics</h3>
                <p>One of the most valuable lessons was converting non-semantic div-based layouts to proper HTML5 elements. Using header, nav, main, article, and footer makes websites more accessible and easier to maintain.</p>
                
                <h3>Accessibility First</h3>
                <p>We learned that building for the web means building for everyone. Adding alt text to images, proper heading hierarchy, and descriptive link text ensures that people using screen readers can navigate our sites effectively.</p>
            </section>
            
            <!-- Related posts section -->
            <aside>
                <h3>Related Posts</h3>
                <ul>
                    <li><a href="#">10 Essential VS Code Extensions for Beginners</a></li>
                    <li><a href="#">Understanding Semantic HTML: A Complete Guide</a></li>
                    <li><a href="#">How to Deploy Your First Website on GitHub Pages</a></li>
                    <li><a href="#">Accessibility Tips Every Developer Should Know</a></li>
                </ul>
            </aside>
        </article>
    </main>
    
    <footer>
        <p>© 2026 Emmanuel Wachira - IYF Season 10 Blog</p>
    </footer>
</body>
</html>
