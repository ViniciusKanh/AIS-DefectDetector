
# 🧠 AIS-DefectDetector  
**Detecção Inteligente de Defeitos de Software com Sistemas Imunológicos Artificiais (AIS)**  

> 🧬 Inspirado no sistema imunológico humano.  
> 🐛 Voltado à identificação adaptativa de falhas em código.  
> ⚙️ Construído com Python, SciKit-Learn, Pandas, e muito mais.

---

## 📌 Visão Geral

Este projeto aplica o algoritmo **Artificial Immune System (AIS)** para **detecção e predição de defeitos em software**, tratando cada falha como um "antígeno" a ser reconhecido por detectores (anticorpos) treinados.

Inspirado nos mecanismos de defesa do corpo humano — como **seleção clonal**, **maturação por afinidade** e **memória imunológica** —, o modelo aprende a identificar padrões de código propensos a erros com **explicabilidade e adaptabilidade contínuas**.

---

## 🧪 Tecnologias Utilizadas

- 🐍 Python 3.11+
- 📊 Pandas & NumPy
- 🎯 Scikit-learn
- 🔬 AIS customizado (Negative Selection + Clonal Selection)
- 📈 Matplotlib / Seaborn
- 🧠 Dataset NASA PROMISE (jm1.csv)

---

## 🧭 Estrutura do Projeto

```
AIS-DefectDetector/
├── data/             # 📂 Datasets utilizados (NASA JM1, etc.)
├── src/              # 🧠 Código-fonte do AIS e pipelines
├── models/           # 🧪 Modelos treinados e serializados
├── notebooks/        # 📒 Jupyter/Colab notebooks com experimentos
├── results/          # 📈 Métricas, gráficos e validações
├── figures/          # 🖼️ Diagramas e imagens (fluxos, AIS, etc.)
├── requirements.txt  # 🧾 Dependências do projeto
└── README.md         # 📘 Este arquivo
```

---

## 🧬 Como Funciona o Algoritmo?

| Componente AIS       | Equivalente no Código        |
|----------------------|------------------------------|
| Antígenos 🦠         | Módulos defeituosos (bugs)   |
| Células normais 🧱   | Módulos corretos             |
| Anticorpos 🛡️       | Detectores simbólicos        |
| Clonagem ♻️         | Geração de novos detectores  |
| Mutação 🔁          | Diversificação de padrões     |
| Maturação 🎓        | Afinidade com o padrão real   |
| Memória 🧠          | Retenção de detectores eficazes |

---

## 🚀 Executando o Projeto

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/seu-usuario/AIS-DefectDetector.git
cd AIS-DefectDetector
```

### 2️⃣ Criar ambiente virtual (opcional)
```bash
python -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate   # (Windows)
```

### 3️⃣ Instalar dependências
```bash
pip install -r requirements.txt
```

### 4️⃣ Executar o notebook
Abra o arquivo `notebooks/ais_model.ipynb` no Jupyter ou Google Colab.

---

## 📊 Resultados

- 📌 **F1-Score médio**: `0.97+` em múltiplas rodadas de teste
- 📈 **Curvas de afinidade** durante o processo evolutivo
- 🧠 **Detectores interpretáveis**, armazenados com memória simbólica
- 🔁 **Reversões de geração** caso a aptidão diminua

---

## 📚 Trabalhos Relacionados

Este projeto é fundamentado em estudos como:

- Khan et al. (2020) - *Hyper-parameter optimization using AIS* [`doi:10.1109/ACCESS.2020.2968362`](https://doi.org/10.1109/ACCESS.2020.2968362)
- Soleimani et al. (2014) - *AIS-based feature selection for fault prediction*
- Yang et al. (2011) - *Negative Selection for Software Aging*
- Gong et al. (2005) - *Immune models for robotic fault detection*

---

## ✍️ Autor

Vinicius de Souza Santos  
📧 vinicius-souza.santos@unesp.br 
📍 UNESP - Universidade Estadual Paulista "Júlio de Mesquita Filho"

---

## 📜 Licença

Distribuído sob a licença MIT. Consulte `LICENSE` para mais informações.

---

## 🌐 Contribuições

Contribuições são bem-vindas!  
Se você tem ideias para melhorar o algoritmo, adaptar para outros datasets ou integrar com deep learning, abra uma issue ou envie um pull request.

---

🧠 *Este projeto une biologia computacional, aprendizado de máquina e engenharia de software para construir soluções explicáveis e adaptativas na detecção de defeitos.*  
