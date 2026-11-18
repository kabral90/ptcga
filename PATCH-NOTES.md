# Patch notes — da R66 até a R116

Todas as mudanças desde a **R66 (v1.0.111-snapshot.66)**, a última versão publicada aqui, até a **R116 (v1.0.161-snapshot.116)**. Da mais nova para a mais antiga. Cada versão inclui tudo o que veio antes.

---

## R116 — 1.0.161-snapshot.116
- **Tela Inicial finalizada com ativos oficiais do jogo:**
  - **Continuar Campanha:** usa os mapas oficiais da campanha (`Ilha dos Clubes`, `Base Rocket`, `Kanto` e `Grande Salão`) conforme o ato atual.
  - **Gachamon:** usa render 3D oficial da máquina de cápsulas do jogo com badge `GIRO GRÁTIS` + contagem de giros grátis e vales.
  - **Mural de Eventos:** exibe mural de cortiça com calendário e aviso destacado acima da barra `Mural de Eventos`.
  - Inclui também o fundo claro com marca d'água sutil de Pokébola, remoção do botão Jogo Rápido na Home (encontros `!` mantidos), remoção da aba Eventos da Gazeta, economia de 1ª compra/recompra de decks, premiações reajustadas e as 16 novas artes do Intro Pack.

## R115 — 1.0.160-snapshot.115
- **Tela Inicial repaginada & Mural de Eventos:** fundo claro com marca d'água sutil de Pokébola e barra superior mais limpa; removido o botão Jogo Rápido (preservando os encontros `!`); novo card **Gachamon** com badge `GIRO GRÁTIS` + contagem de giros grátis e vales; card **Continuar Campanha** com arte ilustrada dinâmica por ato e selo de progresso; card **Mural de Eventos** com composição temática (troféu + carta holo + raio). A aba `Eventos` foi removida da Gazeta.
- **Economia de decks (1ª compra e recompra):** preços iniciais diferenciados (`500` Base Set, `550` Jungle/Fossil/Team Rocket, `600` Base Set — Reforço, `750` Gym Heroes, `800` Gym Challenge) e recompra baseada na soma das cartas avulsas do deck (sem Energias) com desconto de `25%` / `20%` / `15%`.
- **Premiações de batalha reajustadas:**
  - Membros de Clube: `100` créditos + `1` booster (1ª) / `100` créditos (revanche); Mestres: `250` + `2` boosters (1ª) / `1` booster (revanche).
  - Equipe Rocket: Soldados = `100` + `1` booster Team Rocket (1ª e vitória na revanche); Comandantes = `200` + `1` booster Team Rocket (1ª) / `1` booster Team Rocket (vitória na revanche).
  - Rotas `rt1–rt8`: `120` + `1` booster (1ª) / `50` créditos por prêmio + `1` booster ao vencer pegando todos (revanche).
  - Grande Salão: `750` + `1` booster de cada coleção liberada (1ª) / `240` créditos (revanche).
  - Ronald: `500` créditos ao vencer (ticket e revanche em Kanto); líderes de Kanto (`BOSS`/`FINAL`): `1` booster ao vencer na revanche; encontros aleatórios (`!`): `50` / `100` / `150` créditos.
- **Intro Pack:** atualizadas todas as 16 artes das cartas do conjunto Intro Pack.

## R114 — 1.0.159-snapshot.114
- **Save compartilhado na nuvem entre aparelhos (GitHub Gist secreto):** novo painel na tela **Saves e backups (`S31`)** para conectar um token clássico do GitHub (permissão `gist`), salvando o token apenas localmente no aparelho.
- **Auto-descoberta e sincronização em segundo plano:** o primeiro aparelho cria um **Gist secreto** (`ptcga-cloud-save-v1`) com o pacote oficial `.campaign-profile.zip`; novos aparelhos só precisam colar o mesmo token para restaurar o perfil automaticamente. Sincroniza ao abrir o jogo, ao progredir fora de duelo e ao sair/minimizar, exibindo modal comparativo caso dois aparelhos avancem offline.

## R113 — 1.0.158-snapshot.113
- **Versão consolidada para atualização automática:** inclui todas as novidades de **R112** e **R112-2** com `APP_BUILD = 113` e tag `v1.0.158-snapshot.113` para que versões R110–R112 puxem a atualização automaticamente pelo Sam.
- **Gacha & Booster Can:** pré-carregamento simultâneo dos modelos 3D no boot/Início para abrir direto em 3D sem piscar desenho 2D; `Booster Can` oculta da Gazeta até derrotar **3 Mestres da Ilha**, sem dicas de requisito quando acessada travada; botão do Cassino bloqueado no Clube Elétrico mostra apenas **`🔒 Cassino`** e `"O Cassino está em reforma. Volte depois!"`.

## R112 — 1.0.157-snapshot.112
- **Vending Machine (116 cartas) e Máquina Booster Can (`S62`):** nova aba na Gazeta (exibida somente após derrotar **3 Mestres da Ilha**, com aviso único do Sam), máquina 3D de latinhas em cor única por **200 Créditos**, entregando **5 cartas aleatórias sem distinção de raridade**, com som de abertura de latinha, revelação em tela cheia centralizada e resumo em `3 + 2`. Coleção disponível na Coleção (com símbolo Pokébola e logo próprios) e no Editor de Decks, fora dos baralhos aleatórios de NPC.
- **Cassino da Ilha, Cassino de Celadon e Tickets:** nova moeda **Tickets** exibida à esquerda dos Créditos (câmbio 10 Créditos = 1 Ticket), caça-níquel com rolos só de ícones e botões `PARAR 1/2/3`, aba `Cassino` no Clube Elétrico em reforma até a reabertura (anunciada pelo Sam), marcador do Cassino de Celadon em Kanto e **Loja Intro Pack** para adquirir as 16 cartas `intro`.
- **Autobuilder e Encontros (`!`):** checagem universal no Autobuilder para impedir mistura de pré-evoluções incompatíveis ou excesso em linhas evolutivas compartilhadas; placa dos encontros aleatórios não exibe mais dificuldade nem turno do oponente.

## R111 — 1.0.156-snapshot.111
- **Vitória dos Mestres:** a entrega da moeda do Mestre tem prioridade absoluta sobre avisos do Sam, selos e tutorial da Feira, com intervalo mínimo de 2 segundos entre mensagens e sem sobreposição.
- **Encontros aleatórios (`!`):** tocar no marcador abre o banner inferior; tocar em **Duelar** entra direto na partida com **4 prêmios** (sem passar pelo Jogo Rápido), e a dificuldade escala pelos Mestres vencidos (`0–3` Fácil, `4–6` Médio, `7–8` Difícil).
- **Decks por campanha e Autobuilder:** encontros seguem a etapa da campanha (Ilha: Base/Jungle/Fossil; pós-Rocket: +Team Rocket; Kanto: foco em Gym Heroes/Challenge; Johto: Neo 1–4), com geração em pirâmide, filtro de Treinadores sem alvo e Autobuilder do jogador respeitando o estoque real e decks parciais.

## R110 — 1.0.155-snapshot.110
- **Mesa virada:** o número do dano que o adversário sofre agora aparece de pé para você também no celular.
- **Defender e PlusPower** saem do Pokémon e voam até o descarte quando o efeito acaba (antes sumiam e apareciam no descarte).
- **Mestres bloqueados:** ao tocar, volta a aparecer a fala do Sam ou do Mestre; na lista continua só "Bloqueado".

## R109 — 1.0.154-snapshot.109
- Mestre de clube ainda não liberado aparece só como **Bloqueado** na lista.

## R108 — 1.0.153-snapshot.108
- A opção **Cartas do adversário** (De frente para mim / Viradas, como numa mesa) agora fica em **Aparência padrão › Mesa**, no menu do seu avatar.
- O menu do avatar voltou a ser como na R105 (sem os atalhos de Ajustes, Ajuda e Saves da R106).

## R107 — 1.0.152-snapshot.107
- **Mesa virada de verdade** (Cartas do adversário › "Viradas, como numa mesa"; na R108 a opção foi para a Aparência padrão): tudo do adversário fica virado para ele — cartas, Energias, PS, deck, descarte, prêmios, a mão e o tapete dele. Só o número do dano que ele sofre fica virado para você. O lado dele espelha como numa mesa real (prêmios à direita, deck e descarte à esquerda) e as cartas dele já se movem viradas. Em "De frente para mim", nada muda.
- **Seletor de velocidade da partida:** mudar a velocidade na pausa não tinha efeito para quem já tinha escolhido uma velocidade nos Ajustes. Agora funciona na hora.

## R106 — 1.0.151-snapshot.106
- Atalhos de **Ajustes**, **Ajuda** e **Saves e backups** no menu do avatar (retirados na R108).

## R105 — 1.0.150-snapshot.105
Junta a R104 com:
- **Clubes abertos para os membros:** dá para entrar em qualquer clube e enfrentar os cinco membros desde o início. A regra de liberação vale só para o **Mestre**, que aparece com cadeado. No mapa da ilha, nenhum clube aparece mais fechado.
- **Avatares:** num jogo novo, a escolha de avatar mostra só os avatares iniciais; os duelistas só aparecem depois de vencidos. Mark e Mint escolhidos ficam redondos.

## R104 — 1.0.149-snapshot.104
Junta a R103 com tudo o que foi feito depois dela.
- **Selos de Kanto**, com tapetes de duelo por local e um prêmio a cada cinco selos.
- **Ronald** com dois decks (um deles com as Eeveelutions do Game Boy), preparação própria e revanche depois dos quatro Grandes Mestres.
- **15 cartas GB Promos**, com efeitos próprios. A seção da coleção fica escondida até você ganhar a primeira; o nome e o logo aparecem na terceira troca. O Colecionador e o Sam passam a oferecer essas cartas.
- Arte nova do **ticket da Ilha para Kanto**, no diálogo do Mason e no porto.
- **Eventos:** o mosaico não tem mais blocos sobrepostos, e o Sam aparece maior.
- Nova arte da carta Articuno do Game Boy.

## R103 — 1.0.148-snapshot.103
- **Cartas do adversário viradas**, como numa mesa de verdade. É uma opção em Ajustes › Mesa.
- **Tocar e segurar** uma carta para ver os detalhes funciona também no turno do adversário.
- **PlusPower e Defender** ficam ligados ao Pokémon até o efeito acabar, e só então vão para o descarte. O Item Finder não pega mais essas cartas enquanto estão em jogo.
- O **PS** do Pokémon voltou a aparecer cheio e diminuindo com o dano.
- Tela de limite de mão só com as cartas, sem nomes encavalados e sem o botão de informações por cima.
- Retratos maiores nos diálogos. O Imakuni não aparece mais cortado.
- **Mapa da ilha:** o ícone da Feira só aparece aos sábados depois de ser liberada, e um clube travado fecha o banner que estava aberto. Nas batalhas aleatórias, o nível sai do cartão e o avatar fica maior.
- O Sam explica no tutorial o que são as **"!"** do mapa.
- **Tipo do deck** com os símbolos das Energias que o deck realmente usa.
- Círculo do Ativo maior, texto centralizado no aviso de turno e avatar do jogador maior.
- Em jogo novo, a aba do Grande Salão só aparece depois de liberada.

## R102 — 1.0.147-snapshot.102
- **Correção:** o PlusPower ficava preso ao novo Ativo do adversário quando o Pokémon recuava. Agora ele é descartado quando o Pokémon sai do Ativo.
- A **cura de condição ao evoluir** aparece depois da animação de evolução, sem travar.
- Energias ligadas aos Pokémon do Banco centralizadas.

## R101 — 1.0.146-snapshot.101
- O adversário **anuncia o ataque antes** de atacar, como se desse o comando ao Pokémon.
- Círculo redondo sob os Ativos.
- **Ferramentas e cartas ligadas** (PlusPower, Defender, Máquinas Técnicas) ganharam espaços próprios na mesa.
- Tocar numa carta da mão não abre mais o submenu.
- Botão de **Informações** de volta na mesa, explicando os símbolos (como os do Mr. Mime).
- Ícone do porto alinhado com os pontos da ilha.

## R100 — 1.0.145-snapshot.100
- **Mesa de duelo nova**, fiel à prévia aprovada: zonas, prêmios encavalados, emblemas, pilhas e contador de dano.
- Cartas da mão 10% menores e sem o atalho "Atacar". Os ataques continuam ao tocar no Ativo.
- Tapete padrão para o jogador e para adversários sem tema próprio.
- Avatares dos chefes restaurados. As artes HD ficam só nos banners.
- Recortes dos selos corrigidos.
- A tela de carregamento mostra a versão certa.

## R99 — 1.0.144-snapshot.99
- Primeira versão da mesa nova: banco do adversário no topo, Ativo centralizado, prêmios à esquerda, deck e descarte à direita e Estádio na linha do meio.
- Placa do adversário com foto e nome. Avisos "Seu turno" e "Vez do adversário".
- Mão maior, em leque, e bordas menos arredondadas.

## R98 — 1.0.143-snapshot.98
- **Eventos em mosaico:** Gazeta Open, Desafio do Sam, Relâmpago, Pacote surpresa, Tipo da semana e Caça à carta, com resumo do dia. Para jogador novo, só o Sam fica aceso.
- Primeira versão da mesa nova.
- Máquinas do Gachamon para as coleções futuras (Neo e VS), ainda travadas.

## R94 a R97 — artes, jornada e feiras
- **16 artes HD** de personagens. O Mason dá a aula inicial e entrega o ticket; o Sam cuida das demais falas.
- **Jornada até Kanto:** depois da Invasão Rocket, porto, duelo obrigatório com o **Ronald**, campeão da ilha, e embarque. Na derrota, o ticket fica guardado.
- **Feiras regionais:** a da Ilha e a de Celadon, com cotas próprias.
- Fundos transparentes em todos os retratos (sem quadrados pretos), identidades corrigidas (Gene, Isaac, Mitch e Steve) e Mason sem fundo preto nas falas.

## R93
- Correção: a cápsula do Gachamon atravessava a base da máquina.

## R92
- Abas da Gazeta (Pacotes, Avulsas, Gacha, Temáticos e Eventos) no mesmo estilo das telas novas.

## R91 — progressão dos clubes e selos
- Clubes liberados aos poucos: o Cassino depois do Rick, a Mansão depois de três Mestres, o Fogo com 300 cartas na coleção e a Planta depois de três trocas.
- História do acidente do Isaac no laboratório.
- **40 selos**, cinco por Mestre de clube, com objetivos próprios.
- Promoção a Gerente e ícone da Feira aos sábados.

## R89 e R90
- O zoom da ilha não afasta mais além do enquadramento normal. Mapa com cantos retos e ícone novo de reenquadrar.
- O aviso de prêmios pendentes passou para o avatar e para Recibos e notificações.

## R88 — economia
- **Prêmios maiores:**
  - Rocket: recruta 100, executivo 200 e chefe 400;
  - treinadores de rota de Kanto: 120;
  - pupilos de ginásio: 150;
  - líderes: 500 créditos e 3 boosters;
  - Grandes Mestres: 750 créditos e um booster de cada coleção.
- O Sam pede confirmação antes de compras de temáticos e cartas avulsas, e avisa quando a carta é repetida.

## R87
- O passeio do Sam no tutorial mostra as telas atuais (Jogo Rápido e Ilha dos Clubes) e não revela mais a Invasão Rocket antes da hora.
- Corrigido um erro de inicialização.

## R84 a R86 — painéis temáticos
- Painéis próprios para os **oito clubes**, os **oito líderes de Kanto** (com os 24 treinadores de rota), os **seis Rockets** e os **quatro Grandes Mestres**.
- Avatares próprios dos Rockets.

## R83
- **Ilha dos Clubes em 4K**, carregando os detalhes conforme o zoom.

## R79 a R82 — IA do Game Boy
- Os **12 mestres** (oito de clubes e quatro do Grande Salão) jogam com as prioridades dos decks do Pokémon TCG de Game Boy.
- Os chefes e depois todos os NPCs começam com uma mão inicial favorecida, como no Game Boy: pelo menos dois Pokémon Básicos e duas Energias.
- IA revisada: planos por deck, avaliação da mão e personalidades.

## R78 — o Grande Salão
- Arena dos **quatro Grandes Mestres**, com banners próprios.
- Avatares de combate dos Grandes Mestres preservados.

## R77 — base Rocket
- A Invasão Rocket virou uma **base secreta** com seis desafios: três recrutas, dois executivos (Devastation e Trouble) e o chefe.
- **Quatro avatares iniciais** para o jogador.
- Setas de navegação sem moldura.

## R75 e R76
- Pontos maiores em Kanto, com destaque nos líderes e os banners antigos ao selecionar.
- Ilha com mais detalhes e zoom liberado.
- Retratos corrigidos: nomes e rostos dos treinadores agora combinam.

## R74 — mapa de Kanto
- **Mapa ilustrado de Kanto** com 32 pontos: 24 treinadores de rota e oito ginásios. Tocar num ponto aproxima e mostra o cartão do adversário.

## R73
- Boosters de coleção ainda travada não chegam mais antes da hora. Os Team Rocket ganhos na Invasão ficam **apreendidos** e o Sam entrega todos ao final.
- **Encontros opcionais** na ilha: treinadores com "!" aparecem pelas ruas.

## R72 — Ilha dos Clubes
- **Ilha ilustrada e explorável** para a Batalha dos Clubes, com bairros, porto, Gazeta e a praça da Feira do Troca.
- Dá para arrastar, aproximar com dois dedos ou ver a ilha inteira.

## R70 e R71 — Desafio dos 8 ilustrado
- Oito cenários: Floresta de Viridian, Mt. Moon, Ponte Pepita, Túnel de Pedra, Ciclovia, Dojo de Karatê em Saffron, Ilhas Seafoam e Rota 22.
- Trilha no mapa, marcadores por região e cartões dos ginásios com o retrato do líder.

## R69 — Grande Salão
- O Grande Salão abre depois dos 8 líderes, com Courtney, Steve, Jack e Rod. Eles usam os decks e as cartas lendárias do Game Boy, no nível mais alto.
- Capas de booster sorteadas com chance igual entre as artes.

## R68
- Abas da campanha fixas no topo.
- Detalhe da carta abre direto em 3D.
- Lápis para editar o deck na seleção.
- Janine antes do Koga.

## R67
- **Batalha dos Clubes** com seis duelos por clube: cinco membros e depois o Mestre.
- **Desafio dos 8** como caminho, com três treinadores de rota antes de cada ginásio.
- **40 decks novos** de NPC.
- Avatar do jogador: foto própria ou o avatar de qualquer NPC derrotado.
- Efeitos novos na partida (Treinador, Energia, entrada e evolução) e descarte em grade.
- Troca Relâmpago a cada 30 minutos.
