# Deep Learning e Processamento de Linguagem Natural - IDP

Repositório oficial da disciplina **Deep Learning e Processamento de Linguagem Natural (IDP)**.  
Este espaço reúne **notebooks**, **códigos**, **datasets**, e **materiais de apoio** utilizados ao longo do curso, explorando desde os fundamentos de redes neurais até o uso de modelos de linguagem de última geração.

---



## 🧠 Estrutura do Curso

O curso está dividido em **4 módulos** principais, cada um com seus **códigos** e **datasets** organizados em pastas específicas.

---

### Módulo 1 – Fundamentos de Deep Learning

Apresenta os conceitos fundamentais do Deep Learning: a história do campo, motivação, estrutura de redes neurais artificiais, propagação direta e retropropagação, e o processo de otimização via gradiente.  
Também introduz arquiteturas profundas, funções de ativação, inicialização de pesos e algoritmos de otimização (SGD, Momentum, Adam).

**📂 Estrutura:**
- `modulo_01_fundamentos/`
  - `codigo/` → notebooks com implementações básicas de redes neurais e exemplos introdutórios.  
  - `dataset/` → 

#### 📊 Dataset Utilizado

O dataset utilizado neste módulo é proveniente do estudo:

> Valentim Realinho, Jorge Machado, Luís Baptista, & Mónica V. Martins. (2021).  
> *Predict students' dropout and academic success (1.0)* [Data set]. Zenodo.  
> DOI: [https://doi.org/10.5281/zenodo.5777340](https://doi.org/10.5281/zenodo.5777340)

O conjunto de dados contém informações sobre desempenho acadêmico e evasão estudantil, sendo amplamente empregado em estudos sobre predição de sucesso e permanência no ensino superior.


#### 📚 Referências

- MARTINS, Mónica V. et al. *Early prediction of student’s performance in higher education: A case study.*  
  In: *World Conference on Information Systems and Technologies.* Cham: Springer International Publishing, 2021. p. 166–175.  

- RANI, Nisha; PACHIGOLLA, Venkata Suresh; KUMAR, Akshay. *Clustering based pre-processing for feature reduction and robust student dropout classification.*  
  *International Journal of Information Technology*, p. 1–13, 2025.  
  
---

### Módulo 2 – Regularização

Foco em técnicas que promovem generalização e evitam o sobreajuste.  
Discute o compromisso entre viés e variância, e explora métodos clássicos e modernos de regularização, como L1/L2, Dropout, Early Stopping e Data Augmentation.  
Inclui exemplos práticos de controle de complexidade e avaliação de desempenho fora da amostra.

**📂 Estrutura:**
- `modulo_02_regularizacao/`
  - `codigo/` → notebooks aplicando técnicas de regularização em redes densas.  
  - `dataset/` → dados para comparação entre modelos regularizados e não regularizados.

---

### Módulo 3 – Redes Convolucionais e Sequenciais

Introduz arquiteturas especializadas para visão computacional e séries temporais.  
Apresenta **CNNs** (redes convolucionais) para extração de padrões espaciais e **RNNs/LSTM/GRU** para captura de dependências temporais e ordinais em texto ou séries.  


**📂 Estrutura:**
- `modulo_03_cnn_rnn/`
  - `codigo/` → notebooks de CNNs, RNNs, LSTMs e experimentos em visão e sequências.  
  - `dataset/` → imagens e séries temporais para exercícios de classificação e predição.

---

### Módulo 4 – Processamento de Linguagem Natural

Aprofunda-se nas técnicas e modelos para representação e compreensão de linguagem.  
Cobre desde representações clássicas (Bag-of-Words, TF-IDF) até embeddings densos (Word2Vec, GloVe) e modelos contextuais baseados em **Transformers**.  
Inclui fine-tuning supervisionado e alinhamento com preferências humanas (SFT, RLHF, DPO).

**📂 Estrutura:**
- `modulo_04_pln/`
  - `codigo/` → notebooks com embeddings, Transformers e fine-tuning de modelos pré-treinados.  
  - `dataset/` → corpora textuais e dados de preferências para tarefas de PLN.

---

## 📁 Organização do Repositório

Cada módulo é independente e contém:
- 📘 **Códigos** para experimentos e demonstrações.  
- 📊 **Datasets** originais e derivados.  

---

## 👨‍🏫 Sobre

Este repositório foi desenvolvido como parte da disciplina **Deep Learning e Processamento de Linguagem Natural (IDP)**, com foco em **fundamentos teóricos**, **implementação prática** e **aplicações modernas** de Inteligência Artificial.

---

## 📄 Licença

Uso **acadêmico e educacional**.  
Sinta-se livre para explorar, adaptar e contribuir — mantendo os créditos originais da disciplina.

---
