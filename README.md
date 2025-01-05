Sistema de Login em Java
Descrição
Este projeto é um sistema simples de Login desenvolvido em Java. A aplicação solicita o nome de usuário e senha e valida se os dados informados são corretos. O sistema possui um usuário e senha padrão para autenticação. Caso as credenciais estejam corretas, uma mensagem de sucesso será exibida, caso contrário, o sistema informará que as credenciais estão incorretas.

Este tipo de

Funcionalidades
Autenticação: Permite que o usuário entre no sistema usando um nome de usuário e senha.
Validação de Credenciais: Compara as credenciais fornecidas com as configuradas no código.
Mensagem de Sucesso ou Falha: Informa ao usuário se o login foi bem-sucedido ou se houve falha na autenticação.
Tecnólogos
Java 8+: A linguagem de programação utilizada para desenvolver a aplicação.
Scanner: Biblioteca utilizada para capturar entradas do usuário no console.
Como Executar o Projeto
Pré-requisitos
Certifique-se de ter o Java instalado no seu sistema.
Você pode verificar se o Java está instalado executando o seguinte comando:

bater

Copiar código
java -version
Se o Java não estiver instalado, você pode obter a versão mais recente no site oficial: https://www.oracle.com/java/technologies/javase-jdk11-downloads.html

Passos para Executar
Clone o Repositório: Se você ainda não fez isso, clone este repositório para o seu ambiente de desenvolvimento local:

bater

Copiar código
git clone https://github.com/Romeropedro1/LoginSystem.git
cd LoginSystem
Compilação e Execução:

Abra o terminal ou prompt de comando na pasta onde o código está salvo e execute os seguintes comandos:

Compilar o código Java:

b

Copiar código
javac LoginSystem.java
Executar o código compilado:

bater

Copiar código
java LoginSystem
Interação com o Sistema:

Irmã
Tente inserir o nome de usuário como admin e a senha como password para um login bem-sucedido.
Estrutura do Código
O código possui uma classe chamada LoginSysten que contém o método main, o qual executa o fluxo principal da aplicação.

Scanner : Usad
Verificação de Login: A comparação das credenciais fornecidas com as credenciais definidas no código (admine `senhapassword).
Mensagens: Exibe mensagens de sucesso ou erro de autenticação no console.
Exemplo de Execução
Ao executar o código, o terminal exi

Login bem-sucedido:

texto

Copiar código
Digite o nome de usuário: admin
Digite a senha: password
Login bem sucedido.
Falha no login:

texto

Copiar código
Digite o nome de usuário: admin
Digite a senha: senhaerrada
Nome de usuário ou senha incorretos.
Melhorias Futuras
Este sistema pode ser expandido para incluir:

Armazenamento em banco de dados: Para permitir múltiplos usuários e senhas.
Criptografia de senhas: Para garantir que as senhas sejam armazenadas de forma segura.
Interface Gráfica (GUI): Utilizar frameworks como Swing ou JavaFX para criar uma interface mais amigável.
Autenticação com múltiplas tentativas: Bloquear o acesso após um número definido de tentativas incorretas.
Contribuição
Se você deseja contribuir para o projeto, fique à vontade para abrir um pull request com melhorias ou correções de bugs. Certifique-se de que suas mudanças não quebrem a funcionalidade existente e que tudo esteja bem documentado.

Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENÇA .


