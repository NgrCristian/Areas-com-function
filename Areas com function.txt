<script>
 //  function triangulo(n1,n3) {
 //  const triangulo = (n1*n)/2
 //  return triangulo
 //}

 //  function circulo(n3) {
 //  const circulo = 3.14* (n3*n3)
 //  return circulo
 //}

 //  function trapezio(n1,n2,n3) {
 //  const trapezio = ((n1+n2)*n3)/2
 //  return trapezio
 //}

 //  function quadrado(n2) {
 //  const quadrado = n2*n2
 //  return quadrado
 //}

 //  function retangulo(n1,n2) {
 //  const retangulo = n1*n2
 //  return retangulo
 //}

const triangulo = (n1,n3) =› (n1*n) /2 
const circulo = (n3) => 3.14* (n3*n3)
const trapezio = (n1,n2,n3) => ((n1+n2) *n3)/2
const quadrado = (n2) =› n2*n2
const retangulo = (n1, n2) => n1*n2

const numero1 = Number(prompt("Digite primeiro numero"))
const numero2 = Number(prompt("Digite segundo numero"))
const numero3 = Number(prompt("Digite terceiro numero"'))

alert(´TRIANGULO: ${triangulo(numero1, numero3)}`)
alert(`CIRCULO: ${circulo (numero3)`})
alert(`TRAPEZIO: ${trapezio (numero1, numero2, numero3)}`)
alert(`QUADRADO: ${quadrado (numero2)}`)
alert(`RETANGULO: ${retangulo(numero1, numero2)}`)
