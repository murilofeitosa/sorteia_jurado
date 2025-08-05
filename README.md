### **Sistema de Apoio à Sessão do Tribunal do Júri**

#### **Sobre o Projeto**

Este repositório contém um sistema web de apoio para a condução e documentação das sessões do Tribunal do Júri. Desenvolvido para uso em unidades judiciárias, a ferramenta automatiza e organiza as principais etapas do rito processual, desde o registro de presença dos jurados até a geração da ata de julgamento.

O objetivo principal é simplificar a rotina de servidores e magistrados, minimizando a necessidade de procedimentos manuais, reduzindo erros e garantindo um fluxo de trabalho mais ágil e eficiente durante o plenário.

---

#### **Funcionalidades Principais**

O sistema está dividido em três seções intuitivas que guiam o usuário através de todo o processo da sessão:

1.  **📋 Presença dos Jurados:**
    * **Gestão de Lista:** Contém uma lista pré-definida de jurados convocados.
    * **Registro de Presença:** Permite marcar de forma rápida a presença de cada jurado ou justificar sua ausência.
    * **Controle de Quórum:** Ajuda a validar se o número mínimo de jurados está presente para iniciar o sorteio.

2.  **🎲 Sorteio do Conselho de Sentença:**
    * **Sorteio Dinâmico:** Realiza o sorteio aleatório dos jurados presentes.
    * **Gerenciamento de Recusas:** Permite registrar as recusas imotivadas da acusação e da defesa, com contadores para garantir o limite de três recusas para cada parte.
    * **Painel em Tempo Real:** Exibe de forma clara e instantânea a composição do Conselho de Sentença, os jurados recusados e os impedidos, garantindo transparência ao processo.

3.  **📄 Geração da Ata de Julgamento:**
    * **Formulário Interativo:** Reúne todos os dados da sessão em um formulário único e organizado (dados do processo, profissionais, depoimentos, debates, etc.).
    * **Campos Condicionais:** Mostra ou oculta seções do formulário conforme a necessidade (ex: campos de réplica, recurso, próxima sessão).
    * **Geração de Documento:** Compila todas as informações para criar uma ata de julgamento padronizada em formato de texto (`.txt`), pronta para ser salva e utilizada como rascunho oficial.

---

#### **Tecnologia**

O sistema é construído como uma aplicação web estática, totalmente independente de servidores ou bancos de dados.
* **HTML5:** Estrutura e marcação da página.
* **CSS3:** Estilização e design responsivo.
* **JavaScript Puro:** Lógica de negócio, controle das interações, sorteio e geração da ata.

**Vantagens:**
* **Portátil:** Funciona diretamente no navegador, sem a necessidade de instalação.
* **Offline:** Pode ser usado mesmo sem conexão com a internet.
* **Simples de Usar:** A interface foi projetada para ser intuitiva e guiar o usuário em cada etapa.

---

#### **Como Usar (Publicação)**

Este projeto pode ser publicado e acessado facilmente através do **GitHub Pages**. Basta fazer o upload do arquivo `sistema_juri_web.html` para a raiz do seu repositório e habilitar a funcionalidade nas configurações. A partir daí, o sistema estará acessível por meio de uma URL estática.
