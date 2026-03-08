# DESAFIO-QA-BEEDOO-2026
Qual você acredita ser o objetivo da aplicação?
Uma plataforma de cadastro de cursos e aprendizado
Quais são os principais fluxos disponíveis?
Cadastro de curso > listagem dos cursos
Quais pontos do sistema você considera mais críticos para teste?
Testar as funcionalidades do curso dentro da plataforma pois após a criação não consigo acessá-los
Link da planilha do passo a passo estruturado : https://docs.google.com/spreadsheets/d/1bYTVBB0j15LygXuveJ09LGcHR-BPJh4eSVanoNZiHWc/edit?usp=sharing

Registro de bug:
 - Curso não é excluído da plataforma após confirmação de exclusão
Acessar a plataforma em listar cursos, selecionar o curso, clicar na opção excluir curso
Pop up sobe confirmando exclusão mas o curso permananece na lista
O curso deve ser removido da plataforma e não deve mais aparecer na listagem de cursos 
Alto - Cursos que deveriam estar removidos continuam disponíveis no sistema, causar inconsistência nos dados da plataforma, causar confusão aos usuarios do sistema.
