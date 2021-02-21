# desafioAvancadoJava
Desafio Avancado em 

//Inicio


Positivos e Negativos

let valores = [];
let pares = 0;
let negativos = 0;
let positivos = 0;
let impares = 0;
for(i = 0; i<5; i++){
 valores.push(gets());
}
valores.forEach(el =>{
 if(el%2===0){
  pares +=1;
 }else{
  impares +=1;
 }
 if(el>0){
  positivos+=1;
 }else if(el<0){
  negativos +=1;
 }
})
console.log(pares + " valor(es) par(es)");
console.log(impares + " valor(es) impar(es)");
console.log(positivos + " valor(es) positivo(s)");
console.log(negativos + " valor(es) negativo(s)");


