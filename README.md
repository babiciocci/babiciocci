<div align="center">

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=C9A0DC&center=true&vCenter=true&width=700&lines=Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o+%C2%B7+ML+%26+Eye+Tracking" alt="Typing SVG" />

  <br/>

  <a href="https://www.linkedin.com/in/gabriela-molina-ciocci/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;
  <a href="https://www.instagram.com/babiciocci/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>&nbsp;
  <a href="https://www.twitch.tv/babicioccis" target="_blank">
    <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" />
  </a>&nbsp;
  <a href="mailto:unifgciocci@fei.edu.br">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>

</div>

---

## `> whoami`

Sou **Gabriela Molina Ciocci** — graduanda em **Ciência da Computação** no Centro Universitário **FEI** (campus São Bernardo do Campo), com foco em **inteligência artificial**, **aprendizado de máquina** e visão aplicada a dados comportamentais.

Estudo **redes neurais**, **processamento de dados** e como modelos sequenciais ajudam a entender padrões reais — do laboratório à rua.

---

## 🔬 TCC — Eye tracking + ML no trânsito real

> **Uso de Eye Tracker e Machine Learning para Análise do Comportamento Visual de Condutores de Trânsito** (1º semestre/2026, FEI) — trabalho em equipe com Bruno Arthur Basso Silva, Guilherme Barboza de Alburquerque e Sérgio Martins de Oliveira Santos, orientação do **Prof. Victor P. L. Varela**.

A maior parte dos estudos de atenção visual de motoristas ainda roda em **simuladores**; o TCC propõe um **pipeline aberto** para **coleta, sincronização e modelagem em ambiente real**, juntando **rastreamento ocular** (Pupil Core) e **detecção de objetos na cena** (Detectron2).

```
Fixações (Pupil) + frames (world camera) → sync temporal com bounding boxes → janela de 24 passos → LSTM → próximo ponto de fixação (x, y)
```

**Em resumo**

| Aspecto | Detalhe |
|--------|---------|
| Participantes | 7 condutores, trajeto urbano ~**3,7 km** (~9 min), ida para treino e volta para teste |
| Hardware / software | **Pupil Core** (fixações por velocidade e dispersão), vídeo **1920×1080**, **Detectron2** para CSV de classes e caixas |
| Modelo | **LSTM** (48 unidades), saída densa para regressão; **AdamW**, MSE, **early stopping**; **StandardScaler** só no treino; **um modelo por participante** |
| Métricas (teste) | Erro médio ~**2,4%** da imagem (coords. normalizadas); **89,96%** dos quadros com erro **abaixo de 5%** da imagem; **R² médio ~0,868** |

Os resultados mostram que **padrões temporais do olhar** podem ser capturados **fora do simulador**; **dataset e código** são tratados no trabalho como contribuição **reprodutível** para segurança viária e pesquisas futuras.

**Palavras-chave:** atenção visual · eye tracking · detecção de objetos · LSTM · segurança viária

---

## 🧠 Stack que mais uso

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Áreas de interesse:** aprendizado de máquina · séries temporais · visão computacional aplicada · análise de dados

---

<details>
<summary><b>💻 Front & linguagens gerais</b></summary>
<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

</details>

---

## 📊 GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=babiciocci&hide_title=false&hide_rank=true&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=pt-br&hide_border=true" height="165" alt="Estatísticas do GitHub" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=babiciocci&locale=pt-br&hide_title=false&layout=compact&card_width=320&langs_count=6&theme=dracula&hide_border=true" height="165" alt="Linguagens mais usadas" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/babiciocci/babiciocci/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/babiciocci/babiciocci/output/github-snake.svg" />
    <img alt="Animação da cobrinha das contribuições" src="https://raw.githubusercontent.com/babiciocci/babiciocci/output/github-snake-dark.svg" />
  </picture>
</div>

<!--
  A cobrinha depende do GitHub Action em .github/workflows/snake.yml.
  No repositório babiciocci/babiciocci: Settings → Actions → General → Workflow permissions → "Read and write permissions" → Save.
  Depois: Actions → Generate Snake → Run workflow (ou espere o cron diário).
  Na primeira vez o SVG pode 404 até o workflow rodar uma vez.
-->
