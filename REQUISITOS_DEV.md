# 🛠️ Requisitos de Desenvolvimento do ConectaDoa

Este documento lista os softwares, ferramentas e dependências necessárias para configurar o ambiente de desenvolvimento do projeto ConectaDoa. O objetivo é garantir que todos os membros da equipe tenham uma base comum e funcional para trabalhar tanto no front-end quanto no back-end.

---

## 1. Requisitos Gerais

Esses requisitos são fundamentais para qualquer desenvolvedor que irá trabalhar no projeto, independentemente da sua especialização (front-end, back-end ou banco de dados).

*   **Controle de Versão:**
    *   **Git:** Ferramenta de controle de versão distribuído.  
        *   🔗 https://git-scm.com/
        *   **Instalação:** Baixar e instalar a versão mais recente para o seu sistema operacional.
    *   **GitHub Desktop (Opcional):** Para quem prefere uma interface gráfica para operações Git básicas.  
        *   🔗 https://desktop.github.com/

*   **Editor de Código / IDE:**
    *   **Visual Studio Code (VS Code):** **Altamente recomendado** devido à sua leveza, extensibilidade e excelentes integrações com Python, JavaScript/React e ferramentas de Git.  
        *   🔗 https://code.visualstudio.com/
        *   **Extensões Recomendadas (VS Code):**
            *   `Python` (Microsoft)
            *   `Pylance` (Microsoft)
            *   `ESLint` (Dirk Baeumer)
            *   `Prettier - Code formatter` (Prettier) 
            *   `GitLens` (Eric Amodio) 
            *   `Docker` (Microsoft)
            *   `PostgreSQL` (Chris Kolonko) 
            *   `ES7+ React/Redux/React-Native snippets` (dsznajder)  

*   **Ferramentas de Diagramação(Opcional):**
    *   **Draw.io (diagrams.net):**  
        🔗 https://app.diagrams.net/
    *   **Lucidchart:**  
        🔗 https://www.lucidchart.com/
    *   **Miro:**  
        🔗 https://miro.com/

---

## 2. Requisitos para o Back-end (Python com FastAPI)

O *back-end* é desenvolvido em Python utilizando o *framework* FastAPI, com PostgreSQL para o banco de dados.

*   **Linguagem de Programação:**
    *   **Python 3.14+:** Instalar a versão mais recente e estável do Python 3.  
        🔗 https://www.python.org/downloads/

*   **Gerenciador de Pacotes Python e Ambientes Virtuais:**
    *   **`uv`:** Vai ser utilizado como alternativa ao pip.  
        🔗 https://github.com/astral-sh/uv

*   **Framework Back-end:**
    *   **FastAPI:**  
        🔗 https://fastapi.tiangolo.com/

*   **Ferramentas Adicionais (Back-end):**
    *   **Postman:**  
        🔗 https://www.postman.com/downloads/
    *   **Insomnia:**  
        🔗 https://insomnia.rest/download
    *   **Docker:**  
        🔗 https://www.docker.com/
    *   **Docker Compose:**  
        🔗 https://docs.docker.com/compose/

---

## 3. Requisitos para o Front-end (React com Vite)

O *front-end* é construído com React e Vite para uma experiência de desenvolvimento ágil e uma interface reativa.

*   **Ambiente de Execução JavaScript:**
    *   **Node.js (LTS - Long Term Support):** Instalar a versão LTS mais recente do Node.js.  
        🔗 https://nodejs.org/
    *   **nvm (Node Version Manager):**  
        🔗 https://github.com/nvm-sh/nvm

*   **Frameworks e Ferramentas:**
    *   **React:**  
        🔗 https://react.dev/
    *   **Vite:**  
        🔗 https://vitejs.dev/

*   **Ferramentas de Qualidade de Código (Front-end):**
    *   **ESLint:**  
        🔗 https://eslint.org/
    *   **Prettier:**  
        🔗 https://prettier.io/

---

## 4. Requisitos para Banco de Dados (PostgreSQL)

O banco de dados do ConectaDoa é o PostgreSQL.

*   **Servidor de Banco de Dados:**
    *   **PostgreSQL Server:** Instalar localmente para desenvolvimento.  
        🔗 https://www.postgresql.org/download/

*   **Cliente GUI para Banco de Dados (Opcional, mas recomendado):**
    *   **pgAdmin:**  
        🔗 https://www.pgadmin.org/download/
