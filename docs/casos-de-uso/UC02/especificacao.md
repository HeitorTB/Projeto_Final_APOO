# Criar Metas

Atores: Aluno. 

Pré-condições: O Aluno deve estar logado. Devem existir disciplinas cadastradas no sistema.

Pós-condições: Uma nova linha é criada na tabela Meta no banco de dados, associada ao ID do aluno logado.

## Fluxo Principal:
1. O Aluno acessa a opção "Minhas Metas" no menu.
2. O Aluno seleciona "Nova Meta".
3. O sistema exibe o formulário (Descrição, Data Limite, Disciplina).
4. O Aluno preenche os dados e seleciona a Disciplina associada.
5. O Aluno confirma a criação.
6. O sistema valida se os campos obrigatórios estão preenchidos.
7. O sistema salva a nova meta com status = 0 (Não iniciada) e vincula ao id_aluno e id_disciplina.
8. O sistema exibe mensagem de sucesso.

## Fluxo Alternativo:
1. Se não houver disciplinas cadastradas para selecionar, o sistema alerta "Necessário cadastrar disciplinas antes de criar metas".

## Exceções 
1. Dados Inválidos: Se a Data Limite for anterior à data atual, o sistema exibe erro de validação.




