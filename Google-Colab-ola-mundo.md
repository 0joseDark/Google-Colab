# "olá mundo"
```python
# Instalar a biblioteca googletrans
!pip install googletrans==4.0.0-rc1

# Importar a biblioteca
from googletrans import Translator

# Exibir "Olá, Mundo!"
print("Olá, Mundo!")

# Criar um objeto Translator
translator = Translator()

# Texto a traduzir
texto = "Hello, how are you?"

# Traduzir para português
traducao = translator.translate(texto, dest='pt')

# Exibir tradução
print("Texto original:", texto)
print("Tradução:", traducao.text)
```
