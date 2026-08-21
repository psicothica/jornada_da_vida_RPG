# 🎲 Jornada da Vida

**Autoconhecimento e autocuidado em forma de jogo.**

Módulo de gamificação e autogestão do ecossistema **MyDose / Meu Ecossistema Psi** — uma suíte de aplicativos psicoeducacionais interativos desenvolvida para uso clínico, que traduz frameworks terapêuticos em ferramentas de navegador simples, autocontidas e sem necessidade de instalação.

> Este é o **Eixo 1** do ecossistema: o universo *RPG da Vida*, onde a jornada terapêutica ganha a forma de personagem, atributos, missões e um mapa de progresso.

---

## ✨ O que é

*Jornada da Vida* transforma conceitos de autogestão emocional e comportamental em uma experiência única de RPG, navegável por 5 módulos:

| # | Módulo | O que faz |
|---|--------|-----------|
| 🧭 1 | **Hub Central** | Seleção de Modo de Jogo (História, Sobrevivência, Estrategista, Hardcore), radar de exigências de cada modo e gerador do Contrato do Jogador. |
| 🧝 2 | **Ficha de Personagem** | Matriz Psicológica (5 atributos com radar Chart.js), seletor de Arquétipo com estilo de jogo e dinâmica próprios, Biometria Vital (HP/MP), Matriz Moral e Checklist de Traços expansível — tudo com perguntas norteadoras para calibrar a autoavaliação. Ao salvar, gera uma **Análise de Personagem** com pontos fortes, pontos de atenção e sugestões cruzando o Modo de Jogo escolhido com a Árvore de Habilidades. |
| 🔋 3 | **Stamina & Mana** | Check-in diário de Tempo, Stamina e Mana (bateria social/emocional), Quest Board com custo calibrado por exemplos práticos, e um Inventário de Poções Restaurativas totalmente editável (nome, custo em tempo/esforço, pontos de restauração). |
| 📜 4 | **Mural de Missões** | Fundações (Finanças, Aliados) com perguntas norteadoras, Árvore de Habilidades por ramos (Mente, Corpo, Social, Ofício) com níveis evolutivos, e um construtor de Missões com passos secundários, recursos necessários (com checklist "já tenho"/"preciso"), primeiros passos de ativação e a Voz Terapêutica — um mecanismo local que cruza a missão com os recursos já registrados. |
| 🗺️ 5 | **Mapa da Jornada** | Painel de progresso consolidado: mapa visual das missões com anéis de progresso, linha do tempo das missões e de atividades recentes, dicas geradas a partir do estado atual, e exportação de um Dossiê completo em PDF nativo — pronto para levar à sessão. |

Um pop-up de boas-vindas apresenta a jornada no primeiro acesso, e todo o app segue a identidade visual **Cyber-Mística / Neon Glass** (fundo com rede neural animada, glassmorphism, paleta índigo/magenta/ciano).

---

## 🖥️ Como usar

Não há instalação, build ou dependências de servidor.

1. Baixe o arquivo `index.html`.
2. Abra-o em qualquer navegador moderno (Chrome, Firefox, Safari, Edge).
3. Pronto — o app roda 100% no navegador.

Para publicar uma URL pública, basta subir o arquivo em qualquer hospedagem estática gratuita (Netlify, GitHub Pages, Vercel).

---

## 🔒 Dados e privacidade

- Todo dado inserido (personagem, quests, missões, check-ins) é salvo **exclusivamente no `localStorage` do navegador do usuário**.
- Nenhuma informação é enviada a servidores, APIs ou bancos de dados externos.
- O Módulo #5 permite exportar um Dossiê em PDF para compartilhar manualmente com o terapeuta, e "Começar Nova Jornada" apaga os dados locais mediante confirmação explícita.

---

## 🛠️ Stack técnica

- **HTML5** monolítico — um único arquivo autossuficiente, sem etapa de build.
- **Tailwind CSS** via CDN para estilização utilitária.
- **JavaScript (ES6+)** vanilla — sem frameworks.
- **Chart.js** para os radares de atributos e exigências.
- **html2canvas** para exportação de fichas e contratos em PNG.
- **jsPDF** para o Dossiê da Jornada, gerado nativamente em texto/vetor (sem captura de tela) para garantir compatibilidade e um documento limpo e imprimível.
- Fontes: Bebas Neue, Amatic SC, Great Vibes, Cutive, JetBrains Mono, Syne (Google Fonts).

---

## 🗺️ Roadmap

Este repositório cobre o **Eixo 1**. O catálogo modular do ecossistema MyDose prevê eixos adicionais seguindo o mesmo padrão de desenvolvimento, entre eles:

- **Eixo 2** — Reestruturação Cognitiva e Metas
- **Eixo 3** — Regulação Emocional, Mindfulness e Crise *(já entregue como portal independente)*
- **Eixo 4** — Psicoeducação Clínica e Transtornos Específicos
- **Eixo 5** — Relacionamentos, Apego e Comunicação Interpessoal
- **Eixo 6** — Neurociência, Estilo de Vida e Rotina

---

## ⚕️ Aviso legal

Este aplicativo é uma ferramenta educacional e complementar ao processo terapêutico. Ele não fornece aconselhamento psicológico, diagnóstico ou tratamento, nem substitui a avaliação e o acompanhamento de um profissional de saúde mental qualificado.

Desenvolvido para uso clínico por **Alanne Raquel Fragoso de Farias** — CRP 13/9646.
Dúvidas ou orientações: [@psicothica](https://instagram.com/psicothica)
