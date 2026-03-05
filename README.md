
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>CV </title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            color: #000;
            line-height: 1.25;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            font-size: 11px;
        }
        .container {
            width: 21cm;
            min-height: 29.7cm;
            background: white;
            margin: 20px auto;
            padding: 30px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            box-sizing: border-box;
            position: relative;
        }
        strong { font-weight: 700; }
        h1 {
            color: #000;
            margin-bottom: 2px;
            margin-top: 0;
            font-size: 22px;
            letter-spacing: 1px;
            font-weight: 700;
        }
        h2 {
            color: #000;
            border-bottom: 2px solid #000;
            padding-bottom: 2px;
            margin-top: 15px;
            margin-bottom: 8px;
            font-size: 14px;
            text-transform: uppercase;
            font-weight: 700;
        }
        h3 {
            font-size: 12px;
            font-weight: bold;
            margin-bottom: 1px;
            margin-top: 8px;
            color: #000;
        }
        .contact-info {
            font-size: 12px;
            margin-bottom: 10px;
            color: #333;
        }
        .contact-info a {
            color: #000;
            text-decoration: none;
            border-bottom: 1px dotted #000;
        }
        .subtitle {
            font-size: 12px;
            font-weight: bold;
            color: #000;
            margin-bottom: 12px;
            text-transform: uppercase;
            background-color: #f0f0f0;
            padding: 8px;
            text-align: center;
            line-height: 1.4;
        }
        p, li { margin-bottom: 1px; }
        .date {
            float: right;
            font-weight: bold;
            color: #000;
            font-size: 11px;
        }
        ul {
            padding-left: 18px;
            margin-top: 2px;
            margin-bottom: 2px;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }
        .bottom-section {
            margin-top: 15px;
            border-top: 1px solid #ddd;
            padding-top: 10px;
        }
        @media print {
            body { background: white; -webkit-print-color-adjust: exact; }
            .container { margin: 0; box-shadow: none; width: 100%; padding: 25px; }
            @page { margin: 0; }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>DIALLO mamadou</h1>
    <div class="contact-info">
        📍 Paris, France | 📞 06 58 55 04 79 | 📧 mamadou.abdiallo@outlook.fr<br>
        🔗 <a href="https://www.linkedin.com/in/mamadou-diallo-2627a1377/">LinkedIn</a> | 
        🐙 <a href="https://github.com/madwest72">GitHub : madwest72</a>
    </div>
    
    <div class="subtitle">
        RECHERCHE D'UN STAGE EN INFORMATIQUE <br>
    </div>

    <p>
        Actuellement en première année de BTS SIO, je combine des compétences en <strong>montage/maintenance matériel</strong> et en <strong>développement web</strong>. 
        Habitué aux environnements exigeants, je suis réactif, rigoureux et prêt à m'investir dans le <strong>support utilisateur</strong> ou la <strong>gestion de parc informatique</strong>.
    </p>

    <h2>Compétences Techniques</h2>
    <div class="skills-grid">
        <div>
            <strong>Hardware & Support :</strong><br>
            • Montage PC (Composants, Compatibilité)<br>
            • Installation OS (Windows 10/11) & BIOS<br>
            • Diagnostic pannes niveau 1<br>
            • Support utilisateur (Suite Office)<br>
        </div>
        <div>
            <strong>Développement & Web :</strong><br>
            • Web : HTML5, CSS3, Bootstrap (Responsive)<br>
            • Backend : PHP, SQL (Requêtes & BDD)<br>
            • Langage : Python (Notions)<br>
        </div>
    </div>

    <h2>Réalisations Informatiques</h2>
    
    <h3>Montage & Configuration PC Complet</h3>
    <span class="date">Projet Personnel</span>
    <p><em>Hardware & Système</em></p>
    <ul>
        <li>Sélection rigoureuse des composants (CPU, GPU, Alimentation).</li>
        <li>Assemblage physique, cable management et optimisation du flux d'air.</li>
        <li>Installation du système d'exploitation, partitionnement et mise à jour des drivers.</li>
    </ul>

    <h3>Site Web Vitrine & Gestion</h3>
    <span class="date">Projet Académique</span>
    <p><em>Stack : HTML, CSS, Bootstrap, PHP, SQL</em></p>
    <ul>
        <li>Développement d'un site responsive (adapté mobile/tablette) avec Bootstrap.</li>
        <li>Création d'un module de gestion financière en <strong>PHP</strong> avec base de données SQL.</li>
    </ul>

    <h2>Formation</h2>
    
    <h3>BTS SIO (Services Informatiques aux Organisations)</h3>
    <span class="date">2025 - 2027 (En cours)</span>
    <p>CFA INSTA, Paris</p>

    <h3>Licence 1 & 2 Mathématiques</h3>
    <span class="date">2021 - 2024</span>
    <p>Université de Bretagne Occidentale (Parcours suivi)</p>

    <h3>Baccalauréat Scientifique (Spécialité Mathématiques)</h3>
    <span class="date">2020</span>

    <h2>Expériences Professionnelles</h2>

    <h3>Serveur en Brasserie</h3>
    <span class="date">Nov. 2025 - Présent</span>
    <p><em>Paris (En parallèle des études)</em></p>
    <ul>
        <li>Gestion des priorités en environnement sous pression.</li>
        <li>Sens du service client et résolution rapide de problèmes.</li>
    </ul>

    <h3>Équipier polyvalent - McDonald's</h3>
    <span class="date">Sept. 2024 - Août 2025</span>
    <ul>
        <li>Respect strict des procédures et des normes d'hygiène.</li>
        <li>Travail d'équipe et efficacité opérationnelle.</li>
    </ul>

    <h3>Agent d'accueil - RATP (JOP 2024)</h3>
    <span class="date">Juil. 2024 - Sept. 2024</span>
    <ul>
        <li>Orientation et assistance technique de premier niveau aux voyageurs.</li>
        <li>Gestion de foule et communication en anglais.</li>
    </ul>

    <h3>Vendeur à domicile - GENINC (Partenaire Croix-Rouge)</h3>
    <span class="date">Juil. 2023 - Août 2023</span>
    <ul>
        <li>Porte-à-porte pour la <strong>Croix-Rouge Française</strong> : recrutement de donateurs.</li>
        <li>Persévérance, éthique et sensibilisation aux actions humanitaires.</li>
    </ul>

    <div class="skills-grid bottom-section">
        <div>
            <h2>Langues</h2>
            <p><strong>Anglais :</strong> A2 (Scolaire)<br>
            <strong>Espagnol :</strong> A2 (Scolaire)</p>
        </div>
        <div>
            <h2>Centres d'intérêt</h2>
            <p><strong>Sports (Pratique intensive) :</strong><br>
            • Basket-ball (10 ans, esprit d'équipe)<br>
            • Arts Martiaux (Judo, Boxe, Karaté - 10 ans cumulés)<br>
            • Musculation & Cyclisme (Rigueur quotidienne)</p>
            
            <p style="margin-top:5px;"><strong>Loisirs :</strong> Veille Technologique, Gaming & Mangas.</p>
        </div>
    </div>

</div>

</body>
</html>
