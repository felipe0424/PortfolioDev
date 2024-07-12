

* [Anotações](https://github.com/felipe0424/AULA-05---OBJETOS/blob/master/MD/ANOTA%C3%87%C3%95ES.md)

## OBJETOS
>
> Permitem armazenar e organizar dados de maneira mais complexa do que simples valores primitivos, como números e strings. Eles são compostos por pares chave-valor, onde cada chave (também chamada de propriedade) é uma string única que identifica o valor correspondente.

var pessoa = { 
    nome: 'André', 
    idade: 28,
} 
console.log(pessoa.nome, pessoa.idade);

## THIS
> Reutilizar parâmetro fora da função função

var quadrado = {
    lado: 4,
    area: function () {
        return this.lado *this.lado;
    },
    perimetro: function (){
        return this.lado* this.lado;
    }
}

console.log(quadrado.perimetro(8));
