# DESAFIO-QA-BEEDOO  

Funcionalidade:*Listagem cursos cadastrados*   

Como usuário  

eu quero listar cursos cadastrados  

para conseguir acessar os cursos.    


Critérios de aceitação:  

O usuário pode navegar até a aba "Listar Cursos".
O sistema deve exibir uma lista de todos os cursos cadastrados.
A lista de cursos deve incluir informações básicas, como:
Nome do curso
Descrição do curso
Data de início
Duração
Quantidade de vagas  

Decisões Tomadas
Definição do Objetivo Principal:  


Decisão: O objetivo principal é listar os cursos cadastrados.
Fundamento: Isso é essencial para permitir que os usuários visualizem e acessem os cursos disponíveis na plataforma.  

Identificação do Usuário:

Decisão: A história foi escrita na perspectiva do usuário.
Fundamento: Entender quem são os usuários e suas necessidades é crucial para criar histórias relevantes e eficazes.  

Estrutura da História:

Decisão: Usar a estrutura "Como um [tipo de usuário], Eu quero [ação], Para que [benefício]".
Fundamento: Esta estrutura é amplamente utilizada e aceita em metodologias ágeis, pois ajuda a esclarecer o propósito e o benefício da funcionalidade.  

Critérios de Aceitação:

Decisão: Incluir critérios de aceitação claros e específicos.
Fundamento: Os critérios de aceitação ajudam a definir o que é necessário para que a história seja considerada completa e bem-sucedida. Eles fornecem uma base para testes

Funcionalidade:*Cadastrar curso*  

Como usuário  

eu quero cadastrar um curso  

para conseguir acessá-lo  

Critérios de Aceitação:  

Acesso à funcionalidade:
O usuário pode navegar até a aba "Cadastrar Curso".
Formulário de cadastro:
O usuário pode visualizar um formulário de cadastro de curso com os seguintes campos obrigatórios:
Nome do curso
Descrição do curso
Data de início
Duração
Instrutor 
Número de vagas
Url da capa
Tipo de curso(Presencial ou online) 
Validação de campos obrigatórios:
O sistema deve validar que todos os campos obrigatórios estão preenchidos corretamente.
Se algum campo obrigatório estiver vazio, o sistema deve exibir uma mensagem de erro específica informando o usuário sobre os campos que precisam ser preenchidos.
Ação de cadastro:
O usuário pode clicar no botão "Cadastrar Curso".
Se todos os campos estiverem preenchidos corretamente, o sistema deve salvar o novo curso no banco de dados.
Confirmação e redirecionamento:
Após o cadastro bem-sucedido, o sistema deve exibir uma mensagem de sucesso ao usuário (e.g., "Curso cadastrado com sucesso").
O sistema deve redirecionar o usuário para a tela de listagem de cursos, onde o novo curso cadastrado deve estar visível.
Persistência dos dados:
O curso cadastrado deve ser persistido no banco de dados e estar disponível para visualização e acesso em sessões futuras.
Feedback para o usuário:
O sistema deve fornecer feedback adequado para o usuário em caso de falha no cadastro (e.g., erro de rede, problema de servidor)
Definição do Objetivo Principal:  


Decisão: O objetivo principal é permitir que o usuário cadastre um novo curso.
Fundamento: O cadastro de cursos é uma funcionalidade essencial para qualquer sistema de gestão de cursos, permitindo que novos conteúdos sejam adicionados à plataforma.
Identificação do Usuário:

Decisão: A história foi escrita na perspectiva do usuário que deseja cadastrar cursos.
Fundamento: Compreender as necessidades e os objetivos do usuário ajuda a criar uma história que é relevante e útil.
Estrutura da História:

Decisão: Usar a estrutura "Como um [tipo de usuário], Eu quero [ação], Para que [benefício]".
Fundamento: Esta estrutura é amplamente utilizada em metodologias ágeis para garantir que o propósito e o benefício da funcionalidade estejam claros.  

Funcionalidade: Excluir curso  

Como usuário  

eu quero excluir um curso  

para acessar somente os cursos do meu interesse.  


Critérios de Aceitação:
Acesso à funcionalidade:
O usuário pode navegar até a aba "Listar Cursos".
Visualização da lista de cursos:
O usuário pode visualizar uma lista de todos os cursos cadastrados.
Opção de exclusão:
Cada curso na lista deve ter uma opção para excluir (e.g., um botão "Excluir" ao lado do curso).
Confirmação de exclusão:
Ao clicar no botão "Excluir", o sistema deve exibir uma mensagem de confirmação (e.g., "Você tem certeza que deseja excluir este curso?").
Ação de exclusão:
Se o usuário confirmar a exclusão, o sistema deve remover o curso selecionado do banco de dados.
Se o usuário cancelar a exclusão, nenhuma ação deve ser realizada e o curso deve permanecer na lista.
Feedback de sucesso:
Após a exclusão bem-sucedida, o sistema deve exibir uma mensagem de sucesso ao usuário (e.g., "Curso excluído com sucesso").
O curso removido não deve mais aparecer na lista de cursos.
Feedback de falha:
Se houver um erro ao tentar excluir o curso (e.g., problema de rede, problema de servidor), o sistema deve exibir uma mensagem de erro apropriada (e.g., "Erro ao excluir o curso. Por favor, tente novamente mais tarde")
Atualização da lista:
A lista de cursos deve ser atualizada automaticamente para refletir a exclusão do curso sem a necessidade de recarregar a página.

e garantem que todas as partes interessadas tenham a mesma compreensão dos requisitos.  

Definição do Objetivo Principal:  


Decisão: O objetivo principal é permitir que o usuário exclua um curso.
Fundamento: A exclusão de cursos é essencial para que os usuários possam manter sua lista de cursos organizada e relevante, removendo cursos que não são mais de interesse.
Identificação do Usuário:

Decisão: A história foi escrita na perspectiva do usuário que deseja excluir cursos.
Fundamento: Entender as necessidades do usuário ajuda a criar histórias que são relevantes e que atendem aos objetivos do usuário.
Estrutura da História:

Decisão: Usar a estrutura "Como um [tipo de usuário], Eu quero [ação], Para que [benefício]".
Fundamento: Esta estrutura é amplamente utilizada em metodologias ágeis para garantir que o propósito e o benefício da funcionalidade estejam claros.
