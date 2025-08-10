// script.js — builds the portfolio DOM dynamically

const make = (tag, attrs = {}, html = '') => {
  const el = document.createElement(tag);
  for (const k in attrs) {
    if (k === 'class') el.className = attrs[k];
    else if (k === 'src') el.src = attrs[k];
    else if (k === 'href') el.href = attrs[k];
    else if (k === 'alt') el.alt = attrs[k];
    else if (k === 'id') el.id = attrs[k];
    else el.setAttribute(k, attrs[k]);
  }
  if (html) el.innerHTML = html;
  return el;
};

const navbar = () => {
  const nav = make('nav', { class: 'navbar' });
  nav.appendChild(make('a', { href: '#', class: 'logo' }, 'Aditya Kumar'));
  const links = make('div', { class: 'nav-links' });
  ['About', 'Skills', 'Projects', 'Resume', 'Contact'].forEach(txt => {
    const a = make('a', { href: `#${txt.toLowerCase()}` }, txt);
    links.appendChild(a);
  });
  nav.appendChild(links);
  return nav;
};

const header = make('header');
header.appendChild(navbar());

const hero = make('section', { class: 'hero' },
  `<div class="hero-content">
     <div class="hero-text">
       <h1>Hi, I'm Aditya Kumar</h1>
       <p>A passionate and driven student of Electronics and Communication Engineering with a strong interest in web development and software engineering.</p>
       <a href="#contact" class="btn">Get In Touch</a>
     </div>
     <div class="hero-image">
       <img src="aditya_kumar.jpg" alt="Portrait of a professional web developer working on a laptop in a modern workspace">
     </div>
   </div>`);

const about = make('section', { id: 'about', class: 'about' },
  `<h2 class="section-title">About Me</h2>
   <div class="about-content">
     <div class="about-text">
       <p>I enjoy turning ideas into real-world projects using technologies like HTML, CSS, JavaScript, React, and Node.js. I'm constantly exploring new tools and frameworks to stay updated and improve my skills.</p>
       <p>I have experience working on personal projects like portfolios and project management tools, with deployment on platforms such as GitHub Pages, Netlify, and Heroku. I also use GitLab for version control and collaboration. My goal is to build smart, efficient, and user-friendly digital solutions that create real impact.</p>
       <p>When I'm not coding, you can find me playing Volleyball, watching sci-fi movies, or exploring new places and riding bike.</p>
     </div>
     <div class="about-image">
       <img src="aditya_kumar_1.jpg" alt="Close-up portrait of a professional developer with a friendly smile">
     </div>
   </div>`);

const skills = make('section', { id: 'skills', class: 'skills' },
  `<h2 class="section-title">My Skills</h2>
   <div class="skills-container">
     <div class="skill-card">
       <h3>HTML & CSS</h3>
       <p>Building semantic, responsive layouts with modern CSS techniques.</p>
       <div class="skill-bar"><div class="skill-progress" style="width:95%"></div></div>
     </div>
     <div class="skill-card">
       <h3>JavaScript</h3>
       <p>Creating interactive experiences and complex applications.</p>
       <div class="skill-bar"><div class="skill-progress" style="width:90%"></div></div>
     </div>
     <div class="skill-card">
       <h3>React</h3>
       <p>Developing component-based UIs with React ecosystem.</p>
       <div class="skill-bar"><div class="skill-progress" style="width:85%"></div></div>
     </div>
     <div class="skill-card">
       <h3>Python</h3>
       <p>Developing a web and software</p>
       <div class="skill-bar"><div class="skill-progress" style="width:80%"></div></div>
     </div>
   </div>`);

const projects = make('section', { id: 'projects', class: 'projects' },
  `<h2 class="section-title">My Projects</h2>
   <div class="projects-container">
     <div class="project-card">
       <img class="project-image" src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/b10a3580-55a7-4fe5-9ce1-c768c42edfcf.png" alt="Task Manager Dashboard">
       <div class="project-info">
         <h3>Task Manager App</h3>
         <p>A productivity application for organizing tasks with drag-and-drop functionality and team collaboration features.</p>
         <div class="project-links"><a href="#" class="btn">View Live</a></div>
       </div>
     </div>

     <div class="project-card">
       <img class="project-image" src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/283f3a17-dbfc-4632-beb1-752a1a2b9a8e.png" alt="E-commerce Homepage">
       <div class="project-info">
         <h3>E-commerce Platform</h3>
         <p>Complete online store with product catalog, shopping cart, and payment processing integration.</p>
         <div class="project-links"><a href="#" class="btn">View Live</a></div>
       </div>
     </div>

     <div class="project-card">
       <img class="project-image" src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/53a18ea6-5978-4699-8ed0-8d0dbb5861f8.png" alt="Fitness Tracker">
       <div class="project-info">
         <h3>Fitness Tracker</h3>
         <p>Mobile application for tracking workouts, nutrition, and health metrics with personalized recommendations.</p>
         <div class="project-links"><a href="#" class="btn">View Live</a></div>
       </div>
     </div>
   </div>`);

const resume = make('section', { id: 'resume', class: 'resume' },
  `<h2 class="section-title">My Resume</h2>
   <div class="resume-content">
     <p>Download a copy of my resume to learn more about my professional background and experience.</p>
     <a href="#" class="btn" download>Download Resume</a>
   </div>`);

const contact = make('section', { id: 'contact', class: 'contact' },
  `<h2 class="section-title">Get In Touch</h2>
   <form class="contact-form">
     <div class="form-group">
       <label for="name">Name</label>
       <input type="text" id="name" name="name" required>
     </div>
     <div class="form-group">
       <label for="email">Email</label>
       <input type="email" id="email" name="email" required>
     </div>
     <div class="form-group">
       <label for="message">Message</label>
       <textarea id="message" name="message" required></textarea>
     </div>
     <button type="submit" class="btn">Send Message</button>
   </form>`);

const footer = make('footer', {}, 
  `<div class="footer-content">
     <p>© 2023 Aditya Kumar. All rights reserved.</p>
     <div class="social-links">
       <a href="#" aria-label="LinkedIn">LinkedIn</a>
       <a href="#" aria-label="GitHub">GitHub</a>
       <a href="#" aria-label="Twitter">Twitter</a>
     </div>
   </div>`);

// assemble page
document.body.prepend(header);
document.body.appendChild(hero);
document.body.appendChild(about);
document.body.appendChild(skills);
document.body.appendChild(projects);
document.body.appendChild(resume);
document.body.appendChild(contact);
document.body.appendChild(footer);

// simple contact form handler (prevents reload and shows alert)
const form = document.querySelector('.contact-form');
if (form) {
  form.addEventListener('submit', e => {
    e.preventDefault();
    alert('Thanks! Your message was sent (demo).');
    form.reset();
  });
}
