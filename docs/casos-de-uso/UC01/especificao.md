#Realizar Login 

Atores: Professores e Alunos 
Pré-condições: O ator já deve estar cadastrado no sistema (existir no Banco de Dados)
Pós-condições: O ator é autenticado e redirecionado para a tela inicial correspondente ao seu perfil (Menu de Aluno ou Menu de Professor)

##Fluxo Principal:
1. O ator acessa a página inicial do sistema.
2. O sistema exibe o formulário de login solicitando E-mail e Senha.
3. O ator insere suas credenciais e confirma.
4. O sistema verifica se o e-mail existe na tabela Aluno ou Professor.
5. O sistema valida se a senha corresponde ao e-mail informado.
6. O sistema libera o acesso e carrega a sessão do usuário.

##Fluxo Alternativo (Usuário não encontrado):
1. No passo 4, se o e-mail não for encontrado em nenhuma tabela, o sistema exibe a mensagem "Usuário não cadastrado".

##Exceções 
1. Senha Incorreta: No passo 5, se a senha não bater, o sistema exibe "Senha inválida" e solicita nova tentativa.
2. Erro de Conexão: Se o banco de dados não estiver acessível, o sistema exibe erro técnico.



