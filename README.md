# 🧑‍💻 Trilha Progressiva de Desenvolvimento Web

## HTML • CSS • JavaScript (Evolução de Arquitetura Front-End)

---

## 📌 Visão Geral

Este repositório apresenta uma trilha progressiva de aprendizado em desenvolvimento web front-end, estruturada em níveis.

A proposta não é apenas ensinar a criar páginas web, mas demonstrar a **evolução da forma de pensar a construção de interfaces digitais**.

Cada nível representa uma etapa da evolução técnica do desenvolvedor, partindo de conceitos fundamentais até estruturas próximas de aplicações reais.

---

## 🧠 Filosofia do Projeto

Este material segue uma abordagem baseada em evolução incremental.

Cada nível:

* apresenta uma implementação completa e funcional
* introduz novos conceitos técnicos
* mantém independência em relação aos anteriores
* demonstra uma evolução de arquitetura e pensamento

O foco principal não é “substituir soluções”, mas **mostrar como o raciocínio técnico evolui ao longo do aprendizado**.

---

# 🧱 Estrutura do Repositório

```
/nivel-1
/nivel-2
/nivel-3
/nivel-4
/nivel-5
/nivel-6
/nivel-7
```

---

# 🟢 NÍVEL 1 — ESTRUTURA FUNDAMENTAL DA WEB

## 🧠 Contexto técnico

Este nível introduz os conceitos fundamentais do HTML.

Aqui o desenvolvedor tem o primeiro contato com a estrutura de uma página web, entendendo que o navegador interpreta um documento organizado em elementos hierárquicos.

Não há preocupação com estética ou organização avançada — apenas com a estrutura base.

---

## 💻 Código completo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Nível 1</title>
</head>

<body>

    <h1>Minha primeira página web</h1>
    <p>Este é o primeiro contato com HTML.</p>

</body>
</html>
```

---

# 🔵 NÍVEL 2 — SEPARAÇÃO ENTRE ESTRUTURA E ESTILO

## 🧠 Contexto técnico

Neste nível ocorre a introdução do CSS.

O principal conceito aprendido é a separação entre estrutura (HTML) e apresentação (CSS), um dos pilares do desenvolvimento web moderno.

---

## 💻 Código completo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Nível 2</title>

    <style>
        body {
            background-color: black;
        }

        h1 {
            color: white;
        }

        p {
            color: yellow;
        }
    </style>
</head>

<body>

    <h1>Minha página estilizada</h1>
    <p>Agora temos estilos aplicados via CSS.</p>

</body>
</html>
```

---

# 🟡 NÍVEL 3 — ESTRUTURAÇÃO DE DADOS

## 🧠 Contexto técnico

Neste nível o foco passa a ser a organização de informações.

O uso de listas permite representar conjuntos de dados estruturados dentro da interface.

---

## 💻 Código completo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Nível 3</title>

    <style>
        ul {
            color: blue;
            font-size: 18px;
        }
    </style>
</head>

<body>

    <h1>Minhas tarefas</h1>

    <ul>
        <li>Estudar HTML</li>
        <li>Estudar CSS</li>
        <li>Estudar JavaScript</li>
    </ul>

</body>
</html>
```

---

# 🟠 NÍVEL 4 — AGRUPAMENTO E ESTRUTURA VISUAL

## 🧠 Contexto técnico

Aqui o desenvolvedor começa a organizar elementos em blocos.

O uso de `div` introduz o conceito de container, permitindo agrupar elementos relacionados e estruturar visualmente a interface.

---

## 💻 Código completo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Nível 4</title>

    <style>
        .container {
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 8px;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>Minha lista organizada</h1>

        <ul>
            <li>HTML</li>
            <li>CSS</li>
        </ul>
    </div>

</body>
</html>
```

---

# 🟣 NÍVEL 5 — LAYOUT COM CSS GRID

## 🧠 Contexto técnico

O CSS Grid permite a criação de layouts bidimensionais.

Isso representa uma evolução importante, pois o desenvolvedor passa a definir regras de distribuição visual ao invés de posicionamento manual.

---

## 💻 Código completo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Nível 5</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="galeria">
        <img src="imagens/img1.jpg">
        <img src="imagens/img2.jpg">
        <img src="imagens/img3.jpg">
        <img src="imagens/img4.jpg">
    </div>

</body>
</html>
```

```css
.galeria {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
}

img {
    width: 100%;
}
```

---

# 🔴 NÍVEL 6 — NAVEGAÇÃO DE INTERFACE

## 🧠 Contexto técnico

Este nível introduz a construção de navegação dentro de uma interface.

O elemento `<nav>` representa a estrutura de menus e links, permitindo fluxo entre partes de um sistema.

---

## 💻 Código completo

```html
<nav class="menu">
    <a href="#">Home</a>
    <a href="#">Serviços</a>
    <a href="#">Contato</a>
</nav>
```

```css
.menu {
    background-color: black;
    padding: 16px;
}

.menu a {
    color: white;
    margin-right: 16px;
    text-decoration: none;
}
```

---

# ⚫ NÍVEL 7 — ARQUITETURA DE INTERFACE COMPLETA

## 🧠 Contexto técnico

Neste nível, todos os conceitos anteriores são consolidados em uma estrutura completa de interface.

A aplicação passa a ser organizada em seções semânticas bem definidas, aproximando-se de sistemas reais.

---

## 💻 Código completo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nível 7</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <nav class="menu">
        <div class="logo">MinhaLogo</div>

        <ul class="nav-links">
            <li><a href="#">HOME</a></li>
            <li><a href="#">SERVIÇOS</a></li>
            <li><a href="#">CONTATO</a></li>
        </ul>
    </nav>
</header>

<main>
    <h1>Bem-vindo ao site</h1>
    <p>Estrutura completa de interface utilizando HTML e CSS.</p>
</main>

<footer class="rodape-principal">
    <p>Todos os direitos reservados</p>
</footer>

</body>
</html>
```

---

## 🎨 CSS — NÍVEL 7

```css
:root {
    --cor-primaria: #ffffff;
}

/* MENU */
.menu {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: black;
    padding: 12px 24px;
}

.logo {
    color: var(--cor-primaria);
    font-size: 20px;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

.nav-links a {
    color: var(--cor-primaria);
    text-decoration: none;
}

.nav-links a:hover {
    color: bisque;
}

/* CONTEÚDO */
main {
    padding: 24px;
    font-family: Arial, sans-serif;
}

/* RODAPÉ */
.rodape-principal {
    background-color: black;
    color: var(--cor-primaria);
    padding: 16px;
    margin-top: 24px;
    text-align: center;
}
```

---

# 🚀 Próxima evolução — NÍVEL 8

O próximo nível introduzirá JavaScript com foco em:

* manipulação do DOM
* eventos de usuário
* estado da interface
* renderização dinâmica
* introdução de arquitetura estilo framework

---

# 📚 Glossário técnico

* **HTML:** linguagem de estruturação de páginas web
* **CSS:** linguagem de estilização visual
* **DOM:** representação estruturada do documento
* **Grid:** sistema de layout bidimensional
* **Flexbox:** sistema de layout unidimensional
* **Semântica:** significado estrutural dos elementos
* **Container:** agrupamento de elementos

---

# 📌 Conclusão

Este projeto representa uma trilha progressiva de aprendizado em desenvolvimento web, focada na evolução da forma de pensar e estruturar interfaces.

