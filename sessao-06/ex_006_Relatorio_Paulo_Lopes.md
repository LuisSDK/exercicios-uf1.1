1. A diferença entre name e id: Qual é o papel do atributo id e do atributo name num campo de formulário? O que acontece aos dados introduzidos pelo utilizador quando um campo não tem o atributo name? Resposta: O id identifica o campo na página. Ele é unico e liga o campo à <label>. O name é o nome com que o valor é enviado ao servidor. Se um campo não tiver name, o que o utilizador escreve não é enviado.

2. Rótulos e acessibilidade: Porque é que colocar apenas um placeholder não substitui uma etiqueta <label>? Que comportamento útil acontece no navegador quando um utilizador clica em cima do texto de uma <label> corretamente configurada? 
Resposta: O placeholder desaparece quando começamos a escrever e nem sempre é lido pelos leitores de ecrã. A <label> está sempre visível. Clicar no texto de uma <label> coloca o cursor no campo, ou marca o botão de rádio ou a caixa de verificação.

3. Rádios vs Checkboxes: Em que circunstâncias devemos utilizar botões de rádio (type="radio") e em que casos devemos optar por caixas de verificação (type="checkbox")? Qual é a regra técnica para que vários botões de rádio pertençam ao mesmo grupo de escolha exclusiva? Resposta: Usamos rádio quando só podemos escolher uma opção, e checkbox quando podemos escolher várias, ou nenhuma. Para os rádios formarem um grupo, todos têm de ter o mesmo name.


