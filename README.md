# 📚 Meus Snippets de Código

- Coleção pessoal de trechos de código, e gitingores úteis para o dia a dia em desenvolvimento front-end e back-end.

## Tecnologias

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-%23339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![HTML](https://img.shields.io/badge/HTML-%23E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-%231572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 🤝 Contribuição

Este é um repositório está aberto para sugestões e contribuições.

---

## Licença - MIT

---

## 📂 Estrutura do Repositório

```bash
├── 📁 gitignores/
│   ├── dotnet_gitignore.txt
│   ├── html_css_js_gitignore.txt
│   └── nodejs_gitignore.txt
│
├── 📁 snippets_backend/
│   ├── 📁csharp
│   └── 📁nodejs
│
├── 📁 snippets_frontend/
│   ├── 📁css
│   ├── 📁html
│   ├── 📁javascript
│   └── 📁reactjs
│
└── README.md
```

## ⚙️ Como Cadastrar e Usar Snippets no VS Code

Você pode transformar qualquer trecho de código deste repositório em um atalho de digitação nativo no VS Code (_User Snippet_).

---

### 1. Criar o Arquivo de Snippet

1. Abra o VS Code.
2. Acesse as configurações de snippets:
   - **Windows/Linux:** `File` > `Preferences` > `Configure User Snippets`
   - **Mac:** `Code` > `Settings` > `Configure User Snippets`
     _(Ou pressione `Ctrl + Shift + P` / `Cmd + Shift + P` e digite **Configure User Snippets**)_.
3. Selecione a linguagem desejada (ex: `javascript.json`, `csharp.json`, `html.json`).

---

### 2. Colar e Configurar o Snippet

Dentro do arquivo JSON aberto, insira a configuração do seu snippet. 
Exemplo de Estrutura base:

```json
{
  "Função Debounce": {
    "prefix": "debounce",
    "body": [
      "function debounce(func, timeout = 300) {",
      "  let timer;",
      "  return (...args) => {",
      "    clearTimeout(timer);",
      "    timer = setTimeout(() => { func.apply(this, args); }, timeout);",
      "  };",
      "}"
    ],
    "description": "Cria um delay para execução de funções disparadas repetidamente"
  }
}
```

---

**\*`prefix`**: É a palavra-chave/atalho que você vai digitar no código.
**\*`body`**: O código que será inserido (cada linha como um item do array).
**\*`description`**: O texto explicativo no menu de autocompletar.

---

### 3. Salvar

- Pressione `Ctrl + S` (ou `Cmd + S`) para salvar o arquivo de configuração.

---

### 4. Chamar/Usar no Código

1. Abra qualquer arquivo da linguagem configurada (ex: um arquivo `.js`).
2. Digite o atalho configurado no `prefix` (ex: `debounce`).
3. Pressione `Tab` ou `Enter` para expandir e colar todo o código automaticamente!

---

## 🤝 Como Usar este Repositório

1. Navegue até a pasta da tecnologia desejada ou use o **Índice** acima.
2. Copie o trecho de código diretamente para seu projeto ou cadastre no VS Code.
3. Para arquivos `.gitignore`, copie o conteúdo do template desejado para o arquivo `.gitignore` na raiz do seu repositório.
