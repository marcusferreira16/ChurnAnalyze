# Challenge Alura Data Science
Repositório destinado a documentar o desafio de Data Science da Alura

Inicialmente tivemos a informação que o desafio trataria de uma base de dados de churn (indice de saída/desistência) de uma empresa fictícia chamada Alura Voz e que utilizariamos o Python como ferramenta principal.

No começo do desafio, também fomos brifados do andamento que se daria ele. Dividido em 4 semanas, cada semana tinha uma tarefa diferente.

- Semana 1: destinada para a limpeza dos dados;
- Semana 2: destinada a análise exploratória/data visualization;
- Semana 3: construção de um modelo de machine learning de acordo com nosso grupo controle;
- Semana 4: Término do desafio e documentação no Github.

A base de dados inicial, bem como o dicionário das colunas podem ser encontrados no arquivo "XXX"

##

## Como foi na prática:
### Primeira Semana
A primeira semana foi destinada a limpeza dos dados, com o compartilhamento das atividades via Trello com a visão Kanban. 
- Primeiro foi necessário extrair o arquvivo JSON via API e normalizar ele para um Dataframe que poderíamos manipular.
- Após isso, entendemos quais as informações tinhamos e também os tipos de cada dado.
- Visto as informações, pode-se notar inconsistências no tipo das colunas, sendo assim, foi alterado para o formato correto e também foram tratados dados nulos (vazios).
- Os dados nulos (vazios) foram localizados em uma única coluna (referente ao gasto total do indíviduo na empresa). Uma vez que só tinhamos o valor gasto mensal do cliente e que eram poucos dados (11 dados) decidi tirar eles da análise, visto que poderia enviesar o modelo posterior.
- Após o tratamento dessas inconsistências, criamos uma coluna de contas diárias (sendo o valor por mês/30) e também renomeamos as colunas, para fazer mais sentido na análise para nós.
- A base de dados tratada pode ser encontrada no arquivo "Semana 1 - Tratamento de dados", bem como o notebook usado.
