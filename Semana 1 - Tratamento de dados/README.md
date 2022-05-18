# Como foi na prática a primeira semana

A primeira semana foi destinada a limpeza dos dados, com o compartilhamento das atividades via Trello com a visão Kanban. 

- Primeiro foi necessário extrair o arquvivo JSON via API e normalizar ele para um Dataframe que poderíamos manipular (a base JSON está disponível no arquivo "arquivos iniciais")
- Após isso, entendemos quais as informações tinhamos e também os tipos de cada dado.
- Visto as informações, pode-se notar inconsistências no tipo das colunas, sendo assim, foi alterado para o formato correto e também foram tratados dados nulos (vazios).
- Os dados nulos (vazios) foram localizados em uma única coluna (referente ao gasto total do indíviduo na empresa). Uma vez que só tinhamos o valor gasto mensal do cliente e que eram poucos dados (11 dados) decidi tirar eles da análise, visto que poderia enviesar o modelo posterior.
- Após o tratamento dessas inconsistências, criamos uma coluna de contas diárias (sendo o valor por mês/30) e também renomeamos as colunas, para fazer mais sentido na análise para nós.
- Nesse arquivo você pode visualizar a base de dados limpa e também o notebook usado.
