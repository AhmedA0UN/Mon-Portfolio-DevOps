<!-"# Mon-Portfolio-DevOps"
Repository: ahmeda0un/mon-portfolio-devops
Files analyzed: 9

Estimated tokens: 7.4k

Directory structure:
└── ahmeda0un-mon-portfolio-devops/
    ├── README.md
    ├── Eng DevOps.html
    ├── script.js
    ├── styles.css
    └── sources/
        ├── bare - icons/
        ├── docs profile/
        │   └── Profile .docx
        └── imgs/
            ├── 1.avif
            ├── 2.avif
            ├── 3.avif
            └── ph


================================================
FILE: README.md
================================================
"# Mon-Portfolio-DevOps"



================================================
FILE: Eng DevOps.html
================================================
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio DevOps - Ahmed Aoun </title>
    <link rel="icon" type="image/x-icon" href="sources/bare - icons/3.png">
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script> 

</head>
<body>
    <!-- Header & Navigation -->
    <header>
        <div class="container">
            <nav class="navbar">
                <a href="#" class="logo">Dev<span>Ops</span></a>
                <ul class="nav-links">
                    <li><a href="#accueil">Accueil</a></li>
                    <li><a href="#apropos">À Propos</a></li>
                    <li><a href="#competences">Compétences</a></li>
                    <li><a href="#projets">Projets</a></li>
                    <li><a href="#experience">Expérience</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                <div class="mobile-menu">
                    <i class="fas fa-bars"></i>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="accueil">
        <div class="container">
            <div class="hero-content">
                <h1>Ingénieur DevOps & Cloud</h1>
                <p>Je conçois, automatise et optimise des infrastructures cloud pour accélérer le développement et améliorer la fiabilité des applications.</p>
                <a href="#projets" class="btn">Voir mes projets</a>
                <a href="#contact" class="btn btn-outline">Me contacter</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section" id="apropos">
        <div class="container">
            <div class="section-title">
                <h2>À Propos de Moi</h2>
            </div>
            <div class="about-content">
                <div class="about-img">
                    <img src="https://media.licdn.com/dms/image/v2/D4E03AQFb7ivjlKETww/profile-displayphoto-shrink_400_400/B4EZadI2PHHMAg-/0/1746393064909?e=1764806400&v=beta&t=XltxYZmOufghcZwTtXdjA4ke5Gnyu6haYvJVhND-O9U" alt="Photo de profil">
                </div>
                <div class="about-text">
                    <h3>Ingénieur DevOps passionné par l'automatisation et le cloud</h3>
                    <p>Je suis un ingénieur DevOps avec 5 ans d'expérience dans la conception, l'implémentation et l'optimisation d'infrastructures cloud. Mon expertise couvre l'automatisation des déploiements, la gestion de conteneurs, l'orchestration et la surveillance des systèmes.</p>
                    <p>Je suis passionné par l'amélioration continue des processus de développement et d'exploitation, en mettant en œuvre des pratiques DevOps pour accélérer les livraisons tout en garantissant la stabilité et la sécurité des systèmes.</p>
                    <p>Mes compétences incluent AWS, Azure, Docker, Kubernetes, Terraform, Ansible, Jenkins, GitLab CI, Prometheus, Grafana et bien d'autres outils de la stack DevOps moderne.</p>
                    <a href="sources/docs profile/Profile .pdf" target="_blank" class="btn">Télécharger mon CV</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="section skills" id="competences">
        <div class="container">
            <div class="section-title">
                <h2>Mes Compétences</h2>
            </div>
            <div class="skills-container">
                <div class="skill-category">
                    <h3><i class="fas fa-cloud"></i> Cloud & Infrastructure</h3>
                    <ul class="skill-list">
                        <li><i class="fas fa-check"></i> AWS (EC2, S3, RDS, Lambda, EKS)</li>
                        <li><i class="fas fa-check"></i> Azure (VM, AKS, App Services)</li>
                        <li><i class="fas fa-check"></i> Google Cloud Platform</li>
                        <li><i class="fas fa-check"></i> Infrastructure as Code (Terraform, CloudFormation)</li>
                        <li><i class="fas fa-check"></i> Configuration Management (Ansible, Chef)</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3><i class="fas fa-code-branch"></i> CI/CD & Automatisation</h3>
                    <ul class="skill-list">
                        <li><i class="fas fa-check"></i> Jenkins, GitLab CI, GitHub Actions</li>
                        <li><i class="fas fa-check"></i> Pipeline as Code</li>
                        <li><i class="fas fa-check"></i> Déploiement Blue-Green, Canary</li>
                        <li><i class="fas fa-check"></i> Intégration et tests automatisés</li>
                        <li><i class="fas fa-check"></i> Gestion des artefacts (Nexus, Artifactory)</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3><i class="fas fa-box"></i> Conteneurs & Orchestration</h3>
                    <ul class="skill-list">
                        <li><i class="fas fa-check"></i> Docker & Docker Compose</li>
                        <li><i class="fas fa-check"></i> Kubernetes (EKS, AKS, GKE)</li>
                        <li><i class="fas fa-check"></i> Helm Charts</li>
                        <li><i class="fas fa-check"></i> Service Mesh (Istio, Linkerd)</li>
                        <li><i class="fas fa-check"></i> Sécurité des conteneurs</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3><i class="fas fa-chart-line"></i> Monitoring & Observabilité</h3>
                    <ul class="skill-list">
                        <li><i class="fas fa-check"></i> Prometheus & Grafana</li>
                        <li><i class="fas fa-check"></i> ELK Stack (Elasticsearch, Logstash, Kibana)</li>
                        <li><i class="fas fa-check"></i> Datadog, New Relic</li>
                        <li><i class="fas fa-check"></i> Alerting & Dashboards</li>
                        <li><i class="fas fa-check"></i> APM (Application Performance Monitoring)</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section" id="projets">
        <div class="container">
            <div class="section-title">
                <h2>Mes Projets</h2>
            </div>
            <div class="projects-container">
                <div class="project-card">
                    <div class="project-img">
                        <img src="https://images.unsplash.com/photo-1551650975-87deedd944c3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1674&q=80" alt="Pipeline CI/CD">
                    </div>
                    <div class="project-content">
                        <h3>Pipeline CI/CD Multi-Environnements</h3>
                        <p>Conception et implémentation d'un pipeline CI/CD complet avec Jenkins pour une application microservices, permettant des déploiements automatisés sur plusieurs environnements.</p>
                        <div class="project-tags">
                            <span class="project-tag">Jenkins</span>
                            <span class="project-tag">Docker</span>
                            <span class="project-tag">Kubernetes</span>
                            <span class="project-tag">Helm</span>
                        </div>
                        <a href="#" class="btn">Voir les détails</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-img">
                        <img src="https://images.unsplash.com/photo-1627398242454-45a1465c2479?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1674&q=80" alt="Infrastructure as Code">
                    </div>
                    <div class="project-content">
                        <h3>Infrastructure as Code avec Terraform</h3>
                        <p>Développement d'une infrastructure cloud modulaire et scalable sur AWS en utilisant Terraform, avec mise en place de VPC, sécurité, et autoscaling groups.</p>
                        <div class="project-tags">
                            <span class="project-tag">Terraform</span>
                            <span class="project-tag">AWS</span>
                            <span class="project-tag">Infrastructure as Code</span>
                            <span class="project-tag">Modules</span>
                        </div>
                        <a href="#" class="btn">Voir les détails</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-img">
                        <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80" alt="Monitoring">
                    </div>
                    <div class="project-content">
                        <h3>Plateforme de Monitoring Centralisée</h3>
                        <p>Mise en place d'une stack de monitoring complète avec Prometheus, Grafana et Alertmanager pour surveiller l'infrastructure et les applications en temps réel.</p>
                        <div class="project-tags">
                            <span class="project-tag">Prometheus</span>
                            <span class="project-tag">Grafana</span>
                            <span class="project-tag">Monitoring</span>
                            <span class="project-tag">Alerting</span>
                        </div>
                        <a href="#" class="btn">Voir les détails</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section class="section experience" id="experience">
        <div class="container">
            <div class="section-title">
                <h2>Mon Expérience</h2>
            </div>
            
            <div class="timeline">
            <!--
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Ingénieur DevOps Senior</h3>
                        <h4>Tech Solutions SA • 2020 - Présent</h4>
                        <p>Responsable de la conception et de l'implémentation de l'infrastructure cloud, mise en place de pipelines CI/CD, optimisation des coûts cloud et formation des équipes aux pratiques DevOps.</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Ingénieur DevOps</h3>
                        <h4>Innovate Cloud • 2018 - 2020</h4>
                        <p>Automatisation des déploiements, containerisation d'applications legacy, mise en place de Kubernetes en production et développement de scripts d'automatisation.</p>
                    </div>
                </div>
            -->
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Front-end Developer</h3>
                        <h4>Itquan labs • 3 mois hybride</h4>
                        <p>Utiliser le HTML, CSS, JS pour créer une interface web interactive au duré du juin - aout 2025 .</p>
                    </div>
                </div>
                <!-- -->
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Administrateur Système</h3>
                        <h4>stage CPG  •  - 2 mois présentiel</h4>
                        <p>Gestion de l'infrastructure on-premise, virtualisation, sauvegardes, mise en place des premiers processus d'automatisation
                            et maintenance et administration des serveur / juiller - aout 2025
                        </p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Diplôme d'Ingénieur en Informatique</h3>
                        <h4>Institut Supérieur
                            d'Informatique et de
                            Multimédia de Gabès • 2026 - 2030</h4>
                        <p>Spécialisation en Systèmes Embarqué & IOT  .</p> <!-- Spécialisation en systèmes distribués et cloud computing -->
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Cycle préparatoire intégré MPI </h3>
                        <h4>Institut Supérieur
                            d'Informatique et de
                            Multimédia de Gabès • 2024 - 2026</h4>
                        <p> Une formation post-bac de deux ans qui prépare aux études d’ingénieur en " mathématique-physique-informatique ".</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Diplôme nationnal de baccalauréat </h3>
                        <h4>Lycée Nefta • 2024 - science technique </h4>
                        <p>Diplôme du baccalauréat national en science technique avec la montien trés bien - 16.59  .</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contactez-Moi</h2>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="contact-text">
                            <h3>Localisation</h3>
                            <p>Tunis, Tunisie</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-text">
                            <h3>Email</h3>
                            <p>ahmedaoun1@outlook.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div class="contact-text">
                            <h3>Téléphone</h3>
                            <p>+216 99 152 499</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-globe"></i>
                        </div>
                        <div class="contact-text">
                            <h3>Site Web</h3>
                            <p>www.devops-portfolio.com</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form>
                        <div class="form-group">
                            <input type="text" class="form-control" placeholder="Votre nom" required>
                        </div>
                        <div class="form-group">
                            <input type="email" class="form-control" placeholder="Votre email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" class="form-control" placeholder="Sujet" required>
                        </div>
                        <div class="form-group">
                            <textarea class="form-control" placeholder="Votre message" required></textarea>
                        </div>
                        <button type="submit" class="btn">Envoyer le message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>


    <footer>
        <div class="container">
            <div class="footer-content">
                <a href="#" class="logo">Dev<span>Ops</span></a>
                <div class="social-links">
                    <a href="https://www.linkedin.com/in/ahmed-aoun/" target="_blank" class="social-link"><i class="fab fa-linkedin-in"></i>linkedin</a>
                    <a href="sources/docs profile/Profile .pdf" id="CV" target="_blank" class="social-link"><i class="fab fa-github"></i>CV</a>
                    <a href="#" class="social-link"><i class="fab fa-twitter">Profile</i></a>
                    <a href="#" class="social-link"><i class="fab fa-dev"></i></a>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 Portfolio DevOps. Tous droits réservés.</p>
            </div>
        </div>
    </footer>

</body>
</html>



================================================
FILE: script.js
================================================



================================================
FILE: styles.css
================================================
:root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #1abc9c;
            --light: #ecf0f1;
            --dark: #2c3e50;
            --gray: #95a5a6;
            --success: #2ecc71;
            --warning: #f39c12;
            --danger: #e74c3c;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        /* Header & Navigation */
        header {
            background-color: var(--primary);
            color: white;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: white;
            text-decoration: none;
        }

        .logo span {
            color: var(--accent);
        }

        .nav-links {
            display: flex;
            list-style: none;
        }

        .nav-links li {
            margin-left: 30px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        .mobile-menu {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 150px 0 100px;
            text-align: center;
        }

        .hero-content h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero-content p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 30px;
        }

        .btn {
            display: inline-block;
            background-color: var(--accent);
            color: white;
            padding: 12px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #16a085;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .btn-outline {
            background-color: transparent;
            border: 2px solid white;
            margin-left: 15px;
        }

        .btn-outline:hover {
            background-color: white;
            color: var(--primary);
        }

        /* About Section */
        .section {
            padding: 100px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }

        .section-title h2 {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 15px;
            position: relative;
            display: inline-block;
        }

        .section-title h2::after {
            content: '';
            position: absolute;
            width: 70px;
            height: 3px;
            background-color: var(--accent);
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
        }

        .about-content {
            display: flex;
            align-items: center;
            gap: 50px;
        }

        .about-img {
            flex: 1;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .about-img img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.5s;
        }

        .about-img:hover img {
            transform: scale(1.05);
        }

        .about-text {
            flex: 1;
        }

        .about-text h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--primary);
        }

        .about-text p {
            margin-bottom: 20px;
            color: var(--gray);
        }

        /* Skills Section */
        .skills {
            background-color: var(--light);
        }

        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .skill-category {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s;
        }

        .skill-category:hover {
            transform: translateY(-10px);
        }

        .skill-category h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: var(--primary);
            display: flex;
            align-items: center;
        }

        .skill-category h3 i {
            margin-right: 10px;
            color: var(--accent);
        }

        .skill-list {
            list-style: none;
        }

        .skill-list li {
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }

        .skill-list li i {
            color: var(--success);
            margin-right: 10px;
        }

        /* Projects Section */
        .projects-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
        }

        .project-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-10px);
        }

        .project-img {
            height: 200px;
            overflow: hidden;
        }

        .project-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }

        .project-card:hover .project-img img {
            transform: scale(1.1);
        }

        .project-content {
            padding: 25px;
        }

        .project-content h3 {
            font-size: 1.4rem;
            margin-bottom: 10px;
            color: var(--primary);
        }

        .project-content p {
            color: var(--gray);
            margin-bottom: 20px;
        }

        .project-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 20px;
        }

        .project-tag {
            background-color: var(--light);
            color: var(--primary);
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 500;
        }

        /* Experience Section */
        .experience {
            background-color: var(--light);
        }

        .timeline {
            position: relative;
            max-width: 800px;
            margin: 0 auto;
        }

        .timeline::after {
            content: '';
            position: absolute;
            width: 3px;
            background-color: var(--accent);
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -1.5px;
        }

        .timeline-item {
            padding: 10px 40px;
            position: relative;
            width: 50%;
            box-sizing: border-box;
        }

        .timeline-item:nth-child(odd) {
            left: 0;
        }

        .timeline-item:nth-child(even) {
            left: 50%;
        }

        .timeline-content {
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .timeline-content h3 {
            font-size: 1.3rem;
            margin-bottom: 5px;
            color: var(--primary);
        }

        .timeline-content h4 {
            font-size: 1rem;
            color: var(--secondary);
            margin-bottom: 10px;
        }

        .timeline-content p {
            color: var(--gray);
        }

        .timeline-item::after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background-color: white;
            border: 3px solid var(--accent);
            border-radius: 50%;
            top: 20px;
            right: -10px;
            z-index: 1;
        }

        .timeline-item:nth-child(even)::after {
            left: -10px;
        }

        /* Contact Section */
        .contact-container {
            display: flex;
            gap: 50px;
        }

        .contact-info {
            flex: 1;
        }

        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 25px;
        }

        .contact-icon {
            width: 50px;
            height: 50px;
            background-color: var(--accent);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            color: white;
            font-size: 1.2rem;
        }

        .contact-text h3 {
            font-size: 1.2rem;
            margin-bottom: 5px;
            color: var(--primary);
        }

        .contact-form {
            flex: 1;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            transition: border 0.3s;
        }

        .form-control:focus {
            border-color: var(--accent);
            outline: none;
        }

        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }

        /* Footer */
        footer {
            background-color: var(--primary);
            color: white;
            padding: 50px 0 20px;
        }

        .footer-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
        }

        .social-links {
            display: flex;
            gap: 15px;
        }

        .social-link {
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            transition: all 0.3s;
        }

        .social-link:hover {
            background-color: var(--accent);
            transform: translateY(-3px);
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.7);
        }

        /* Responsive Design */
        @media (max-width: 992px) {
            .about-content {
                flex-direction: column;
            }
            
            .contact-container {
                flex-direction: column;
            }
            
            .timeline::after {
                left: 31px;
            }
            
            .timeline-item {
                width: 100%;
                padding-left: 70px;
                padding-right: 25px;
            }
            
            .timeline-item:nth-child(even) {
                left: 0;
            }
            
            .timeline-item::after {
                left: 21px;
            }
            
            .timeline-item:nth-child(even)::after {
                left: 21px;
            }
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
                position: absolute;
                top: 100%;
                left: 0;
                width: 100%;
                background-color: var(--primary);
                flex-direction: column;
                padding: 20px;
                box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            }
            
            .nav-links.active {
                display: flex;
            }
            
            .nav-links li {
                margin: 10px 0;
            }
            
            .mobile-menu {
                display: block;
            }
            
            .hero-content h1 {
                font-size: 2.2rem;
            }
            
            .section-title h2 {
                font-size: 2rem;
            }
        }



================================================
FILE: sources/docs profile/Profile .docx
================================================
[Non-text file]


================================================
FILE: sources/imgs/1.avif
================================================
[Non-text file]


================================================
FILE: sources/imgs/2.avif
================================================
[Non-text file]


================================================
FILE: sources/imgs/3.avif
================================================
[Non-text file]


================================================
FILE: sources/imgs/ph
================================================
[Non-text file]
