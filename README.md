# aprendendo-python

altura = float(input('Informe sua altura: '))
sexo = int(input('Informe o seu gênero (homem 1 ou mulher 2): '))

if sexo==1:
    print(f'Seu peso ideal é {(72.7*altura)-58}')
else:
    print(f'Seu peso ideal é {(62.1*altura)-44.7}')
