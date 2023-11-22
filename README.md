


Nome do App: 📦 Gerenciador de Estoque Simples 📱

Descrição:
Este aplicativo é um gerenciador de estoque que permite ao usuário adicionar, visualizar, editar e excluir itens do estoque. Ele utiliza a biblioteca Room para armazenar os dados localmente no dispositivo. 📝

Funcionalidades:

Adicionar Item: ➕ Permite ao usuário adicionar um novo item ao estoque com nome, quantidade e detalhes.
Visualizar Itens: 👀 Lista todos os itens presentes no estoque.
Editar Item: ✏️ Permite ao usuário editar o nome, quantidade ou detalhes de um item existente.
Excluir Item: ❌ Permite ao usuário remover um item do estoque.
Tecnologias Utilizadas:

Kotlin: 🧑‍💻 Linguagem de programação principal.
Android Room: 🗄️ Biblioteca de persistência de dados que oferece uma camada de abstração sobre SQLite.
Arquitetura MVVM: 🏗️ Utilização do padrão de arquitetura Model-View-ViewModel para separação de responsabilidades.
Passos Básicos de Implementação:

Crie um projeto Android usando o Android Studio. 🛠️
Adicione as dependências necessárias para a Room no arquivo build.gradle. 📦
Crie uma entidade que represente a estrutura de um item no estoque. 📑
Crie um Data Access Object (DAO) para realizar operações CRUD (create, read, update, delete) no banco de dados. 🔄
Crie um banco de dados utilizando a classe RoomDatabase. 🏦
Implemente as funcionalidades do aplicativo (adicionar, listar, editar, excluir itens) utilizando a Room em conjunto com a arquitetura MVVM. 📲

©Feito por Gabriel Messias 
Projeto para a Aula de Pam
