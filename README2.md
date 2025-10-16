# Data_Basic
Basic Study to Data science Students.


Curso de Python.
Google Colab:
-> Print'',numero)
-> Variaveis
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
