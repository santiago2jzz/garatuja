Garatujas - Daniel Santiago Mendonça
HTML: Html é uma linguagem de marcação, onde ele serve para estrutuar o site.

Css: Css serve para dar uma "maquiagem" para o site. Ele é quem faz a interface para o site.

===================================================================================================================================================================

#Js (JavaScript) vs Ts(Type Scipt) Vs Jv(Java)

COMO CRIAR UMA FUNÇÃO

JS: Para criar uma função em JavaScript, utilize a palavra-chave function, seguida de um nome, parênteses () para parâmetros opcionais e chaves {} para o corpo da função. A lógica é colocada dentro das chaves e a função pode retornar um valor com return.

// Exemplo: Função de soma function somar(a, b) { return a + b; }

// Como chamar a função let resultado = somar(5, 3); // Retorna 8 console.log(resultado);

TS:Para criar uma função em TypeScript, defina o nome, os tipos dos parâmetros e o tipo de retorno, utilizando function ou arrow functions () => {}. A sintaxe principal exige (parametro: tipo): tipoRetorno. O compilador verifica erros de tipo automaticamente.

// Exemplo de função tradicional function somar(a: number, b: number): number { return a + b; }

// Exemplo de Arrow Function const subtrair = (a: number, b: number): number => a - b;

console.log(somar(5, 3)); // Saída: 8

Jv:Para criar uma função (método) em Java, defina seu modificador de acesso (ex: public), tipo de retorno (ex: void ou int), nome, parâmetros entre parênteses e o bloco de código {}. Métodos devem ter responsabilidade única e, preferencialmente, serem descritivos, como public int somar(int a, int b) { return a + b; }.

modificadorRetorno nomeDaFuncao(parametros) { // Corpo do método // return valor; // Necessário se não for void }

===========================================================================================================================================================

JS: FUNCTION Em JavaScript, uma função é um bloco de código reutilizável que executa uma tarefa quando é chamado. function saudar() { console.log("Olá, bem-vindo!"); } Method Um método é uma função que está associada a um objeto e pode acessar ou modificar os dados desse objeto. const carro = { marca: "Ford", buzinar: function() { console.log("Beep beep!"); } };

variable Uma variável é um espaço na memória usado para armazenar dados que podem ser alterados durante a execução do programa. let idade = 25;

attribute Um atributo é uma propriedade de um objeto que armazena um valor ou característica relacionada a ele. const botao = document.querySelector('button'); botao.setAttribute('data-id', '123');

================================================================================================================================================================

JAVA: Function Em Java, o termo “função” geralmente é chamado de método, sendo um bloco de código que executa uma tarefa específica quando invocado. public class Calculadora { // Função que recebe dois inteiros e retorna a soma public int somar(int a, int b) { return a + b; }

public static void main(String[] args) {
    Calculadora calc = new Calculadora();
    int resultado = calc.somar(5, 10); // Chamada da função
    System.out.println("Soma: " + resultado); // Saída: Soma: 15
}
}

Method Um método é uma função definida dentro de uma classe que pode manipular dados e comportamentos dos objetos dessa classe. public int somar(int a, int b) { return a + b; }

variable Uma variável é um espaço de memória nomeado usado para armazenar valores que podem ser utilizados e alterados durante a execução do programa. int numero = 10; String saudacao = "Olá Mundo"; double valor = 50.50; boolean isJavaFun = true;

attribute Um atributo é uma variável declarada dentro de uma classe que representa as características ou estados de um objeto. public class Carro { // Atributos de instância private String marca; private int ano;

// Atributo estático
public static int totalCarros;

// Construtor
public Carro(String marca, int ano) {
    this.marca = marca;
    this.ano = ano;
    totalCarros++;
}
}

====================================================================================================================================================================

TS:

Function Em TypeScript, uma função é um bloco de código tipado que executa uma tarefa específica e pode receber parâmetros e retornar valores. // função com tipagem de parâmetros e retorno function somar(a: number, b: number): number { return a + b; }

// Arrow function com retorno implícito const subtrair = (a: number, b: number): number => a - b;

Method Um método é uma função definida dentro de uma classe ou objeto que opera sobre os dados internos dessa estrutura. // Método comum saudar(saudacao: string): string { return ${saudacao}, ${this.nome}!; }

// Método sem retorno logNome(): void { console.log(this.nome); } }

Variable Uma variável é um identificador que referencia um valor na memória, podendo ter seu tipo explícito ou inferido pelo TypeScript.Precisa definir o tipo, diferente do JS let nome: string = "João";

Attribute Um atributo é uma propriedade de uma classe ou objeto que armazena valores e pode ter um tipo definido. class Produto { public nome: string; private preco: number; readonly id: number;

constructor(nome: string, preco: number, id: number) {
    this.nome = nome;
    this.preco = preco;
    this.id = id;
}
}

=========================================================================================================================================================================

GET E SET

Get: Usado para ler o valor de uma propriedade. Set: Usado para alterar o valor de uma propriedade.

class Pessoa { private _idade: number = 0;

get idade(): number { return this._idade; }

set idade(novaIdade: number) { if (novaIdade < 0) { throw new Error("Idade não pode ser negativa"); } this._idade = novaIdade; } }

=========================================================================================================================================================================

DIFERENÇA ENTRE METODO E FUNÇÃO

funções são blocos de código independentes chamados pelo nome, enquanto métodos são funções associadas a um objeto ou classe

const pessoa = new Pessoa(); pessoa.idade = 25; // Chama o set console.log(pessoa.idade); // Chama o get

const srv = Bun.serve({ port: 8080, routes: { "/wspeed": () => new Response(
<a href='https://www.reddit.com/r/brasilivre/comments/klpyrk/goku_careca/'>clica</a> , { headers: { "Content-Type": "text/html"}} ) } , fetch(request) { return new Response("67", {headers: {'content-Type': "text/html"}}) }

})
