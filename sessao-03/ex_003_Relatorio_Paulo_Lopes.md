1. Os repositórios: Quais são os endereços dos vossos dois repositórios no GitHub (portefolio e exercicios-uf1.1)? 
Resposta: [https://github.com/LuisSDK/Portifolio.git] & [(https://github.com/LuisSDK/exercicios-uf1.1.git)]

2. O ciclo de trabalho: Expliquem, por palavras vossas, o que fazem git add, git commit e git push, e porque é que são três passos separados. 
Resposta: "O git add" escolhe  as alteracoes  que vao ser guardadas, o "git commit" grava essas alteracoes no historico local com uma mensagem, e o "git push" envia essas gravacoes para um servidor. Eles sao passos separados para controlar o que, como e quando o trabalho fica registado e visivel.

3. O texto alternativo: Que alt escreveram para a imagem dos ovos moles? Quem vai precisar desse texto? 
Resposta: Escrevi "Uma barrica de madeira pintada com flores, cheia de ovos moles". Serve para pessoas cegas que usam leitores de ecra, tambem quem navega sem imagens com internet lenta, e para motores de busca, que não veem imagens.

Rodando o git log --oneline:

PS C:\Users\user\Documents\dawfs_\exercicios-uf1.1> git log --oneline
7563980 (HEAD -> main, origin/main) Alterando o "alt" da imagem ovos-moles.
435622b Pagina de ovos moles
0c8cde7 Pagina da cidade Versao 3
a7b5da3 Exercicios das aulas 1 e 2
PS C:\Users\user\Documents\dawfs_\exercicios-uf1.1> 

A mensagem menos clara pra mim e a "a7b5da3 Exercicios das aulas 1 e 2", porque ela nao indica o que, onde e nem porque foi alterado. Alem disso ele agrupa dois commit num so. Eu melhoraria-a dividindo em dois commits como por exemplo "Adiciona exercicios da aula 1 (sessao-01)" e "Adiciona pagina da cidade (sessao-02)".