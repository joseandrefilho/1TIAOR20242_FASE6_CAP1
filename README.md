
# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width="40%" height="40%"></a>
</p>

---

# Capítulo 1 – Despertar da Rede Neural  
### Projeto PBL - Fase 6

---

## 👨‍🎓 Integrantes:

- <a href="https://www.linkedin.com/in/">Edmar Ferreira Souza</a>
- <a href="https://www.linkedin.com/in/alexomantovani">Alexandre Oliveira Mantovani</a>
- <a href="https://www.linkedin.com/in/ricardolcoube/">Ricardo Lourenço Coube</a>
- <a href="https://www.linkedin.com/in/joseandrefilho">Jose Andre Filho</a>

---

## 👨‍🏫 Professores

### Tutor(a)
- [Leonardo Ruiz Orabona](https://www.linkedin.com/in/leonardoorabona)

### Coordenador(a)
- [André Godoi](https://www.linkedin.com/in/profandregodoi)

---

## 📌 Descrição do Projeto
Este repositório apresenta o projeto da Fase 6 do curso 1TIAOR20242 da FIAP, desenvolvido no contexto do Projeto Baseado em Problemas (PBL).  
O desafio proposto pela empresa fictícia **FarmTech Solutions** envolveu a aplicação de técnicas de **Visão Computacional** com foco em:

- 📦 Detecção de objetos
- 🧠 Classificação de imagens
- 🛠️ Comparação entre arquiteturas modernas de IA

---
## 📦 Entregas do Projeto

### 🧩 Entrega 1 – YOLOv5 Adaptado
Desenvolvimento completo de um sistema de detecção de veículos (**carros** e **motos**) utilizando o modelo **YOLOv5**, treinado com dataset customizado.

🔗 [`README_entrega01.md`](./README_entrega01.md)  
📓 [`Notebook Entrega 1`](./notebooks/Entrega01_YOLOv5_adaptado.ipynb)

---

### 🧪 Entrega 2 – Comparação entre Abordagens

Comparação entre três abordagens distintas:
- ✅ YOLOv5 adaptado (com re-treinamento)
- 📦 YOLOv5 tradicional (pré-treinado, sem ajustes)
- 🧱 CNN do zero (classificação binária com softmax)

🔗 [`README_entrega02.md`](./README_entrega02.md)  
📓 [`Notebook Entrega 2`](./notebooks/Entrega02_Comparacao_YOLO_CNN.ipynb)

---

---

## 📈 Principais Aprendizados

- Diferença prática entre **detecção e classificação**
- Importância da **personalização de modelos** (ex: YOLO adaptado vs tradicional)
- Limitações e pontos fortes de abordagens como **CNNs simples**
- Boas práticas de organização de projetos em **notebooks e GitHub**
- Técnicas para análise crítica de resultados com **métricas e visualizações**

---

## 🧗‍♀️ Desafios Enfrentados

- Curadoria e organização do dataset (imagens balanceadas, rotulagem no MakeSense)
- Configuração de ambiente local com GPU e integração com Google Colab
- Interpretação de métricas complexas como mAP e F1-score
- Prevenção de overfitting em treinos com CNN

---

## ▶️ Demonstração em Vídeo

🎥 Link para o vídeo de apresentação (YouTube – não listado): **[inserir aqui]**

---

## 📁 Estrutura Geral do Projeto

```
📦 1TIAOR20242_FASE6_CAP1
│
├── 📁 notebooks
│   ├── Entrega01_YOLOv5_adaptado.ipynb
│   ├── Entrega02_Comparacao_YOLO_CNN.ipynb
│
├── 📁 dataset_images          # Para treino do YOLO
├── 📁 dataset_cnn             # Para treino da CNN
├── 📁 modelos                 # Modelos salvos (.pt, .keras)
│
├── 📄 README.md               # Este arquivo
├── 📄 README_entrega01.md
├── 📄 README_entrega02.md
└── 📄 requirements.txt
```
---

## 📝 Licença

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/">
Este projeto segue o modelo FIAP e está licenciado sob 
<a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer">Attribution 4.0 International (CC BY 4.0)</a>.
</p>
