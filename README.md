<a href="https://yurishiroiva.github.io">
  <img src="assets/banner.png" alt="Yuri Shiroiva, cientista de dados e engenheiro de IA" width="100%">
</a>

<p align="center">
  <a href="https://yurishiroiva.github.io"><img src="https://img.shields.io/badge/Portf%C3%B3lio-6d4dff?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio"></a>
  <a href="https://www.linkedin.com/in/yurishiroiva"><img src="https://img.shields.io/badge/LinkedIn-161616?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTQuOTggMy41YTIuNSAyLjUgMCAxIDEgMCA1IDIuNSAyLjUgMCAwIDEgMC01Wk0zIDkuNzVoNHYxMUgzdi0xMVptNi41IDBoMy44djEuNmguMDZjLjUzLTEgMS44NC0yLjA2IDMuNzktMi4wNiA0LjA1IDAgNC44IDIuNjcgNC44IDYuMTN2NS4zM2gtNHYtNC43M2MwLTEuMTMtLjAyLTIuNTgtMS41Ny0yLjU4LTEuNTggMC0xLjgyIDEuMjMtMS44MiAyLjV2NC44MWgtNHYtMTFaIi8%2BPC9zdmc%2B" alt="LinkedIn"></a>
  <a href="mailto:yurishiroivabr@gmail.com"><img src="https://img.shields.io/badge/E--mail-161616?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
  <a href="https://yurishiroiva.github.io/assets/cv/Yuri_Shiroiva_Curriculo.pdf"><img src="https://img.shields.io/badge/Curr%C3%ADculo-161616?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTE0IDJINmEyIDIgMCAwIDAtMiAydjE2YTIgMiAwIDAgMCAyIDJoMTJhMiAyIDAgMCAwIDItMlY4bC02LTZabS0xIDEuNUwxOC41IDlIMTNWMy41Wk04IDEzaDh2MS44SDhWMTNabTAgMy42aDh2MS44SDh2LTEuOFoiLz48L3N2Zz4%3D" alt="Currículo"></a>
</p>

Sou cientista de dados e engenheiro de IA em Curitiba, com mais de 2 anos de experiência. Na **IoTag**, cuido do pipeline de dados e da parte de IA de uma plataforma que recebe a telemetria de máquinas agrícolas. Fora do trabalho, pesquiso deep learning com imagens de satélite. O que mais me motiva é ver um modelo sair do notebook e ser usado por alguém.

### No dia a dia

- **LLMs e agentes em produção:** diagnóstico de máquinas com o Claude na Vertex AI, com resposta estruturada e validada por schema, e agentes que usam ferramentas via MCP.
- **Pipelines de telemetria:** dados brutos de CAN e ISOBUS viram datasets organizados, mapas de cobertura em GeoJSON e arquivos ISOXML.
- **Machine learning e séries temporais:** modelos com validação cruzada e métricas que fazem sentido para o problema.
- **Visão computacional:** segmentação e classificação com PyTorch e visão clássica com OpenCV, de imagens de satélite a peças industriais.

### Projetos em destaque

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://yurishiroiva.github.io/projetos/talhoes.html"><img src="https://yurishiroiva.github.io/assets/og/talhoes.jpg" alt="Imagem Sentinel-2, talhões detectados e instâncias"></a>
      <br><b>Talhões por satélite</b> <sub>TCC · PUCPR</sub>
      <br>Deep learning com imagens Sentinel-2 que encontra cada talhão e entrega os polígonos numa plataforma web. Dice mediano de 0,87; no Brasil, o fine-tuning regional levou o Dice de 0,25 para 0,72.
      <br><a href="https://yurishiroiva.github.io/projetos/talhoes.html">Estudo de caso</a> · <a href="https://github.com/YuriShiroiva/talhoes-sentinel2">Código</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://yurishiroiva.github.io/projetos/folhasa.html"><img src="https://yurishiroiva.github.io/assets/og/folhasa.jpg" alt="Página de demonstração do FolhaSã"></a>
      <br><b>FolhaSã</b> <sub>Visão computacional</sub>
      <br>Reconhece 10 condições da folha do tomateiro a partir de uma única foto. Acertou 99,9% das imagens de teste. Modelo exportado para ONNX e servido por uma API em FastAPI.
      <br><a href="https://yurishiroiva.github.io/projetos/folhasa.html">Estudo de caso</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://yurishiroiva.github.io/projetos/redes-neurais.html"><img src="https://yurishiroiva.github.io/assets/og/redes-neurais.jpg" alt="Previsões da LSTM para o dólar e veículos agrupados por CO₂"></a>
      <br><b>Redes neurais: câmbio e CO₂</b> <sub>Data Science</sub>
      <br>LSTM em PyTorch que prevê a cotação do dólar (R² de 0,92 no teste) e rede competitiva que agrupa veículos por cilindrada, eficiência e emissão de CO₂.
      <br><a href="https://yurishiroiva.github.io/projetos/redes-neurais.html">Estudo de caso</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://yurishiroiva.github.io/projetos/falhas.html"><img src="https://yurishiroiva.github.io/assets/og/falhas.jpg" alt="Peça metálica, bordas detectadas e fissura destacada"></a>
      <br><b>Falhas industriais</b> <sub>OpenCV</sub>
      <br>Visão computacional clássica, sem rede neural, que encontra e destaca uma rachadura numa chapa de metal: CLAHE, Canny e morfologia.
      <br><a href="https://yurishiroiva.github.io/projetos/falhas.html">Estudo de caso</a>
    </td>
  </tr>
</table>

**Mais em dados:** [Redes de Game of Thrones](https://github.com/YuriShiroiva/redes-game-of-thrones) (grafos e centralidade) · [Cadastros duplicados com Levenshtein](https://github.com/YuriShiroiva/levenshtein-duplicados) · [Covid-19 no Brasil](https://github.com/YuriShiroiva/Projeto-Covid-19-) (ARIMA e Prophet) · [Previsão de chuva na Austrália](https://github.com/YuriShiroiva/IBM-Lab-Rain-Prediction-in-Australia)

### Stack

<p>
  <img src="https://img.shields.io/badge/Python-161616?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-161616?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-161616?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-161616?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/PyTorch-161616?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging%20Face-161616?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face">
  <img src="https://img.shields.io/badge/OpenCV-161616?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <br>
  <img src="https://img.shields.io/badge/Claude-6d4dff?style=flat-square&logo=anthropic&logoColor=white" alt="Claude">
  <img src="https://img.shields.io/badge/LangChain-6d4dff?style=flat-square&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/Vertex%20AI-6d4dff?style=flat-square&logo=googlecloud&logoColor=white" alt="Vertex AI">
  <img src="https://img.shields.io/badge/MCP-6d4dff?style=flat-square" alt="MCP">
  <img src="https://img.shields.io/badge/RAG-6d4dff?style=flat-square" alt="RAG">
  <br>
  <img src="https://img.shields.io/badge/PostgreSQL-161616?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Cassandra-161616?style=flat-square&logo=apachecassandra&logoColor=white" alt="Cassandra">
  <img src="https://img.shields.io/badge/SQL-161616?style=flat-square" alt="SQL">
  <img src="https://img.shields.io/badge/FastAPI-161616?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Docker-161616?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Google%20Cloud-161616?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud">
  <img src="https://img.shields.io/badge/Git-161616?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

### Formação

**Tecnólogo em Inteligência Artificial Aplicada** pela PUCPR (2024 a 2026), com média 9,27 e Menção Honrosa.

**Certificados**

| Instituição | Certificado | Ano |
|---|---|---|
| IBM | Generative AI Engineering e Generative AI Engineering with LLMs | 2026 |
| Kaggle | Computer Vision e Intermediate Machine Learning | 2026 |
| DeepLearning.AI | Supervised ML: Regression and Classification | 2025 |
| IBM | Data Science Professional e Applied Data Science | 2024 |
| Google | Data Analytics | 2023 |

---

<p align="center">
  Aberto a oportunidades em dados e IA. O jeito mais rápido de falar comigo é por <a href="mailto:yurishiroivabr@gmail.com">e-mail</a>.
</p>
