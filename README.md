# 🌿 BioColeta Studio V7.2
> **Ambiente Portátil de Engenharia de Formulários de Campo e Estudo Ativo para Engenharia Florestal Tropical**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Web / PWA](https://img.shields.io/badge/Platform-Web%20%7C%20PWA%20Offline-success)](https://github.com)
[![Focus: Forestry Engineering](https://img.shields.io/badge/Focus-Forestry%20%26%20Ecology-1b5e20)](https://github.com)
[![Institution: UEPA](https://img.shields.io/badge/Institution-UEPA%20CCNT%20Castanhal-darkgreen)](https://www.uepa.br)

---

## 📌 Visão Geral

O **BioColeta Studio** é um ecossistema *single-file* (executável 100% offline em qualquer navegador moderno) desenvolvido para resolver dois gargalos centrais da formação e da prática profissional em **Engenharia Florestal na Amazônia**:

1. **No Campo (Operação Offline):** Permite criar, personalizar e exportar aplicações móveis progressivas (PWAs) para coleta de dados dendrológicos, inventários florestais contínuos, identificação macroscópica de madeira e vistorias ambientais (CAR/PRAD), com integração de coordenadas geográficas e sem depender de sinal de internet.
2. **Na Academia (Estudo Ativo & Foco TDAH):** Atua como uma central de aprendizagem neuroadaptada que converte as ementas oficiais do Projeto Pedagógico de Curso (PPC) da Universidade do Estado do Pará (UEPA) em fichas diagnósticas dicotômicas e cartões de repetição espaçada em loop contínuo (*Active Recall & Retrieval Practice*).

---

## 🚀 Funcionalidades Principais

* **Arquitetura *Single-File* Zero-Dependency:** Uma única aplicação em HTML5, CSS3 e JavaScript puro que roda direto do navegador de computadores públicos (como da biblioteca universitária) ou de smartphones, sem necessidade de servidores, instalação ou dependências via `npm`.
* **Explorador em Árvore & Inspetor Contextual:** Manipulação visual da hierarquia do formulário (`details.section`, `fieldset` e `options`), com botões de reordenação dinâmica (`⬆️ Subir` / `⬇️ Descer`).
* **Caixas de Notas Dinâmicas (`📝 note-box`):** Inserção de blocos de anotações em qualquer nível (na raiz do formulário, em seções exclusivas de texto ou dentro de subseções), com anexação contextual automática no relatório final (`.TXT` e `.MD`).
* **Lupa Botânica Interativa (Zoom Mobile e Desktop):** Inspeção de imagens de lâminas anatômicas e pranchas botânicas de até 5x via pinça com dois dedos (*pinch-to-zoom*), duplo toque, roda do mouse e navegação por arraste (*pan*).
* **Isolamento de Toque em Tabelas (*Touch Lock*):** Tabelas Markdown amplas ganham rolagem horizontal independente (`.md-table-wrap`), impedindo que o deslize lateral do dedo avance acidentalmente os cards do carrossel no celular.
* **Geolocalização & Links de Navegação Automáticos:** Captura de dados GPS em Graus Decimais (DD) e GMS, gerando links diretos e clicáveis para **Google Maps**, **OpenStreetMap** (com zoom na coordenada) e **Google Street View** dentro dos laudos técnicos.
* **Scrubber de Lógica (Limpador Automático):** Sanitização contínua do script de exportação, eliminando variáveis e referências órfãs de campos excluídos ou renomeados.

---

## 💻 Como Utilizar

### 1. Acesso Online Imediato (GitHub Pages)
Você pode executar o estúdio a partir de qualquer computador ou celular acessando o link do projeto via GitHub Pages:
> **`https://[SEU-USUARIO].github.io/[NOME-DO-REPOSITORIO]/`**

### 2. Uso Local / Offline
1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/[SEU-USUARIO]/biocoleta-studio.git
   ```
2. Dê um duplo clique no arquivo `index.html` (ou abra-o em qualquer navegador: Chrome, Edge, Firefox, Safari).
3. Importe o código-fonte da sua ficha de campo base ou comece uma nova estrutura a partir dos botões do estúdio.
4. Ao concluir, clique em **⬇️ Exportar HTML** para obter seu aplicativo de campo final pronto para o celular.

---

## 🌲 Alinhamento Curricular e Normativo (Amazônia Oriental)

O projeto foi parametrizado com base na matriz curricular de **Engenharia Florestal da UEPA (CCNT / Campus Castanhal)** e normas do setor florestal brasileiro:

* **Legislação Ambiental e Fundiária:** Lei Federal nº 12.651/2012 (Código Florestal Brasileiro), SNUC (Lei 9.985/2000), Instruções Normativas do IBAMA e SEMAS-PA.
* **Normas Técnicas Oficiais:** ABNT NBR 7190 (Projetos de Estruturas de Madeira), ABNT NBR 14653-3 (Avaliação de Imóveis Rurais) e Padrão Anatômico IAWA (*International Association of Wood Anatomists*).
* **Fundamentação Pedagógica:** Volumes 1 e 2 do PPC de Engenharia Florestal da UEPA, aplicando métodos de recuperação ativa de memória em disciplinas como *Dendrologia*, *Dendrometria*, *Anatomia da Madeira*, *Solos Florestais* e *Manejo de Florestas Tropicais*.

---

## 🤖 Co-criação e Desenvolvimento Apoiado por Inteligência Artificial

Este é um projeto acadêmico e tecnológico pessoal concebido, arquitetado e validado por **Evandro Maia Neves**, discente de Engenharia Florestal da Universidade do Estado do Pará. 

Em conformidade com as boas práticas de integridade acadêmica, pesquisa aberta e transparência técnica, registra-se que o desenvolvimento deste sistema utilizou modelos de linguagem de larga escala (LLMs) em regime de co-autoria instrumental e mentoria técnica:

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                       ARQUITETURA DE CO-CRIAÇÃO                             │
├─────────────────────────┬───────────────────────────────────────────────────┤
│ Ator / Sistema          │ Papel e Escopo no Projeto                         │
├─────────────────────────┼───────────────────────────────────────────────────┤
│ Evandro Maia Neves      │ • Concepção do ecossistema BioColeta              │
│ (Autor e Pesquisador)   │ • Curadoria botânica, dendrométrica e ecológica   │
│                         │ • Parametrização para a Amazônia e ementas UEPA   │
│                         │ • Especificação de requisitos e testes em campo   │
├─────────────────────────┼───────────────────────────────────────────────────┤
│ Claude                  │ • Engenharia de software e estruturação DOM       │
│ (Anthropic)             │ • Implementação do motor de Scrubber heurístico   │
│                         │ • Refatoração da reordenação e persistência local │
├─────────────────────────┼───────────────────────────────────────────────────┤
│ Gemini                  │ • Engenharia pedagógica reversa do PPC (Vols 1/2) │
│ (Google)                │ • Adaptação neurocognitiva para TDAH e mnemônica  │
│                         │ • Injetor V12.2 (Lupa Botânica, Zoom, Touch-Lock) │
│                         │ • Modelagem de fórmulas LaTeX e citações ABNT     │
└─────────────────────────┴───────────────────────────────────────────────────┘
```

> *"A inteligência artificial atuou como aceleradora de código e consultora pedagógica reversa; a curadoria ecológica, o rigor taxonômico e o direcionamento para as necessidades reais da floresta amazônica representam a visão do autor."*

---

## 📄 Licença

Este projeto é distribuído sob a licença **MIT** — consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes. Livre para uso acadêmico, científico e comunitário.