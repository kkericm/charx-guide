# ChARX Guide

## Mercado
Nesse menu você pode encontrar varios itens para comprar usando dinheiro.
- **Comidas**: Onde você pode encontrar qualquer comida.
- **Armas**: Onde você pode encontrar qualquer arma e munição (sem encantamentos).
- **Ferramentas**: Onde você pode encontrar qualquer ferramentas (sem encantamentos).
- **Armaduras**:Onde você pode encontrar qualquer armaduras (sem encantamentos). 
    - *O conjunto de armadura tem um preço 8% menor que comprar cada peça adquirida individualmente.*
- **Minerios**: Onde você encontra qualquer minério.
- **Drops de Mobs**: Onde você encontra os drops de mobs mais comuns.
- **Blocos**: Onde você encontra os blocos mais comuns.
- **Madeiras**: Onde você encontra qualquer item feito de madeira. 
    - *Os itens são separados por tipo de madeira.*
- **Enchantamentos**: Onde se pode comprar qualquer tipo de livro encantado.
    - *A cada nível de encantamento o preço aumenta 75% por nível.*
- **Poções**: Onde se pode comprar qualquer tipo de poção.

> Jogadores com nível de permissão **4** ou superior podem alterar os modificadores de preço. Específico e generalizado. Por padrão todos são **1.0**.

## Venda
O menu de vendas é utilizado para trocar certos minerios por dinheiro. Os minerios tem um modificador expecífico, por padrão é **0.75** (**75%** do preço original). Jogadores com nível de permissão **4** ou superior podem alterar esse valor. É recomendado deixar esse valor abaixo de **1.0**.

## Missões
Onde os jogadores podem ver suas missões atuais, e adiquirir novas missões, cada um podendo ter no máximo 10 missões.

- **Sorteio de Missões**: A cada 1 dia do jogo, você tem direito a sortear uma nova missão. Ao sortear, uma pop-up de missão irá aparecer na sua tela, clique em "***Aceitar***" para aceitar ou "***Próxima***", para sortear uma nova missão. São 5 sorteios, e você não pode voltar para a missão que já descartou.

    As missões são separadas por raridade, sendo elas **Comuns**, **Incomuns**, **Raras**, **Épicas** e **Lendárias**, sendo possível distinguir pela cor dos nomes.
    
    | Raridade |   Cor   |
    |----------|---------|
    | Comum    | Sem cor |
    | Incomum  | Azul    |
    | Rara     | Verde   |
    | Épica    | Roxo    |
    | Lendária | Amarelo |

    A dificuldade e recompensa aumenta junto com a raridade, porém a chance de uma missão mais rara aparecer é menor.

- **Resgate**: Missões requerem que você resgate o seu prêmio. O botão de "Resgate" está no menu da missão.

## Eventos e Avisos
<!-- Onde você encontra os eventos que estão ocorrendo no mundo. -->
Eventos podem ser encontrados no menu ***Eventos***, e os Avisos, além de aparecer no menu de eventos como um evento comum, aparecem na tela do jogador assim que eles entram no mundo.

É possivel bloquear que os avisos aparecam na sua tela no menu ***Opções***.

Jogadores com nível de permissão 3 ou superior podem adicionar ou remover eventos no menu  ***Eventos*** > ***Gerenciar Eventos***

## Banco
O menu Banco é utilizado para realizar procedimentos envolvendo dinheiro, como saques, depósitos e transferências.

## Teleport
O menu Teleport é usado para se teleportar entre locais.
- **Salto**: O botão "Salto" é utilizado para se teleportar para um ponto específico no mapa.

- **Criar Ponto**: O botão "Criar Ponto" permite que você estabeleça um local para o qual outras pessoas possam saltar, se for privado, somente o criador pode acessar esse ponto. O seu ponto deve ter um titulo, e, opcionalmente, um subtitulo e/ou uma senha.
    
    O preço do ponto pode ser definido nas opções de moderador (por padrão: **10,000.00$**). O preço aumenta em **10%** a cada ponto que o player possui.

    > Um player pode deletar um ponto, adiquirindo **75%** do preço base de volta.

## Chat
O chat agora é dividido em canais, os pricipais canais são o ***Global*** e ***Proximidade***. 
- **Global**: É o canal que pode ser ouvido em todo o mundo, por qualquer pessoa em qualquer outro canal, que não esteja com ele mutado.
- **Proximidade**: É o canal que pode ser ouvido em todos que estão em 100 blocos de distancia de você, a menos que ele tenha esse canal mutado.
- **Canais Normais**: Qualquer outro canal que não seja o *Global* ou *Proximidade* só pode ser ouvido por jogadores que também estão nesse canal.

## Comandos
Os comandos são usandos para rodar funções especiais no mundo. Os comandos podem ser desativados e ativados nas opções de moderador. 

Existem 5 níveis de permissão

- Nível de permissão **1**: 
    - Não possui nenhuma permissão, representa ausencia de qualquer de permissões dentro do mundo.

- Nível de permissão **2**: 
    | Comando | Descrição |
    |---------|-----------|
    | help    | Fornece ajuda com os comandos. |
    | tchat   | Troca o canal do chat de player. (*Deprecied*) |

- Nível de permissão **3**: 
    | Comando | Descrição |
    |---------|-----------|
    | addevent | Adiciona um evento ao mundo. (*Deprecied*) |
    | removeevent | Remove um evento do mundo que tenha ID. (*Deprecied*) |
    <!-- | kick | Expulsa um jogador. | -->

- Nível de permissão **4**: 
    | Comando | Descrição |
    |---------|-----------|
    | allow | Permite que um player jogue no mundo. |
    | setworldspawn | Define o ponto spawn do mundo. |
    | bloc | Bloqueia os movimentos de um player. |
    | propp | Pega uma propriedade de um player pelo ID. |
    | setpropp | Define uma propriedade de um player pelo ID. |
    | prop | Pega uma propriedade do mundo pelo ID. |
    | setprop | Define uma propriedade do mundo pelo ID. |
    | money | Modifica o dinheiro de um player. |
    | viewlocal | Pode vizualizar qualquer lugar. |
    | clearcam | Voltar para sua visão padrão |
    | setperm | Define o nível de permissão de um player no mundo. |
    | copyinventory | Clona o invantario de um player para um baú. |
    <!-- | ban | Bane um jogador. |
    | unban | Remove o banimento de um jogador. | -->

- Nível de permissão **5**: 
    | Comando | Descrição |
    |---------|-----------|
    | test | Testa uma função. (*Dev*) |
    | ultag | Doa uma tag a um player. |
    | getdesc | Recebe um cartão de desconto. |
    | back | Bolta ao local da ultima morte. (*BETA*) |
    | reset | Redefine todas as propriedades de um mundo, e reinicializa o mesmo. Todos os dados do mundo, e players será pedido. |
    | resetplayer | Reseta todos os dados de um player. |
    | enchant | Encanta algo com um encantamento especial. (*BETA*) |
    | emoji | Mostra um emoji. (*Dev*) |
## Player
## Maestria