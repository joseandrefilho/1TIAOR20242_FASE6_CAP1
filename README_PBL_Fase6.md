
# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width="40%" height="40%"></a>
</p>

---

# Capítulo 1 – Despertar da Rede Neural  
### Projeto PBL - Fase 6

---

## 🎓 Grupo

**Grupo Solo – Jose André Filho**

[LinkedIn](https://www.linkedin.com/in/joseandrefilho)

---

## 👨‍🏫 Professores

### Tutor(a)
- [Leonardo Ruiz Orabona](https://www.linkedin.com/in/leonardoorabona)

### Coordenador(a)
- [André Godoi](https://www.linkedin.com/in/profandregodoi)

---

## 📌 Descrição do Projeto

O objetivo desta fase do projeto é aplicar uma rede neural prática com foco em visão computacional, utilizando o modelo YOLOv5 para identificar objetos em imagens.

A proposta simula uma situação real, em que a empresa fictícia FarmTech Solutions está expandindo seus serviços com o uso de IA em segurança patrimonial e controle de acessos. Para isso, foi desenvolvido um modelo de detecção de **carros** e **motos**, com posterior comparação entre diferentes abordagens de IA.

---

## 📦 Estrutura do Projeto

```bash
1TIAOR20242_FASE6_CAP1/
│
├── dataset_images/             # Conjunto de imagens e rótulos rotulados manualmente
│   ├── images/                 # Subpastas: train/, val/, test/
│   └── labels/                 # Subpastas: train/, val/, test/
│
├── veiculos.yaml               # Arquivo de configuração para o YOLOv5
├── README.md                   # Este arquivo
├── <notebook>.ipynb            # Notebook do projeto com código, análises e resultados
└── assets/                     # Imagens para documentação e apresentação
```

---

## ✅ Entrega 1 – Detecção com YOLOv5 Adaptado

Nesta primeira etapa, foi desenvolvido um sistema de detecção de veículos utilizando YOLOv5 customizado. As etapas realizadas incluíram:

- Organização e rotulagem de dataset com 80 imagens (40 de cada classe).
- Separação em treino, validação e teste conforme exigido.
- Treinamento do modelo com duas quantidades de épocas:
  - **30 épocas**: desempenho base
  - **60 épocas**: avaliação de melhoria
- Visualização das métricas e curvas de aprendizado (`results.png`)
- Inferência nas imagens de teste com medição de tempo
- Análise comparativa entre os dois modelos
- Conclusão baseada em precisão, tempo de execução e cobertura

📌 Link para o notebook:  
👉 [Clique aqui para abrir no Colab](https://colab.research.google.com/drive/SEU_LINK_AQUI)

📺 Link do vídeo de demonstração (YouTube – não listado):  
👉 [Assistir no YouTube](https://youtube.com/SEU_LINK_AQUI)

---

## 🔄 Entrega 2 – Comparação entre Abordagens

A Entrega 2 propõe a avaliação de diferentes soluções para o mesmo problema de detecção/classificação, visando compreender a eficácia e aplicabilidade de cada abordagem.

### 🔹 Abordagens previstas

1. **YOLOv5 Adaptado** (modelo treinado na Entrega 1)
2. **YOLO Tradicional** (modelo pré-treinado, sem fine-tuning)
3. **CNN do Zero** (modelo de classificação usando arquitetura simples)

### 🔍 Critérios de comparação

- Facilidade de uso e integração
- Precisão da solução
- Tempo de treinamento (quando aplicável)
- Tempo de inferência
- Qualidade dos resultados (visuais ou métricos)

### 🛠️ Estrutura prevista das seções

```markdown
## 1. Aplicação do YOLO Tradicional
- Carregamento do modelo
- Avaliação qualitativa em imagens do dataset

## 2. Construção e Treinamento da CNN do Zero
- Preparação dos dados
- Arquitetura da rede
- Métricas e avaliação

## 3. Comparativo Geral entre os Modelos
- Tabela comparativa
- Conclusão sobre desempenho e aplicabilidade
```

Essas seções serão preenchidas com os resultados obtidos a partir das execuções práticas.

---

## 📝 Licença

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/">
Este projeto segue o modelo FIAP e está licenciado sob 
<a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer">Attribution 4.0 International (CC BY 4.0)</a>.
</p>
