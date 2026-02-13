Este projeto apresenta um sistema de portaria inteligente desenvolvido para a empresa fictícia TechZone. A aplicação tem como finalidade simular o controle de acesso de colaboradores a um prédio, utilizando como critérios o nome do colaborador e o horário de chegada informado pelo usuário.

O sistema foi construído utilizando HTML, CSS e JavaScript em um único arquivo. O HTML é responsável pela estrutura da página, contendo campos para a inserção do nome do 
colaborador e da hora atual, além de um botão que inicia a verificação de acesso. O CSS foi aplicado para criar um layout moderno e 
visualmente agradável, com um cartão centralizado na tela, cores contrastantes, bordas arredondadas e animações suaves. O JavaScript é utilizado para implementar toda a lógica
de funcionamento do sistema.

O funcionamento do sistema ocorre de forma simples e direta. Existe uma lista pré-definida de colaboradores autorizados no código JavaScript. Quando o usuário digita seu nome
e a hora atual e clica no botão de verificação, o sistema primeiro confere se o nome informado está presente na lista de autorizados. Caso o nome não esteja cadastrado, o acesso
é negado imediatamente e uma mensagem de aviso é exibida na tela.

Se o nome estiver autorizado, o sistema verifica o horário informado. Caso a hora esteja dentro do intervalo permitido, que vai das 6 horas da manhã até as 22 horas, o acesso
é liberado e uma mensagem de boas-vindas é exibida ao colaborador. Se o horário estiver fora desse intervalo, o acesso é negado e o sistema informa que a tentativa ocorreu fora
do horário permitido. Caso o valor digitado para a hora seja inválido, o sistema exibe uma mensagem orientando o usuário a informar um horário entre 0 e 23.

Dessa forma, o projeto demonstra de maneira prática como é possível utilizar JavaScript para criar validações simples, interagir com elementos da página e simular o
funcionamento de um sistema real de controle de acesso, unindo lógica de programação, estrutura HTML e estilização com CSS em uma única aplicação.
