# Google-Colab
O **Google Colab** (Colaboratory) é uma plataforma gratuita baseada na nuvem que permite executar código Python diretamente no navegador, sem necessidade de configuração. Ele é amplamente usado para aprendizado de máquina, análise de dados e desenvolvimento de IA, pois suporta **Jupyter Notebooks** e oferece acesso gratuito a GPUs e TPUs.  

## 📌 **Vantagens do Google Colab**  
✔️ Não precisa instalar nada no computador.  
✔️ Armazena e sincroniza arquivos no Google Drive.  
✔️ Permite colaboração em tempo real, como no Google Docs.  
✔️ Suporte a bibliotecas populares como TensorFlow, PyTorch, OpenCV e Matplotlib.  
✔️ Permite acesso a hardware acelerado (GPU/TPU).  

---

## **🔹 Como acessar o Google Colab**  
1️⃣ Acesse o site [https://colab.research.google.com/](https://colab.research.google.com/)  
2️⃣ Faça login com uma conta Google.  
3️⃣ Clique em **"Novo Notebook"** para criar um novo arquivo.  

---

## **🔹 Exemplo prático no Google Colab**  
Aqui está um exemplo de código simples para exibir um gráfico com Matplotlib:

```python
import matplotlib.pyplot as plt
import numpy as np

# Criando dados para o gráfico
x = np.linspace(0, 10, 100)
y = np.sin(x)

# Criando o gráfico
plt.plot(x, y, label="Seno")
plt.xlabel("Eixo X")
plt.ylabel("Eixo Y")
plt.title("Gráfico de uma Função Seno")
plt.legend()
plt.show()
```

---

## **🔹 Como salvar e compartilhar um notebook**  
✔️ Clique em **"Arquivo" → "Salvar no Google Drive"** para armazenar seu código.  
✔️ Para compartilhar, clique em **"Compartilhar"** e gere um link de acesso.  
