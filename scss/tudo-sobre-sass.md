# Tudo sobre o Sass

O Sass é um preprocessador css que serve para criar codigo css de maneira mais rapida e que fique facil a manutenção do codigo.

Com sass podemos usar variaveis, dividir em arquivos menores e usar o @use e o arquivo isso é semelhante ao importe de algumas linguagem de programação.

Também podemos criar funções para reaproveitar codigos.

## Intalação do sass

Eu instalei o sass atravez do apt-get do ubuntu que o meu sistema operacional.

1. Eu instalei o Ruby
2. Eu instalei o Sass
3. Pronto eu já estava pronto para programar.

Os comandos foram esses se você também usa o Ubuntu:

    sudo apt-get install Ruby

Para saber qual o comando é para instalar o sass é só você digitar no terminal que o proprio terminal vai lhe disser qual é o comando.


## Principais comandos

Neste arquivo em markdown eu vou compartilhar os principais comandos do sass.

Esse comando é para compilar o arquivo sass em um arquivo css.

    sass scss/style.scss css/style.css

### Criação de variaveis

Para criar variavieis precisamos de declarar uma variavel assim: 

    $tamanho: 15px;

Tudo na mesma linha.

E depois é só chamar a variavel.

    a {
        font-size: $tamanho;
    }

Tudo na mesma linha.


### Importação de arquivos sass

Na importação de arquivos sass utilizamos o comando:
@use mais o nome do arquivo, exemplo:

    @import "background", "fontes";

Na mesma linha e no final da linha o ponto-e-virgula, podemos como no exemplo acima importar dois arquivos.
Mas alguns casos vamos importar só uma vez:

    @import "cores";

Pronto isso é tudo sobre importação.



