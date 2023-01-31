# Login

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

# Registro

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

# Chat

**Como** estudante, 
**eu quero** ser capaz de me comunicar com outros alunos,
**para** interagir e buscar ajuda de pessoas que estão no mesmo curso que eu.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário logado acessa o curso que deseja pela tela de seleção de times;
1. Usuário acessa a tela de ranking ou de mensagens;
1. Usuário seleciona um segundo usuário para a troca de mensagens;
1. Ao enviar uma mensagem pela caixa de texto na parte inferior da tela, a mensagem aparecerá no corpo da conversa em um balão de texto.

# Gerenciamento de conta

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

# Realização de desafio

**Como** estudante, 
**eu quero** ser capaz de realizar os desafios existentes,
**para** aprender e aumentar a minha colocação no ranking.

### Critérios de Aceitação (CAs)

CA01:
1. Usuário logado acessa o time que contém o curso que deseja fazer;
1. Usuário acessa os tópicos do curso pela tela Home;
1. Usuário visualiza os subtópicos pertencentes ao tópico pai com seu progresso de conclusão dos desafios presentes a cada um;
1. Usuário acessa os desafios de um subtópico;
1. Usuário é levado para o primeiro desafio do tópico, onde terá acesso às funções de avançar para o próximo desafio ou voltar para o anterior;
1. Se o desafio ainda não estiver respondido, o usuário será capz de responder, senão, o botão de responder será desabilitado e o usuário apenas poderá visualizar a sua resposta e qual é a resposta correta;
1. Ao pular ou responder o último desafio, o usuário será redirecionado para a tela de feedback;
1. Será exibida a quantidade de questões acertadas, com erro e não respondidas, assim como a quantidade de pontos obtida em cada desafio respondido;
1. Usuário será capaz de revisar as respostas ou retornar aos subtópicos por meio de botões presentes na extremidade inferior da tela.
