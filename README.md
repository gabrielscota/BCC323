# Urna Eletrônica

Projeto para desenvolver uma urna eletrônica utilizando conceitos da arquitetura de software 2.
</br>UFOP - BCC323

## Construindo para Windows

#### Passo 1: Entrar no site e ler sobre o suporte para Windows
- https://flutter.dev/desktop

#### Passo 2: Instalar o Visual Studio (Não é o VSCode)
- https://visualstudio.microsoft.com/downloads/

#### Passo 3: Rodar o doctor para ver se está tudo certo
- flutter doctor

#### Passo 4: Habilitar a plataforma desejada no projeto
- flutter config --enable-windows-desktop
- flutter create --platforms=windows .

#### Passo 5: Rodar o projeto
- flutter run -d windows

## Dependências utilizadas
- Persistência de dados: [Moor](https://pub.dev/packages/moor)
- Requisições HTTP: [Dio](https://pub.dev/packages/dio)
- Gerenciamento de estados e rotas: [Get](https://pub.dev/packages/get)
- Comparação de objetos instanciados: [Equatable](https://pub.dev/packages/equatable)

## Desenvolvedores

- Gabriel Scotá Arruda
- João Paulo Prata Costa
- João Vitor Gonçalves da Silva
- Vinicius Nascimento Targa
