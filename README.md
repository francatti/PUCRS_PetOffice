# Pet Office
Projeto da matéria de Fundamentos de Sistemas Web da PUC RS - 3º Trimestre

# Objetivo

O objetivo é a concepção de um projeto de aplicação web que possa proporcionar ao usuário uma experiência de Pet Shop online, com a possibilidade de adquirir produtos no sistema sem ter que sair de casa, recebendo-os em sua casa, contratar serviços de banho e tosa para o seu pet de forma agendada, tendo ainda a opção do serviço de tele-busca em sua residência para não precisar levá-lo. Ademais, o projeto tem como propósito a cativação do cliente, provendo a possibilidade de cadastro próprio e do seu pet. Tudo isso contribuiria para uma melhor colocação no ramo de petshops e com o crescimento da marca, valorizando o negócio e aumentando as possibilidades e chances criadas para o estabelecimento.
Público-Alvo
Grande parte dos usuários serão pessoas que buscam praticidade ao cuidar do seu pet, pessoas ocupadas que não possuem tempo para no dia a dia realizar essas ações que a aplicação proporciona fisicamente.

# Funcionalidades

Formulário de cadastro de usuários: permitir que os usuários criem uma conta no sistema, inserindo as informações pessoas, seu endereço, e-mail e telefone - tendo o e-mail como verificador para o cadastro do usuário;

Login no sistema: permitir que os usuários após já terem feito cadastro no sistema possam logar e se identificar a partir do e-mail e senha criados - tendo o e-mail como forma de recuperação da senha;

Visualização dos produtos e serviços: permitir que os usuários visualizem detalhadamente os produtos com as suas respectivas fotos, a descrição e o valor, e os serviços também com a respectiva descrição e o valor correspondente;

Busca dos produtos e dos serviços no sistema: permitir que os usuários pesquisem os produtos e serviços, filtrando a partir de preço, data e horários disponíveis, tipo do serviço e outras opções;

Cadastro do pet: permitir que o usuário cadastre o seu animal de estimação no sistema inserindo o nome, tipo, a raça e o temperamento;

Escolha do serviço com agendamento e com opção de tele-busca: permitir ao usuário ao escolher o serviço agendá-lo pelo sistema selecionando data e horário desejados, recebendo a confirmação do agendamento por e-mail e podendo escolher como opção a tele-busca;

Pagamento online (requisito adicionado): permitir que os usuários realizem o pagamento dos serviços e dos produtos de forma remota fácil e com segurança, aceitando diversas formas de pagamento, como cartão de crédito e Pix;


# Metas

• As metas para o projeto se baseiam no objetivo, para que possamos dar ao usuário a possibilidade de adquirir os produtos, iremos dispor na homepage a sequência de produtos que estão disponíveis e filtros de preço para que possam ser mostrados apenas os que o usuário quer, com a possibilidade dele adicionar ao carrinho o produto que deseja. Agora, para os serviços propostos, precisaremos dar a opção de o usuário escolher datas, tipo do serviço e o pet daquele usuário.

• Na sequência, para que usuário possa selecionar um pet para o agendamento do serviço, ele precisa primeiro adicionar um pet e para isso teremos uma tela de cadastro de pet, que por consequência para tal o usuário precisa estar logado, o que exige que o mesmo tenha feito cadastro, exigindo então que tenhamos uma página de cadastro e uma de login para o usuário.

• Sendo assim, ao agendar o usuário irá precisar de uma tela com funcionalidade para confirmar seu agendamento de serviço com as devidas opções e ao fim confirmar, para então ter a possibilidade de pagar pelo serviço ou pelo produto que adicionou ao carrinho.


• Prazo para desenvolvimento: considerando a complexidade do
sistema, equipe e tecnologias usadas a estimativa de desenvolvimento
é de 4 a 6 meses para desenvolvimento do MVP e de 1 a 2 meses
para adicionar novas funcionalidades e melhorias.

• Orçamento: considerando o custo de hospedagem do sistema, as
licenças de software e o custo da equipe de desenvolvimento, o
orçamento para a realização do MVP, o valor giraria em torno de R$
150.000 a R$165.000.

# Recursos necessários

• Farei uso da IDE do Visual Studio Code e me basearei em protótipos
realizados na plataforma do Figma para o FrontEnd do sistema.

• O controle de versão do software vai ser feito pelo GIT + GITHUB.
Tecnologias empregadas

• Serão usadas as tecnologias de HTML5, CSS3, o framework
Bootstrap e um banco de dados feito com mySQL como SGRGD.

• A aplicação deve rodar nativamente no browser e deve gerar
diretamente o HTML, Javascript e CSS para a interface com o cliente;

# Projeto arquitetural de navegação

<strong> Projeto arquitetural:  </strong>

• O sistema web para comércio de produtos e serviços de um PetShop
será desenvolvido através de uma arquitetura em camadas, em que a
camada de apresentação (UI) será separada da camada de negócio e
da camada de dados. O sistema será hospedado em um servidor web
com alta disponibilidade e escalabilidade para que vários acessos,
compras, agendamentos e outras ações possam ser feitas
concomitantemente no servidor.

<strong> Camada De Apresentação </strong>

• Responsável pela interface do usuário (UI), as páginas web de
formulário de cadastro do cliente, login no sistema, visualização de
detalhes dos produtos e dos serviços, busca de produtos e serviços,
cadastro do pet, agendamento de serviço e de pagamento online.

<strong> Camada De Negócio/Lógica </strong>

• Será responsável por implementar as funções que giram em torno da
lógica de negócio, tais como validação dos dados de entrada de todas
as páginas em que o usuário deve preencher dados, como será feito o
cálculo de preço dos produtos e serviços ofertados, verificação da
disponibilidade de datas e horários para agendamento dos serviços.

<strong> Camada De Dados </strong>

• Será responsável por armazenar, gerenciar e recuperar os dados do
sistema que são processados no sistema através da comunicação
entre a camada de negócio por meio de API e desta para a de
apresentação;

• Aqui é implementado um SGRBD que irá armazenar as informações
dos usuários cadastrados, dos pets cadastrados, dos serviços e
produtos disponíveis, dos agendamentos e dos pagamentos;
Projeto arquitetural de interface e de conteúdo (aqui você também deve prever as telas
prototipadas)

# Projeto De Navegação:

• O sistema terá uma interface de usuário (ui) minimalista, bem intuitiva
e fluida

• Na homepage o usuário poderá acessar o seu carrinho, a página de
login, poderá ainda acessar a página de adicionar o seu pet,
juntamente da possiblidade de ao selecionar as opções que deseja,
iniciar uma tentativa de agendamento de um dos dois serviços
disponíveis.

• Ademais, ainda na homepage, teremos os produtos disponíveis, tendo
a possiblidade de filtrá-los por faixa de preço e podendo adicioná-los
ao carrinho ou a lista de favoritos. Além disso, temos os cães que são
cadastrados e com a devida permissão do cliente, expostos no site,
bem como uma seção para falarmos um pouco sobre a empresa.

• Por fim, temos a seção de serviços para expor os dois serviços
disponíveis para o cliente, assim como um mapa interativo que o
cliente pode ver onde nos localizamos. Logo abaixo, temos enfim o
rodapé da homepage com algumas informações e contatos.

• Em seguida temos a página de login, que por consequência leva a
página de cadastro, caso o usuário ainda não tenha se cadastrado.
• Temos também uma página de cadastro do pet, com algumas
informações necessárias.

• Em seguida a tela de agendamento tanto de banho como de tosa com
as seleções e preços disponíveis.

• Por fim, a página de pagamento com as opções de pagamento,
valores e itens.

• Caso queiram acessar o projeto diretamente no FIGMA para tirar
algumas dúvidas, deixo aqui também o link aberto para acesso direto
ao projeto:
https://www.figma.com/file/8SL6wUEnxc1yDQHWd3V24d/PetOffice?type=design&nodeid=0%3A1&mode=design&t=tNevbpVvkV233UO0-1

# Autor do Projeto

<a href="https://github.com/francatti"> Nicholas Francatti </a>
