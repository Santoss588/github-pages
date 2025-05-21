import zipfile

html_code = """<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mentalidade Alfa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d0d0d;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #e60000;
        }
        button {
            background-color: #e60000;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            font-size: 16px;
            cursor: pointer;
        }
        .section {
            margin-bottom: 40px;
        }
        .highlight {
            color: #e60000;
            font-weight: bold;
        }
        .cta {
            text-align: center;
            margin: 40px 0;
        }
        .img-banner, .img-section {
            width: 100%;
            border-radius: 10px;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://i.imgur.com/YkzKJbA.jpg" alt="Homem alfa" class="img-banner">

        <h1>Você Está Cansado de Ser Ignorado, Fraco e Invisível?</h1>
        <p>Chegou a hora de se tornar o homem que impõe respeito, atrai olhares e domina seu próprio caminho — sem depender de dinheiro, beleza ou fama.</p>

        <div class="section">
            <h2>Você não precisa nascer "alfa". Você precisa aprender a se tornar um.</h2>
            <p>Enquanto você se distrai com reels e pornografia, outros caras estão construindo corpo, mente e dinheiro.</p>
            <img src="https://i.imgur.com/GYLeVvj.jpg" alt="Decisão Alfa" class="img-section">
        </div>

        <div class="section">
            <h2>O que é o <span class="highlight">Mentalidade Alfa</span>?</h2>
            <p>Um guia prático, direto e sem mimimi pra transformar sua mentalidade, postura, rotina e até sua presença online.</p>
            <ul>
                <li>Pensamento de liderança e comando</li>
                <li>Respeito e presença de autoridade</li>
                <li>Corte de vícios e distrações</li>
                <li>Autoridade digital sem aparecer</li>
            </ul>
            <img src="https://i.imgur.com/7o5nNkU.jpg" alt="Postura Alfa" class="img-section">
        </div>

        <div class="section">
             <h2>Você vai receber:</h2> 
            <ul>
                 <li><strong>E-book Mentalidade Alfa (R$47)</strong></li> 
                <li><strong>Vídeo-aulas Alfa (R$147)</strong></li>
                  <li><strong>Acesso ao Grupo Fechado no WhatsApp (R$97)</strong></li>  
                  <li><strong>E-book Grátis: "7 Hábitos que Mudam a Vida de um Homem"</strong></li>  
                  <li><strong>Bônus Exclusivo dentro do e-book principal</strong> (surpresa especial para quem chegar até o final)</li>  
     </ul> 
                <p>Valor total: <del>R$291</del> | <span class="highlight">Hoje por apenas R$47</span></p>    
     </div> 

     <classe Div="cta"> 
                <button>Quero Me Tornar Um Alfa Agora</button>    
     </div> 

         <div class="seção">     
                <h3>Garantia incondicional de 7 dias</h3>    
                <p>Se em até 7 dias você não sentir nenhuma mudança, devolvemos seu dinheiro. Sem perguntas. Sem enrolação.</p>    
                 <img src="https://i.imgur.com/z9bRXe7.jpg" alt="Confiança e Garantia" class="img-section">     
     </div> 

         <div class="seção">     
                 <h2>Você escolhe:</h2>     
                 <p>Continuar sendo o cara que ninguém leva a sério, ou o homem que impõe respeito em qualquer lugar que pisa.</p>     
                <img src="https://i.imgur.com/W84DprW.jpg" alt="Escolha ser Alfa" class="img-section">    
     </div> 
    </div>
</"Corpo">
</<HTML>>
"""

arquivo_path = '/mnt/data/mentalidade_alfa/index.html'

import os
os.makedirs('/mnt/data/mentalidade_alfa', exist_ok=True)

com open(file_path, 'w', codificação='utf-8') como f:
   F. Escrever (HTML_Code)   

zip_path = '/mnt/data/mentalidade_alfa.zip'

com um arquivo. ZipFile (zip_path, 'w') como zipf:
 zipf.write(file_path, arcname='index.html') 

Zip_Path


<!--
      <<<< Notas do autor: Cabeçalho do curso >>>      
       Inclua uma imagem de 1280 x 640, título do curso no caso da frase e uma descrição concisa em ênfase.       
        Nas configurações do repositório: ative o repositório de modelos, adicione sua imagem social 1280x640, exclua automaticamente as ramificações de cabeça.        
  Adicione sua licença de código aberto, o GitHub usa licença do MIT.  
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

<cabeça>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Welcome

With GitHub Pages, you can host project blogs, documentation, resumes, portfolios, or any other static content you'd like. Your GitHub repository can easily become its own website. In this course, we'll show you how to set up your own site or blog using GitHub Pages.

- **Para quem é isto?**: Iniciantes, estudantes, mantenedores de projetos, pequenas empresas.
- **O que você vai aprender**Como criar um site de páginas do GitHub.
- **O que você vai construir**: Vamos construir um site simples do GitHub Pages com um blog. Nós vamos usar [Jóia](https://jekyllrb.com)um gerador de site estático.
- **Pré-requisitos**: Se você precisa aprender sobre ramos, commits e pull requests, tome [Introdução ao GitHub](https://github.com/skills/introduction-to-github) Primeiro.
-  **Quanto tempo?**Este curso leva menos de uma hora para ser concluído.

In this course, you will:

1. Enable GitHub Pages
2. Configure your site
3. Customize your home page
4. Create a blog post
5. Merge your pull request

### How to start this course

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'github-pages',
  owner: '@me',
  name: 'skills-github-pages',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=github-pages&owner=%40me&name=skills-github-pages&description=My+clone+repository&visibility=public)

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
