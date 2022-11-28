<br>msg = "Hello, " + "world"; // Produz a string "Hello, world"
<br>greeting = "Welcome to my blog," + " " + name;
<br>
<br>var s = "hello, world" // Começa com um texto.
<br>s.charAt(0) // => "h": o primeiro caractere.
<br>s.charAt(s.length-1) // => "d": o último caractere.
<br>s.substring(1,4) // => "ell": o 2º, 3º e 4º caracteres.
<br>s.slice(1,4) // => "ell": a mesma coisa
<br>s.slice(-3) // => "rld": os últimos 3 caracteres
<br>s.indexOf("l") // => 2: posição da primeira letra l.
<br>s.lastIndexOf("l") // => 10: posição da última letra l.
<br>s.indexOf("l", 3) // => 3: posição do primeiro "l" em ou após 3
<br>s.split(", ") // => ["hello", "world"] divide em substrings
<br>s.replace("h", "H") // => "Hello, world": substitui todas as instâncias
<br>s.toUpperCase() // => "HELLO, WORLD"

<br>
<br>s = "hello, world";
<br>s[0] // => "h"
<br>s[s.length-1] // => "d"
