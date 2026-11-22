1. As Três Formas de Inclusão de CSS: Quais são as três formas de aplicar CSS a um documento HTML (inline, interno e externo) e por que razão o CSS externo é considerado a melhor prática da indústria? 
Resposta: Inline com atributo style, interno com tag <style> no <head> e externo com ficheiro .css ligado com <link> no head. O externo é melhor porque separa o conteúdo do estilo e serve para várias páginas de uma só vez.

2. Seletores de Tipo vs Classe vs ID: Expliquem a diferença prática entre um seletor de tipo (p), um seletor de classe (.destaque) e um seletor de identificador (#formulario), dando um exemplo de quando se deve usar cada um. 
Resposta: O p aplica-se a todos os parágrafos. O .destaque aplica-se aos elementos que têm essa classe e pode repetir-se. O #formulario aplica-se a um único elemento. Usa-se o tipo para estilos gerais, a classe para estilos reutilizáveis e o ID para um elemento específico.

3. Seletores Descendentes: Qual é a diferença entre a regra nav, a { ... } (com vírgula) e a regra nav a { ... } (com espaço)? 
Resposta: O "nav, a" aplica a regra ao nav e a todos os links da página. "nav a" aplica-a só aos links dentro do nav.

4. Depuração com DevTools: Como é que o separador "Styles" das Ferramentas de Programador (DevTools) ajuda um programador a identificar problemas quando uma regra de estilo não está a funcionar? 
Resposta: Ele mostra as regras aplicadas ao elemento e as que foram anuladas, e deixa testar alterações em tempo real.