# 25-webm-front-end

Exemplo do desenvolvimento de um front-end consumindo um back-end com as operações CRUD.

### Etapas

As etapas estão numeradas nas _branches_ do projeto.

### Estrutura do projeto
- [index.html]: Página inicial com botão para buscar informações (ex: autor, API, BD).

- [questoes.html]: Dashboard de questões. Lista as questões e permite navegar para inserir/editar.

- [inserir-questao.html]: Formulário para inserir nova questão (enunciado, disciplina, tema, nível e imagem via Uploadcare).

- [ver-questao.html]: Página de edição/visualização de uma questão existente (formulário semelhante ao de inserção).

- [usuarios.html]: Dashboard de usuários. Lista usuários com ações (editar/excluir) e botão para inserir.

- [inserir-usuario.html]: Formulário para inserir novo usuário (nome, e-mail, senha e imagem via Uploadcare).

- [ver-usuario.html]: Página de edição/visualização de um usuário existente (formulário para atualizar dados e imagem).

- [css/estilo.css]: Estilos principais do projeto (layout, formulários, botões e tabela).

### Observações
Os formulários usam componentes do Uploadcare (pubkey pública presente nos HTMLs) para upload de imagens.
- [Para executar localmente: abrir index.html no navegador.
