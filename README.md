<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Presentación</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
        }
        .banner {
            width: 100%;
            height: 250px;
            background-color: #d9d9d9;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #555;
            font-size: 1.2rem;
            margin: 25px 0;
            border-radius: 8px;
        }
        .section-title {
            font-size: 1.5rem;
            margin-top: 35px;
            margin-bottom: 10px;
            font-weight: bold;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill-item {
            background-color: #e8e8e8;
            padding: 8px 14px;
            border-radius: 6px;
            font-size: 0.95rem;
        }
        .contact {
            margin-top: 40px;
            display: flex;
            gap: 15px;
        }
        .contact img {
            width: 30px;
            height: 30px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Presentación puntual -->
        <h1>Hola, soy Diego — Data Analyst</h1>

        <!-- Banner -->
        <div class="banner">AQUÍ IRÁ TU BANNER — Se insertará como imagen</div>

        <!-- Descripción larga -->
        <div class="section-title">Sobre mí</div>
        <p>
            Texto de presentación larga. Aquí puedes incluir tu experiencia, tu enfoque profesional,
            tecnologías que dominas y tu propuesta de valor como analista de datos.
        </p>

        <!-- Skills -->
        <div class="section-title">Skills</div>
        <div class="skills">
            <div class="skill-item">Python</div>
            <div class="skill-item">SQL</div>
            <div class="skill-item">Power BI</div>
            <div class="skill-item">Tableau</div>
            <div class="skill-item">Machine Learning</div>
            <div class="skill-item">Pandas</div>
            <div class="skill-item">Scikit-learn</div>
        </div>

        <!-- Contacto -->
        <div class="section-title">Contacto</div>
        <div class="contact">
            <a href="mailto:tu_correo@example.com">
                <img src="gmail_icon.png" alt="Gmail" />
            </a>
            <a href="https://www.linkedin.com/in/tuusuario" target="_blank">
                <img src="linkedin_icon.png" alt="LinkedIn" />
            </a>
        </div>
    </div>
</body>
</html>
