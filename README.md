# 🐍 Exercícios de Python

Meus exercícios de Python, organizados por tema. Em cada arquivo explico o que o exercício pede e o que aprendi.

## Temas

| Python | Exercicios |
|---|---|
| `01-basico` | Saída na tela, variáveis e operações |
| Exercício | O que faz |
|---|---|
| [ex001](01-basico/ex001-soma-de-dois-numeros.py) | Soma de dois números |

# Exercício 001 - Soma de dois números
## Enunciado: ler dois números inteiros e mostrar a soma.

primeiro = int(input('Primeiro número: '))
segundo = int(input('Segundo número: '))

soma = primeiro + segundo

print(f'A soma é {soma}')

| [ex002](01-basico/ex002-operacao-com-tres-numeros.py) | Operação com três números |

# Exercício 002 - Operação com três números
## Enunciado: ler três números inteiros, somar os dois primeiros e subtrair o terceiro.

primeiro = int(input('Primeiro número: '))
segundo = int(input('Segundo número: '))
terceiro = int(input('Terceiro número: '))

resultado = primeiro + segundo - terceiro

print(f'O resultado de {primeiro} + {segundo} - {terceiro} é {resultado}')

| [ex003](01-basico/ex003-saudacao-com-nome.py) | Saudação com nome |

# Exercício 003 - Saudação com nome
## Enunciado: ler o nome da pessoa e mostrar uma mensagem de boas-vindas.

nome = input('Digite o seu nome: ')

print(f'É um prazer te conhecer, {nome}!')

| [ex004](01-basico/ex004-analisando-uma-entrada.py) | Analisando o tipo e o conteúdo de uma entrada |

# Exercício 004 - Analisando uma entrada
## Enunciado: ler algo digitado e mostrar o tipo e várias informações sobre o conteúdo.

texto = input('Digite algo: ')

print(f'O tipo primitivo desse valor é {type(texto)}')
print(f'Só tem espaços? {texto.isspace()}')

print(f'É um número? {texto.isnumeric()}')

print(f'É alfabético? {texto.isalpha()}')

print(f'É alfanumérico? {texto.isalnum()}')

print(f'Está em maiúsculo? {texto.isupper()}')

print(f'Está em minúsculo? {texto.islower()}')

print(f'Está capitalizado? {texto.istitle()}')

| [ex005](01-basico/ex005-vendo-operadores-aritméticos.py) | Operações aritméticas |

# Exercício 005 - Operações aritméticas
## Enunciado: Ler as operações.

n1 = int(input('Um valor: '))

n2 = int(input('Outro valor: '))

s = n1 + n2

m = n1 * n2

d = n1 / n2

di = n1 // n2

e = n1 ** n2

print(f'A soma é {s}, o produto é {m}, e a divisão é {d}')

print(f'Divisão inteira {di}, e potência {e}')

#

| `02-condicoes` | if, elif e else |

| `03-lacos` | for e while |

| `04-funcoes` | Funções e parâmetros |

## Como rodar

1. Instale o Python.
2. Baixe o repositório.
3. No terminal, rode: `python 01-basico/ex001-ola-mundo.py`
