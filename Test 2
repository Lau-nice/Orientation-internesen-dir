<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Orientation - Internes Faculté de Médecine</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 20px;
        }
        h1 {
            color: #004080;
        }
        .question {
            margin-top: 20px;
            padding: 10px;
            border-left: 4px solid #004080;
            background-color: #ffffff;
        }
        .answer {
            margin-top: 10px;
        }
        a {
            color: #0066cc;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>

<h1>Orientation - Internes Faculté de Médecine</h1>

<div class="question">
    <p>Quelle est votre situation ?</p>
    <div class="answer">
        <a href="#" onclick="showSection('pedagogie')">Problème pédagogique</a> |
        <a href="#" onclick="showSection('sante')">Problème de santé</a> |
        <a href="#" onclick="showSection('social')">Problème social</a> |
        <a href="#" onclick="showSection('harcelement')">Harcèlement / Violences sexuelles</a>
    </div>
</div>

<div id="pedagogie" class="question hidden">
    <h2>Problème pédagogique</h2>
    <ul>
        <li>Informer son coordinateur</li>
        <li>Informer son tuteur (si applicable)</li>
        <li>Contacter l'interne responsable disciplinaire</li>
        <li>Contacter le 3ème cycle : <a href="mailto:medecine.scolarite.cycle3@univ-cotedazur.fr">medecine.scolarite.cycle3@univ-cotedazur.fr</a></li>
        <li>Informer le bureau de l'internat :
            <a href="mailto:president.beihn@gmail.com">president.beihn@gmail.com</a>,
            <a href="mailto:vicepresident.beihn@gmail.com">vicepresident.beihn@gmail.com</a>
        </li>
    </ul>
</div>

<div id="sante" class="question hidden">
    <h2>Problème de santé</h2>
    <ul>
        <li>Contacter SOS interne</li>
        <li>Informer le bureau de l'internat :
            <a href="mailto:president.beihn@gmail.com">president.beihn@gmail.com</a>,
            <a href="mailto:vicepresident.beihn@gmail.com">vicepresident.beihn@gmail.com</a>
        </li>
        <li>Contacter la médecine du travail : <a href="mailto:medecine.sante.au.travail@chu-nice.fr">medecine.sante.au.travail@chu-nice.fr</a></li>
        <li>Contacter le 3ème cycle : <a href="mailto:medecine.scolarite.cycle3@univ-cotedazur.fr">medecine.scolarite.cycle3@univ-cotedazur.fr</a></li>
    </ul>
</div>

<div id="social" class="question hidden">
    <h2>Problème social</h2>
    <ul>
        <li>Contacter l'assistante sociale universitaire</li>
        <li>Contacter l'assistante sociale du CHU</li>
        <li>Informer le bureau de l'internat :
            <a href="mailto:president.beihn@gmail.com">president.beihn@gmail.com</a>,
            <a href="mailto:vicepresident.beihn@gmail.com">vicepresident.beihn@gmail.com</a>
        </li>
        <li>Informer le 3ème cycle : <a href="mailto:medecine.scolarite.cycle3@univ-cotedazur.fr">medecine.scolarite.cycle3@univ-cotedazur.fr</a></li>
    </ul>
</div>

<div id="harcelement" class="question hidden">
    <h2>Harcèlement et violences sexuelles</h2>
    <ul>
        <li>Possibilité d'informer son coordinateur</li>
        <li>Aide universitaire : <a href="mailto:cvss@univ-cotedazur.fr">cvss@univ-cotedazur.fr</a></li>
        <li>Informer le 3ème cycle : <a href="mailto:medecine.scolarite.cycle3@univ-cotedazur.fr">medecine.scolarite.cycle3@univ-cotedazur.fr</a></li>
        <li>Contacter la médecine du travail : <a href="mailto:medecine.sante.au.travail@chu-nice.fr">medecine.sante.au.travail@chu-nice.fr</a></li>
    </ul>
</div>

<script>
    function showSection(sectionId) {
        // Masquer toutes les sections
        document.querySelectorAll('.question').forEach(section => {
            section.classList.add('hidden');
        });
        // Afficher la section sélectionnée
        document.getElementById(sectionId).classList.remove('hidden');
    }
</script>

</body>
</html>
