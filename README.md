<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Priyadharshini | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Priyadharshini J</h1>
    <p>Aspiring CSBS Professional | Creative Technologist</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section id="about">
      <h2>About Me</h2>
      <p>I’m a Computer Science and Business Systems student passionate about building impactful, tech-driven solutions.</p>
    </section>

    <section id="skills" class="flex">
      <div class="card"><h3>Languages</h3><p>Java, Python</p></div>
      <div class="card"><h3>Web</h3><p>HTML, CSS, JavaScript</p></div>
      <div class="card"><h3>Tools</h3><p>Power BI, Tableau, MySQL</p></div>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="flex">
        <div class="card">
          <h3>TalkAble</h3>
          <p>Assistive communication app using gestures and voice for differently-abled users.</p>
        </div>
        <div class="card">
          <h3>DevChain</h3>
          <p>Blockchain + DevOps for secure and transparent software development.</p>
        </div>
        <div class="card">
          <h3>MBA Dashboard</h3>
          <p>Survey-based Power BI dashboard for MBA student insights and data management.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:youremail@gmail.com">youremail@gmail.com</a></p>
      <p>Location: Mayiladuthurai, India</p>
      <p>LinkedIn: <a href="#">LinkedIn Profile</a></p>
    </section>
  </main>

  <footer>
    <p>© 2025 Priyadharshini J | Portfolio</p>
  </footer>
</body>
</html>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(135deg, #1a001f, #2b001f, #000000);
  color: #f8f8f8;
  line-height: 1.6;
  scroll-behavior: smooth;
  animation: fadeIn 1.3s ease;
  background-size: 400% 400%;
  animation: animatedBg 15s ease infinite;
}
@keyframes animatedBg {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
header {
  text-align: center;
  padding: 3rem 1rem;
  background: rgba(0, 0, 0, 0.7);
  color: #f8bbd0;
  animation: slideDown 1s ease-out;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.5);
  border-bottom: 2px solid #ec407a;
}
header h1 { font-size: 2.8rem; color: #ff80ab; }
header p { font-size: 1.1rem; color: #f48fb1; margin-top: 0.5rem; }
nav { margin-top: 1rem; }
nav a {
  margin: 0 1.2rem;
  color: #f06292;
  font-weight: bold;
  text-decoration: none;
  font-size: 1rem;
  transition: 0.4s ease;
}
nav a:hover {
  color: #fce4ec;
  text-shadow: 0 0 10px #f06292;
  transform: scale(1.1);
}
.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 2rem;
}
section {
  margin: 3rem 0;
  padding: 1.5rem;
  background: rgba(255, 255, 255, 0.03);
  border-left: 5px solid #f06292;
  border-radius: 12px;
  box-shadow: 0 0 15px rgba(240, 98, 146, 0.3);
  animation: fadeInUp 1s ease;
}
h2 {
  color: #f06292;
  margin-bottom: 1rem;
  text-align: center;
  font-size: 1.8rem;
}
.flex {
  display: flex;
  flex-wrap: nowrap;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  gap: 1.5rem;
  padding-bottom: 1rem;
}
.card {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid #f06292;
  padding: 1.5rem;
  border-radius: 12px;
  min-width: 280px;
  scroll-snap-align: start;
  text-align: center;
  box-shadow: 0 0 20px rgba(240, 98, 146, 0.3);
  transition: transform 0.3s ease, box-shadow 0.3s;
}
.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 0 25px rgba(255, 64, 129, 0.8);
}
a {
  color: #f8bbd0;
  transition: 0.3s ease;
}
a:hover {
  color: #fff;
  text-shadow: 0 0 5px #f06292;
}
footer {
  text-align: center;
  padding: 1rem;
  background: #000;
  color: #f48fb1;
}
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
@keyframes slideDown {
  from { transform: translateY(-100px); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: translateY(0); }
}

