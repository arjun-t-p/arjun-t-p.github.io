<!-- Personal Academic Website -->
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Arjun T P – Academic Profile</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

    <!-- Icons -->
    <script src="https://kit.fontawesome.com/a2e0e6ad59.js" crossorigin="anonymous"></script>

    <style>
        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            background-color: #0A2342;
            color: #ffffff;
            transition: background 0.3s ease, color 0.3s ease;
        }

        .light-mode {
            background-color: #ffffff;
            color: #000000;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 30px;
            text-align: justify;
        }

        /* Header */
        h1 {
            margin: 0;
            text-align: left;
            font-size: 2.4rem;
        }

        h2 {
            margin-top: 5px;
            text-align: left;
            font-weight: 400;
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Profile section */
        .profile-section {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-top: 20px;
        }

        .profile-photo {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #ffffff;
        }

        .icons a {
            margin-right: 15px;
            font-size: 1.6rem;
            color: #ffffff;
            text-decoration: none;
        }

        .light-mode .icons a {
            color: #000000;
        }

        /* Section title */
        .section-title {
            margin-top: 40px;
            font-size: 1.4rem;
            font-weight: 600;
            text-align: left;
            border-left: 4px solid #ffffff;
            padding-left: 10px;
        }

        .light-mode .section-title {
            border-color: #000000;
        }

        /* Dark/Light toggle */
        .toggle-btn {
            position: fixed;
            top: 20px;
            right: 20px;
            background: none;
            border: 2px solid #ffffff;
            padding: 8px 15px;
            border-radius: 20px;
            cursor: pointer;
            color: #ffffff;
        }

        .light-mode .toggle-btn {
            border-color: #000000;
            color: #000000;
        }

        a {
            color: #9BD1FF;
        }

        .light-mode a {
            color: #003366;
        }
    </style>
</head>

<body>
    <button class="toggle-btn" onclick="toggleMode()">Toggle Mode</button>

    <div class="container">
        <h1>Arjun T P</h1>
        <h2>Academic Profile</h2>

        <div class="profile-section">
            <img src="YOUR_PHOTO.jpg" alt="Profile Photo" class="profile-photo" />
            <div class="icons">
                <a href="https://www.linkedin.com/in/arjun-t-p-b94ba8152" target="_blank"><i class="fab fa-linkedin"></i></a>
                <a href="https://scholar.google.com/citations?user=sX62stUAAAAJ&hl=en" target="_blank"><i class="fas fa-graduation-cap"></i></a>
                <a href="https://orcid.org/0000-0001-9531-0121" target="_blank"><i class="fab fa-orcid"></i></a>
            </div>
        </div>

        <p><strong>Email:</strong> <a href="mailto:arjuntp30@gmail.com">arjuntp30@gmail.com</a></p>

        <div class="section-title">Research Interest</div>
        <p>Financial Markets | Corporate Finance | FinTech | Digital Economy</p>

        <div class="section-title">Publications</div>
        <p>
            Add your publication list here. All external website links will automatically appear as hyperlinks.
        </p>

        <div class="section-title">Teaching</div>
        <p>
            Add your teaching details here.
        </p>
    </div>

    <script>
        function toggleMode() {
            document.body.classList.toggle('light-mode');
        }
    </script>
</body>
</html>
