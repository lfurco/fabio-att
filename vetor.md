# fabio-att

programa {
  funcao inicio() {
    inteiro a[20] , b[20], soma = 0 , i

  //preencher
    para( i = 0; i < 20; i++ ) {        // escolhe 20 numero aleatorios   ||   percorrer as posições 
      a[i] = i * 2 + 3 // atribui valor aos 20 numeros

      se(a[i] % 2 == 0) {
        b[i] = a[i] * 2     // dobro
      } senao {
        b[i] = a [i] * a [i]        // quadrado
      }
    }
    para( i = 0; i < 20; i++ ) {        // mostra o resultado dos 20 numeros  ||  percorrer as posições dos resultados

      escreva("\n ", a[i], "  ", b[i])
  } 
}
}
