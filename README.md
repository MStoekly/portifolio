<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Resume – Mateus Stoekly</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
      max-width: 800px;
      margin: auto;
      padding: 20px;
    }
    h2, h3 {
      color: #005288;
    }
    section {
      margin-bottom: 30px;
    }
    .contact {
      font-size: 0.95em;
    }

    /* Skill Bar Styles */
    .skills-grid {
      display: flex;
      gap: 40px;
      flex-wrap: wrap;
    }
    .skill-column {
      flex: 1;
      min-width: 300px;
    }
    .skill {
      margin-bottom: 10px;
    }
    .skill-name {
      font-size: 0.95em;
      margin-bottom: 3px;
    }
    .bar {
      background: #ddd;
      border-radius: 5px;
      height: 10px;
      overflow: hidden;
    }
    .bar-fill {
      height: 100%;
      background: #005288;
      display: block;
    }

    /* Proficiency levels */
    .p100 { width: 100%; }
    .p90  { width: 90%; }
    .p85  { width: 85%; }
    .p80  { width: 80%; }
    .p75  { width: 75%; }
    .p70  { width: 70%; }
    .p60  { width: 60%; }
  </style>
</head>
<body>

  <p class="contact">
    Curitiba, PR | +55 41 99980-3022 |
    <a href="mailto:mateus.stoekly@gmail.com">mateus.stoekly@gmail.com</a> |
    <a href="https://linkedin.com/in/mateus.stoekly" target="_blank">LinkedIn</a>
  </p>

  <section>
    <h2>Summary</h2>
    <p>Dynamic and results-oriented Data Analyst with a proven ability to transform complex datasets into actionable insights. Proficient in SQL, Power BI, and advanced Excel VBA. Experienced in public and private sectors, optimizing workflows, automating processes, and supporting strategic decision-making through data visualization and predictive analytics.</p>
  </section>

  <section>
    <h2>Skills</h2>

    <h3>Hard Skills</h3>
    <div class="skills-grid">
      <div class="skill-column">
        <div class="skill"><div class="skill-name">SQL</div><div class="bar"><span class="bar-fill p90"></span></div></div>
        <div class="skill"><div class="skill-name">Excel (VBA)</div><div class="bar"><span class="bar-fill p90"></span></div></div>
        <div class="skill"><div class="skill-name">Power BI</div><div class="bar"><span class="bar-fill p85"></span></div></div>
        <div class="skill"><div class="skill-name">ETL Processes</div><div class="bar"><span class="bar-fill p80"></span></div></div>
      </div>
      <div class="skill-column">
        <div class="skill"><div class="skill-name">Data Visualization</div><div class="bar"><span class="bar-fill p85"></span></div></div>
        <div class="skill"><div class="skill-name">Cloud Platforms</div><div class="bar"><span class="bar-fill p70"></span></div></div>
        <div class="skill"><div class="skill-name">Statistical Analysis</div><div class="bar"><span class="bar-fill p75"></span></div></div>
        <div class="skill"><div class="skill-name">Python</div><div class="bar"><span class="bar-fill p60"></span></div></div>
      </div>
    </div>

    <h3>Human Skills</h3>
    <div class="skills-grid">
      <div class="skill-column">
        <div class="skill"><div class="skill-name">Data Storytelling</div><div class="bar"><span class="bar-fill p85"></span></div></div>
        <div class="skill"><div class="skill-name">Communication</div><div class="bar"><span class="bar-fill p90"></span></div></div>
        <div class="skill"><div class="skill-name">Time Management</div><div class="bar"><span class="bar-fill p80"></span></div></div>
      </div>
      <div class="skill-column">
        <div class="skill"><div class="skill-name">Critical Thinking</div><div class="bar"><span class="bar-fill p85"></span></div></div>
        <div class="skill"><div class="skill-name">Problem Solving</div><div class="bar"><span class="bar-fill p80"></span></div></div>
        <div class="skill"><div class="skill-name">Teamwork & Adaptability</div><div class="bar"><span class="bar-fill p75"></span></div></div>
      </div>
    </div>

  </section>

  <section>
    <h2>Experience</h2>
    <h3>State Department of Infrastructure and Logistics — Business Analyst</h3>
    <p><em>Feb 2023 – Present</em></p>
    <ul>
      <li>Reduced processing time from one week to four hours with Excel VBA and SQL.</li>
      <li>Created Power BI dashboards and predictive KPIs using SQL.</li>
      <li>Built SQL databases to enhance public transparency.</li>
      <li>Led CLP Ranking analysis and COPEL resource dashboard projects.</li>
      <li>Automated ETL processes and implemented audit trails and access controls.</li>
    </ul>

    <h3>Faurecia — PC&L Trainee</h3>
    <p><em>June 2022 – Feb 2023</em></p>
    <ul>
      <li>Automated freight data validation using VBA + SAP, cutting debt by 97%.</li>
      <li>Managed international freight KPIs with Power BI and SQL.</li>
      <li>Improved container utilization by 86% with custom dashboards.</li>
      <li>Collaborated globally to streamline supply chain analytics.</li>
    </ul>
  </section>

  <section>
    <h2>Education</h2>
    <p><strong>ESIC Business & Marketing School</strong><br>Bachelor's in International Business — Jan 2020 to Dec 2023</p>
  </section>

  <section>
    <h2>Certifications</h2>
    <ul>
      <li>Power BI Experience Course – 130h (2024)</li>
      <li>Power BI Masterclass – 72h (2022)</li>
      <li>Excel Pro Tips, Tables & Charts – Maven Analytics</li>
      <li>Chris Voss Negotiation – MasterClass</li>
    </ul>
  </section>

  <section>
    <h2>International Experience</h2>
    <p><strong>Limerick, Ireland (2018–2019):</strong> Reached advanced English in 7 months, enhancing global communication skills.</p>
    <p><strong>Jack Monday’s Coffee House:</strong> Provided high-quality service and streamlined operations while working collaboratively in a fast-paced setting.</p>
  </section>

</body>
</html>
