let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 },
 {
   nome: "Fernando Puntel",
   notas:  [8, 10, 10, 7, 9.33]
 },
 {
   nome: "Daiane Jelinsky",
   notas: [7, 10, 9.5, 9.5, 8]
 },
 {
   nome: "Bruno Castro",
   notas: [10, 10, 10, 9, 9.5]
 }
];

function mediaAtletas(atletas) {
for (let i = 0; i < atletas.length; i++){
     let notasComputadas = [...atletas[i].notas].sort((a, b) => a - b);
     notasComputadas = notasComputadas.slice(1, 4);
     notasComputadas = notasComputadas.reduce(function(total, atual) {
         return total + atual;
     }, 0);
     notasComputadas = notasComputadas / 3;
     console.log(`
     Atleta: ${atletas[i].nome}
     Notas Obtidas: ${atletas[i].notas}
     Média Válida: ${notasComputadas}
     `)
  }
}

mediaAtletas(atletas)
