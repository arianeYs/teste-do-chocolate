print("Olá!")

Nome = input("Qual é o seu nome?")
print('Olá', Nome)

idade = input("E qual é a sua idade?")

if int(idade) > 17:
  print("Legal, você já é um adulto!")

else:
  print("Você é menor de idade então. Muito legal!")

resposta = input("Você gosta de chocolate? (Sim/Não): ")

if resposta.lower() == "sim":
    print("Que bom! Chocolate é uma delícia!")
elif resposta.lower() == "não":
    print("Ah, que pena! Chocolate é muito gostoso!")
else:
    print("Resposta inválida. Por favor, responda 'Sim' ou 'Não'.")
  
