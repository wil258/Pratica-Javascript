let nome = "João"; // Declara uma variável mutável
const idade = 25;  // Declara uma constante
var cidade = "São Paulo"; // Declara uma variável (evite usar `var`, prefira `let` ou `const`)
let numero = 10;
let texto = "20";

console.log(Number(texto));  // Converte para número
console.log(String(numero)); // Converte para string
console.log(Boolean(0));     // false
console.log(Boolean(1));     // true

if (idade >= 18) {
    console.log("Maior de idade");
} else {
    console.log("Menor de idade");
}

let status = idade >= 18 ? "Maior" : "Menor"; // Correção da palavra-chave 'let'
console.log(status);

// for tradicional
for (let i = 0; i < 5; i++) {
    console.log("Número: " + i);
}

// while
let contador = 0;
while (contador < 3) {
    console.log("Contador: " + contador);
    contador++;
}

// do while
do {
    console.log("Executa pelo menos uma vez");
} while (false);

// forEach em array
let numeros = [1, 2, 3, 4, 5];
numeros.forEach(num => console.log(num)); 

