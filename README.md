# Exercicio0016.py
#Crie um programa que leia um número Real qualquer pelo teclado e mostre na tela a sua porção Inteira

from math import trunc
#t = float(input('Digite um numero: '))
#print('o valor digitado foi {} e sua porção inteira é: {}'.format(t,trunc(t)))


t = float(input('Digite um valor: '))
print('O valor {} tem sua parte inteira sendo: {}'.format(t,int(t)))
