var nome = prompt ('Digite o nome da aluna')
var nota1 = Number (prompt ('Digite a 1 nota'))
var nota2 = Number (prompt ('Digite a 2 nota'))
var nota3 = Number (prompt ('Digite a 3 nota'))

var media = (nota1+nota2+nota3)/3
var status = ""
 if (media>=7 && media<=10){
   status = "Aprovado"
 } else if (media>=5 && media<=6.9){
    status = "Recuperação"
 } else if (media>=0 && media<=4.9){
   status ="Reprovado"
 }else{
    status = "Fora do escopo"
 }
console.log(`A aluna ${nome} com media ${media.toFixed(2)} e está ${status}.`)


