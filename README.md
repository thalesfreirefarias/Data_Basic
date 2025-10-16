
# Data_Basic
Basic Study to Data science Students.

Curso de Python.
Google Colab:
-> Print'',numero)
-> Variaveis
```python
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

contador = 1
while contador <= 3:
    nome = input(f'
Digite o nome do {contador}º aluno: ')
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

# Power Automate Basics

![GitHub repo size](https://img.shields.io/github/repo-size/thalesfarias/powerautomate-basics?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/thalesfarias/powerautomate-basics?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/thalesfarias/powerautomate-basics?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/thalesfarias/powerautomate-basics?style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/thalesfarias/powerautomate-basics?style=for-the-badge)

---

## 📘 Basic Concepts of Power Automate

**What are Triggers?**
Triggers are events that start a workflow in Power Automate. Think of them as the “start” of a race — once the trigger occurs, the flow begins to execute the configured actions.

---

## 📝 Creating a Form

You can create a Microsoft Form to collect user information.
Create your form here: https://forms.office.com/

---

## ⚙️ What is Power Automate for?

Power Automate allows you to create automated workflows that perform actions when a trigger occurs.
In this project, every time a user fills out a form, the responses will be sent automatically to Power Automate for processing.

---

## 📂 Creating a SharePoint Library

Go to make.powerautomate.com and click on SharePoint in the left panel.
Then create a new site → choose “Team Site”.
After that, go to New → Document Library, select Excel, and link it with your form data.

<table>
  <tr>
    <td align="center">
      <a href="#" title="Library">
        <img src="3.png" width="100" alt="SharePoint Library"/><br>
      </a>
    </td>
  </tr>
</table>

---

## 🔄 Creating the Flow

On the left panel, click on “Create” → “Automated cloud flow”.
This is where we will define the conditions.

<table>
  <tr>
    <td align="center">
      <a href="#" title="Flow Step 1">
        <img src="1.png" width="100" alt="Flow Step 1"/><br>
      </a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">
      <a href="#" title="Flow Step 2">
        <img src="2.png" width="100" alt="Flow Step 2"/><br>
      </a>
    </td>
  </tr>
</table>

In the first image, you can see the workflow being created.
The trigger is set to activate whenever a new response is submitted in the form.
The flow checks if all required data is provided:
- If data is missing, an automatic message is sent (via email, Teams, etc.).
- If all data is present, it adds the information to the Excel file.

---

## 📂 Creating a flow when every time someone uploads a file send a message on Teams

Choose a specific File where the trigger will activate and the Teams group where the message will be sent.

<table>
  <tr>
    <td align="center">
      <a href="#" title="Flow Step 2">
        <img src="5.png" width="100" alt="Flow Step 2"/><br>
      </a>
    </td>
  </tr>
</table>

---

## 📂 Creating connection with Power BI

---

## 🚀 Future Improvements

The project is still under development. Upcoming updates will include:

- [x] Advanced Data science courses and resources
- [ ] Integration with Teams notifications
- [ ] Adding conditional branches for dynamic responses

---

## 🧰 Tools Used

- [Python](https://www.python.org/doc/)
- [Google Colab](https://colab.google/)

---

## 🤝 Creator

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/thalesfreirefarias/" title="Thales Farias">
        <img src="grecia.jpg" width="100" alt="Photo of Thales Farias"/><br>
        <sub><b>Thales Farias</b></sub>
      </a>
    </td>
  </tr>
</table>
