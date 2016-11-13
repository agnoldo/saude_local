# Saúde Local

- [Introdução](https://github.com/agnoldo/saude_local#introdução)
- [Tema](https://github.com/agnoldo/saude_local#tema)
- [Funcionamento](https://github.com/agnoldo/saude_local#funcionamento)
- [Funcionalidades Principais](https://github.com/agnoldo/saude_local#funcionalidades-principais)
    - [Cadastro de novo usuário](https://github.com/agnoldo/saude_local#cadastro-de-novo-usuário)
    - [Login por email/senha](https://github.com/agnoldo/saude_local#login-por-emailsenha)
    - [Recuperação de senha](https://github.com/agnoldo/saude_local#recuperação-de-senha)
    - [Login por Facebook](https://github.com/agnoldo/saude_local#login-por-facebook)
    - [Mapa com postos de saúde na região](https://github.com/agnoldo/saude_local#mapa-com-postos-de-saúde-na-região)
    - [Postagem de atendimento](https://github.com/agnoldo/saude_local#postagem-de-atendimento)
    - [Postos de saúde na região](https://github.com/agnoldo/saude_local#postos-de-saúde-na-região-ordenados-por-distância-geográfica-do-ponto-corrente)
    - [Postos de saúde favoritos do usuário corrente](https://github.com/agnoldo/saude_local#postos-de-saúde-favoritos-do-usuário-corrente)
    - [Informações detalhadas sobre Posto de Saúde](https://github.com/agnoldo/saude_local#detalhe-de-posto-de-saúde)
    - [Histórico de atendimentos do usuário corrente](https://github.com/agnoldo/saude_local#histórico-de-atendimentos-do-usuário-corrente)
    - [Alteração de avatar na plataforma](https://github.com/agnoldo/saude_local#alteração-de-avatar-imagem-de-perfil-na-plataforma)
- [Tecnologias Utilizadas](https://github.com/agnoldo/saude_local#tecnologias-utilizadas)
- [Coordenação e Equipe Técnica](https://github.com/agnoldo/saude_local#coordenação-e-equipe-técnica)
- [Disponibilidade](https://github.com/agnoldo/saude_local#disponibilidade)


## Introdução

Aplicativo que mostra postos de saúde pública na região e permite ao usuário registrar e compartilhar problemas, opiniões e tempo de atendimento classificados por serviço prestado. Possui filtros por especialidades atendidas e guarda histórico de visitas do usuário, que pode ser visualizado posteriormente sob a forma de linha do tempo.

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Saúde Local-feature-graphic.png" width="600px" />

## Tema

O principal objetivo deste aplicativo é facilitar o acesso do cidadão à rede pública de postos de saúde, permitindo encontrar unidades por meio de proximidade geográfica, serviços prestados e especialidades atendidas. Informações de contato como endereço e telefone são disponibilizadas e integradas aos recursos de navegação e telefonia do dispositivo móvel para maior facilidade de uso.

Em complemento, o aplicativo também apresenta informações publicadas por outros usuários com relação à qualidade dos serviços prestados e ao tempo de atendimento. Estes dados podem ser usados para subsidiar a escolha de dia, horário e opção de posto de saúde a ser visitado.

Finalmente, problemas no atendimento podem ser classificados e relatados pelos usuários. Estes dados podem ser usados atualmente por gestores de saúde sob a condição de usuários comuns e, futuramente, se vislumbra o desenvolvimento de sistema web com comparativos locais e regionais de qualidade de serviços prestados.

## Funcionamento

A interação com o usuário começa na tela de abertura, a partir da qual ele pode entrar com email/senha previamente cadastrados, cadastrar novo usuário (fornecendo para isto informações como nome de usuário, email, nome completo, senha, sexo e data de nascimento) e recuperar senha de usuário. Também pode optar por efetuar login por conta do Facebook, caso em que o aplicativo abre tela do referido site para autenticação do usuário. Ao ser autorizado pelo site, o usuário tem sua conta automaticamente cadastrada ou autenticada no aplicativo, sem necessidade de cadastro de nova senha. A tela inicial possui ainda atalhos para Termos de Serviço e Política de Privacidade.

Ao entrar no aplicativo, o usuário será levado ao menu central. A partir daí, poderá acessar uma das principais funcionalidades, um mapa com os postos de saúde próximos geograficamente à sua posição atual. Nesta tela ele poderá filtrar os postos por especialidade atendida ou clicar em cada posto e acessar sua tela de detalhe.

A tela de detalhe do posto de saúde, por sua vez, apresenta informações como telefone (com atalho para discagem), endereço (com atalho para aplicativo de mapa e navegação). O usuário poderá visualizar também as opiniões de outros usuários acerca dos serviços prestados, além de gráfico com tempo médio de atendimento geral ou por serviço. Finalmente o usuário poderá marcar o posto de saúde como “favorito”, o que faz com que esta unidade apareça em lista facilmente acessível a partir do menu central ou do menu lateral esquerdo da ferramenta.

Também a partir do menu central o usuário pode acessar listas gerais de postos de saúde na sua região ou a lista de seus favoritos. Estas listas mostram dados resumidos sobre cada posto de saúde, com atalhos para discagem telefônica e para acesso à tela de detalhe do posto.

Outra importante funcionalidade é a postagem de informações sobre um atendimento em posto de saúde. Isto pode ser feito por meio do atalho “Postar novo” (atendimento) ou por meio do botão “+”. Ao registrar um atendimento, o usuário será instado a registrar informações como:
- posto de saúde visitado: a lista apresenta postos ordenados por distância geográfica crescente;
- descrição textual do atendimento;
- avaliação: com estrelas numa escala de 1 a 5;
- serviço utilizado: alguns exemplos são Vacinação e Clínica Geral;
- resultado do atendimento: opções como “Serviço realizado com sucesso”, “Material em falta”, “Funcionário não presente” ou “Desistência por causa de fila”;
horários de chegada e saída.

Finalmente, o aplicativo possui a tela Histórico, que apresenta os registros de atendimento feitos pelo usuário corrente sob a forma de linha do tempo, com atalhos para os dados de cada posto de saúde visitado.

## Funcionalidades Principais

Nesta seção, apresentaremos por meio de capturas de tela (*screenshots*) as principais funcionalidades do aplicativo:

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-19-25.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-27-47.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-40-29.png" width="290px" />

### Cadastro de novo usuário

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-51-13.png" width="290px" />

### Login por email/senha

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-50-30.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-49-31.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-42-49.png" width="290px" />

### Recuperação de senha

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-50-49.png" width="290px" />

### Login por Facebook

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-13-05-16.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-13-05-27.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-13-05-34.png" width="290px" />

### Mapa com postos de saúde na região

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-28-11.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-13-07-08.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-29-43.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-30-43.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-32-15.png" width="290px" />

### Detalhe de posto de saúde

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-32-25.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-32-32.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-32-53.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-22-51-14.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-52-58.png" width="290px" />

### Postagem de atendimento

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-53-56.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-54-04.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-54-22.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-54-41.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-54-54.png" width="290px" />
  
### Histórico de atendimentos do usuário corrente

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-53-29.png" width="290px" />
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-53-40.png" width="290px" />

### Postos de saúde na região (ordenados por distância geográfica do ponto corrente)
  
<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-33-37.png" width="290px" />

### Postos de saúde favoritos do usuário corrente

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-10-52-46.png" width="290px" />

### Alteração de avatar (imagem de perfil) na plataforma

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/Screenshot_2016-11-12-11-01-30.png" width="290px" />


## Tecnologias Utilizadas

O aplicativo foi desenvolvido em HTML, Javascript e CSS sobre os frameworks Apache Cordova, ionic e Angular.js. O primeiro, Apache Cordova, se trata de um framework criado para viabilizar a execução de um mesmo código HTML/Javascript em múltiplas plataformas, com destaque a sistemas móveis tais como iOS, Android, Windows, Blackberry OS e Firefox OS. O segundo, ionic, se baseia no Apache Cordova e no Angular.js para facilitar a criação de aplicativos móveis com visual nativo nos ambientes citados. Finalmente, o terceiro, Angular.js, é um framework criado pelo Google para facilitar a implementação de lógica sofisticada de interação em aplicativos web.

Além destas tecnologias e frameworks basilares, foram utilizados inúmeros plug-ins e bibliotecas de código fonte aberto para viabilizar a implementação de funcionalidades avançadas do aplicativo, dentre os quais podemos destacar:

- angular-material: biblioteca para adoção de linguagem visual Material Design no ionic;
- ngCordova: biblioteca com componentes para funcionalidades avançadas como login em Facebook (e outras redes sociais) e download/upload de imagens, por exemplo;
- ionic-platform-web-client, cordova-plugin-whitelist, cordova-plugin-inappbrowser: em conjunto, estes três plug-ins viabilizam a implementação do login no Facebook com uso de tela nativa do referido site e, por isso, sem qualquer trânsito de senha do Facebook pelo aplicativo Saúde Local;
- ionic-toast: mensagens flutuantes temporárias no aplicativo;
- ionic-rating: componente para avaliação de atendimento em estrelas (1 a 5);
- angular-chart.js: gráficos de barras usados em tempo médio de atendimento;
- moment.js: cálculos diversos relacionados a data/hora no aplicativo;
- ionic-timepicker: componente para edição de hora de chegada e saída em atendimento.

## Coordenação e Equipe Técnica

- Arnaldo Gomes dos Santos Junior (Coordenador)
- Júnia Gaudereto Carvalho Gomes

## Disponibilidade

Aplicativo lançado inicialmente em beta fechado no Google Play. [Solicite seu convite](mailto:agnoldo@gmail.com)!

<img src="https://raw.githubusercontent.com/agnoldo/saude_local/master/imagens/FireShot Capture 43 - Saúde Local – Apps para Android _ - https___play.google.com_store_apps_details.png" width="900px" />


<a href='https://play.google.com/store/apps/details?id=com.agnoldo.sl01&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Disponível no Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/pt-br_badge_web_generic.png'/></a>
