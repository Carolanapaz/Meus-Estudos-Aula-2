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
