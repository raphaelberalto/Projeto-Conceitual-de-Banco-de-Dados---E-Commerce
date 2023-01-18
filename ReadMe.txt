Cliente PJ e PF: pensei na criação de duas entidades separadas, uma para pessoa física e outra para pessoa júrídica
e nesse sentido eu criei um campo dentro da entidade Cliente perguntando se é um cadastro de pessoa física ou jurídica,
com um tipo boolean (mas que o próprio SQL mudou o tipo automaticamente). Caso seja uma pessoa física, o banco de dados
deve ativar a entidade Cliente PF para preencher os dados. Senão, preenche os dados como pessoa júrídica.

Pagamento: Pensei na criação de duas entidades para dois cartões distintos e uma entidade para fazer a junção
com a tabela Cliente.

Entrega: No meu ponto de vista, fez mais sentido adicionar os campos status e código de rastreio dentro do pedido
do que criar uma nova entidade somente para esses dois atríbutos.