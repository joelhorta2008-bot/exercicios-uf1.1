Missão 3: O Relatório

Respondam às seguintes questões por palavras vossas:

A diferença entre name e id: Qual é o papel do atributo id e do atributo name num campo de formulário? O que acontece aos dados introduzidos pelo utilizador quando um campo não tem o atributo name? 
Resposta:
- O <id> é o identificador único para o navegador!
ela serve para dar "um nome exclusivo e único" ao um certo elemento da página

- O <name> é o nome que o servidor lê 
Ela serve exclusivamente no envio e processamento de dados do formulário.

- Quando introduzimos e enviamos os dados num campo que não tem o atributo <name>
todas as informações vão ser ignorados 
Porque o navegador só envia para o servidor os campos que têm o atributo <name> definido


Rótulos e acessibilidade: Porque é que colocar apenas um placeholder não substitui uma etiqueta <label>? Que comportamento útil acontece no navegador quando um utilizador clica em cima do texto de uma <label> corretamente configurada?
Resposta: 

- Colocar apenas um placeholder não substitui uma etiqueta <label> porque o <placeholder> desaparece
quando o utilizador começa a escrever, mas o <label> continua mesmo assim;
Além disso o que fica escrito no <label> é muito importante porque
é ela que vai ser lido pelos leitores de ecrã, enquanto que o <placeholder>
é apenas uma dica do oque deve ser escrito naquele campo 

- Quando o utilizador clica em cima do texto da <label>, o navegador foca automaticamente o campo de texto ou marca/desmarca a caixa de seleção correspondente, facilitando muito a navegação.




Rádios vs Checkboxes: Em que circunstâncias devemos utilizar botões de rádio (type="radio") e em que casos devemos optar por caixas de verificação (type="checkbox")? Qual é a regra técnica para que vários botões de rádio pertençam ao mesmo grupo de escolha exclusiva? 
Resposta:

- O <type="radio"> deve ser usado quando o utilizador deve escolher só
uma das opções!
Por exemplo: 
O utilizador não pode escolher dois regimes de frequências 
para o mesmo curso.

- O <type="checkbox"> deve ser usado quando o utilizador pode excolher inúmeras opcões
ou uma, ou nenhuma das opções!
Por exemplo: 
O utilizador pode escolher vários dias da semana em que 
ele estará disponível para o curso

- A regra é que todos os botões de rádio desse grupo devem ter exatamente o mesmo atributo <name>, porque é isso que diz ao navegador que eles são exclusivos entre si