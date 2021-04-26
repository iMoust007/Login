<h2>
  <p align="center">
    Sistema de login
  </p>
</h2>

1. Clone o repositório.
```bash
git clone https://github.com/codifycommunity/Login.git
```
2. Alterar o diretório de trabalho.
```bash
cd Login
```
3. E abre a pasta
```
 index.html
```
4. Digite o nome de usuário e a senha
```
dev
lcbr
```

# Obs.:
```js
const loginForm = document.getElementById("login-form");
const loginButton = document.getElementById("login-form-submit");
const loginErrorMsg = document.getElementById("login-error-msg");

loginButton.addEventListener("click", (e) => {
    e.preventDefault();
    const username = loginForm.username.value;
    const password = loginForm.password.value;

    if (username === "dev" && password === "lcbr") {
        alert("Você está conectado.");
        location.reload();
    } else {
        loginErrorMsg.style.opacity = 1;
    }
})
```

🌟 E pronto. ^-^

Gostou? Bom!

## ❤️ Apoio, suporte.
A aplicação deverá funcionar nos seguintes navegadores:

| <img src="https://clipboardjs.com/assets/images/chrome.png" width="48px" height="48px" alt="Chrome logo"> | <img src="https://clipboardjs.com/assets/images/edge.png" width="48px" height="48px" alt="Edge logo"> | <img src="https://clipboardjs.com/assets/images/firefox.png" width="48px" height="48px" alt="Firefox logo"> | <img src="https://clipboardjs.com/assets/images/ie.png" width="48px" height="48px" alt="Internet Explorer logo"> | <img src="https://clipboardjs.com/assets/images/opera.png" width="48px" height="48px" alt="Opera logo"> | <img src="https://clipboardjs.com/assets/images/safari.png" width="48px" height="48px" alt="Safari logo"> |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 89+ ✔ | 90+ ✔ | 86+ ✔ | ✘ | 74+ ✔ | 14+ ✔ |

Se por acaso você adora este projeto, deixe uma estrela no repo. Isso vai me manter motivado. Deixe-me saber sua opinião com a resposta. Clique [Diego Melo](https://tifodao.tk/#contact).

Obrigado!

---
<div align="center">
<a href="https://tifodao.tk">
 <img style="border-radius: 70%;" src="https://tifodao.tk/images/autor/perfil.jpg" width="30%" height="30%">
<br/>

[![Telegram Badge](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&link=https://t.me/tifodao)](https://t.me/tifodao)
[![Gmail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:diegomelo.info@gmail.com)](mailto:diegomelo.info@gmail.com)
</div>

<div align="center">
Desenvolvido com ❤️ no Brasil 🌟 <br/>

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com/)
</div>

<br>

## Licença
Construído sob licença.

```
MIT License

Copyright (c) [2021] [Diego Melo]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
