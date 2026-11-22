1. Cores: Escrevam a cor branca de três formas diferentes. Para que serve o quarto número em rgba(0, 0, 0, 0.5)? 
Resposta: Sao #ffffff, rgb(255, 255, 255) e hsl(0, 0%, 100%). O quarto número é a opacidade, que vai de 0 a 1. Com 0.5, a cor fica meio transparente.

2. Fontes: Porque é que escrevemos font-family: "Poppins", system-ui, sans-serif; em vez de só font-family: "Poppins";? 
Resposta: Se a Poppins não carregar, o navegador usa a fonte seguinte da lista. O sans-serif no fim garante que aparece sempre uma fonte sem serifa.

3. Unidades: Qual é a diferença entre rem e em? Quantos píxeis tem um título com font-size: 1.5rem? 
Resposta: "rem" é relativo ao tamanho de letra da página enquanto que "em" é relativo ao tamanho de letra do próprio elemento ou do elemento pai. Com font-size: 1.5rem, o título tem 1,5 × 16 = 24px.

4. Box model: Expliquem, com as vossas palavras, a diferença entre padding e margin. Qual dos dois mostra a cor de fundo da caixa? 
Resposta: O padding é o espaço dentro da caixa, entre o conteúdo e a borda. A margin é o espaço fora da caixa, que a afasta das outras. É o padding que mostra a cor de fundo.

5. box-sizing: Uma caixa tem width: 300px, padding: 20px e border: 5px solid. Que largura ocupa no ecrã com content-box? E com border-box? 
Resposta: Com content-box, a caixa ocupa 300 + 20 + 20 + 5 + 5 = 350px. Com border-box, ocupa 300px, porque o padding e a borda ficam incluídos nos 300px.
