# Jogo de Adivinha��o

![](https://imgur.com/iylqf6z.gif)

## Projeto

Desenvolvido durante o curso Fullstack da [Academia do Programador](https://www.academiadoprogramador.net) 2025

---
## Detalhes

Ao iniciar o jogo, temos tr�s op��es para jogar: o modo F�cil, M�dio e Dif�cil, onde
cada um deles acompanha uma quantidade de tentativas que o usu�rio tem para jogar:
- facil:   10 tentativas 
- medio:    5 tentativas 
- dificil:  3 tentativas 

---
## Entrada

Os jogadores interagem com o console. Nessa intera��o, eles digitam um n�mero e o sistema j� retorna a mensagem correspondente ao 
feedback do n�mero escolhido pelo jogador. Caso ele acerte, haver� uma mensagem dizendo que ele ganhou. Caso o
jogador erre, ele pode continuar a jogar, desde que esteja alinhado com o n�mero de tentativas escolhidas de acordo com a
dificuldade.

---
## Funcionalidades

- **Gera��o de N�mero Secreto:** No in�cio de cada jogo, um n�mero secreto � gerado aleatoriamente entre 1 e 20.
- **Sele��o de Dificuldade:** Os jogadores podem escolher entre tr�s n�veis de dificuldade (F�cil, M�dio, Dif�cil), que influenciam o n�mero de tentativas dispon�veis.
- **Feedback Instant�neo:** Ap�s cada tentativa, o jogo fornece feedback indicando se o n�mero escolhido � maior ou menor que o n�mero secreto.
---
## Requisitos

- .NET SDK (recomendado .NET 8.0 ou superior) para compila��o e execu��o do projeto.
---
## Como Usar

#### Clone o Reposit�rio
```
https://github.com/LeandroJader/jogo_de_adivinhacao_2025
```

#### Navegue at� a pasta raiz da solu��o
```
cd jogo-de-adivinhacao-2025
```

#### Restaure as depend�ncias
```
dotnet restore
```

#### Navegue at� a pasta do projeto
```
cd JogoDaAdivinhacao.ConsoleApp
```

#### Execute o projeto
```
dotnet run
```
