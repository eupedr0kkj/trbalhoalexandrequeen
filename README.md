Na primeira linha do código, inserimos a constante "form" na primeira linha. Empregamos o "Documento.getElementById" para acessar o documento HTML "FormCadastro". Assim, conseguimos acessar as informações que o usuário preencher no Id. Na segunda parte do código, inserimos a constante "tabelaUsuarios" na segunda linha. O "Documento.getElementById" é utilizado para acessar o documento HTML "tabelaUsuarios", permitindo-nos acessar as informações que o usuário inserir no Id. Na mesma linha, empregamos o "getElementsbyTagName" para acessar o "tbody", o que nos possibilita fazer modificações diretamente no primeiro corpo da tabela. O número "0" é empregado para encontrar o primeiro item da coleção escolhida, neste caso, o "Tbody". Na terceira linha, a função "AdicionarUsuario" é declarada. Como o nome sugere, a função irá manipular as informações dos inputs "nome" e "email" e adicionará um novo usuário à tabela. Na quarta linha, estabelecemos uma 'const(Const) "Novalinha" vinculada à tabela "Usuários", isto é, estamos associando a "NovaLinha" à "tabelaUsuários", e utilizamos o "InsertRow()" para inserir uma nova linha na "tabelaUsuários". Na quinta e sexta linhas, estamos introduzindo duas novas colunas na "NovaLinha", criando duas novas constantes para isso, denominadas "Colunanome" e "Colunaemail". O comando "insertcell", como o nome sugere, irá inserir as "Cells" que se referem a uma célula na tabela. Como a "ColunaNome" recebeu o valor "(0)", ela é a primeira célula da tabela. Sendo "(1)" a primeira parte. Na sétima e oitava linhas, as colunas às quais atribuímos os valores "Nome" e "Email" estão sendo preenchidas. Isso foi feito através do "TextContent", que nos possibilita acessar o valor do elemento HTML e também alterar os valores. Na nona linha, utilizamos "Form.addEventListener("submit", Function(Event)" para inserir um evento no "Form". O "submit" é ativado quando o usuário preenche o formulário. Quando isso acontece, o "event" simboliza o evento que acontecerá. O evento mencionado é o "event.preventDefault()", que, conforme indicado pelo nome, é a prevenção para que o formulário não seja enviado de maneira convencional. Neste caso, quando enviamos o formulário, ele recarrega a página. Na décima e décima primeira linha, estamos registrando os valores inseridos pelo usuário nos IDs "Nome" e "Email", usando o atributo ".value" para obter os valores. Na décima segunda chamada, utilizamos a função "AdicionarUsuario", passando os valores de "Nome" e "Email", para que os dados que sejam incorporados à tabela. Finalmente, na linha décima terceira, nós apagamos todos os campos dos formulários.

