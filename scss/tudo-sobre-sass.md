# Tudo sobre o Sass

O Sass é um preprocessador css que serve para criar codigo css de maneira mais rapida e que fique facil a manutenção do codigo.

Com sass podemos usar variaveis, dividir em arquivos menores e usar o @use e o arquivo isso é semelhante ao importe de algumas linguagem de programação.

Também podemos criar funções para reaproveitar codigos.


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

    @use "background";

Na mesma linha e no final da linha o ponto-e-virgula;



