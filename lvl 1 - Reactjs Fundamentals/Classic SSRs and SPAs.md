# SSRs e SPAs (ReactJS Fundamentals)

React is a _library_ for building highly interactive interfaces (for mobile, web, smart gadgets).

## Giving a context
In the early days of the web (1990s), all websites were static.


> **And what is the biggest difference between a static and non-static website?** 

The database 🎲 (which represents dynamism, personalized and on-demand data).

## Rendering Patterns
In web development, a rendering pattern refers to the way in which the $${\color{orange}HTML}$$ , $${\color{cyan}CSS}$$, and $${\color{yellow}JavaScript}$$ code is all processed and rendered in a web application or website.

Different rendering patterns are used to achieve different performance and user experience goals. SSR and SPA are examples of that.

![image](https://user-images.githubusercontent.com/23065460/209484149-5ce763b4-e66b-4931-9bf1-bdfaacbc7207.png)

SPA → Single Page Application (React, Angular, Vue…)

- O backend não abriga as instruções para construção das telas frontend
- O backend retorna apenas dados funcionais (normalmente por JSON)
-- JSON é um padrão muito difundido, e por isso permite a comunicação entre sistemas de diferentes linguagens (um sistema em JAVA para um em PYTHON por exemplo)
- Modularização que favorece a escala (um mesmo back pode se comunicar com vários fronts e por aí vai)


<img src="https://user-images.githubusercontent.com/23065460/209484166-8626d520-b870-4fac-bca3-5962462b699f.png" width=300>

SSR → Server Side Rendering (Wordpress, Ruby on Rails) , padrão tradicional muito presente na web

- Um único servidor fornece todo código backend e frontend
- Envia os arquivos (HTML, CSS, JS) a cada requisição do usuário
- Enquanto o site processa a requisição, a tela fica branca
- Excesso de centralização compromete a escala

## Bundlers & Compilers

Surgem para resolver o problema de compatibilidade dos sites em browsers que tenham diferentes versões(compiladores) do Javascript

Exemplo de compilador: babel

Os bundlers são interpretadores de módulos (imports e exports do ecmaScript), que geram um código único para ser interpretado pelo browser (que não sabe usar módulos) 

Exemplo de bundler: webpack

O site [Can I Use ](https://caniuse.com/?search=es%20modules) revela quais browsers já ão compativeis nativamente com esse mecanismo de módulos do ecma…

Vite e Snowpack tbm são insterpretadores.

O vite já faz o processo de compilação de modo automático (não precisa do babel) e já é compatível nativamente com os módulos do ecma.
