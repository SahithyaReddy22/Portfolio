<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sahithya Reddy | Portfolio</title>
  <link
    href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap"
    rel="stylesheet"
  />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background-color: #121212;
      color: #e0e0e0;
      line-height: 1.6;
    }
    header {
      background-color: #1f1f1f;
      color: #82aaff;
      padding: 40px 0;
      text-align: center;
      border-bottom: 2px solid #82aaff;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 8px;
    }
    header p {
      font-size: 1.2rem;
      font-weight: 300;
      color: #a3bffa;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #82aaff;
      margin-bottom: 20px;
      border-bottom: 1px solid #82aaff;
      padding-bottom: 6px;
      font-weight: 700;
    }
    .project,
    .skill,
    .contact {
      margin-bottom: 30px;
      background-color: #1f1f1f;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px #3949ab88;
    }

    .project h3 {
      margin-bottom: 8px;
      color: #a3bffa;
    }
    .project p {
      margin-bottom: 12px;
      color: #cbd5e1;
    }
    .project a {
      color: #82aaff;
      text-decoration: none;
      font-weight: 600;
    }
    .project a:hover {
      text-decoration: underline;
    }

    .skills-list {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }
    .skills-list span {
      background: #3949ab;
      padding: 8px 14px;
      border-radius: 20px;
      font-weight: 600;
      color: #e0e0e0;
      box-shadow: 0 0 10px #3949abcc;
      user-select: none;
    }

    .contact p {
      margin-bottom: 10px;
      font-size: 1rem;
    }
    .contact a {
      color: #82aaff;
      text-decoration: none;
      font-weight: 600;
    }
    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      background-color: #1f1f1f;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #777;
      margin-top: 40px;
      border-top: 1px solid #3949ab;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sahithya Reddy</h1>
    <p>Aspiring Developer | Problem Solver | Tech Explorer</p>
  </header>

  <section>
    <h2>🧠 About Me</h2>
    <p>
      I’m a passionate developer exploring AI, backend development, and
      open-source contributions. I love building real-world tools that solve
      real problems.
    </p>
  </section>

  <section>
    <h2>🚀 Projects</h2>

    <div class="project">
      <h3>ChatPDF</h3>
      <p>
        An AI-powered chatbot that reads and answers questions from PDF files
        using LangChain and OpenAI.
      </p>
      <a
        href="https://github.com/SahithyaReddy22/ChatPDF"
        target="_blank"
        >View on GitHub →</a
      >
    </div>

    <div class="project">
      <h3>Integrated Crop Protection and Management</h3>
      <p>
        A web application designed for farmers to check weather conditions,
        predict diseases by uploading pictures of plants/leaves, and recommend
        fertilizers.
      </p>
    </div>

    <div class="project">
      <h3>Email Spam Detector</h3>
      <p>
        An application that detects whether an email is spam or ham by
        recognizing hidden patterns in emails using Natural Language
        Processing (NLP).
      </p>
    </div>
  </section>

  <section>
    <h2>🛠️ Skills</h2>
    <div class="skills-list">
      <span>Java</span>
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>MySql</span>
      <span>GitHub</span>
      <span>Git</span>
      <span>Python</span>
      <span>Web Development</span>
    </div>
  </section>

  <section>
    <h2>📬 Contact</h2>
    <div class="contact">
      <p>
        Email:
        <a href="mailto:reddysahithya75@gmail.com">reddysahithya75@gmail.com</a>
      </p>
      <p>
        GitHub:
        <a href="https://github.com/SahithyaReddy22" target="_blank"
          >SahithyaReddy22</a
        >
      </p>
    </div>
  </section>

  <footer>
    <p>© 2025 Sahithya Reddy | Portfolio</p>
  </footer>
</body>
</html>
