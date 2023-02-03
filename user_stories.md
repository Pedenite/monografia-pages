
# Front Office

## Login

**Como** usuário, 
**eu quero** ser capaz de fazer login com as minhas credenciais no sistema,
**para** acessar as funcionalidades da plataforma.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário digita as suas credenciais corretamente e pressiona no botão de login;
1. Usuário acessa a ferramenta normalmente com a sua conta.

CA02:
1. Usuário digita as credenciais incorretas e pressiona o botão de login;
1. Acesso negado e mensagem de erro explicativa é mostrada na tela.

## Registro

**Como** usuário, 
**eu quero** ser capaz de me registrar no sistema caso não tenha acesso,
**para** ser capaz de acessar as funcionalidades da plataforma.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário preenche todos os dados corretamente na tela de registro;
1. Usuário tem suas credenciais criadas e pode realizar o login com elas.

CA02:
1. Usuário deixa de preencher campos obrigatórios ou preenche campo incorretamente;
1. Credenciais não são criadas e mensagem de erro explicativa é exibida na tela.

## Chat

**Como** estudante, 
**eu quero** ser capaz de me comunicar com outros alunos,
**para** interagir e buscar ajuda de pessoas que estão no mesmo curso que eu.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário logado acessa o curso que deseja pela tela de seleção de times;
1. Usuário acessa a tela de ranking ou de mensagens;
1. Usuário seleciona um segundo usuário para a troca de mensagens;
1. Ao enviar uma mensagem pela caixa de texto na parte inferior da tela, a mensagem aparecerá no corpo da conversa em um balão de texto.

## Gerenciamento de conta

**Como** estudante, 
**eu quero** ser capaz de visualizar e editar minha senha e meus dados pessoais salvos no aplicativo e ser capaz de fazer o logout,
**para** ter controle dos meus dados e acesso e/ou corrigir quaisquer dados editáveis conforme necessário.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário logado acessa a aba de conta;
1. Usuário visualiza todos os seus dados conforme cadastrados no registro.

CA02:
1. Usuário logado acessa, pela aba de conta o botão para editar dados pessoais;
1. Usuário é levado para a tela de edição com os campos editáveis contendo seus dados pessoais;
1. Usuário altera os dados e salva;
1. Usuário é redirecionado de volta para a tela de conta;
1. Os dados pessoais são exibidos com as alterações feitas.

CA03:
1. Usuário logado acessa, pela aba de conta, o botão para alterar a senha pessoal;
1. Usuário é levado para a tela de alteração de senha;
1. Usuário informa a sua senha atual e nova senha confirmada corretamente seguindo os critérios de criação de senha;
1. Usuário é informado que a senha foi alterada com sucesso.

CA04:
1. Usuário comete um dos seguintes erros durante a alteração de senha:
    * a senha atual está incorreta;
    * confirmação de senha diverge da original;
    * nova senha foge dos critérios estabelecidos para a segurança da senha;
    * nova senha é igual à antiga.
1. Mensagem de erro é exibida na tela para o usuário e a senha não é alterada;

## Realização de desafio

**Como** estudante, 
**eu quero** ser capaz de realizar os desafios existentes,
**para** consolidar os meus conhecimentos e aumentar a minha colocação no ranking.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário logado acessa o time que contém o curso que deseja fazer;
1. Usuário acessa os tópicos do curso pela tela Home;
1. Usuário visualiza os subtópicos pertencentes ao tópico pai com seu progresso de conclusão dos desafios presentes a cada um;
1. Usuário acessa os desafios de um subtópico;
1. Usuário é levado para o primeiro desafio do tópico, onde terá acesso às funções de avançar para o próximo desafio ou voltar para o anterior;
1. Se o desafio ainda não estiver respondido, o usuário será capaz de responder, senão, o botão de responder será desabilitado e o usuário apenas poderá visualizar a sua resposta e qual é a resposta correta;
1. Ao pular ou responder o último desafio, o usuário será redirecionado para a tela de feedback;
1. Será exibida a quantidade de questões acertadas, com erro e não respondidas, assim como a quantidade de pontos obtida em cada desafio respondido;
1. Usuário será capaz de revisar as respostas ou retornar aos subtópicos por meio de botões presentes na extremidade inferior da tela.
1. Ao visualizar o ranking novamente, a sua pontuação terá sido alterada com base nos pontos ganhos mostrados no feedback, tendo a possibilidade de subir de posição.

# Back Office

## Login

**Como** usuário, 
**eu quero** ser capaz de fazer login com as minhas credenciais no sistema,
**para** acessar as funcionalidades da plataforma.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário digita as suas credenciais corretamente e pressiona no botão de login;
1. Usuário acessa a ferramenta normalmente com a sua conta.

CA02:
1. Usuário digita as credenciais incorretas e pressiona o botão de login;
1. Acesso negado e mensagem de erro explicativa é mostrada na tela.

## Registro

**Como** usuário, 
**eu quero** ser capaz de me registrar no sistema caso não tenha acesso,
**para** ser capaz de acessar as funcionalidades da plataforma.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário preenche todos os dados corretamente na tela de registro;
1. Usuário tem suas credenciais criadas e pode realizar o login com elas.

CA02:
1. Usuário deixa de preencher campos obrigatórios ou preenche campo incorretamente;
1. Credenciais não são criadas e mensagem de erro explicativa é exibida na tela.

## Gerenciar Times

**Como** usuário, 
**eu quero** ser capaz de cadastrar times na plataforma,
**para** organizar e monitorar melhor as minhas turmas de alunos.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário preenche todos os dados corretamente na tela de cadastro de times;
1. Usuário define a descrição do time que será exibida no aplicativo;
1. Usuário cadastra o time e, consequentemente, poderá gerenciá-lo.

CA02:
1. Usuário deixa de preencher os campos obrigatórios ou preenche incorretamente;
1. Time não é cadastrado e mensagem de erro explicativa é exibida na tela.

## Gerenciar Participantes

**Como** usuário, 
**eu quero** ser capaz de cadastrar e desativar participantes nos meus times da plataforma,
**para** que eu possa ser capaz de gerenciar melhor as minhas equipes e alunos.

CA01:
1. Usuário preenche o *e-mail* corretamente na tela de cadastro de participantes;
1. Usuário cadastra o participante e, consequentemente, poderá gerenciá-lo e monitorá-lo;
1. Usuário desativa o participante, quando necessário.

CA02:
1. Usuário deixa de preencher o *e-mail* do participante, preenche um *e-mail* inválido ou o participante não está cadastrado na plataforma;
1. Participante não é inserido no time e mensagem de erro explicativa é exibida na tela.

## Gerenciar Tópicos

**Como** usuário, 
**eu quero** ser capaz de cadastrar tópicos na plataforma,
**para** organizar melhor os conteúdos que serão ministrados em cada time.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário preenche todos os dados corretamente na tela de cadastro de tópicos;
1. O usuário define o ícone do tópico que será exibido na tela do aplicativo;
1. Usuário cadastra o tópico e, consequentemente, poderá gerenciá-lo.

CA02:
1. Usuário deixa de preencher campos obrigatórios ou preenche incorretamente;
1. Tópico não é cadastrado e uma mensagem de erro explicativa é exibida na tela.

## Gerenciar Subtópicos

**Como** usuário, 
**eu quero** ser capaz de cadastrar subtópicos na plataforma,
**para** organizar melhor os conteúdos que serão ministrados em cada tópico.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário preenche todos os dados corretamente na tela de cadastro de subtópicos;
1. O usuário define a descrição do subtópico que será exibido na tela do aplicativo;
1. Usuário cadastra o subtópico e, consequentemente, poderá gerenciá-lo.

CA02:
1. Usuário deixa de preencher os campos obrigatórios ou preenche incorretamente;
1. Subtópico não é cadastrado e uma mensagem de erro explicativa é exibida na tela.

## Gerenciar Desafios

**Como** usuário, 
**eu quero** ser capaz de gerenciar os desafios em cada um dos meus times,
**para** para criar e gerenciar questões passadas aos alunos.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário preenche todos os dados corretamente na tela de cadastro de desafios;
1. Usuário adiciona descrição ao desafio;
1. Usuário define o modelo de resposta;
1. Usuário insere o feedback que será exibido aos alunos ao realizarem a questão;
1. Usuário cadastra o desafio e, consequentemente, poderá gerenciá-lo.

CA02:
1. Usuário deixa de preencher campos obrigatórios ou preenche o(s) campo(s) incorretamente;
1. Desafio não é criado e uma mensagem de erro explicativa é exibida na tela.
