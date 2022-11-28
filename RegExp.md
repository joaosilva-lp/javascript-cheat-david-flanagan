<br>/^HTML/ // Corresponde às letras H T M L no início de uma string
<br>/[1-9][0-9]*/ // Corresponde a um dígito diferente de zero, seguido de qualquer
// número de dígitos
<br>/\bjavascript\b/i // Corresponde a "javascript" como uma palavra, sem considerar letras
// maiúsculas e minúsculas
<br>var text = "testing: 1, 2, 3"; // Exemplo de texto
<br>var pattern = /\d+/g // Corresponde a todas as instâncias de um ou mais
// dígitos
<br>pattern.test(text) // => verdadeiro: existe uma correspondência
<br>text.search(pattern) // => 9: posição da primeira correspondência
<br>text.match(pattern) // => ["1", "2", "3"]: array de todas as correspondências
<br>text.replace(pattern, "#"); // => "testing: #, #, #"
<br>text.split(/\D+/); // => ["","1","2","3"]: divide em não dígitos
