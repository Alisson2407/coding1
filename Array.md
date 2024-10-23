Pequisa a respeito do Array: Métodos interessantes;

1)Arrays.copyOf : 2 - Permite copiar um array específico, ajustando seu tamanho conforme necessário. Além disso, ele preenche o array conforme seu tipo de dados. Por exemplo, se o array for do tipo booleano, ele será preenchido com false, se for do tipo numérico, será preenchido com zeros e se for do tipo char, será preenchido com nulos. 

2) Remoção do último item de uma lista :

var ultimo = frutas.pop(); // remove Laranja (do final)
 ['Maçã', 'Banana'];

3) Busca por intem específico no índice :
frutas.push("Manga");
// ['Morango', 'Banana', 'Manga']

var pos = frutas.indexOf("Banana");
// 1
4) Remove intens do índice
var vegetais = ["Repolho", "Nabo", "Rabanete", "Cenoura"];
console.log(vegetais);
// ['Repolho', 'Nabo', 'Rabanete', 'Cenoura']

var pos = 1,
  n = 2;

var itensRemovidos = vegetais.splice(pos, n);
// Isso é como se faz para remover itens, n define o número de itens a se remover,
// a partir da posição (pos) em direção ao fim da array.

console.log(vegetais);
// ['Repolho', 'Cenoura'] (o array original é alterado)

console.log(itensRemovidos);
// ['Nabo', 'Rabanete']

5) Copia uma Array
var copiar = frutas.slice(); // é assim que se copia
// ['Morango', 'Manga']



