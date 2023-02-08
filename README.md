# React-Firebase-CRUD

Este repositório contém uma implementação de um componente React que permite o CRUD (Criar, Ler, Atualizar e Deletar) de dados de usuários com o Firebase. Utiliza a biblioteca Firebase SDK para conectar ao banco de dados Firestore e implementar as funcionalidades descritas acima.

Instalação

Para utilizar este componente em seu projeto, você precisará ter uma conta no Firebase e criar um novo projeto. Depois, você precisará instalar as dependências necessárias, incluindo o Firebase SDK e o React:

npm install firebase react

Uso

O componente pode ser importado em seu projeto React e utilizado como qualquer outro componente. Ele se conecta automaticamente ao seu banco de dados Firestore ao ser inicializado e carrega uma lista de usuários da coleção "users".

import ReactFirebaseCrud from './ReactFirebaseCrud';

function App() {
  return (
    <div>
      <ReactFirebaseCrud />
    </div>
  );
}

export default App;

Funcionalidades

Recupera uma lista de usuários da coleção "users" do Firestore e armazena no estado users
Possui dois campos de entrada para o nome e o email de um usuário
Botão "Criar usuário" que adiciona um novo usuário à coleção "users" do Firestore ao ser clicado
Botão "Excluir" para cada usuário que exclui o usuário correspondente da coleção "users" do Firestore quando clicado
Contribuição
Se você deseja contribuir para este projeto, fique à vontade para abrir uma pull request com suas alterações. Todas as contribuições são bem-vindas e serão cuidadosamente avaliadas.
