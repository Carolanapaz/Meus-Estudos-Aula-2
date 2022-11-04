# Meus-Estudos-Aula-2

/*ESTRUTURA CONDICIONAL

Variáveis booleanas */

const camisetaRenanAzul = true;
const camisetaLemaoAzul = falso;

% = resto da divisão
= atribuição
== igualdade porém ignora o tipo da variavel
=== igualdade

---------------------------------------

const numero = 10;
const numeroPar = (numero % 2) === 0;

console.log(numeroPar);

---------------------------------------

const numero = 10;
const numeroPar = (numero % 2) === 0;

if (numeroPar) {
    console.log('executei');
}

---------------------------------------

const numero = 10;
const numeroPar = (numero % 2) === 0;

if (numeroPar) {
    console.log('par');
}
if (!numeroPar) {
    console.log('impar');
}

----------------------------------------

const numero = 10;
const numeroPar = (numero % 2) === 0;

if (numeroPar) {
    console.log('par');
} else {
    console.log('impar');
}

-------------------------------------

const numero = 10;
const numeroDivisivelPor5 = (numero % 5) === 0;

if (numeroDivisivelPor5) {
    console.log('SIM');
} else {
    console.log('NAO');
}

--------------------------------------

const numero = 10;
const numeroDivisivelPor5 = (numero % 5) === 0;

if (numero === 0) {
    console.log('numero invalido');
}else if (numeroDivisivelPor5) {
    console.log('SIM');
} else {
    console.log('NAO');
}

-----------------------------------------------------------------------------

/*Faça um programa para calcular o valor de uma viagem.
Você terá 5 variáveis. Sendo elas:
    1- Preço do etanol;
    2- Preço da gasolina;
    3- O tipo de combustível que está no seu carro;
    4- Gasto médio de combustível do carro por KM;
    5- Distancia em KM da viagem;
Imprima no console o valor que será gasto para realizar essa viagem.*/

const valorEtanol = 4.35;
const valorGasolina = 6.95;
const litroPorKm = 10;
const distanciaEmKm = 267;
const tipoCombustivel = 'Etanol';
const litrosConsumidos = distanciaEmKm /litroPorKm

if (tipoCombustivel == 'Etanol') {
    const valorGasto = litrosConsumidos * valorEtanol;
    console.log(valorGasto.toFixed(2));
} else {
    const valorGasto = litrosConsumidos * valorGasolina;
    console.log(valorGasto.toFixed(2));
}

---------------------------------------------------------------------------------

