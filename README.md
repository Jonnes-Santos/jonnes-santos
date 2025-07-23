## Seja bem vindo(a)!

<p align="right">
<table width="100%">
<tr><td valign="top" width="50%">



<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jonnes Santos | Desenvolvedor Full Stack & Supervisor de TI</title>
    <style>
        :root {
            --primary: #2b3137;
            --secondary: #444d56;
            --accent: #0366d6;
            --text: #24292e;
            --light: #f6f8fa;
            --border: #e1e4e8;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        
        body {
            background-color: var(--light);
            color: var(--text);
            line-height: 1.6;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .profile-header {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        
        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-right: 20px;
            border: 4px solid var(--accent);
            object-fit: cover;
        }
        
        .header-text h1 {
            font-size: 28px;
            margin-bottom: 5px;
            color: var(--primary);
        }
        
        .header-text p {
            font-size: 18px;
            color: var(--secondary);
        }
        
        section {
            margin-bottom: 30px;
            background: white;
            padding: 25px;
            border-radius: 6px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        
        h2 {
            color: var(--accent);
            margin-bottom: 15px;
            font-size: 22px;
            border-bottom: 1px solid var(--border);
            padding-bottom: 8px;
        }
        
        h3 {
            margin: 15px 0 10px;
            font-size: 18px;
        }
        
        .job-title {
            font-weight: 600;
            color: var(--primary);
        }
        
        .company {
            color: var(--accent);
            text-decoration: none;
        }
        
        .company:hover {
            text-decoration: underline;
        }
        
        ul {
            padding-left: 20px;
        }
        
        li {
            margin-bottom: 8px;
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }
        
        .skill-category {
            flex: 1;
            min-width: 200px;
        }
        
        .contact-links {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        .contact-link {
            display: inline-flex;
            align-items: center;
            padding: 8px 15px;
            background-color: var(--accent);
            color: white;
            text-decoration: none;
            border-radius: 6px;
            transition: background-color 0.3s;
        }
        
        .contact-link:hover {
            background-color: #005cc5;
        }
        
        .icon {
            margin-right: 8px;
            width: 16px;
            height: 16px;
        }
        
        @media (max-width: 600px) {
            .profile-header {
                flex-direction: column;
                text-align: center;
            }
            
            .avatar {
                margin-right: 0;
                margin-bottom: 15px;
            }
            
            .skills-container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header class="profile-header">
        <!-- Substitua pela URL da sua foto -->
        <img src="https://via.placeholder.com/120" alt="Jonnes Vieira" class="avatar">
        <div class="header-text">
            <h1>Jonnes Santos</h1>
            <p>Graduando em Ciência da Computação | Desenvolvedor Full Stack | Líder de TI</p>
        </div>
    </header>

    <section>
        <p>Com formação em andamento em <strong>Ciência da Computação</strong> e experiência multidisciplinar em TI, atuo na interseção entre <strong>desenvolvimento de software</strong>, <strong>gestão de equipes</strong> e <strong>infraestrutura de sistemas</strong>. Minha carreira é impulsionada pela busca por soluções técnicas robustas, segurança cibernética e eficiência operacional.</p>
    </section>

    <section>
        <h2>💼 Experiência Profissional</h2>
        
        <h3><span class="job-title">Desenvolvedor Full Stack</span> @ <a href="https://dadengenharia.com.br" class="company">DAD Engenharia</a></h3>
        <ul>
            <li>Desenvolvimento de soluções especializadas em <strong>monitoramento e investigação para a Polícia Civil</strong> utilizando:</li>
            <ul>
                <li><strong>Backend:</strong> PHP (Laravel/Lumen), Node.js</li>
                <li><strong>Frontend:</strong> Vue.js, JavaScript, HTML/CSS</li>
                <li><strong>Banco de Dados:</strong> MySQL (modelagem e administração via Workbench)</li>
            </ul>
            <li>Integração de boas práticas de segurança no ciclo de desenvolvimento.</li>
        </ul>
        
        <h3><span class="job-title">Supervisor de TI</span></h3>
        <ul>
            <li>Liderança de equipes de <strong>suporte e infraestrutura</strong>, garantindo estabilidade de sistemas corporativos.</li>
            <li>Otimização de processos tecnológicos e implementação de melhorias contínuas.</li>
            <li>Resolução de problemas complexos e definição de estratégias para eficiência operacional.</li>
        </ul>
    </section>

    <section>
        <h2>🛠 Habilidades Técnicas</h2>
        <div class="skills-container">
            <div class="skill-category">
                <h3>Linguagens</h3>
                <ul>
                    <li>JavaScript</li>
                    <li>PHP</li>
                    <li>Java</li>
                    <li>HTML/CSS</li>
                </ul>
            </div>
            <div class="skill-category">
                <h3>Frameworks</h3>
                <ul>
                    <li>Laravel</li>
                    <li>Lumen</li>
                    <li>Vue.js</li>
                    <li>Express.js</li>
                </ul>
            </div>
            <div class="skill-category">
                <h3>Bancos de Dados</h3>
                <ul>
                    <li>MySQL (modelagem, administração, queries complexas)</li>
                </ul>
                <h3>Segurança</h3>
                <ul>
                    <li>Ethical Hacking (foco em segurança ofensiva)</li>
                </ul>
            </div>
            <div class="skill-category">
                <h3>Ferramentas</h3>
                <ul>
                    <li>Git</li>
                    <li>Docker</li>
                    <li>Workbench</li>
                    <li>Metodologias Ágeis</li>
                </ul>
            </div>
        </div>
    </section>

    <section>
        <h2>🎯 Objetivos</h2>
        <p>Unir <strong>liderança técnica</strong> e <strong>expertise em desenvolvimento</strong> para criar soluções:</p>
        <ul>
            <li><strong>Escaláveis</strong> e de alta performance.</li>
            <li><strong>Seguras</strong>, com foco em mitigação de riscos.</li>
            <li><strong>Alinhadas a negócios</strong>, agregando valor estratégico.</li>
        </ul>
    </section>

    <section>
        <h2>🌟 Interesses</h2>
        <ul>
            <li>Colaborar em projetos desafiadores de <strong>software e segurança</strong>.</li>
            <li>Explorar inovações em <strong>DevSecOps e infraestrutura resiliente</strong>.</li>
            <li>Conectar-me com profissionais que compartilhem paixão por <strong>tecnologia transformadora</strong>.</li>
        </ul>
    </section>

    <section>
        <h2>📫 Vamos conversar?</h2>
        <div class="contact-links">
            <!-- Substitua pelos seus links reais -->
            <a href="https://linkedin.com/in/seu-perfil" class="contact-link">
                <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                </svg>
                LinkedIn
            </a>
            <a href="mailto:seu-email@provedor.com" class="contact-link">
                <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M12 12.713l-11.985-9.713h23.97l-11.985 9.713zm0 2.574l-12-9.725v15.438h24v-15.438l-12 9.725z"/>
                </svg>
                E-mail
            </a>
            <a href="https://seuportfolio.com" class="contact-link">
                <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-2 16h-2v-6h2v6zm-1-6.891c-.607 0-1.1-.496-1.1-1.109 0-.612.492-1.109 1.1-1.109s1.1.497 1.1 1.109c0 .613-.493 1.109-1.1 1.109zm8 6.891h-1.998v-2.861c0-1.881-2.002-1.722-2.002 0v2.861h-2v-6h2v1.093c.872-1.616 4-1.736 4 1.548v3.359z"/>
                </svg>
                Portfólio
            </a>
        </div>
    </section>
</body>
</html>

  
<div align="center"> 
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzlhaTkwODhua2V0YmE3azlidGs0MTFpOXIzZzkzMnd4MzVhdmdjZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/HscDLzkO8EOTmgkhQP/giphy.gif" alt="Gif de um cachorrinho de gravata mexendo no computador">
</div>

</td></tr>
</table>
</p>

<p align="right">
<img src="https://views.whatilearened.today/views/github/jonnes-santos/views.svg"> <a href="https://github.com/jonnes-santos/"><img src="https://img.shields.io/github/followers/jonnes-santos?color=%234CC61E&label=GitHub%20Followers%20%3A"/></a>
</p>

### Experiência 
- 💻 Graduando em Ciência da Computação (Faculdade Anhanguera)
  
### Certificados
- 📚 Git e GitHub: compartilhando e colaborando em projetos (Alura)
- 📚 Java: criando a sua primeira aplicação (Alura)
- 📚 Java: aplicando a orientação a objetos (Alura)
- 📚 Lógica de programação: mergulhe em programação com JavaScript (Alura)
- 📚 PHP: criando sua aplicação (Alura)
- 📚 PHP: conceitos, lidando com dados, loops e mais (Alura)
- 📚 MySQL: conhecendo a ferramenta (Alura)
- 📚 Linux: gerenciando diretórios, arquivos, permissões e processos (Alura)
- 📚 Segurança da informação para todos: Proteja você e sua empresa contra ameaças cibernéticas (ALura)
- 📚 Pentest: explorando vulnerabilidades em aplicações web (Alura)
- 📚 Pentest: Investigando vulnerabilidades em um servidor web (Alura)
- 📚 Segurança web em Java: evitando SQL Injection, força bruta e outros ataques (Alura)
- 📚 Introduction to Cybersecurity (CISCO Networking Academy)
- 📚 Ethical Hacker (CISCO Networking Academy)
  
### Formação
- 📚Java Web: crie aplicações usando Spring Boot (em andamento)













##
<div>
  <a href="https://github.com/jonnes-santos">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jonnes-santos&layout=compact&langs_count=7&theme=dracula"/>
  
</div>

##
### Contatos:
<div align="center"> 
  <a href="https://www.instagram.com/john1santoz/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a> 
  <a href = "mailto:jonnes.santos01@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/jonnes-santos" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>

##
  ![Snake animation](https://github.com/camilafernanda/camilafernanda/blob/output/github-contribution-grid-snake.svg)
  

