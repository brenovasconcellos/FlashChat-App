# FlashChat-App
FlashChat-App foi desenvolvido em **_Swift_** e é um **_app iOS_** de chat moderno que permite o registro de uma conta de usuário bem como uma vez conectado o usuário poderá enviar mensagens em tempo real para outro usuário registrado no app. O app conta com diversas tecnologia e ferramentas que auxiliaram o desenvolvimento do app como Firebase, Bibliotecas de Terceiros e o framework de User Interface Cocoa Touch. 

<img src="/img/chat.png">

É importante frisar que o arquivo a ser utilizado pelo usuário, é o arquivo gerado a partir da instalação de gerenciadores de dependências a seguir: 

Flash Chat iOS13.xcworkspace:

<img src="/img/icon.png">

# Firebase 
O App conta com a tecnologia Firebase que é responsável pela autenticação do usuário, e manipulação de banco de dados através do Firestore, desta forma esta tecnologia garante a autenticação do usuário bem como armazena as mensagens que os usuários enviarem.

<img src="/img/firebase.png">

Ao entrar no app, o usuário visualizará a screen principal que lhe permitirá escolher as opções registro ou se conectar no app fazendo log in se acaso já tenha se registrado no app.

<img src="/img/flashchat.png">

Ao clicar na opção "Register" o usuário poderá se registrar com a sua conta de e-mail e uma senha que lhe permitirá ter acesso ao app.

<img src="/img/register.png">

Ao clicar na opção "Log In" o usuário poderá se conectar no app usando o seu e-mail e senha cadastrados anteriormente. Após efetuar o log in, o usuário poderá enviar mensagens em tempo real para outros usuários do app.

<img src="/img/login.png">

Além disso como mencionado anteriormente o app conta com gerenciadores de depenência iOS, Cocoapods e Swift Package Manager, os gerenciadores de dependencias são ferramentas importantes que permitem a instalação de bibliotecas de terceiros que auxiliam o desenvolvimento projeto.

<img src="/img/cocoapods.png">

<img src="/img/SwiftPackageManager.png">

A biblioteca de terceiros CLTypingLabel é uma lib que permite realizar o famoso "efeito de máquina de escrever", em outras palavras na tela de apresentação do app, a lib permite que o nome do app "⚡️FlashChat" seja exibido caractere por caractere, realiznado o efeito mencionado.

<img src="/img/CLTyping.png">

A biblioteca de terceiros IQKeyboardManager é uma lib que permite que o desenvolvedor com poucas linhas de código configure comportamentos de teclado importantes para apps de chat, permitindo a melhor experiëncia do usuário possível.

<img src="/img/IQKeyboardManager.png">

# Design Pattern
O FlashChat-App foi estruturado a partir do MVC (Model View Controller) Desing Pattern, facilitando a organização e o entendimento do App.
