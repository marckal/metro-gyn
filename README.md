# Metrô Goiânia · Mapa ao vivo (Projeto de Design Especulativo)

> **Acesse a interface online:** [marckal.github.io/metro-gyn](https://marckal.github.io/metro-gyn/)

Simulação interativa de um painel de operação em tempo real para o sistema de transporte metroferroviário concebido por **Marck Al** ([Neuralbrand](https://neuralbrand.medium.com/)), a partir do artigo:  
👉 **[“O Metrô de Goiânia: o design especulativo como reflexão da realidade”](https://neuralbrand.medium.com/metr%C3%B4-de-goi%C3%A2nia-5af7bfac647c)** *(publicado em setembro de 2017)*.

---

## 📖 Contexto e Origem do Projeto

O transporte público de massa e de qualidade é um consenso global quando se pensa no futuro das metrópoles. Em Goiânia, quem acompanha a cidade há décadas já ouviu inúmeras promessas e planos de grandes obras de mobilidade — desde o antigo projeto do **Metrô de superfície** nos anos 1980 e 1990 até as discussões sobre o **VLT (Veículo Leve sobre Trilhos)** no corredor do Eixo Anhanguera. Em comum, tais projetos historicamente acabaram engavetados ou utilizados como bandeiras retóricas em períodos eleitorais.

Diante desse hiato entre a promessa e a realidade urbana, surge a provocação do **Design Especulativo**:

> *“Se é pra imaginar como seria, por que não imaginar de verdade? Com isso em mente eu passei a pensar no metrô dos sonhos que poderia existir em Goiânia — com direito a linha de trem até Brasília.”*

O mapa original foi elaborado como um exercício estético e poético, sem rigor de engenharia de tráfego ou viabilidade financeira estrita, mas com o propósito de tensionar a realidade presente e alimentar o imaginário coletivo:

> *“Obviamente o mapa é só um exercício estético sem rigor científico algum. Mas ele nos leva a refletir sobre as possibilidades que existem. Toda cidade nasce de sonhos. Em algum momento da história alguém olhou para um descampado e pensou que ali poderia ser uma cidade.*  
> *Acredito que devemos refletir sobre as cidades, sobre os espaços públicos e o mais importante, sonhar com suas possibilidades. Vale lembrar que o Metrô de Shenzhen foi construído em pouco mais de dez anos.”*  
> — **Marck Al**, 2017

---

## 🚇 A Rede Especulativa

A malha do Metrô de Goiânia desenhada no projeto integra as principais centralidades, eixos de adensamento, polos universitários e conexões intermunicipais da Região Metropolitana:

* 🟠 **Linha 1 — Norte–Sul** (`Itatiaia ↔ Aparecida`):  
  Artéria estrutural ligando o Campus Samambaia da UFG, Goiânia 2, Rodoviária de Goiânia, Setor Central/Praça Cívica, Setor Marista, Setor Bueno, Parque Amazônia, Buriti Shopping até Aparecida de Goiânia *(24 estações)*.

* 🔴 **Linha 2 — Expressa** (`São Carlos ↔ Pq. Ateneu`):  
  Conecta o extremo Noroeste (Jardim Curitiba, Vila Mutirão, Campinas), cruzando os setores Central e Sul (Praça do Avião, Bosque dos Buritis, Cepal), o polo universitário da PUC e Jardim Goiás até o Parque Ateneu *(20 estações)*.

* 🔵 **Linha 3 — Aeroporto** (`Garavelo ↔ Aeroporto`):  
  Une o Terminal Garavelo e o Sudoeste da metrópole (Residencial Eldorado, Jardim Europa, Jardim América) ao Centro Cívico, Setor Jaó, Santa Genoveva e ao Aeroporto Internacional de Goiânia *(19 estações)*.

* 🟢 **Linha 4 — Anhanguera** (`Padre Pelágio ↔ Senador Canedo`):  
  O tradicional corredor leste-oeste metropolitano, conectando o Terminal Padre Pelágio, Dergo, Praça da Bíblia, Novo Mundo e Vila Pedroso até Senador Canedo *(20 estações)*.

* 🟢 **Linha 5 — Circular** (`Praça Cívica ↔ Praça da Bíblia`):  
  Circuito de distribuição interna atendendo o Setor Sul, Setor Universitário, Hospital das Clínicas (HC-UFG), Riviera e Novo Mundo *(12 estações)*.

* ⚫ **Trem Regional Planalto** (`Goiânia ↔ Brasília`):  
  Ligação ferroviária interestadual de passageiros conectando Goiânia à capital federal, com paradas estratégicas em Teresópolis de Goiás, Anápolis, Abadiânia e Alexânia *(6 estações)*.

---

## 💻 Esta Interface (Mapa ao Vivo)

Esta aplicação web adiciona uma camada viva de telemetria e operação dinâmica ao desenho original:

* **Sincronização com o Horário Local:** O sistema adapta o volume de viagens, passageiros/hora e frequências (headway) em tempo real conforme os horários de pico e vale do seu dispositivo.
* **Simulação de Movimento dos Trens:** Trens trafegam dinamicamente pelos vetores dos trilhos em SVG, respeitando tempos de viagem, desaceleração e parada nas plataformas.
* **Painel da Estação:** Ao clicar em qualquer estação, visualize as linhas atendidas e as próximas partidas em tempo real (ETA regressivo).
* **Planejador de Trajetos:** Algoritmo de roteirização que calcula a rota mais rápida e indica pontos de transferência entre estações.
* **Filtros e Visualização:** Isolamento de linhas no mapa, avisos de incidentes simulados e suporte a modo claro e escuro (*light/dark mode*).
* **Arquitetura Zero-Dependency:** Construído em arquivo estático único (`index.html`), utilizando apenas SVG responsivo e Vanilla JavaScript puro (sem bibliotecas externas, frameworks ou etapa de build).

---

## 👤 Autor e Contato

* **Autor do Conceito e Design:** Marcilon Almeida de Melo (Marck Al)
* **Texto de Referência:** [O Metrô de Goiânia: o design especulativo como reflexão da realidade](https://neuralbrand.medium.com/metr%C3%B4-de-goi%C3%A2nia-5af7bfac647c) (Medium / Neuralbrand, 2017)
* **E-mail de Contato:** [marcilon@ufg.br](mailto:marcilon@ufg.br)

---

## ⚠️ Nota Legal / Isenção de Responsabilidade

Este é um projeto estritamente artístico, acadêmico e de **design especulativo**. Todos os trens, trajetos, horários, avisos e dados apresentados são **simulações ficcionais**. O projeto não possui ligação, endosso ou vínculo oficial com concessionárias de transporte público, Prefeitura Municipal de Goiânia, Governo do Estado de Goiás ou Governo Federal.
