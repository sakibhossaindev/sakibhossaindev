<h1 align="center">Hi, I'm Sakib 👋</h1>
<h3 align="center">🚀 MERN Stack Developer</h3>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <style>
    :root {
      --bg: #020617;
      --card: #0f172a;
      --primary: #38bdf8;
      --text: #e5e7eb;
      --muted: #94a3b8;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Segoe UI", sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
      background: radial-gradient(circle at top, #0ea5e9, #020617 60%);
    }

    header h1 {
      font-size: 52px;
      font-weight: 700;
    }

    header span {
      color: var(--primary);
    }

    header p {
      margin-top: 15px;
      font-size: 20px;
      color: var(--muted);
    }

    section {
      max-width: 1100px;
      margin: auto;
      padding: 70px 20px;
    }

    h2 {
      font-size: 32px;
      margin-bottom: 30px;
      color: var(--primary);
    }

    .about {
      font-size: 18px;
      color: var(--muted);
      max-width: 800px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    .skill {
      background: var(--card);
      padding: 14px 20px;
      border-radius: 999px;
      border: 1px solid #1e293b;
      font-size: 15px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
    }

    .project {
      background: var(--card);
      padding: 25px;
      border-radius: 16px;
      border: 1px solid #1e293b;
      transition: 0.3s;
    }

    .project:hover {
      transform: translateY(-6px);
      border-color: var(--primary);
    }

    .project h3 {
      margin-bottom: 10px;
    }

    .project p {
      color: var(--muted);
      font-size: 15px;
      margin-bottom: 15px;
    }

    .project a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 500;
    }

    .contact a {
      color: var(--pri
