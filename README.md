teste@sistema.com 369369

Policy de Doador:
Select: Using (id_usuario = auth.uid()) -> (original)

Policy de Interacao:
(id_usuario = auth.uid()) -> (original)

Observações:

- Entrar com email e senha: Ok
- Cadastrar user e entrar apareceu "Erro: Invalid login credentials" (acho que nao foi porq nao apareceu o alert)
- Cadastrar Doador: apareceu Erro: new row violates row-level security policy for table "doador"
- Cadastrar Doação: Ok, depois deu isso (Erro: insert or update on table "doacao" violates foreign key constraint "doacao_id_doador_fkey")
- Cadastrar Interação: Ok
- Deletar: seria interessante pra mim sim
- Selecionar doador: não entendi a função, poderia ser o botão editar no lugar
- Editar interação e doação: não editou nem deu erro no console
- Sair: Ok
- O usuário ficou no lugar da tabela de doadores né? Na verdade o usuário seria tipo o funcionário da Ong, e o doador é a pessoa que foi contatada pelo telefone ou email
