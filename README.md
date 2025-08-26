<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zineb Alalouche - Data Analyst</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #2c3e50 0%, #4a6580 100%);
            color: white;
            border-radius: 8px;
            margin-bottom: 30px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        header h2 {
            font-size: 1.5rem;
            font-weight: 400;
            margin-bottom: 20px;
            color: #ecf0f1;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 5px;
            transition: opacity 0.3s;
        }
        
        .contact-info a:hover {
            opacity: 0.8;
        }
        
        section {
            background: white;
            border-radius: 8px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
        }
        
        h3 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .education-item, .experience-item, .certification-item {
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }
        
        .education-item:last-child, .experience-item:last-child, .certification-item:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }
        
        .item-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
        }
        
        .item-title {
            font-weight: 600;
            color: #2c3e50;
        }
        
        .item-date {
            color: #7f8c8d;
            font-style: italic;
        }
        
        .item-subtitle {
            color: #3498db;
            margin-bottom: 10px;
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .skill-category {
            margin-bottom: 15px;
        }
        
        .skill-category h4 {
            margin-bottom: 10px;
            color: #2c3e50;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill-tag {
            background: #e8f4fc;
            color: #3498db;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .languages {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .language-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            flex: 1;
            min-width: 200px;
            text-align: center;
        }
        
        .language-item h4 {
            margin-bottom: 10px;
            color: #2c3e50;
        }
        
        .progress-bar {
            height: 8px;
            background: #ecf0f1;
            border-radius: 4px;
            overflow: hidden;
            margin-top: 10px;
        }
        
        .progress {
            height: 100%;
            background: #3498db;
            border-radius: 4px;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #7f8c8d;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .skills-container {
                grid-template-columns: 1fr;
            }
            
            .item-header {
                flex-direction: column;
            }
            
            .language-item {
                min-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Zineb Alalouche</h1>
            <h2>Data Analyst à la recherche d'un CDI</h2>
            <div class="contact-info">
                <a href="#"><i class="fas fa-envelope"></i> email@example.com</a>
                <a href="#"><i class="fas fa-phone"></i> +33 XX XX XX XX XX</a>
                <a href="#"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <a href="#"><i class="fab fa-github"></i> GitHub</a>
            </div>
        </header>
        
        <section id="about">
            <h3><i class="fas fa-user"></i> Profil</h3>
            <p>Data Analyst passionnée avec une solide formation en ingénierie des systèmes complexes, big data et intelligence artificielle. Je suis à la recherche d'un CDI où je pourrais mettre à profit mes compétences en analyse de données, machine learning et business intelligence pour aider à la prise de décision stratégique.</p>
        </section>
        
        <section id="experience">
            <h3><i class="fas fa-briefcase"></i> Expériences Professionnelles</h3>
            
            <div class="experience-item">
                <div class="item-header">
                    <div class="item-title">Data / Business Analyst</div>
                    <div class="item-date">Mars 2025 - Août 2025</div>
                </div>
                <div class="item-subtitle">Capgemini, Nantes | Stage de 6 mois</div>
                <ul>
                    <li>Recueil et analyse des besoins, rédaction de User Stories dans un environnement agile.</li>
                    <li>Conception et déploiement d'un tableau de bord Power BI pour l'analyse des KPI digitaux.</li>
                    <li>Configuration et validation de tags sur Piwik PRO pour suivre et analyser le comportement des utilisateurs.</li>
                    <li>Analyse des données pour SEO vocal et optimisation de la visibilité digitale.</li>
                </ul>
            </div>
            
            <div class="experience-item">
                <div class="item-header">
                    <div class="item-title">Data Scientist</div>
                    <div class="item-date">Avril 2023 - Août 2023</div>
                </div>
                <div class="item-subtitle">SOKIDAM, Rabat | Stage de 6 mois</div>
                <ul>
                    <li>Création d'un modèle prédictif des prix avec une précision de 98%.</li>
                    <li>Collecte de données, analyse exploratoire, machine learning et développement d'une interface interactive.</li>
                </ul>
            </div>
            
            <div class="experience-item">
                <div class="item-header">
                    <div class="item-title">Data Analyst</div>
                    <div class="item-date">Avril 2023 - Juillet 2023</div>
                </div>
                <div class="item-subtitle">Commune de Fes | Stage de 4 mois</div>
                <ul>
                    <li>Analyse des données pour optimiser la qualité du transport urbain.</li>
                    <li>Création d'un tableau de bord interactif.</li>
                </ul>
            </div>
        </section>
        
        <section id="education">
            <h3><i class="fas fa-graduation-cap"></i> Formations</h3>
            
            <div class="education-item">
                <div class="item-header">
                    <div class="item-title">Master en Ingénierie des Systèmes Complexes - Data Science</div>
                    <div class="item-date">2023 - 2025</div>
                </div>
                <div class="item-subtitle">École d'ingénieurs du Littoral-Côte-d'Opale (EILCO)</div>
            </div>
            
            <div class="education-item">
                <div class="item-header">
                    <div class="item-title">Licence Professionnelle en Big Data et Intelligence Artificielle</div>
                    <div class="item-date">2022 - 2023</div>
                </div>
                <div class="item-subtitle">Faculté des sciences de Rabat</div>
            </div>
            
            <div class="education-item">
                <div class="item-header">
                    <div class="item-title">DUT en Business Intelligence</div>
                    <div class="item-date">2020 - 2022</div>
                </div>
                <div class="item-subtitle">Ecole Supérieure de Technologie</div>
            </div>
        </section>
        
        <section id="skills">
            <h3><i class="fas fa-code"></i> Compétences</h3>
            <div class="skills-container">
                <div class="skill-category">
                    <h4><i class="fas fa-chart-line"></i> Data Science</h4>
                    <div class="skills-list">
                        <span class="skill-tag">Python</span>
                        <span class="skill-tag">Pandas</span>
                        <span class="skill-tag">NumPy</span>
                        <span class="skill-tag">Matplotlib</span>
                        <span class="skill-tag">Seaborn</span>
                        <span class="skill-tag">Scikit-learn</span>
                        <span class="skill-tag">TensorFlow</span>
                        <span class="skill-tag">PyTorch</span>
                        <span class="skill-tag">NLP</span>
                        <span class="skill-tag">Time Series</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h4><i class="fas fa-database"></i> Bases de Données</h4>
                    <div class="skills-list">
                        <span class="skill-tag">SQL</span>
                        <span class="skill-tag">MySQL</span>
                        <span class="skill-tag">PL/SQL</span>
                        <span class="skill-tag">Oracle Database</span>
                        <span class="skill-tag">Datawarehouse</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h4><i class="fas fa-brain"></i> Business Intelligence</h4>
                    <div class="skills-list">
                        <span class="skill-tag">Modélisation multidimensionnelle</span>
                        <span class="skill-tag">Reporting</span>
                        <span class="skill-tag">ETL</span>
                        <span class="skill-tag">Data Mining</span>
                        <span class="skill-tag">Data Visualization</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h4><i class="fas fa-tools"></i> Technologies & Outils</h4>
                    <div class="skills-list">
                        <span class="skill-tag">Power BI</span>
                        <span class="skill-tag">Tableau</span>
                        <span class="skill-tag">QlikView</span>
                        <span class="skill-tag">Talend</span>
                        <span class="skill-tag">Google Analytics</span>
                        <span class="skill-tag">SPSS</span>
                        <span class="skill-tag">Jira</span>
                        <span class="skill-tag">Confluence</span>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="certifications">
            <h3><i class="fas fa-certificate"></i> Certifications</h3>
            
            <div class="certification-item">
                <div class="item-header">
                    <div class="item-title">IBM : IA Generative</div>
                </div>
            </div>
            
            <div class="certification-item">
                <div class="item-header">
                    <div class="item-title">Atlassian : Jira Confluence</div>
                </div>
            </div>
            
            <div class="certification-item">
                <div class="item-header">
                    <div class="item-title">Piwik Pro : Piwik Pro Analytics</div>
                </div>
            </div>
            
            <div class="certification-item">
                <div class="item-header">
                    <div class="item-title">University of Virginia Darden School Foundation : Content Marketing Using Generative AI</div>
                </div>
            </div>
            
            <div class="certification-item">
                <div class="item-header">
                    <div class="item-title">Coursera : Advanced Relational Database and SQL</div>
                </div>
            </div>
        </section>
        
        <section id="languages">
            <h3><i class="fas fa-language"></i> Langues</h3>
            <div class="languages">
                <div class="language-item">
                    <h4>Français</h4>
                    <div>Courant</div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 100%"></div>
                    </div>
                </div>
                
                <div class="language-item">
                    <h4>Anglais</h4>
                    <div>Courant</div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 90%"></div>
                    </div>
                </div>
            </div>
        </section>
        
        <footer>
            <p>© 2023 Zineb Alalouche - Tous droits réservés</p>
        </footer>
    </div>
</body>
</html>
