<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Habilidades Profesionales</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --accent-primary: #38bdf8;
            --accent-secondary: #06b6d4;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --border-color: #334155;
            --tag-bg: #1e293b;
            --tag-border: #475569;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.5;
            padding: 40px 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .header h1 {
            font-size: 2.5rem;
            font-weight: 800;
            background: linear-gradient(to right, var(--accent-primary), var(--accent-secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }

        .header p {
            color: var(--text-muted);
            font-size: 1.1rem;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));
            gap: 24px;
        }

        @media (max-width: 600px) {
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }

        .card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 24px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            transition: transform 0.2s, border-color 0.2s;
        }

        .card:hover {
            transform: translateY(-2px);
            border-color: var(--accent-primary);
        }

        .card-title {
            font-size: 1.25rem;
            font-weight: 700;
            margin-bottom: 16px;
            display: flex;
            align-items: center;
            gap: 10px;
            color: var(--accent-primary);
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 8px;
        }

        .tag-container {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tag {
            background-color: var(--tag-bg);
            border: 1px solid var(--tag-border);
            color: var(--text-main);
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 0.875rem;
            font-weight: 500;
            transition: all 0.2s;
        }

        .tag:hover {
            background-color: var(--accent-primary);
            color: var(--bg-color);
            border-color: var(--accent-primary);
        }

        /* Colores temáticos por sección */
        .card.backend .card-title { color: #38bdf8; }
        .card.frontend .card-title { color: #34d399; }
        .card.devops .card-title { color: #fbbf24; }
        .card.social .card-title { color: #f472b6; }
    </style>
</head>




<h1 align="center">#Hola! ¿Cómo estás?👋 </h1>
<h2 align="center" > Bienvenido al repo de Ing. Alejandro Millan 
</h2>
<h4>
    <div align="center">
        IMPORTANTE !    
    </div>
    <div>
    Los repositorios que ves a continuacion, son basicamente DE PRUEBAS, no puedo exponer repos de clientes aqui, permanecen PRIVADOS, por una cuestion de seguridad y privacidad de los mismos.
    se preguntaran porque figura en mi cv, esto ?
    aqui podes encontrar algun trabajos practicos que he hecho en la universidad, pruebas de codigo que realizo habitualmente antes de que las deje productivas, y resultan utiles, poder ver este codigo para que veas como programo y que hago, o hice.
    </div>
    <br>
    <ul>
       <li>
              RGRID : 
               <br>
               una grilla para react totalmente configurable, exporta a pdf, pagina, y ordena.
              <br>
              <a href="http://rgrid.vercel.app/" target="_blank" > Deployado aqui rgrid.vercel.app/ </a>
        </li>
        <li>
            WEBAPI : 
            <br>
            Una WebApi RestFull con Claims de roles, hecha con SWAGGER y autenticacion.
            <br>
             <a href="http://sirfreedom.somee.com/index.html" target="_blank" > Deployado aqui sirfreedom.somee.com/index.html </a>
        </li>
        <li>
            TESTSPAINCITIZEN : 
            <br>
            Una web en react para render el examen de ciudadania espanola que utiliza la api, NO con todos los abms pero se puede ver ya que ahi realizo muchas pruebas de controles
            <br>
             <a href="http://testspaincitizen.vercel.app/" target="_blank" >  Deployado aqui testspaincitizen.vercel.app/ </a>
        </li>
        <li>
            Ajedrez :
            <br>
             Un Ajedrez utilizando el algoritmo MINMAX en winform TOTALMENTE JUGABLE. si le ganas avisame.
        </li>
    </ul>
</h3>
<h5>
    Desde el 2004 trabajó cómo desarrollador, y he alcanzado puestos cómo ayudante de arquitectura, y líder tecnico, en este último tiempo, con las tecnologías qué figuran aqui
Los rubros más destacables en mi trayectoria son Transporte, bancos, Alimentos, Juegos, Envío de mensajes, y gestión de edificios.
Me apasiona el trabajo colaborativo en entornos ágiles y compartir conocimientos sobre buenas prácticas, tambien puedo comentarles que he sido profesor universitario de la Universidad de Palermo, 
    De EducacionIT y he dado materias como Diseño de sistemas, Base de datos, programacion para iniciantes, y .net.
    mis patrones de diseño favoritos son. 
    Repository, Observer, Adapter, Factory, Decorator, y conceptos SOLID
</h4>
<div align="center">
<br>
    <p>
    🔍 Apasionado por mejorar la calidad del software con un enfoque en la eficiencia, la automatización y las mejores prácticas.
    <br>
    🚀 Siempre abierto a nuevos desafíos en los que pueda continuar aprendiendo y agregando valor.
    </p>    
</div> 
<div align="center">
    🚀 Soft Skills:
        📚 Autodidacta  🤝 Trabajo en equipo  🏃‍♂️ Scrum    💬 Asertividad   🤗 Cooperación
        ⚖️ Resolución de conflictos   🤝 Negociador   ❤️ Empatía    🗣️ Comunicador nato
    
### 🚀 Tecnologias:
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat&logo=typescript&logoColor=fff)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=fff)
![C#](https://img.shields.io/badge/-.net-ED8B00?style=flat&logo=.net&logoColor=fff)
![GitHub Actions](https://img.shields.io/badge/-react-ED8B00?style=flat&logo=react&logoColor=ffff)
![html](https://img.shields.io/badge/-html-ED8B00?style=flat&logo=html&logoColor=ffff)
![html5](https://img.shields.io/badge/-html5-ED8B00?style=flat&logo=html5&logoColor=ffff)
![Sass](https://img.shields.io/badge/-sass-ED8B00?style=flat&logo=sass&logoColor=ffff)
![MongoDB](https://img.shields.io/badge/-mongodb-ED8B00?style=flat&logo=mongodb&logoColor=ffff)
![C++](https://img.shields.io/badge/-c++-ED8B00?style=flat&logo=C++&logoColor=ffff)
![Android](https://img.shields.io/badge/-android-ED8B00?style=flat&logo=android&logoColor=ffff)
![Jquery](https://img.shields.io/badge/-jquery-ED8B00?style=flat&logo=Jquery&logoColor=fffff)
<br>
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat&logo=postman&logoColor=fff)
<br>
Social Skills
 Autodidacta - Trabajo en equipo -  Scrum  - Asertividad  - Cooperación
 Resolución de conflictos - Negociador - Empatía  - Comunicador nato
 <br>
<div class="container">
    <div class="header">
        <h1>Technical & Social Skills</h1>
        <p>Ecosistema tecnológico y habilidades interpersonales</p>
    </div>

    <div class="skills-grid">
        <div class="card backend">
            <div class="card-title">
                <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2e3a10 10 0 0 0-10 10v2a10 10 0 0 0 10 10 10 10 0 0 0 10-10v-2a10 10 0 0 0-10-10zm0 3c3.87 0 7 1.79 7 4s-3.13 4-7 4-7-1.79-7-4 3.13-4 7-4zm0 6c3.87 0 7 1.79 7 4s-3.13 4-7 4-7-1.79-7-4 3.13-4 7-4zm0 6c3.87 0 7 1.79 7 4s-3.13 4-7 4-7-1.79-7-4 3.13-4 7-4z"/></svg>
                Technical BackEnd Skills
            </div>
            <div class="tag-container">
                <span class="tag">Vb .Net / C# / .NET (v1.0 a .NET 9)</span>
                <span class="tag">Minimal APIs</span>
                <span class="tag">WCF / RESTful Api / Swagger</span>
                <span class="tag">JWT / OAuth 2.0 / gRPC</span>
                <span class="tag">Validación CORS</span>
                <span class="tag">Microservicios (Patrón SAGA y CQRS)</span>
                <span class="tag">Microsoft Message Queue / Kafka</span>
                <span class="tag">Sql Server (2000 → 2019 Cloud)</span>
                <span class="tag">Oracle (10 → 18 PL Sql)</span>
                <span class="tag">MongoDB / Cassandra / MySql / PostgreSQL</span>
                <span class="tag">GraphQL</span>
                <span class="tag">Node.js / Express.js</span>
                <span class="tag">Java / Android Native</span>
                <span class="tag">Visual Basic 6</span>
                <span class="tag">Entity Framework / ADO.NET / nHibernate</span>
                <span class="tag">LINQ to Entity / SQL</span>
                <span class="tag">Ingeniería en Firmware (C / C++)</span>
                <span class="tag">Arduino / Domótica / Electrónica</span>
            </div>
        </div>

        <div class="card frontend">
            <div class="card-title">
                <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.53c-.26-.81-1-1.4-1.9-1.4h-1v-3c0-.55-.45-1-1-1h-6v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/></svg>
                Technical FrontEnd Skills
            </div>
            <div class="tag-container">
                <span class="tag">React (v16 a v19)</span>
                <span class="tag">Next.js 15.5</span>
                <span class="tag">Zustand</span>
                <span class="tag">TypeScript</span>
                <span class="tag">Angular 20</span>
                <span class="tag">ASP.NET / MVC.NET</span>
                <span class="tag">HTML4 / HTML5</span>
                <span class="tag">CSS3 / CSS5 / Sass</span>
                <span class="tag">Bootstrap / Material UI</span>
                <span class="tag">JavaScript / jQuery</span>
                <span class="tag">npm / pnpm / nvm</span>
            </div>
        </div>

        <div class="card devops">
            <div class="card-title">
                <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24"><path d="M19.43 12.98c.04-.32.07-.64.07-.98s-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.12-.22-.39-.3-.61-.22l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1c-.23-.09-.49 0-.61.22l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98s.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46c.12.22.39.3.61.22l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.23.09.49 0 .61-.22l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zM12 15.5c-1.93 0-3-1.07-3-3s1.07-3 3-3 3 1.07 3 3-1.07 3-3 3z"/></svg>
                DevOps & Management Skills
            </div>
            <div class="tag-container">
                <span class="tag">Azure Curso AZ-900 (IaaS / PaaS)</span>
                <span class="tag">Pipelines Azure / Azure DevOps</span>
                <span class="tag">GitHub / GitLab CI/CD</span>
                <span class="tag">Configuración de Docker / Contenedores</span>
                <span class="tag">Enterprise Architect / UML</span>
                <span class="tag">Jira / Scrum / Agile</span>
                <span class="tag">Hexagonal Architecture / DDD / SOLID</span>
                <span class="tag">Clean Code / Value Object</span>
                <span class="tag">Unit Test xUnit / TDD</span>
                <span class="tag">Automatización con Selenium</span>
                <span class="tag">HtmlDocument / HtmlWeb</span>
                <span class="tag">Figma</span>
                <span class="tag">Windows Server 2008-2016 / Linux</span>
                <span class="tag">VisualStudio Code</span>
            </div>
        </div>

        <div class="card social">
            <div class="card-title">
                <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24"><path d="M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 5 8 5C6.34 5 5 1.34 5 3s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V19h14v-2.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V19h6v-2.5c0-2.33-4.67-3.5-7-3.5z"/></svg>
                Social Skills
            </div>
            <div class="tag-container">
                <span class="tag">Autodidacta</span>
                <span class="tag">Trabajo en equipo</span>
                <span class="tag">Scrum</span>
                <span class="tag">Asertividad</span>
                <span class="tag">Cooperación</span>
                <span class="tag">Resolución de conflictos</span>
                <span class="tag">Negociador</span>
                <span class="tag">Empatía</span>
                <span class="tag">Comunicador nato</span>
            </div>
        </div>
    </div>
</div>
<br>
<h3 align="center">📫 Contacto:</h3>
<p align="center">
<a href="https://mail.google.com/mail/?view=cm&fs=1&to=alemillan22@gmail.com&su=Contacto%20desde%20GitHub%20- &body=Hola%20Alejandro,%20vi%20tu%20perfil%20en%20GitHub%20y%20me%20gustaría%20saber%20más%20sobre%20tus%20servicios%20y/o%20pactar%20una%20meet." target="_blank">
<img src="https://img.shields.io/badge/-Gmail-EA4335?style=flat&logo=Gmail&logoColor=white" alt="Enviar correo con Gmail"></a>
<a href="https://linkedin.com/in/appmaker" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=flat&logo=linkedin&logoColor=white&padding=5px"></a>
</p>
</div> 
