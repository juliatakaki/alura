# alura
imersão dev alura - dia 1

var nome = "Júlia"
var notaDoPrimeiroBimestre = 9.351
var notaDoSegundoBimestre = 7.968
var notaDoTerceiroBimestre = 4.563
var notaDoQuartoBimestre = 2.862

var notaFinal = (notaDoPrimeiroBimestre + notaDoSegundoBimestre + notaDoTerceiroBimestre + notaDoQuartoBimestre) / 4

var notaFixada = notaFinal.toFixed(1)

console.log("Bem vindo(a) " + nome)

if (notaFixada > 7) {
  console.log("Parabéns, você foi aprovado(a). Sua nota final é " + notaFixada)
}
else {
  console.log("Lamentamos, você não foi aprovado(a). Sua nota final é " + notaFixada)
}

//Isto é um comentário

//Revisão: 
//variáveis (lugares na memória do computador utilizadas para referenciar um valor)
//strings (palavras em aspas)
//console.log (imprime)
//tofixed (fixar quantas casas decimais irão aparecer no número)
//operações matemáticas (+ - / *)
//concatenação (linhas 11 e 12: junção de strings com variáveis)
