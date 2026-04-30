# 🧑‍💻 Tutorial Básico: Primeiro Projeto HTML no VS Code

Este guia mostra como criar seu primeiro projeto HTML do zero usando o Visual Studio Code.
---
> ⚠️ **Aviso importante**
>
> Este repositório contém exemplos práticos organizados por níveis (Nivel1, Nivel2, etc).
>
> 👉 Dentro de cada pasta existem arquivos com **comentários mais detalhados no código**, explicando passo a passo cada parte.
>
> 💡 Recomendo que você:
> - Leia este README para entender o passo a passo geral  
> - E abra os arquivos `.html` para ver explicações mais completas dentro do código
>
> 🚀 Assim você aprende teoria + prática ao mesmo tempo!
---

## 📌 1. Abrindo o VS Code

- Abra o menu iniciar
- Procure por **Visual Studio Code**
- Clique para abrir

💡 Dica: fixe o VS Code na barra de tarefas

---

## 📁 2. Criando a pasta do projeto

1. Abra o **Explorador de Arquivos**
2. Vá em **Documentos**
3. Clique com botão direito → **Novo > Pasta**
4. Nomeie como: projeto

---

## 📂 3. Abrindo a pasta no VS Code

1. Clique em **File (Arquivo)**
2. Clique em **Open Folder (Abrir Pasta)**
3. Selecione a pasta `projeto`

---

## 📁 4. Criando a pasta Nivel1

- Clique com botão direito na pasta `projeto`
- Clique em **New Folder**
- Nomeie como: Nivel1

---

## 📄 5. Criando o arquivo HTML

- Clique com botão direito em `Nivel1`
- Clique em **New File**
- Nomeie como: index.html

---

## 💻 6. Código HTML básico

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nivel 1</title>
</head>

<body>
    <h1>Esta é uma tag de título.</h1>
    <p>Esta é uma tag de parágrafo.</p>
</body>
</html>
```
---

# 🎨 Nível 2: Adicionando CSS ao HTML

Agora vamos criar um segundo nível, onde você vai aprender a estilizar a página com CSS.

---

## 📁 1. Criando a pasta Nivel2

1. No VS Code, clique com o botão direito na pasta `projeto`
2. Clique em **New Folder**
3. Nomeie como: Nivel2

---

## 📄 2. Criando o arquivo index.html

1. Clique com botão direito na pasta `Nivel2`
2. Clique em **New File**
3. Nomeie como: index.html

---

## 💻 3. Código com CSS

Copie e cole:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nivel 2</title>

    <style>
        body {
            background-color: #000000;
            font-family: Arial;
        }

        h1 {
            color: #ff0000;
        }

        p {
            color: #fffb00;
            font-size: 20px;
        }
    </style>

</head>
<body>
    <h1>Exemplo 2</h1>
    <p>Este é um parágrafo de exemplo.</p>
</body>
</html>
```
---

# 📋 Nível 3: Listas no HTML

Agora vamos aprender a usar listas para organizar informações.

---

## 📁 1. Criando a pasta Nivel3

1. Clique com botão direito na pasta `projeto`
2. Clique em **New Folder**
3. Nomeie como: Nivel3

---

## 📄 2. Criando o arquivo index.html

1. Clique com botão direito na pasta `Nivel3`
2. Clique em **New File**
3. Nomeie como: index.html

---

## 💻 3. Código com lista

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nivel 3</title>

    <style>
        ul {
            font-size: 20px;
            font-family: Arial, sans-serif;
            color: blue;
        }
    </style>

</head>
<body>

    <ul>
        <li>Estudar HTML</li>
        <li>Estudar CSS</li>
        <li>Estudar JavaScript</li>
    </ul>

</body>
</html>
```
---

# 🧱 Nível 4: Organização com DIV + Estilo

Agora vamos organizar melhor o conteúdo usando uma `div` e aplicar estilos visuais mais interessantes.

---

## 📁 1. Criando a pasta Nivel4

1. Clique com botão direito na pasta `projeto`
2. Clique em **New Folder**
3. Nomeie como: Nivel4

---

## 📄 2. Criando o arquivo index.html

1. Clique com botão direito na pasta `Nivel4`
2. Clique em **New File**
3. Nomeie como: index.html

---

## 💻 3. Código com layout

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nivel 4</title>

    <style>
        ul {
            font-size: 20px;
            font-family: Arial, sans-serif;
            color: blue;
        }
    </style>

</head>
<body>

    <div style="background-color: rgb(208, 231, 0); border-radius: 8px; padding: 20px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
        <ul>
            <li>Estudar HTML</li>
            <li>Estudar CSS</li>
            <li>Estudar JavaScript</li>
        </ul>
    </div>
    
</body>
</html>
```
