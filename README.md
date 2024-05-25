# desafio-classificador-nivel-heroi
Esse repositório é do meu desafio de lógica de programação
let nomeHeroi = "Jão, o matador" , classification = ""
let xp = 0 , adventure = 0

 adventure= 8

for (let i = 0; i < adventure; i++) {
  xp += 1000

}
if (xp <= 1000) {
  classification = "Ferro"
}else if (xp > 1000 && xp <= 2000) {
  classification = "Bronze"
  
}else if (xp > 2000 && xp <= 5000) {
   classification = "Prata"
}
else if (xp > 5000 && xp <= 7000) {
   classification = "Ouro"
}else if (xp > 7000 && xp <= 8000) {
   classification = "Platina"
}
else if (xp > 8000 && xp <= 9000) {
   classification = "Ascendente"
}
else if (xp > 9000 && xp <= 10000) {
   classification = "Imortal"
}
else {
   classification = "Radiante"
}
console.log ("O herói de nome "+ nomeHeroi + " está no nível de "+classification)
