# DESAFIO-QA-BEEDOO-2026
Análise da aplicação
Objetivo da aplicação

A aplicação tem como objetivo permitir o gerenciamento de cursos dentro de uma plataforma educacional. O sistema possibilita que usuários realizem o cadastro e a visualização de cursos, facilitando a organização e administração das informações relacionadas aos cursos disponíveis.

Através da aplicação, é possível registrar novos cursos, armazenar seus dados e disponibilizá-los para consulta na listagem de cursos. Dessa forma, o sistema atua como uma ferramenta de controle e gerenciamento de conteúdos educacionais.

Principais fluxos disponíveis

Com base na análise da aplicação, foram identificados os seguintes fluxos principais:

1. Cadastro de cursos

Este fluxo permite que o usuário registre um novo curso no sistema.

Passos principais do fluxo:

Acessar a página de cadastro de cursos

Preencher os campos obrigatórios do formulário

Enviar os dados através do botão de cadastro/salvar

O sistema realiza validações dos dados inseridos

Caso os dados estejam corretos, o curso é cadastrado no sistema

Esse fluxo é essencial para alimentar a base de cursos da aplicação.

2. Listagem de cursos

Esse fluxo permite visualizar todos os cursos cadastrados no sistema.

Passos principais do fluxo:

Acessar a página de listagem de cursos

O sistema consulta os cursos cadastrados

Os cursos são exibidos em uma lista ou tabela

Esse fluxo permite que o usuário consulte as informações dos cursos disponíveis.

3. Validação de dados no cadastro

Durante o processo de cadastro, o sistema deve validar as informações fornecidas pelo usuário.

Entre as validações esperadas estão:

Verificação de campos obrigatórios

Validação de formatos de dados

Bloqueio do envio de formulários incompletos

Exibição de mensagens de erro quando necessário

Esse fluxo garante a integridade e qualidade dos dados armazenados.

Pontos críticos do sistema para teste

Durante a análise da aplicação, alguns pontos foram considerados mais críticos e merecem maior atenção durante os testes.

Cadastro de cursos

O cadastro de cursos é um dos fluxos mais importantes do sistema, pois envolve a inserção e armazenamento de dados. Problemas nesse fluxo podem comprometer a confiabilidade das informações cadastradas.

Principais riscos:

Falhas na validação de campos obrigatórios

Cadastro de cursos com dados inválidos

Erros no envio ou salvamento do formulário

Validação de campos

As validações de campos são fundamentais para garantir que os dados inseridos estejam corretos.

Pontos de atenção:

Campos obrigatórios aceitando valores vazios

Falta de mensagens de erro para o usuário

Validações inconsistentes ou incompletas

Persistência de dados

Após o cadastro de um curso, é importante garantir que os dados sejam corretamente armazenados no sistema.

Possíveis problemas:

Curso não sendo salvo corretamente

Dados sendo salvos de forma incorreta

Informações não aparecendo na listagem

Listagem de cursos

A listagem de cursos é responsável por apresentar os dados cadastrados ao usuário.

Riscos associados:

Cursos não sendo exibidos na lista

Dados inconsistentes ou incompletos

Problemas de carregamento da lista

https://drive.google.com/drive/folders/1cZviINY2o9fKqlM97mdQwoyq0uzxHnI7?usp=drive_link
