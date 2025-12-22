# Publicar Material

Atores: Professor 

Pré-condições: Professor logado

Pós-condições: Um novo registro é criado na tabela Material, contendo o ID do professor criador.

## Fluxo Principal:
1. O Professor acessa a área "Gestão de Conteúdo".
2. O sistema lista as Matérias/Tópicos disponíveis.
3. O Professor clica em "Adicionar Material".
4. O sistema solicita: Título e descrição.
5. O Professor preenche as informações.
6. O sistema salva o material no banco de dados, registrando o id_professor atual como autor.
7. O sistema confirma a publicação.

## Exceções 
1. Campos Vazios: O sistema impede a gravação se "Título" for vazio, o sistema exibe "Campos vazios".




