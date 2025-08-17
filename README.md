# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ApplyGOAT – Career Assistant</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f5f7fa;
      color: #222;
      margin: 0;
      padding: 40px 20px;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
    }

    header {
      text-align: center;
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 2.8rem;
      color: #0073e6;
      margin-bottom: 8px;
    }

    header p {
      font-size: 1.1rem;
      color: #555;
    }

    main {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 25px;
    }

    @media (max-width: 600px) {
      main {
        grid-template-columns: 1fr;
      }
    }

    .card {
      background: white;
      padding: 25px 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 115, 230, 0.15);
      transition: box-shadow 0.3s ease;
    }

    .card:hover {
      box-shadow: 0 6px 18px rgba(0, 115, 230, 0.3);
    }

    .card h2 {
      font-size: 1.4rem;
      color: #0073e6;
      margin-bottom: 12px;
    }

    .card p {
      font-size: 1rem;
      color: #444;
      margin-bottom: 18px;
      line-height: 1.4;
    }

    button {
      background-color: #0073e6;
      border: none;
      padding: 10px 18px;
      border-radius: 7px;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.25s ease;
      width: 100%;
    }

    button:hover {
      background-color: #005bb5;
    }

    footer {
      margin-top: 50px;
      text-align: center;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>ApplyGOAT</h1>
    <p>Your AI Career Assistant for Students and Professionals</p>
  </header>

  <main>
    <section class="card">
      <h2>Auto Apply</h2>
      <p>Automatically submit applications to multiple jobs with one click and save time.</p>
      <button onclick="window.open('https://applygoat.com', '_blank')">Learn More</button>
    </section>

    <section class="card">
      <h2>ATS Resume Scan</h2>
      <p>Optimize your resume for Applicant Tracking Systems and increase your chances.</p>
      <button onclick="window.open('https://applygoat.com/pricing', '_blank')">Pricing & Features</button>
    </section>

    <section class="card">
      <h2>CV & Cover Letter Generator</h2>
      <p>Create tailored resumes and cover letters fast and professionally.</p>
      <button onclick="window.open('https://applygoat.com', '_blank')">Get Started</button>
    </section>

    <section class="card">
      <h2>Job Board</h2>
      <p>Browse curated job openings matching your skills and interests.</p>
      <button onclick="window.open('https://applygoat.com/jobs', '_blank')">Browse Jobs</button>
    </section>

    <section class="card">
      <h2>Interview Preparation</h2>
      <p>Practice interview questions and get expert tips to ace your interviews.</p>
      <button onclick="window.open('https://applygoat.com/pricing', '_blank')">View Plans</button>
    </section>

    <section class="card">
      <h2>Plans & Pricing</h2>
      <p>Explore free and premium plans designed to help you land your dream job.</p>
      <button onclick="window.open('https://applygoat.com/pricing', '_blank')">See Plans</button>
    </section>
  </main>

  <footer>
    &copy; 2025 ApplyGOAT. All rights reserved.
  </footer>
</body>
</html>
indexx.html
Responsive and clean landing page for ApplyGOAT, an AI-powered career assistant helping students and professionals with job applications, resume optimization, cover letter generation, and job discovery.
