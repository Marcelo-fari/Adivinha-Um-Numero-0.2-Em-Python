# Adivinha-Um-Numero-0.2-Em-Python
Adivinha Um Numero 0.2 Em Python

importrandom
numero_a_ser_adivinhado = random.randint(0,20000)

for i in range(10):
    numero_respondido = int(input('Qual O Numero A Ser Adivinhado? '))

if numero_respondido >int(numero_a_ser_adivinhado):
print('O Numero é Menor')

elif numero_respondido == int(numero_a_ser_adivinhado):
print('Você Acertou')

elif numero_respondido <int(numero_a_ser_adivinhado):
print('O Numero é Maior')

print('Suas Tentativas Terminaram!')
print(numero_a_ser_adivinhado)

