# 📚 ConectaDoa - Documentação Técnica e do Projeto

Este repositório (`conectadoa-docs`) serve como a **fonte central de toda a documentação técnica e de projeto** para o sistema **ConectaDoa** . O ConectaDoa é um **site de intermediação entre doadores e entidades carentes**, desenvolvido para a **Casa de Passagem Geisiane Valente, em Rio Claro-SP**.

## 🎯 Sobre o Projeto ConectaDoa

O ConectaDoa tem como objetivo principal **mitigar a assimetria de informações e as falhas logísticas** enfrentadas pela Casa de Passagem Geisiane Valente. A instituição sofre com a **escassez crítica de alimentos perecíveis e não perecíveis ("mistura") e produtos de limpeza**, ao mesmo tempo em que recebe um **volume excessivo e desproporcional de roupas e itens de higiene**. A ausência de uma comunicação estruturada e em tempo real sobre as necessidades impacta diretamente a qualidade do atendimento.

Para solucionar essa dor, o sistema permitirá que a instituição **publique suas necessidades urgentes de forma dinâmica e gerencie agendamentos**, equilibrando a oferta de donativos com as demandas reais. O doador poderá **visualizar as necessidades e agendar a entrega de itens**.

### Metodologia

O desenvolvimento do ConectaDoa baseia-se na **Aprendizagem Baseada em Problemas (ABP)** e segue as três fases do **Design Thinking**: **Ouvir**, **Criar** e **Implementar**.

### Stack Tecnológico Principal

*   **Front-end:** **React com Vite** (substituindo a abordagem inicial de HTML5, CSS3, JavaScript para otimizar o desenvolvimento e a interatividade).
*   **Back-end:** **Python** utilizando o *framework* **FastAPI**. Escolhido pela sua **alta performance, tipagem estática e velocidade de desenvolvimento**, além da autogeração de documentação (Swagger UI).
*   **Banco de Dados:** **PostgreSQL**. Selecionado por ser um SGBDR **robusto, de código aberto, com alta integridade e capacidade de armazenamento complexo**, ideal para sistemas de gestão institucionais.

## 📂 Conteúdo Deste Repositório

Este repositório contém a documentação essencial para entender, desenvolver e manter o sistema ConectaDoa, incluindo:

*   **Documentação da Arquitetura:** Detalhamento da estrutura, componentes, fluxos e decisões técnicas.
*   **Modelagem de Dados:** O Diagrama Entidade-Relacionamento (DER) do banco de dados .
*   **Decisões de Arquitetura (ADRs):** Justificativas para as escolhas tecnológicas e de design.
*   **Especificações de Requisitos:** User Stories, cenários BDD e critérios de aceitação .
*   **Protótipos de Interface:** Links e referências aos protótipos de alta fidelidade desenvolvidos no Figma.
*   **Guias de Setup e Contribuição:** Instruções para configurar o ambiente de desenvolvimento e diretrizes para colaborar com o projeto.

---

### 🛠️ Requisitos de Desenvolvimento

A lista completa de ferramentas, dependências e configurações necessárias para o desenvolvimento do **ConectaDoa** está disponível no link abaixo:

➡️ **[Acessar requisitos de desenvolvimento](REQUISITOS_DEV.md)**

Neste documento, você encontrará:

* Requisitos gerais (Git, VS Code e extensões recomendadas)
* Configuração do ambiente **Back-end** (Python, Docker, etc.)
* Configuração do ambiente **Front-end** (Node.js, etc.)
* Ferramentas de suporte (Postman, Insomnia, diagramas, entre outros)
* Setup do **banco de dados PostgreSQL**

Essa documentação garante que todos os desenvolvedores tenham um ambiente padronizado e funcional para trabalhar no projeto.

---

### 📐 Arquitetura do Sistema

A documentação completa da arquitetura do **ConectaDoa** está disponível no link abaixo:

➡️ **[Acessar documentação de arquitetura](Arquitetura.md)**

Neste documento, você encontrará:

* Diagramas de **Contexto**
* Diagramas de **Contêineres**
* Diagramas de **Componentes** (modelo C4)
* **Diagrama Entidade-Relacionamento (DER)**

Essa documentação é essencial para entender a estrutura técnica do sistema, bem como as interações entre seus principais componentes.
