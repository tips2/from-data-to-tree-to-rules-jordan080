# Machine Learning To Tree to Rules

Gerar regras a partir dos dados de forma automática pode ser um suporte para a criação da base de regras nos sistemas especialista. Para isso vamos construir um código para converter uma árvore de decisão em regras. 

Requisitos:
Criar um modelo preditivo com o algoritmo árvore de decisão e converter a árvore de decisão em regras textuais do tipo se então de forma automática.

Por exemplo se a base de dados mudar, tanto em número de observações como em número de atributos preditivos o código deve se manter o mesmo.

Utilize a base de dados disponibilizada (dataset.xls) para treinar um modelo preditivo do tipo árvore de decisão.

Em seguida gere um arquivo texto, ou uma saída no console com as regras da árovre de decisão em um formato textual de regras definido abaixo.

Formato da regra: 
SE (VAR OP VAR) ENTAO (VAR OP VALOR) (onde operador pode ser =, > ou <; VAR é o nome da varíavel ) 

Exemplo de regra:
SE FEBRE > 37 E SEXO = M ENTAO DOENÇA = GRIPE

![Arquitetura](https://github.com/giseldo/ml_to_tree_to_rules/blob/main/arquitetura.png)

OBS: Cada nó folha da árvore pode  ser uma regra
