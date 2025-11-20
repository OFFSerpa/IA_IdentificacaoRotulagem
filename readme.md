# 🥫 Detecção de Rótulos Nutricionais Frontais com YOLOv8

Este projeto tem como objetivo desenvolver um sistema de **Visão Computacional** para detectar e classificar rótulos nutricionais frontais obrigatórios em embalagens de alimentos no Brasil, conforme a **Resolução RDC nº 429/2020** e a **Instrução Normativa nº 75/2020** da ANVISA.  

O foco está na identificação automática dos selos de advertência que indicam “Alto em” **açúcar adicionado**, **gordura saturada** e **sódio**, utilizando técnicas de **Machine Learning** e o modelo **YOLOv8** implementado em **Python**.  

---

## 🚀 Tecnologias Utilizadas
- **Python 3** ([Documentação Oficial](https://docs.python.org/3/))  
- **YOLOv8** ([Ultralytics Docs](https://docs.ultralytics.com/pt/models/yolov8/))  
- Principais bibliotecas:  
  - `torch`  
  - `ultralytics`  
  - `opencv-python`  
  - `pandas`  
  - `matplotlib`  

---

## 📊 Dataset
- Imagens **autorais**, capturadas em prateleiras de supermercados e closes de rótulos em diferentes condições de iluminação e ângulos.  
- Classes alvo: `alto-acucar`, `alto-gordurasaturada`, `alto-sodio`.  

---

## 🎯 Objetivos
- [x] Realizar análise exploratória do dataset.  
- [x] Padronizar anotações para classes individuais.  
- [x] Treinar modelo YOLOv8 para detecção dos selos da ANVISA.  
- [x] Avaliar métricas de desempenho (mAP, precisão, recall).  
- [x] Disponibilizar resultados e relatórios em notebook e PDF.  

---

## 📓 Notebook
👉 [Acesse o notebook aqui](https://colab.research.google.com/drive/1bEsZttDg9Hl4F9eSYQkN4p3pVbqOcsT-#scrollTo=WCGLCXMtXvJ1)  

---

## 📖 Referências
- Brasil. ANVISA (2020a). [RDC nº 429/2020](https://www.in.gov.br/en/web/dou/-/resolucao-de-diretoria-colegiada-rdc-n-429-de-8-de-outubro-de-2020-282070599)  
- Brasil. ANVISA (2020b). [Instrução Normativa nº 75/2020](https://www.gov.br/anvisa/pt-br/assuntos/alimentos/rotulagem/rotulagem-nutricional)  
- Ultralytics (2023). [YOLOv8 Documentation](https://docs.ultralytics.com/pt/models/yolov8/)  
- Python Software Foundation (2024). [Python 3 Documentation](https://docs.python.org/3/)  
