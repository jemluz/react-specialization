## Introduction 
React is a library created for building highly interactive interfaces (for mobile, web, smart gadgets).
In the early days of the web (1990), all websites were static.

### What is the biggest difference between a static and a non-static site?

The database (which represents dynamism, personalized, and on-demand data).

But beyond that you need to understand a little about rendering patterns 👇👇👇

## Oldschool SSRs and SPAs 

Rendering patterns are specific ways how the HTML, CSS, and JavaScript codes will be processed and rendered in a web application or website.

So, in the past we used SSR, after we start to using SPA, (then now we are going back to SSR, but that's not the point now)

### SPA → Single Page Application (React, Angular, Vue…)

- O backend não abriga as instruções para construção das telas frontend
- backend retorna apenas dados funcionais (normalmente por JSON)
-- JSON é um padrão muito difundido, e por isso permite a comunicação entre sistemas de diferentes linguagens (um sistema em JAVA para um em PYTHON por exemplo)
Modularização que favorece a escala (um mesmo back pode se comunicar com vários fronts e por aí vai)

![image](https://user-images.githubusercontent.com/23065460/209484149-5ce763b4-e66b-4931-9bf1-bdfaacbc7207.png)

### SSR → Server Side Rendering (Wordpress, Ruby on Rails) , padrão tradicional muito presente na web

- Um único servidor fornece todo código backend e frontend
- Envia os arquivos (HTML, CSS, JS) a cada requisição do usuário
- Enquanto o site processa a requisição, a tela fica branca
- Excesso de centralização compromete a escala

<img src="https://user-images.githubusercontent.com/23065460/209484166-8626d520-b870-4fac-bca3-5962462b699f.png" width=300>
