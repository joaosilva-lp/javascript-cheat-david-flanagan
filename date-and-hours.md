<br>var then = new Date(2010, 0, 1); // O 1º dia do 1º mês de 2010
<br>var later = new Date(2010, 0, 1, // O mesmo dia, às 5:10:30 da tarde, hora local
17, 10, 30);
<br>var now = new Date(); // A data e hora atuais
<br>var elapsed = now – then; // Subtração de data: intervalo em milissegundos
<br>later.getFullYear() // => 2010
<br>later.getMonth() // => 0: meses com base em zero
<br>later.getDate() // => 1: dias com base em um
<br>later.getDay() // => 5: dia da semana. 0 é domingo, 5 é sexta-feira.
<br>later.getHours() // => 17: 5 da tarde, hora local
<br>later.getUTCHours() // Horas em UTC; depende do fuso horário
<br>later.toString() // => "Sexta-feira, 01 de janeiro de 2010, 17:10:30 GMT-0800
// (PST)"
<br>later.toUTCString() // => "Sábado, 02 de janeiro de 2010, 01:10:30 GMT"
<br>later.toLocaleDateString() // => "01/01/2010"
<br>later.toLocaleTimeString() // => "05:10:30 PM"
<br>later.toISOString() // => "2010-01-02T01:10:30.000Z"; somente ES5
