# Curso Flutter
Esse projeto tem como objetivo, armazenar as aulas do curso de flutter a medida em que vou estudando.

# Documentação
* Dart - https://dart.dev/
* Flutter - https://flutter.dev/
* Material Design - https://material.io/design/

# Aplicativo 1 - Contador de Pessoas.

Foram utilizados nesse aplicativo os seguintes widgets:

* StateFulWidget - Para utilizar o Hot Reload
* Stack - Para Utilizar um component em cima de outro como layout
* Children - Quando um widget contém vários filhos é necessário utilizar isso
* Image.Asset - Utilização de imagens no aplicativo
* fit - Para ajustar tamanho da imagem
* Adição de assets e pasta de imagens
* Column - Utilizado como o LinearLayout de forma vertical
* alinhamento no centro com mainAxisAligment
* Text - Texto padrão na tela é um label ou como se fosse o texview
* Row - Utilizado como o LinearLayout de forma horizontal
* Padding - Para regular espaçamentos entre widgets
* FlatButton - Botões sem fundo

# Aplicativo 2 - Cálculo do IMC.

Foram utilizados nesse aplicativo os seguintes widgets:

* TextFormField - Igual ao EditText mas com validações utilizando formulários
* TextEditingController - Controlador de TextField e TextFormField para não precisar set o estado do widget a todo momento ele fica funcionando de forma totalmente dinâmica
* GlobalKey - Utilizado para validações no formulário e verificar erros
* double.parse - Para converter valores em double
* Scaffold - Layout mais robusto com utilização de barra do app e tambem botões, alem do funcionamento normal do container
* AppBar
* IcpnButton - Botão com ícone utilizado na AppBar
* SingleChildScrollView - Barra de rolagem do aplicativo com apenas 1 filho
* Form - Utilizado para validações
* RaisedButton - Botão normal com fundo
* EdgeInserts.fromLTRB - padding onde seta os valores de cada lado
* EdgeInserts.only - padding onde seta os valores que se quer
* keyboardType - seta o tipo de dado em que pode ser digitado no TextField ou TextFormField
* TextInputType.number - Utilizado para um tipo de campo de texto com apenas numeros

# Aplicativo 3 - Conversor de Moedas.

Foram utilizados nesse aplicativo os seguintes widgets:

* Consumindo dados de apis na internet;
* Utilização de biblioteca html adicional no arquivo pubspec.yaml;
* Biblioteca async - para esperar dados de chamadas assincronas de outros locais;
* Biblioeca convert - para converter dados utilizado no caso do projeto de String para Json;
* ThemeData - Para personalizar o tema do app;
* Utilização de bordas personalidades nos TextField;
* FutureBuilder<Map> - Conseguir requisições de apis com resposta como map;
* future - Buscar dados de chamada assincrona e instanciar no FutureBuilder<Map>;
* builder - com contexto e snapshot para busca de dados e verificacão de erros da api para o app;

# Aplicativo 4 - Lista de Tarefas.

Foram utilizados nesse aplicativo os seguintes widgets:

* Map<String, dynamic> - Utilizado normalmente para pegar jsons com o título e o valor de cada componente do json
* Expanded - Expande o widget child at´quanto der para nao quebrar a tela
* RefreshIndicator - Refresh puxando a tela de cima pra baixo ou baixo pra cima
* Future.delayed - Delay utilizado com o Duration para esperar uma quantidade de tempo especificada
* sort - Busca utilizada na lista padrão do Dart;
* File - Arquivo
* getApplicationDocumentsDirectory - função que retorna a localização do diretório de documentos da aplicação
* Dismissible - Component para puxar itens de lista para laterais e fazer determinada ação
* CheckboxListTile - Lista com checklist integrada
* CircleAvatar - Imagem com moldurade círculo
* SnackBar - Barra utilizada no final da tela para mostrar mensagens ou com botões e ações
* SnackBarAction - Ação de botão integrado na SnackBar
* Duration - Seta uma duração em vários tipos de unidades temporárias como, milisegundo, segundo...
* file.writeAsString - Escrita de String em arquivo;
* file.readAsString - Leitura de String de arquivo
* initState - Método sobre escrito que é executado quando o aplicativo é iniciado

# Aplicativo 5 - Buscador de GIFs.

Foram utilizados nesse aplicativo os seguintes widgets:

* Separação de telas do aplicativo e sendo chamadas com Navigator.push
* GridView - layout do tipo tabela e suas respectivas configurações
* GestureDetector - para pegar tipos de gestos on cliues nos widgets e tomar ações diferentes.
* Share - Para compartilhamento de qualquer coisa do aplicativo.
* Image.network - Para trabalhar com imagens da internet.

# Aplicativo 6 - Agenda de Contatos.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 7 - Chat Online (Firebase).

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 8 - Loja Virtual.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 9 - Animações Vetoriais com Flare.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 10 - Favoritos do YouTube (BLoC Pattern).

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 11 - Animações Complexas.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 12 - App Gerenciamento da Loja Online.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 13 - Integração com Código Android Nativo.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 14 - XLO Clone.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 15 - Adicionando Anúncios com AdMob.

Foram utilizados nesse aplicativo os seguintes widgets:

# Aplicativo 16 - Adicionando Maps ao App.

Foram utilizados nesse aplicativo os seguintes widgets:
