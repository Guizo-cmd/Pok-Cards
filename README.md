Relatório do Trabalho Final da disciplina de Tecnologias Web - 2025

1. Informações Gerais
Nome do(a) estudante: Jorge Lucas Matias dos Santos
Professor: Paulo Ricardo de Souza Silva
Template utilizado: Shop Homepage - https://startbootstrap.com/template/shop-homepage 
Tema/Empresa escolhida: PokéCards: Uma loja onde é possível comprar cartas de pokémons.
Repositório do GitHub: https://github.com/Guizo-cmd/Pok-Cards.git 

2. Sobre o Projeto
O site foi desenvolvido para representar uma loja fictícia de cartas Pokémon chamada Pokécards.
O objetivo é exibir cartas colecionáveis, apresentar informações sobre cada item e permitir que o usuário finalize uma compra por meio de um formulário interativo dentro de um modal.
O foco do projeto é treinar HTML, CSS, JavaScript e Bootstrap, além de aplicar validação de formulários no processo de compra.

3. Customizações Realizadas
Foram realizadas diversas adaptações no template original, incluindo:
Alteração da paleta de cores para tons de roxo e lilás, que combinam com a temática Pokémon.
Personalização dos botões com bordas brancas e efeitos de hover.
Ajuste de textos e alteração do fundo principal.
Substituição das imagens padrão.
Modificação da navbar com novos links e menu suspenso.
Criação de um modal personalizado para a finalização da compra.
Implementação de alertas e validação para o botão "Confirmar Pedido".
Correção de estrutura e duplicação de código que impediam o funcionamento dos scripts.
Ajustes de espaçamento, alinhamento e responsividade usando as classes do Bootstrap.

4. Formulários
O site possui um formulário principal dentro de um modal para efetuar a compra da carta selecionada.
Campos presentes no formulário principal:
Nome completo
CPF
E-mail
Forma de pagamento (select)
Endereço completo
O formulário recebe as informações necessárias para concluir o pedido.
A validação é feita em JavaScript, verificando se todos os campos foram preenchidos antes de permitir a conclusão.
Caso algum campo esteja vazio:
Um alerta é exibido informando que os dados são obrigatórios.
O modal não é fechado até que o usuário complete tudo corretamente.
Quando todos os campos estão preenchidos:
Uma mensagem de sucesso é exibida.
O modal é fechado automaticamente usando a API do Bootstrap.
Foram desenvolvidos outros formulários, como o de entrar em contato com o estabelecimento, que mostra mensagem de sucesso, falha ao enviar se as informações não estão preenchidas corretamente, entre outras funções e entre outros formulários.

5. Uso de Inteligência Artificial
Durante o desenvolvimento do site, a IA foi utilizada como apoio em diversas etapas, como:
Auxílio na correção de erros no JavaScript que impediam o  funcionamento.
Explicações sobre funcionamento da API do Bootstrap 5.3 para manipular modais via script.
Apoio na organização da estrutura HTML e remoção de duplicações.
Na implementação de ações mais complicadas, mas que afetam diretamente para que o site se torna-se quase que completamente funcional
A IA foi usada como ferramenta de apoio, mas todas as implementações foram compreendidas e adaptadas manualmente no código, buscando entender o que cada nova função tinha de diferente e como funcionava.

6. Recursos Implementados em JavaScript
Os principais scripts utilizados no desenvolvimento foram:
Validação do formulário do modal, verificando preenchimento de todos os campos.
Exibição de alertas personalizados para campos vazios.
Fechamento automático do modal após o envio bem-sucedido.
Vinculação do botão "Confirmar Pedido" ao evento de verificação e conclusão.

7. Responsividade
O site é totalmente responsivo devido ao uso do Bootstrap 5, que forneceu:
Sistema de grid para organização dos elementos.
Ajuste automático de imagens.
Componentes responsivos como navbar.
 Realizei testes de minimização das telas no computador e tive resultados efetivos.

8. Créditos e Referências
Shop Homepage - https://startbootstrap.com/template/shop-homepage
Bootstrap, Google Imagens (armazenadas na pasta assets/img), ChatGPT, Copilot, JavaScript, HTML
Links usados para entender e por curiosidade do processo:
https://www.jdevtreinamento.com.br/validacao-de-campos-obrigatorios/ 
https://pt.stackoverflow.com/questions/94483/como-validar-um-formul%C3%A1rio-corretamente 
https://getbootstrap.com/docs/5.0/getting-started/introduction/ 

9. Considerações Finais
Durante o processo de criação do site Pokécards, foi possível praticar e consolidar conhecimentos sobre HTML, CSS, Bootstrap e JavaScript. Tive curiosidade sobre o processo de ligação entre uma página e outra e sobre as validações em JavaScript. Aprendi sobre as modificações visuais do site e como o sistema responsivo de comporta. 
Como resultado, o projeto final apresenta uma interface moderna, responsiva e interativa, com funcionalidades completas de compra simulada, dentro do que foi possível fazer dentro dos aprendizados em sala de aula e do auxílio de IA.


