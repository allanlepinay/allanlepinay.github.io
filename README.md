<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Service de Ménage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenue chez notre Service de Ménage</h1>
        <nav>
            <ul>
                <li><a href="#services">Nos Services</a></li>
                <li><a href="#about">À Propos</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="services">
        <h2>Nos Services</h2>
        <p>Nous offrons une gamme complète de services de ménage adaptés à vos besoins :</p>
        <ul>
            <li>Ménage régulier</li>
            <li>Nettoyage en profondeur</li>
            <li>Nettoyage après déménagement</li>
            <li>Nettoyage après chantier</li>
        </ul>
    </section>
    
    <section id="about">
        <h2>À Propos de Nous</h2>
        <p>Notre équipe est composée de professionnels expérimentés et fiables, prêts à rendre votre espace propre et accueillant.</p>
    </section>
    
    <section id="contact">
        <h2>Contactez-Nous</h2>
        <p>Pour toute demande de renseignement, n'hésitez pas à nous contacter :</p>
        <form action="submit_form.php" method="post">
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>
    
</body>
</html>
