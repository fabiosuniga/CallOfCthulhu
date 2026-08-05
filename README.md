# 🐙 Call of Cthulhu 7e - Gerenciador de Fichas Web

Apresentando a aplicação web para criação e controle dinâmico de fichas de investigadores para o RPG **Call of Cthulhu 7ª Edição**! 

Criado para facilitar a vida na mesa de jogo, este sistema remove a carga matemática da criação de personagens, permitindo que os jogadores e o Guardião (Keeper) foquem no que realmente importa: a investigação, o horror e a narrativa.

---

## Visão Geral
<!-- Substitua a tag abaixo pelo link ou caminho da imagem do print da tela inicial -->
<img width="1600" height="694" alt="d45f42f1-6fcc-4d96-8300-44e619f9d6f9" src="https://github.com/user-attachments/assets/7a43cbb7-f18b-4f55-8161-ab08b5e17646" />
*Tela inicial do sistema listando os investigadores ativos e seus respectivos jogadores.*

---

## Tecnologias Utilizadas

![Oracle APEX](https://img.shields.io/badge/Oracle_APEX-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL/SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

O projeto foi desenvolvido unindo um banco de dados relacional robusto com uma interface responsiva e dinâmica:
* **Oracle APEX:** Estruturação da aplicação, interface de usuário (UI) e navegação (como fluxos Master-Detail e Interactive Reports).
* **PL/SQL:** Lógica de back-end no banco de dados, utilizando *Triggers* para automatizar cálculos e garantir a integridade dos atributos.
* **JavaScript:** Interatividade no front-end, possibilitando Ações Dinâmicas (Dynamic Actions) e atualizações na tela sem necessidade de recarregar a página.

---

## Principais Funcionalidades

### Automação Completa (O sistema faz a matemática)
A criação de investigadores nunca foi tão rápida. O jogador precisa apenas preencher:
* Características Pessoais Básicas
* Atributos Base (Força, Destreza, Inteligência, etc.)
* Perícias escolhidas

Todo o resto do trabalho pesado **o back-end faz sozinho**! Por meio de *Triggers* e *JavaScript*, o sistema calcula automaticamente os valores de metades (Sucesso Árduo), quintos (Sucesso Extremo), Pontos de Vida (HP), Sanidade Inicial, Pontos de Magia, Taxa de Movimento e Esquiva.

### Administração Dinâmica e Design Intuitivo
Durante as sessões de jogo, a agilidade é fundamental. O aplicativo foi desenhado com foco total na usabilidade do jogador:
* **Foco no que importa:** O design intuitivo ajuda o jogador a reconhecer de forma prática e visual todos os pontos e status mais cruciais da ficha na hora do desespero.
* **Controle de Status em Tempo Real:** Botões de ação rápida diretamente na página do investigador permitem aplicar Dano, Cura ou Perda de Sanidade com um clique, atualizando o banco de dados na hora.
* **Gestão de Elenco:** Controle organizado vinculando perfeitamente cada ficha ao seu respectivo jogador, mantendo a base de dados limpa e a tela inicial (Lista de Investigadores) sempre organizada.

---

## 🚀 Como Executar o Projeto
Em breve publicarei o site na internet, por enquanto está rodando nos servidores da APEX, caso queira testar entre em contato comigo que crio um cadastro pra você!
