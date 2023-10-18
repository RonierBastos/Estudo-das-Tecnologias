<p align="center">
<img src="https://github.com/RonierBastos/Estudo-das-Tecnologias/blob/main/Ciencia-da-Computacao/files/codigo-binario.png?raw=true" />
</p>

# Representando Números

Desde pequenos aprendemos um sistema eficiente para representar números, onde temos dez dígitos, de 0 a 9:
<p align="center">0 1 2 3 4 5 6 7</p>

- Esse sistema é denominado decimal, ou base 10, uma vez que existem dez valores diferentes que um dígito pode representar.
<br/>

Os computadores usam um sistema mais simples chamado **binário**, ou base dois, com apenas dois dígitos possíveis:
<p align="center">0 1</p>

- Cada dígito binário também é chamado de **bit**.

<br/>

⚠️ **ATENÇÃO!** ⚠️
>Para facilitar o restante da leitura assista esse: [**Vídeo**](https://www.youtube.com/watch?v=q3xLvOsqhpo&list=PLX0VJrazYICDX3T4-DXkxp4g7dpF_4xBH) e retorne quando acabar.

<br/>

Como os computadores funcionam com eletricidade, que pode ser ligada ou desligada, podemos convenientemente representar um bit ligando ou desligando alguma chave para representar 0 ou 1.

- Com uma lâmpada, por exemplo, podemos ligá-la para contar até 1.

<br/>

Com três lâmpadas podemos acendê-las em padrões diferentes e contar de 0 (com as três apagadas) a 7 (com as três acesas):

<p align="center">
<img src="https://github.com/RonierBastos/Estudo-das-Tecnologias/blob/main/Ciencia-da-Computacao/files/lampadas-binarios.png?raw=true" />
</p>

Dentro dos computadores modernos, existem milhões de pequenos interruptores chamados **transistores** que podem ser ligados e desligados para representar valores diferentes. Por exemplo, sabemos que o seguinte número em decimal representa cento e vinte e três.
<p align="center">123</p>


- O **3** esta na coluna das unidades
- O **2** esta na coluna das dezenas
- O **1** esta na coluna das centenas

<br/>

Portanto, **123** é:
```(100 x 1) + (10x2) + (1x3) = 100 + 20 + 3 = 123```
 
- **IMPORTANTE:** Se você não entendeu é só assistir o [**Vídeo**](https://www.youtube.com/watch?v=q3xLvOsqhpo&list=PLX0VJrazYICDX3T4-DXkxp4g7dpF_4xBH) que recomendei. Para facilitar o restante do conteúdo procure sobre Potencialização, apenas para relembrar caso tenha esquecido.

<br/>

Cada casa de um dígito representa uma potência de dez, pois há dez dígitos possíveis para cada casa. O lugar mais a direita é para **10°**, o do meio **10¹** e o lugar mais à esquerda **10²**:
```
 1   2   3
10² 10¹ 10°
```
<br/>
Em binário, com apenas dois dígitos, temos potências de dois para cada valor de casa:

```
2° = 1
2¹ = 2
2² = 4
2³ = 8
2⁴ = 16
2⁵ = 32
```
<br/>

O valor **0** representa uma "lâmpada ou interruptores desligados".

Por exemplo, o valor binário **011**, representa o valor decimal **3**, uma vez que somamos o 2 e o 1, o 0 não tem valor:
```
0 1 1 (Valor binário)
4 2 1 (Potencia de 2)

Logo:
2 + 1 = 3

O valor 4 não entra no cálculo, pois esta no valor binário **0**.
```

Se tivéssemos mais lâmpadas, poderíamos ter um valor binário de **110010**, que teria o valor decimal equivalente a 50:

```
1  1  0  0  1  0 
2⁵ 2⁴ 2³ 2² 2¹ 2°

32 16 8  4  2  1
```
- Observe que 32 + 16 + 2 = 50.
- Os valores 8, 4 e 1 não entram no cálculo, pois estão no valor binário **0**.



## 🔗 Referências

 - [[VIDEO] Entenda o sistema binário e como ele funciona](https://www.youtube.com/watch?v=q3xLvOsqhpo)
 - [[VIDEO] Conversão de Valores Binários e Decimais](https://www.youtube.com/watch?v=VcNSBwQjVnQ)
 - [[VIDEO] Potenciação](https://www.youtube.com/watch?v=cWL3FjqLhOM)
 - [CC50 - CURSO DE CIÊNCIA DA COMPUTAÇÃO DE HARVARD GRÁTIS](https://materiais.napratica.org.br/cc50)

## 💻 Conteúdos
<table>
 <thead>
    <tr align="center">
      <th>Matéria</th>
      <th>Link de acesso</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>Ciência da Computação</td>
      <td align="center">
        <a href="https://github.com/RonierBastos/Estudo-das-Tecnologias/tree/main/Ciencia-da-Computacao">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Voltar%20-30A3DC?style=for-the-badge">
        </a>
      </td>
    </tr>
  </tbody>
</table>
