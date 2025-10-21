# Data_Basic
Basic Study to Data science Students.


![GitHub repo size](https://img.shields.io/github/repo-size/iuricode/README-template?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/iuricode/README-template?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/iuricode/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge)

---

### Introduction to Basic Concepts for Data Science 
Fundamental concepts essential for anyone who wants to work with data analysis.

---


🔹 Data Types
---
int, float, str, bool
Conversão de tipos com int(), float(), str()

```
idade = 25
altura = 1.75
nome = "Thales"
print(f"{nome} tem {idade} anos e {altura}m de altura.")
```
🔹 Operators
---

Aritméticos: +, -, *, /, **, %
Comparação: ==, !=, >, <, >=, <=
Lógicos: and, or, not

---
🔹Creating Functions
---
```
def media(lista):
    calculo = sum(lista) / len(lista)
    print(calculo)


notas = [7.5, 8.0, 9.0]
resultado = media(notas)
print(f"A média é {resultado:.2f}")

```
🔹 Text
---
```
texto = texto.strip().replace('y','t').upper()
texto

nota_entrada = float(input('Digite a nota do teste de ingresso: '))
print(f'Ano de entrada {ano_entrada} - nota do teste de ingresso {nota_entrada}')

nome_aluno = 'Fabricio Daniel'
idade_aluno = 15
media_aluno = 8.45

print('Nome do aluno é {}, ele tem {} anos e sua média é {}.' .format(nome_aluno, idade_aluno, media_aluno))


nota_1 = float(input('Digite a 1° nota: '))
nota_2 = float(input('Digite a 2° nota: '))

print(f'Média: {(nota_1+nota_2)/2}')
```
🔹 Data Visualization with Matplotlib
---
```
import matplotlib.pyplot as plt

estudantes = ["João", "Maria", "José"]
notas = [8.5, 9, 6.5]

plt.bar(x=estudantes, height=notas)
plt.title("Notas dos Estudantes")
plt.xlabel("Estudantes")
plt.ylabel("Notas")
plt.show()
```

🔹 List
---
A list is an ordered collection of elements. These elements can be of any type — numbers, strings, other lists, etc.
A tuple is also an ordered collection, but immutable — once created, you cannot change its elements.
```
from random import randrange, sample

lista = []
for i in range(20):
    lista.append(randrange(100))

amostra = sample(lista, 5)
print("Amostra aleatória:", amostra)
```

🔹 While
---
```
contador = 1

while contador <= 3:
    nome = input(f'\nDigite o nome do {contador}º aluno: ')
    nota_1 = float(input('Digite a 1ª nota: '))
    nota_2 = float(input('Digite a 2ª nota: '))

    media = (nota_1 + nota_2) / 2

    print('-' * 40)
    print(f'Aluno: {nome}')
    print(f'Notas: {nota_1:.1f} e {nota_2:.1f}')
    print(f'Média: {media:.2f}')
    print('-' * 40)

    contador += 1
```
🔹 Exception
---
try: Where you put code that might cause an error.
except: Where you handle specific errors.
else: Runs only if no error occurs.
finally: Always runs, no matter what.
Custom exception: InvalidAgeError is created to handle specific invalid input.
```
# Custom exception
class InvalidAgeError(Exception):
    """Exception raised when the age is negative or unrealistically high."""
    pass

def check_age(age):
    if age < 0 or age > 120:
        raise InvalidAgeError("Invalid age! Age must be between 0 and 120.")
    return f"Valid age: {age} years old."

# Main program
try:
    age = int(input("Enter your age: "))  # Might raise ValueError if input is not a number
    result = check_age(age)               # Might raise InvalidAgeError
except ValueError:
    print("Error: You must enter an integer number.")
except InvalidAgeError as e:
    print(f"Custom error: {e}")
else:
    print(result)
finally:
    print("Program execution finished. Thank you for using it!")
```
🔹frequency distributio
---

A frequency distribution is a way to organize data that shows how often each value (or range of values) occurs in a dataset.
```
 frequencia = dados['Profissão'].value_counts()
 percentual = dados['Profissão'].value_counts(normalize = True) * 100
dist_freq_qualitativas = pd.DataFrame({'Frequência': frequencia, 'Porcentagem (%)': percentual})
dist_freq_qualitativas.rename(index = {1: 'Estatístico', 2: 'Cientista de Dados', 3: 'Programador Python'}, inplace = True)
dist_freq_qualitativas.rename_axis('Profissão', axis= 'columns', inplace = True)
dist_freq_qualitativas
```
---
### Adjustments and improvements.

The project is still under development, and the upcoming updates will focus on the following tasks:

- [x] Advanced courses about Phyton

The following tools were used in the construction of the project:

- [Python](<https://www.python.org/doc//>)
- [Google colab](<https://colab.google/>)



## 🤝 Creator

<table>
  <tr>
    <td align="center">
      <a href="#" title="Thales Farias">
        <img src="grecia.jpg" width="100" alt="Foto do Thales Farias no GitHub"/><br>
        <sub>
          <b><a href="https://www.linkedin.com/in/thalesfreirefarias/" target="_blank">Thales Farias</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

