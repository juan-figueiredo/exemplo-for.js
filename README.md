// exemplo-for.js

// Utilizando for para imprimir números de 1 a 5
console.log("Usando for para imprimir números de 1 a 5:");
for (let i = 1; i <= 5; i++) {
  console.log(i);
}

// Utilizando for para percorrer um array
console.log("\nUsando for para percorrer um array:");
const frutas = ['Maçã', 'Banana', 'Laranja', 'Morango'];
for (let i = 0; i < frutas.length; i++) {
  console.log(frutas[i]);
}

// Utilizando for-in para iterar sobre propriedades de um objeto
console.log("\nUsando for-in para iterar sobre propriedades de um objeto:");
const carro = {
  marca: 'Toyota',
  modelo: 'Corolla',
  ano: 2022
};

for (let propriedade in carro) {
  console.log(`${propriedade}: ${carro[propriedade]}`);
}
