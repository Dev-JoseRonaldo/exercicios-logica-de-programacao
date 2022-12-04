<h1 align="center">Aang em apuros</h1>

### 🕵🏼 Problem Statement

Aang está em uma base da nação do fogo procurando uma saída para se livrar de cinco soldados que o perseguem. Depois de muito tentar, Aang não encontra uma forma de escapar e se depara com um salão sem escapatórias. Sua única chance é lutar pela sua vida contra cinco dobradores do fogo.

<br/>

<p align="center">
  <img src="../../.github/aang.gif" width="75%">
</p>

<br/>

Para saber quem vence o combate, você deve criar um programa que decida quem será o vencedor do combate. Os critérios são: força, agilidade e precisão.

Nesse combate, contaremos apenas com os atributos de Aang e a soma dos atributos dos cinco dobradores de fogo combinados em um só. Os critérios são:

- quem tiver a maior força vence o combate;
- caso a força seja igual, quem possuir maior agilidade vence;
- caso também ocorra empate, quem tiver maior precisão vencerá a luta;
- se todos os atributos forem iguais, Aang terá que apelar e usar seu poder de avatar para escapar e irá vencer o combate.

Ao final do combate, deverá ser informado quem saiu vitorioso.

<br/>

### 📥 Input

A entrada é composta por 6 linhas. A primeira e a segunda indicam a força de Aang (F1) e a força dos soldados juntos (F2):

```bash
F1
F2
```

1 <= F1 <= 10 <br/>
1 <= F2 <= 10

A terceira e a quarta entradas indicam a agilidade de Aang (A1) e a agilidade dos soldados juntos (A2):

```bash
A1
A2
```

A1 - String ("Rapido" ou "Lento") <br/>
A2 - String ("Rapido" ou "Lento")

A quinta e a sexta entradas indicam a precisão (números de ponto flutuante) de Aang (P1) e dos soldados juntos (P2):

```bash
P1
P2
```

Obs.: P1 > 0 e P2 > 0

<br/>

### 📤 Output

Caso Aang saia vitorioso, a saída deverá ser:

```bash
Aang venceu o combate!
```

Caso contrário, a saída será:

```bash
Aang perdeu o combate e agora esta preso na fortaleza da nacao do fogo.
```

<br/>

### ✏️ Examples

Case: 1

```bash
#Input
7
7
Lento
Lento
71.5
71.5

#Output
Aang venceu o combate!
```

Case: 2

```bash
#Input
5
5
Rapido
Rapido
30.5
45.3

#Output
Aang perdeu o combate e agora esta preso na fortaleza da nacao do fogo.
```

Case: 3

```bash
#Input
10
8
Rapido
Lento
53.2
35.9

#Output
Aang venceu o combate!
```
