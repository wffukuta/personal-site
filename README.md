<div align="center">

# ARQUITETURA DE ENGAJAMENTO TEMPORAL

<br>

<a href="https://wffukuta.github.io/arquitetura-engajamento-temporal/">
  <img src="https://img.shields.io/badge/VISUALIZAR_ARQUITETURA_APLICADA-2ea44f?style=for-the-badge" alt="VISUALIZAR" width="300">
</a>
</a>
<br>
<br>
<br>
<br>
</div>
<br>


# **AET: O TEMPO COMO ATIVO DE CONVERSÃO**

O tempo como mecanismo de conversão. Este projeto subverte o portfólio tradicional, utilizando uma progressão de estímulos para transformar visitantes casuais em leads qualificados através da arquitetura de engajamento temporal (AET)

---

<br><br>
## **OS PILARES DA AET**
Em vez de entregar toda a informação de imediato, esta arquitetura utiliza ciclos temporais para modular a experiência do usuário, baseando-se em quatro pilares estratégicos:

> **AUTORIDADE:** Exposição técnica imediata para estabelecer autoridade. O visitante encontra projetos desenvolvidos, repositórios, vídeos e histórico de produção. Essa etapa responde à pergunta: Essa pessoa realmente consegue desenvolver um projeto? Sem essa validação, a conversão é enfraquecida.

   
> **RETENÇÃO:** O botão Play rompe o padrão de leitura e inicia um cronômetro de expectativa.O visitante sente curiosidade sobre o que acontece ao clicar. Isso ativa um mecanismo de exploração: um cronômetro inicia, o sistema promete revelar algo e o usuário passa a esperar pela próxima interação.

   
> **RECOMPENSA:** Liberação de micro-experiências visuais e atmosféricas (Modos) que recompensam a espera. O visitante entra em um ciclo de comportamento: esperar → receber recompensa → explorar → esperar novamente.

     
> **FECHAMENTO:**  A remoção súbita de estímulos cria o momento ideal para a chamada de ação. Esse silêncio visual cria um vácuo de atenção usado para capturar um lead qualificado.

---


<br><br>
## **Estrutura do Projeto**


```text
📦 Arquitetura de Engajamento Temporal
 ┣ 📜 index.html------------------# Arquitetura Aplicada
 ┣ 📂 modo/-----------------------# Micro-experiências de Recompensa
 ┗ 📜 README----------------------# Documentação estratégica
```

<br><br>
## **Decisões de Engenharia & Arquitetura**
A escolha das tecnologias foi pautada em eficiência operacional e escalabilidade de conteúdo:

> Estratégia de Headless CMS (Google Sheets)
Utilizo o Google Sheets (via TSV) como fonte de dados. Isso permite atualizações em tempo real enquanto gerencio varios projetos através de uma unica planilha como painel sem necessidade de novos deploys, garantindo uma separação total entre dados e renderização.

> Micro-Frontends de Experiência (/modo/)
Os modos interativos são isolados em um ambiente Sandbox. Essa modularidade permite injetar novas tecnologias (Canvas, WebGL, Three.js) de forma desacoplada, facilitando testes de retenção sem risco de regressão no core do sistema.

> Persistência e Captura (Firebase)
Integração com Firebase Realtime DB para captura assíncrona de leads, armazenando não apenas o contato, mas o contexto da jornada do usuário.




<br><br>
## LICENSE

This project is **Source-Available** under a [Custom License](LICENSE). 

> **Warning:** The freedom to use the code does not extend to creative assets or the AET methodology. Narrative, visual identity, and engagement logic are protected by copyright. You are welcome to study the structure, but please respect the exclusivity of our strategic architecture! All intellectual property and code remain the property of W.F.FUKUTA and cannot be used for profit outside of the company's production environment.

