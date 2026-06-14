# 📐 Laboratório de Matemática — Tabuada de Multiplicar

> Aplicação web interativa para geração e visualização de tabuadas de multiplicação

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green?style=flat)

---

## 📋 Descrição

Aplicação web de página única (*single-page*) que permite ao utilizador gerar e consultar tabuadas de multiplicação de forma interativa e visualmente organizada, **sem necessidade de instalação ou dependências externas**.

---

## ✨ Funcionalidades

- ✅ Geração da **tabuada completa** de 1 a 10
- 🔍 Pesquisa de **tabuada por número específico**
- 📱 Layout **responsivo** para mobile e desktop
- 🎨 Cards com **animação hover** e scroll personalizado
- 📅 Ano do rodapé **atualizado automaticamente** via JavaScript
- ⚠️ **Validação de input** com mensagem de aviso ao utilizador

---

## 📂 Estrutura do Projeto

```
tabuada/
└── tabuada.html      # aplicação completa (HTML + CSS + JS)
```

---

## 🚀 Como Usar

Sem instalação necessária. Basta abrir o ficheiro no browser:

```bash
# Opção 1 — abrir diretamente
Clique duplo em tabuada.html

# Opção 2 — via terminal com VS Code
code tabuada.html

# Opção 3 — via Live Server (extensão VS Code)
Clique direito no ficheiro > Open with Live Server
```

---

## 🖥️ Prévia da Saída

```
┌─── Tabuada do Número 7 ────────────┐
│  7 x 1  =  7                       │
│  7 x 2  =  14                      │
│  7 x 3  =  21                      │
│  7 x 4  =  28                      │
│  7 x 5  =  35                      │
│  7 x 6  =  42                      │
│  7 x 7  =  49                      │
│  7 x 8  =  56                      │
│  7 x 9  =  63                      │
│  7 x 10 =  70                      │
└────────────────────────────────────┘
```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| `HTML5` | Estrutura semântica da página |
| `CSS3` | Variáveis CSS, Flexbox, transições e scrollbar customizada |
| `JavaScript` | Geração dinâmica de DOM e validação de input |

---

## 💡 Como Funciona

O projeto utiliza três funções JavaScript principais:

```javascript
// Gera o bloco HTML de uma tabuada individual
function gerarBlocoHTML(n) { ... }

// Gera a tabuada completa de 1 a 10
function gerarCompleta() { ... }

// Gera a tabuada de um número específico informado pelo utilizador
function gerarEspecifica() { ... }
```

---

## 👤 Autor

**Gustavo Douglas**

---

## 📄 Licença

Distribuído sob a licença **MIT**. Uso livre para fins educacionais.

---

> © 2025 Gustavo Douglas — Todos os direitos reservados.
