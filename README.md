# 💌 5 Love Languages Self-Assessment

> Uma aplicação web *zero-dependency* desenvolvida para avaliar e quantificar a pontuação individual das cinco linguagens do amor através de uma experiência interativa e direta no navegador.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

---

## 📌 Visão Geral do Projeto

Este projeto consiste em um teste interativo baseado na metodologia das 5 Linguagens do Amor (Palavras de Afirmação, Tempo de Qualidade, Receber Presentes, Atos de Serviço e Toque Físico). 

O objetivo principal foi criar uma solução autossuficiente e rápida, eliminando qualquer atrito de configuração, deploy ou dependência de infraestrutura em nuvem para execução.

---

## 🏗️ Arquitetura e Decisões Técnicas

### 1. Modelo *Single-File Application* (Zero-Backend)
- **Armazenamento de Dados Embutido:** As perguntas, pesos, categorias e regras de pontuação residem diretamente no documento HTML (via estruturas de dados JSON / objetos JavaScript no próprio script).
- **Sem Dependência de Bancos de Dados Externos:** Como o teste gera métricas de uso pontual e volátil sem necessidade de auditoria ou sigilo regulamentado (LGPD), dispensou-se intencionalmente uma camada de persistência externa (SQL/NoSQL).
- **Latência Zero & Privacy-First:** Todo o processamento algorítmico de pontuação ocorre localmente no motor JavaScript do navegador (*client-side*). Nenhum dado pessoal transita pela rede.

---

## ✨ Funcionalidades

- [x] Questionário estruturado e intuitivo de múltipla escolha.
- [x] Cálculo e agregação em tempo real da pontuação por categoria.
- [x] Exibição instantânea do resultado final com a linguagem primária e distribuição percentual/absoluta.
- [x] Totalmente responsivo (adaptável para desktop e dispositivos móveis).
- [x] Portabilidade total: o arquivo pode ser executado offline abrindo diretamente em qualquer navegador moderno.

---

## 📊 As 5 Linguagens Avaliadas

| Linguagem | Foco Principal |
| :--- | :--- |
| **Palavras de Afirmação** | Elogios verbais, apreço e encorajamento |
| **Tempo de Qualidade** | Atenção plena, conversas e experiências compartilhadas |
| **Receber Presentes** | Gestos visuais de lembrança e esforço intencional |
| **Atos de Serviço** | Ações práticas de apoio e alívio de tarefas cotidianas |
| **Toque Físico** | Proximidade, abraços, carinho e contato físico |

---

## 🚀 Como Executar

Por ser um projeto puramente estático em arquivo único, não é necessário instalar Node.js, compilar pacotes ou rodar servidores dedicados.
### Opção 1: Execução Direta
1. Faça o download ou clone este repositório:
   ```bash
    git clone [https://github.com/engsoftmax/TesteLinguagensDoAmor.git](https://github.com/engsoftmax/TesteLinguagensDoAmor.git)
