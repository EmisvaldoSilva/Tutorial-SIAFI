Tutorial: Como criar uma Lista de Credores no SIAFI

Pré-requisitos

Antes de criar uma Lista de Credores (LC), certifique-se de que todos os credores que farão parte da lista possuem cadastro no SIAFI. Para isso, na linha de comando digite >CONCREDOR (consulta credor por CPF).

Caso o CPF do Credor não possua cadastro no SIAFI, deve-se inserir na linha de comando >ATUCREDOR (atualiza credor).

Se o Credor já possua cadastro, mas as informações bancárias do credor precisem ser atualizadas, volte para a tela inicial e digite >ATUDOMCRED (atualiza domicílio do credor), na linha de COMANDO. Na tela seguinte, digite o CPF e no campo OPCAO digite:

a letra I para inclusão;
a letra A para alteração;
a letra E para exclusão;
a letra R para reinclusão.

Criando uma Lista de Credores

Para criar uma LC, na tela inicial digite >ATULC na linha de COMANDO. Tecle Enter.
No campo TIPO DE PAGAMENTO, digite 1 e tecle Enter.
Em seguida, cada linha deve ser preenchida com os dados de cada credor. Na coluna CREDOR/FAVORECIDO, digite o CPF e tecle TAB. Na coluna DOMICÍLIO BANCARIO tecle F1 para carregar os dados bancários.
Se o credor possuir mais de um domicílio bancário, posicione o cursor do lado esquerdo dos dados corretos e tecle Enter.
Na coluna VALOR, digite o valor a ser recebido sem separação por vírgulas. Por exemplo, o valor 100 corresponde a R$ 1,00 e o valor 12550 corresponde a R$ 125,50. Repita os passos para inserir todos os credores na lista. Tecle Enter.
Na tela seguinte, confira todos os dados. Se estiverem corretos, no campo CONFIRMA, digite S. Tecle Enter.
Nesse momento a LC é criada. Será exibida uma mensagem de confirmação com o número gerado. Tecle Enter.
Para consultar a LC, na tela inicial digite >CONLC. Tecle Enter.
Em seguida, digite o número da LC que deseja consultar. Tecle Enter.

Copiando uma Lista de Credores

Gerada a primeira lista, é possível copiá-la para efetuar outro pagamento para os mesmos credores, podendo alterar, incluir ou excluir dados. Basta digitar na linha de comando >ATULC. Informe o número da lista a ser copiada, pressione a Tecla F4.
