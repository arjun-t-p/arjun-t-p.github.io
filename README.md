<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Arjun T P | Academic Profile</title>
  
  <style>
    body.dark-mode{background:#0b2b5a; color:white;}
    body.dark-mode .container{background:#ffffff11; color:white;}
    body.dark-mode a{color:#9ecbff;}
    :root{
      --dark-bg:#0b2b5a; /* dark blue */
      --accent:#235aa6;
      --white:#ffffff;
      --black:#111111;
      --container-radius:12px;
      --max-width:960px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:'Inter',sans-serif;
      background:var(--white);
      color:var(--black);
      line-height:1.6;
      -webkit-font-smoothing:antialiased;
    }

    /* Header (dark background with white text) */
    header{
      background:var(--dark-bg);
      color:var(--white);
      padding:48px 20px;
    }
    .header-inner{
      max-width:var(--max-width);
      margin:0 auto;
      display:flex;
      flex-direction:column;
      align-items:flex-start; /* left align title and subtitle */
      gap:8px;
    }
    header h1{margin:0;font-size:2.25rem;font-weight:700}
    header p{margin:0;font-size:1rem;opacity:0.95}
    header .links{margin-top:10px}
    header .links a{color:var(--white);text-decoration:none;margin-right:12px;font-weight:600}

    /* Main container (white background with black text) */
    .container{
      max-width:var(--max-width);
      margin: -28px auto 40px; /* pull up to overlap header slightly */
      background:var(--white);
      color:var(--black);
      padding:28px 32px;
      border-radius:var(--container-radius);
      box-shadow:0 8px 30px rgba(11,43,90,0.08);
    }

    /* Headings left aligned */
    h2{margin-top:0;font-size:1.5rem;color:var(--dark-bg);text-align:left}

    /* Justify all paragraph and list content */
    .container p,
    .container ul,
    .container li,
    .pub-item{
      text-align:justify;
      margin:0 0 12px 0;
      color:var(--black);
    }
    ul{padding-left:20px}

    .pub-item{padding-left:12px;border-left:4px solid var(--accent);background:transparent}
    a{color:var(--accent);text-decoration:none}
    a:hover{text-decoration:underline}

    /* Footer (dark background) */
    footer{
      background:var(--dark-bg);
      color:var(--white);
      padding:18px 20px;
      text-align:left;
    }
    footer .inner{max-width:var(--max-width);margin:0 auto}

    /* Responsive tweaks */
    @media (max-width:640px){
      header h1{font-size:1.6rem}
      .container{padding:20px;margin-top:12px}
    }
  </style>
</head>
<body>

<header>
  <div style="position:absolute; top:20px; right:20px;">
    <button onclick="document.body.classList.toggle('dark-mode')" style="background:#ffffff22; border:1px solid #ffffff55; color:white; padding:6px 14px; border-radius:6px; cursor:pointer;">Toggle Mode</button>
  </div>
  <div class="header-inner">
    <h1>Arjun T P</h1>
    
    <div class="links" style="display:flex; gap:14px; align-items:center; margin-top:12px;">
      <a href="https://www.linkedin.com/in/arjun-t-p-b94ba8152" target="_blank" aria-label="LinkedIn"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/linkedin.svg" alt="LinkedIn" style="width:24px; filter:invert(1);"></a>
      <a href="https://scholar.google.com/citations?user=sX62stUAAAAJ&hl=en" target="_blank" aria-label="Google Scholar"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/googlescholar.svg" alt="Google Scholar" style="width:24px; filter:invert(1);"></a>
      <a href="https://orcid.org/0000-0001-9531-0121" target="_blank" aria-label="ORCID"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/orcid.svg" alt="ORCID" style="width:24px; filter:invert(1);"></a>
    </div>
  </div>
</header>

<main class="container" style="margin-top:40px;">
  <div style="text-align:center; margin-bottom:20px;">
    <img src="https://via.placeholder.com/160" alt="Profile Photo" style="width:160px; height:160px; border-radius:50%; object-fit:cover; border:4px solid var(--dark-bg);">
  </div>

  <section id="about-me" class="section">
    <h2>About Me</h2>
    <p>I recently completed my Ph.D. in the area of personal finance. Over the past five years, I have worked extensively in this domain, exploring themes ranging from the conceptualisation and operationalisation of financial literacy to the role of community-based organisations in enhancing financial capability. My work examines the nuanced relationship between money and well-being, as well as how individual differences shape personal financial wellness.</p>
    <p>My broader interests include behavioural finance, FinTech, microfinance, and consumer behaviour. I am currently seeking post-doctoral opportunities in personal finance and behavioural finance, aiming to continue contributing to research with real-world impact.</p>
  </section>

  <section id="employment" class="section">
    <h2>Employment</h2>
    <p><strong>Guest Faculty</strong><br>Department of Commerce,<br>Dr. B.R. Ambedkar Memorial Government Arts and Science College, Kozhikode, India<br><em>July 2025 – Current</em></p>
  </section>

  <section id="academic-background" class="section">
    <h2>Academic Background</h2>
    <ul>
      <li><strong>Ph.D.</strong>, Department of Commerce, Central University of Tamil Nadu, India (2021–2025)<br>Thesis: <em>Impact of Personal Financial Wellness on the Subjective Well-Being of Working Adults: An Empirical Investigation in Kerala.</em></li>
      <li><strong>M.Phil.</strong>, Department of Commerce, Central University of Tamil Nadu, India (2019–2021)<br>Thesis: <em>Financial Literacy and Financial Well-being of the Members of Kudumbashree Neighbourhood Group – The Case of Panangad Grama Panchayat in Kerala.</em></li>
      <li><strong>M.Com. (Finance)</strong>, Mar Ivanios College, University of Kerala, India (2016–2018)</li>
      <li><strong>B.Com. (Finance)</strong>, Farook College, University of Calicut, India (2013–2016)</li>
    </ul>
  </section>

  <section id="certification" class="section">
    <h2>Professional Certification</h2>
    <p><strong>Professional Certificate Programme in Advanced Analytics and Business Intelligence</strong><br>IIM Kozhikode, India (2025–2026)<br>Professional training in data handling, Tableau, R, Python, statistics, machine learning, deep learning and business applications.</p>
  </section>

  <section id="qualifications" class="section">
    <h2>Additional Qualification</h2>
    <p>Qualified for Assistant Professor in Commerce (UGC NET – November 2017).</p>
  </section>

  <section id="fellowships" class="section">
    <h2>Fellowships</h2>
    <ul>
      <li>American Council on Consumer Interests (ACCI) Annual Conference Student/Young Professional Scholarship Award, 2025.</li>
      <li>Junior Research Fellowship (NET-JRF), University Grants Commission, Government of India, 2020.</li>
      <li>National Fellowship for Persons with Disabilities (NFPwD), Ministry of Social Justice & Empowerment, Government of India, 2020.</li>
    </ul>
  </section>

  <section id="research-interests" class="section">
    <h2>Research Interests</h2>
    <p>Personal Finance | Behavioural Finance | Consumer Behaviour | Diversity Management</p>
  </section>

  <section id="publications" class="section">
    <h2>Research Publications</h2>

    <h3>Journal Articles</h3>
    <div class="pub-item">Arjun, T. P., & Subramanian, R. (2025). <strong>Does participation in self-help group-based micro-financial activities enhance the financial literacy of women?</strong> International Journal of Social Economics. <a href="https://doi.org/10.1108/IJSE-10-2023-0843" target="_blank">https://doi.org/10.1108/IJSE-10-2023-0843</a></div>
    <div class="pub-item">Arjun, T. P., & Subramanian, R. (2024). <strong>Defining and measuring financial literacy in the Indian context</strong>. Managerial Finance, 50(7). <a href="https://doi.org/10.1108/MF-08-2022-0358" target="_blank">https://doi.org/10.1108/MF-08-2022-0358</a></div>
    <div class="pub-item">Subramanian, R., & Arjun, T. P. (2024). <strong>Do explicit and implicit parental financial socialisation influence students’ financial literacy?</strong> Indian Journal of Finance, 18(10). 10.17010/ijf/2024/v18i10/174612</div>

    <h3>Book Chapters</h3>
    <div class="pub-item">Subramanian, R., Arjun, T. P., & Ashique Ali, K. A. (2024). <strong>How do the socio-economic characteristics of migrant workers shape their financial behaviour?</strong> In Informal Economy and Sustainable Development Goals. <a href="https://doi.org/10.1108/978-1-83753-980-220241003" target="_blank">https://doi.org/10.1108/978-1-83753-980-220241003</a></div>
    <div class="pub-item">Subramanian, R., & Arjun, T. P. (2023). <strong>Consumer cash-flow management and budgeting behavior</strong>. In A Research Agenda for Consumer Financial Behavior. <a href="https://doi.org/10.4337/9781803922652.00013" target="_blank">https://doi.org/10.4337/9781803922652.00013</a></div>

    <h3>Conference Proceedings</h3>
    <div class="pub-item">Arjun, T. P., Subramanian, R., Xiao, J. J., & K. A., A. A. (2025). <strong>Personal finance and subjective well-being – A multi-dimensional analysis</strong>. Consumer Interests Annual, 71. <a href="https://www.consumerinterests.org/assets/docs/CIA/CIA2025/TPArjunCIA2025.pdf" target="_blank">https://www.consumerinterests.org/assets/docs/CIA/CIA2025/TPArjunCIA2025.pdf</a></div>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:arjuntp30@gmail.com">arjuntp@gmail.com</a></p>
  </section>

</main>

<footer>
  <div class="inner">© Arjun T P — Academic Profile</div>
</footer>

</body>
</html>
