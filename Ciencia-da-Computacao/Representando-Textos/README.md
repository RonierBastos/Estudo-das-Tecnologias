<p align="center">
<img src="https://www.convertbinary.com/wp-content/uploads/Text-to-Binary.jpg" />
</p>

# Representando Textos

Para representar as letras, tudo que precisamos fazer é decidir como os números são mapeados para as letras. Alguns humanos, muitos anos atrás, decidiram coletivamente um mapeamento padrão de números em letras.

A letra "**_A_**", por exemplo, é o número 65, e a letra "**_B_**" é o 66, e assim por diante.

Ao usar o contexto, como quando estamos olhando uma planilha ou um e-mail, diferentes programas podem interpretar e exibir os mesmos **_bits_** como números ou textos.

O mapeamento padrão é o [**ASCII**](https://pt.wikipedia.org/wiki/ASCII), também inclui letras minusculas e pontuação.

Se recebêssemos uma mensagem de texto com um padrão de bits que tivesse os valores decimais: _**71** **105** **116** **72** **117** **98** **33**_, esses bits seriam mapeados para as letras **_GitHub!_**.

>Para melhor entender é só entrar na tabela [**ASCII**](https://pt.wikipedia.org/wiki/ASCII) e comparar os valores decimais a cima.

Cada letra é normalmente representada com um padrão de oito bits, ou um byte, então as sequências de bits que receberíamos são **_0100 0111_**, **_0110 1001_**, **_0111 0100_**, **_0100 1000_**, **_0111 0101_**, **_0110 0010_** e **_0010 0001_**.

- Podemos já estar familiarizados com o uso dos bytes como uma unidade de medida para dados, como em Megabytes ou Gigabytes, para milhões ou bilhões de bytes.

Com oito bits, ou um byte, podemos ter 2⁸ ou 256 valores diferentes(incluindo zero, o valor mais alto que podemos contar seria 255).

Outros caracteres, como letras com acentos e símbolos em outros idiomas, fazem parte de um padrão chamado [**Unicode**](https://pt.wikipedia.org/wiki/Unicode), que usa mais bits do que o ASCII para acomodar todos esses caracteres.

- Quando recebemos um emoji, nosso computador está apenas recebendo um número binário que mapeia para a imagem do emoji baseado no padrão Unicode. Por exemplo, o emoji "face com lágrimas de alegria" tem apenas os bits: **_11110000100111111001100010000010_**

<p align="center"> <img src="https://edools-3-production.s3.amazonaws.com/org-6988%2Fschool-7227%2F512657e41deb7c4ee12bc597ef039e78%2Fface_with_tears_of_joy.png" /> </p>


## 💭 Depoimento do aluno

Para fixar legal na cabeça o ideal é ir brincar com os conversores que deixei nas referências e assistir uns vídeos no YouTube sobre o tema. Eu não coloquei link de vídeo por que já entendi bem só com o artigo.

É muito legal saber de fato como funciona a linguagem de máquina(computador), eu sempre falei "o computador só entende 0 e 1", mas eu mesmo não tinha o conhecimento sobre o assunto e hoje eu sei, é muito empolgante.







## 🔗 Referências

 - [Conversor de Texto para ASCII](https://pt.rakko.tools/tools/76/)
 - [Conversor de Binário para Unicode](https://cryptii.com/pipes/binary-decoder)
 - [Mapeamento ASCII](https://pt.wikipedia.org/wiki/ASCII)
 - [Mapeamento Unicode](https://pt.wikipedia.org/wiki/Unicode)
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
        <a href="https://github.com/RonierBastos/Ciencia-da-Computacao">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Voltar%20-30A3DC?style=for-the-badge">
        </a>
      </td>
    </tr>
  </tbody>
</table>