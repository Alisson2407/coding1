* Os primeiros pontos , foram a respeito da programação em si o que é ?  e para quê serve? algoritmos e suas representações atravées de fluxogramas o que ilustra a tomada de decisão, além de, da lógica na qual usamos para formular códigos dos mais simples ao mais complexo;
  
* Outros pontos que foram explanados como os  tipos primitivos e  variáveis(let,const,var) e strings..... ;

* Aprendemos alguns comandos que envolviam operações matemática como (*,-,/,+,%) além de como imprimir frases na tela como "Olá mundo";
 Exemplo 01: Um código que soma e depois divide

nota1 =8;
const nota2 =6;
const nota3 =10;
const media = (nota1 + nota2 + nota3)/3;

console.log(`Sua média é: ${media}`)

 Exemplo 02:Um código com as 04 operações básicas

  const num1= 500
 const num2= 20 
 console.log (num1+num2)
 console.log (num1-num2)
 console.log (num1/num2)
 console.log (num1*num2)

* Nas primeiras aulas tivemos a oportunidade de aprender os conceitos básicos da lógica de programação com alguns comandos como (if,else,else if,Switch...) ;
  Exemplo Switch case :
  let nome = prompt("Qual seu nome?");
let filme = prompt("Escolha o filme: Vingadores ou Pantera Negra?").toLowerCase();

switch(filme) {
  case "vingadores":
    console.log(`${nome},O filme Vingadores para ser alugado custa 30,00 reais.`);
    break;
  case "pantera negra":
    console.log(`${nome}, o filme Pantera Negra para ser alugado custa 25,00 reais.`);
    break;
  default:
    console.log("Desculpe, não existe essa opção.");
    break;
}

Exemplo If else:let Saude=prompt("Opção1:Consulta,Opção2:Volta ao médico,Opção 3:Novo exame")


if (Saude==1){
  console.log("Você escolheu consulta");
}else if (Saude==2){
  console.log("Você escolheu Volta ao médico")
} else {
  console.log("Você escolheu novo exame")
}

* Avançamos no conteúdo e começamos a aprender estrutura condicionais contendo os principais sinais (>,<,=);
  Exemplo : Código que utiliza uma condição para que o aluno seja Aprovado ou reprovado.

   const nota = 3
const resultado = (nota>=7)?'Aprovado':'Reprovado'
console.log(resultado)

* O próximo assunto foi Array onde foi possível instalar várias váriaveis em um espaço que contado por posição  tivemos exempos como de uma livraria onde existe uma área para cada tema de livro e uma estante para cada determinado genêro de livro se assemelhando a uma array;
Exemplo de Array:let frutas=["Apple","Orange","Bannana"]
//console.log(frutas.pop())

 let frutas= ["Apple","Orange","Bannana"]
 let inserir = prompt ("Digite a fruta para inserir:")
 console .log(frutas.push (inserir))
console.log(frutas)
 
let frutas= ["Apple","Orange","Bannana,Grapes"]
console.log(frutas)

let compras= prompt ("Apple,Orange,Bannana,Grapes,Escolha as frutas que vão para seu carrinho")
console.log(compras)

* Chegando ao assunto de Função onde apredemos diversas forma de aplicar a mesma função além de outras funções que possuem suas particularidades.
  Exemplo de Função:

  function mediaMat (prova ,redacao){
  return (prova + redacao)/2
}
console.log(mediaMat(10,5));

function dobro(num){
  return num*2
}

function calcularMedia (nota1,nota2,nota3){
  const soma= (nota1+nota2+nota3)
  const media = soma/3
  return media

}

function ordenar(a,b)
{
  if(a <= b){
    return[a,b]
  }else{
    return[b,a]
  }
}
console.log(ordenar(9,7))

*Por fim chegamos ao assunto de Objetos onde aprendemos tivemos alguns exempllos a respeito de cadastro por exemplo onde se podia por nome,mátricula telefone etc...
Exemplo de Objeto:
const estudante={
  nome:"Alisson",
  idade:23,
  matricula:"20010724",
}

console.log(estudante.nome);
 console.log(estudante["matricula"]);

console.log(`Meu nome é ${estudante.nome} e tenho ${estudante.idade} anos.`);

console.log(estudante.matricula.substring(0,3));

for (const key in estudante){
  console.log(estudante[key]);
}

estudante.matricula="24072001"
estudante.fones=["87456932","12453698"];
console.log(estudante);


estudante .curso="front-end";
estudante.fones=["65369878","45698712"]

 const estudante={
  nome:"Alisson",
  idade:23,
  matricula:"168421354",
}
 alert("Boas vindas !")
const escolha=prompt("Digite 1, para  adicionar ,Digite 2, para remover.")

if (escolha === "1"){
  console.log(adicionar())

}
  
 function remover() {
  const chave = prompt("Informe a chave que deseja remover");
  
  if (estudante.hasOwnProperty(chave)) {
    delete estudante[chave];
    return `A chave '${chave}' foi removida com sucesso!`;
  } else {
    return `A chave '${chave}' não foi encontrada no objeto.`;
  }

const estudante = {
  nome: "Alisson",
  idade: 23,
  matricula: "168421354",
};

alert("Boas vindas!");
const escolha = prompt("Digite 1 para adicionar, ou 2 para remover.");

if (escolha === "1") {
  console.log(adicionar());
} else if (escolha === "2") {
  console.log(remover());
} else {
  console.log("Opção inválida.");
}


function adicionar() {
  const chave = prompt("Informe a chave que deseja adicionar");
  const valor = prompt(`Informe o valor para a chave '${chave}'`);

  if (chave) {
    estudante[chave] = valor;
    return `A chave '${chave}' foi adicionada com sucesso!`;
  } else {
    return "Chave não informada.";
  }
}

function remover() {
  const chave = prompt("Informe a chave que deseja remover");

  if (estudante.hasOwnProperty(chave)) {
    delete estudante[chave];
    return `A chave '${chave}' foi removida com sucesso!`;
  } else {
    return `A chave '${chave}' não foi encontrada no objeto.`;
  }
}




* Além do que já foi exposto acima aprendemos o básico de como  usar o Github e de  como personalizado também aprendemos os seus comandos mais comuns além de fazer buscas por githubs já desevolvidos com materias interessantes sobre a programação etc...
