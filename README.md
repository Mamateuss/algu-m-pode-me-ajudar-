input('Olá! seja muito bem vindo a Google! digite Olá para continuar... ')
name = input('Para começar diga o seu nome ')
age = input(print('prazer {}! agora nos diga: qual a sua idade? '.format(name)))
estado = input(print('Ótimo {}, também precisamos saber qual o seu estado civil atualmente '.format(name)))
print('Ok, Estamos quase acabando {}, agora responda as seguintes perguntas para finalizarmos... '.format(name))
escolaridade = input(print('qual o seu nivel de escolaridade? '))
numero = input(print('número de telefone para contato '))
input(print('Tudo pronto, só precisamos que confirme as informações: seu nome é {}, vc tem {} anos, seu atual estado civil é {}, seu nível de escolaridade é: {}, e seu número para contato é {}, tudo certo? '.format(name, age, estado, escolaridade, numero)))
print('Informações enviadas e registradas com sucesso {}! Entraremos em contato em breve, Obrigado pela atenção!'.format(name))
