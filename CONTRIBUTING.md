
# 🤝 Contribuindo para o Projeto ConectaDoa

Bem-vindo(a) ao guia de contribuição do projeto ConectaDoa! Agradecemos o seu interesse em ajudar a desenvolver uma solução tecnológica que visa transformar o processo de doações para a Casa de Passagem Geisiane Valente. Sua colaboração é fundamental para o sucesso e o impacto social do nosso projeto.

Este documento fornece as diretrizes para que você possa contribuir de forma eficaz e alinhada com as práticas da nossa equipe.

## 💻 Stack Tecnológico

O ConectaDoa é construído com as seguintes tecnologias:

*   **Front-end:** **React com Vite**. Esta escolha visa uma **interface reativa, moderna e uma experiência de desenvolvimento ágil**.
*   **Back-end:** **Python** com o *framework* **FastAPI**. Selecionado pela **alta performance, tipagem estática, velocidade de desenvolvimento e autogeração de documentação**.
*   **Banco de Dados:** **PostgreSQL**. Escolhido por sua **robustez, integridade e capacidade de armazenamento complexo**.
*   **Controle de Versão:** **Git e GitHub**.

## 🚀 Como Contribuir

Siga os passos abaixo para iniciar sua contribuição:

### 1. **Código de Conduta**

Mantenha um ambiente de colaboração **respeitoso e inclusivo**. Todas as interações devem ser profissionais e construtivas.

### 2. **Configuração do Ambiente de Desenvolvimento**

Antes de começar, certifique-se de que seu ambiente de desenvolvimento esteja corretamente configurado:

*   Consulte o documento **[Requisitos de Desenvolvimento](REQUISITOS_DEV.md)** para instalar todos os softwares e ferramentas necessários para o Front-end, Back-end e Banco de Dados.

### 3. **Obtenha o Código**

O projeto ConectaDoa é dividido em múltiplos repositórios no GitHub:

*   **`conectadoa-docs`**: Contém a documentação do projeto.
*   **`conectadoa-frontend`**: Código-fonte da aplicação React com Vite.
*   **`conectadoa-backend`**: Código-fonte da API Python com FastAPI.

Clone o(s) repositório(s) relevantes para a sua contribuição:

```bash
git clone https://github.com/seu-usuario/conectadoa-frontend.git
git clone https://github.com/seu-usuario/conectadoa-backend.git
# E se for contribuir com a documentação:
git clone https://github.com/seu-usuario/conectadoa-docs.git
```

### 4. **Estratégia de Branching**

Utilizamos uma estratégia de *branching* baseada em Git Flow simplificado:

*   **`main`**: Contém o código da última versão estável em produção.
*   **`develop`**: Branch de integração para o desenvolvimento de novas funcionalidades.
*   **`feature/<nome-da-feature>`**: Para desenvolver novas funcionalidades.
*   **`bugfix/<nome-do-bug>`**: Para corrigir bugs.

**Sempre crie uma nova *branch*** a partir de `develop` para suas contribuições:

```bash
git checkout develop
git pull origin develop
git checkout -b feature/nome-da-sua-feature
```

### 5. **Mensagens de Commit**

Escreva mensagens de commit claras e descritivas. Comece com um prefixo indicando o tipo de alteração (ex: `feat:`, `fix:`, `docs:`, `chore:`):

*   `feat: Adiciona registro de doador`
*   `fix: Corrige erro de login para administradores`
*   `docs: Atualiza diagrama de componentes`
*   `chore: Atualiza dependências do back-end`

### 6. **Guidelines de Pull Request (PR)**

Quando sua funcionalidade ou correção estiver completa e testada em sua *branch*:

1.  **Faça um *pull* da `develop`** para sua *branch* e resolva quaisquer conflitos.
2.  **Abra um Pull Request** para a branch `develop`.
3.  **Descreva claramente sua alteração** no corpo do PR, explicando o *que* foi feito e o *porquê*. Se a PR resolver uma User Story ou um problema específico, mencione-o.
4.  **Peça por Pull Request** para a branch `develop`.
3.  **Descreva claramente sua alteração** no corpo do PR, explicando o *que* foi feito e o *porquê*. Se a PR resolver uma User Story ou um problema específico, mencione-o.
4.  **Peça por revisão de código**. Pelo menos um outro membro da equipe deve revisar e aprovar sua PR.

### 7. **Estilo de Código e Qualidade**

*   **Front-end:** Utilizamos **ESLint** para *linting* e **Prettier** para formatação automática. Certifique-se de rodar essas ferramentas antes de fazer o commit.
*   **Back-end:** Utilize o **Ruff** para formatação de código Python e siga as diretrizes de estilo PEP 8.

### 9. **Contribuições para a Documentação**

*   Mantenha a documentação atualizada no repositório `conectadoa-docs`.
*   Para diagramas de arquitetura, utilize a notação **C4 Model** e o **DER** para modelagem de banco de dados.

## ❓ Precisa de Ajuda?

Se você tiver alguma dúvida, precisar de esclarecimentos ou encontrar dificuldades, não hesite em entrar em contato com a equipe principal do projeto. Estamos aqui para ajudar!
