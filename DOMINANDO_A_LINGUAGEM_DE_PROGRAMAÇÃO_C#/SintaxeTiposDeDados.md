## Conceito de Classe
Inicialmente, vamos utilizar um Computador como nosso objeto de referência para compreender o conceito de Classe.

Suponhamos que este computador contenha os seguintes elementos:

- Placa de Vídeo
- Processador
- Memória RAM
- Gabinete
- Fonte
- SSD
Esses elementos mencionados comportam-se como os atributos do computador. Dessa forma, podemos afirmar que esse Computador se configura como uma classe.

Explicarei com maior detalhe no diagrama a seguir:

|  Computador (Classe)  |Tipo de Dado|
|-----------------------|-|
|Placa de Vídeo:  |`string`|
|Processador:     |`string`|
|Memória RAM:       |`int `|
|Gabinete:       |`string `|
|Fonte:           |`string`|
|SSD:               |`int `|
-------------------------

Neste diagrama de classe, é perceptível que após o nome dos componentes (Atributos) do computador existem duas nomenclaturas declaradas: `int` e `string`. Essas definições especificam o tipo de dado que será armazenado nesses atributos.

## Tipos de Dados

Para entendermos melhor o que será representado nos diagramas e nos exemplos que irei citar, precisaremos compreender os tipos de dados existentes no C# e como poderemos utilizá-los no dia a dia.

| Tipo     | Descrição                                  | Faixa de Valores                                   | Valor Padrão |
|----------|--------------------------------------------|----------------------------------------------------|--------------|
| `string` | Uma série de caracteres                    | -                                                  | -            |
| `char`   | Um caractere Unicode                        | -                                                  | -            |
| `object` | Tipo objeto                                | -                                                  | -            |
| `bool`   | Valor booleano                             | Verdadeiro ou Falso                                | Falso        |
| `byte`   | Número inteiro sem sinal de 8 bits          | 0 a 255                                            | 0            |
| `decimal`| Valores decimais com 28-29 dígitos significativos | (+ ou -)1.0 x 10e-28 a 7.9 x 10e28               | 0.0M         |
| `double` | Tipo de ponto flutuante de dupla precisão de 64 bits | (+/-)5.0 x 10 elevado a -324 a (+/-)1.7 x 10 elevado a 308 | 0.0D         |
| `int`    | Tipo de inteiro de 32 bits                  | -2.147.483.648 a 2.147.483.647                    | 0            |
| `float`  | Tipo de ponto flutuante de precisão simples de 32 bits | -3.4 x 10 elevado a 38 a + 3.4 x 10 elevado a 38 | 0.0F         |
| `long`   | Tipo de inteiro de 64 bits                  | -9.223.372.036.854.775.808 a 9.223.372.036.854.775.807 | 0L       |
| `uint`   | Tipo de inteiro sem sinal de 32 bits        | 0 a 4.294.967.295                                | 0            |
| `short`  | Tipo de inteiro de 16 bits                  | -32.768 a 32.767                                 | 0            |
| `ulong`  | Tipo de inteiro sem sinal de 64 bits        | 0 a 18.446.744.073.709.551.615                   | 0            |
