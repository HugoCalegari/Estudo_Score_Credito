# Estudo_Score_Credito

Estudo de score de crédito para clientes de uma instituição financeira. O link para a descrição original do problema é: https://www.kaggle.com/datasets/parisrohan/credit-score-classification/data.


## Descrições iniciais

De acordo com os dados apresentados, pode-se tratar de um modelo comportamental (behavior score). Existem informações de relacionamento do cliente com a instituição financeira, por exemplo: número e o tipo de empréstimos tomado pelo cliente, proporção de uso do limite do cartão de crédito, quantidade média de pagamentos em atraso, etc. 

Trata-se de um problema de classificação multi-rótulo (*Good*, *Standard*, *Poor*). De maneira geral, instituições financeiras definem o problema como classificação binária, sendo que os MAUS possuem atrasos superiores ou iguais a X dias de atraso em um horizonte de Y meses (mob - month of book).

Vamos definir a interpretação dos rótulos como:

**Good**: clientes que não possuiram nenhum atraso na instituição financeira, para qualquer que seja o produto de crédito;

**Standard**: clientes que possuiram algum atraso, mas não superaram um limite, por exemplo, atrasos acima de 90 dias, para qualquer que seja o produto de crédito;

**Poos**: clientes que possuiram algum atraso superior ou igual a 90 dias, para qualquer que seja o produto de crédito.