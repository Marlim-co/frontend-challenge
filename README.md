# Desafio Front-End

Construir uma SPA em React de lista de tarefas (To-Do List) usando uma stack de alta performance.

#### Dicas:

- Trabalhe pensando em:
	- Reutilização de código;
	- Adoção de padrões de projeto;
- Não é obrigado seguir as sugestões de layouts da Marlim ou as telas propostas na pasta Design. Se quiser, você pode usar até algum Design System do seu gosto (Ant Design, Material UI, Bootstrap, Tailwind CSS, etc...);
- Levamos tudo em conta: de README a commits.
- Divirta-se, construa uma solução que seja a sua cara.
- Quando terminar, criar um repositório privado no github com acesso para o usuário [@abMarlim](https://github.com/abMarlim)

#### Funcionalidades

Não há restrições quanto a plugins ou frameworks para implementação de CSS ou JS, mas você ganha um bônus se usar [NextJS](https://nextjs.org), [styled-components](https://styled-components.com) e [React Hooks](https://reactjs.org/docs/hooks-intro.html) na sua stack.

Sugerimos usar o [](http://www.mockapi.io/)  [http://www.mockapi.io/](http://www.mockapi.io/) para construir uma simples API de REST. Mas sinta-se à vontade para implementar qualquer outra solução. 

#### SPA de listagem de tarefas

- Criação de um filtro de tarefas realizadas ou não realizadas;
- Funcionalidade de visualizar tarefas por dia, semana ou mês;
- Botão de cadastro de uma nova tarefa;
- Modal (ou qualquer outra solução personalizada) para criação de tarefa com possibilidade de adicionar ou remover tags;
- Botão de remoção da tarefa;
- Botão para editar tarefa;
- Modal (ou qualquer outra solução personalizada) para edição de tarefa com possibilidade de adicionar ou remover tags;

Sugestão de atributos para um objeto _Tarefa_

- Descrição;
- Data e hora que a tarefa acontecerá;
- Previsão para duração da tarefa;
- Tempo para lembrete da tarefa;
- Data e hora da criação da tarefa.

Tente implementar o maior número de itens possíveis descritas nas funcionalidades.
Implemente conceitos mínimos de padrões de projetos.

## Quer impressionar mais?

**Na listagem de tarefas**

- A listagem poder ser apresentada com paginação ou um scroll infinito;
- Construir um campo de busca por tags;
- Busca por comparação de string (do campo de busca da tarefa) com a descrição da tarefa.

**Na listagem de tags**

- Listar as tags cadastradas
- Modal para criação de uma nova tag
- Modal para edição de uma tag
- Botão para remover a tag

## Que tal elevar um pouco mais o nível do desafio? Aceita mais essa?

**Firebase**

Crie um projeto no Firebase e utilize, **Firestore**, **Cloud Functions** e **Hosting**. Quando finalizar conceda acesso ao projeto com permissões de Editor para o email alex@marlim.co

- **Firestore**: 
  - Para armazenar as Tarefas; 
  - Para armazenar as Tags; 

- **Cloud Functions:**
  - Para criar sua API REST, com os verbos necessários para criar, ler, alterar e deletar Tarefas e Tags;
  - Para fazer a build do Next.JS utilizando [SSR](https://nextjs.org/docs/basic-features/data-fetching#getserversideprops-server-side-rendering);

- **Hosting**
  - Para armazer a build do projeto em uma URL utlizando a CDN do Firebase;
  - Para interagir com a build SSR do Next.js