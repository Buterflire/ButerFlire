# Jogabilidade 

## <a name="stats"> Stats

### <a name="stats_pontos"> Pontos de Stats
Pontos de Stats podem ser usados para melhorar suas estatísticas

Stats       | Aumento/ponto investido   | Descrição
:-----:     | :-----------------------: | :--------:
HP          | 5                         | Máximo de vida
Mana        | 5                         | Máximo de Mana
Força       | 5                         | Força de [Ataques Físicos](#combate_fisico)
Arma        | 5                         | Força de [Ataques com Equipamento](#combate_fisico_equipamentos)
Agilidade   | 1                         | Velocidade de movimentação
Resistência | 5                         | Diminuição de dano sofrido
Sorte       | 1                         | Chances de conseguir itens
Percepção   | 1                         | Distância que um inimigo será percebido
Defesa      | 5                         | Chances de defender um [Ataque Físico](#combate_fisico)
Magia       | 5                         | Força de [Ataques Mágicos](#combate_magico)

## <a name="status"> Status

Status      | Descrição
:---------: | :-------:
Gold        | Dinheiro comum do jogo. Pode ser usado para comprar itens em lojas, aprender magias com NPCs, entre ouros
BGC         | Dinheiro especial do jogo. Pode ser usado para comprar itens que não são encontrados nas lojas mas que são dropados de NPCs e Bosses
Nível       | Nível atual do personagem
Experiência | Experiência acumulada para aumentar o nível do personagem
Inventário  | Inventário que retém todos os itens pertecentes a este personagem

## <a name="combate"> Combate

### <a name="combate_fisico"> Ataque Físico

#### <a name="combate_fisico_estilos"> Estilos
Estilos de luta é um Combate Físico de mãos vazias

Estilo      | Descrição
:---------: | :-------:

#### <a name="combate_fisico_equipamentos"> Equipamentos
É um Combate Físico usando Equipamentos

##### <a name ="combate_fisico_equipamentos_curto"> Curta Distância
Combate Físico utilizando Equipamentos de curta distância. São eles:


##### <a name ="combate_fisico_equipamentos_media"> Média Distância
Combate Físico utilizando Equipamentos de média distância São eles:
- Arco e Flecha

##### <a name ="combate_fisico_equipamentos_longa"> Longa Distância
Combate Físico utilizando Equipamentos de longa distância São eles:

### <a name="combate_magico"> Ataque Mágico

#### <a name="combate_magico_elementos"> Magias
Cada tipo de magia tem habilidades e formas diferentes de lutar

Magia       | Mestre        | Tipo          |
:---------: | :-------:     | :-----------: |
Fogo        | Blaze Heart   | Intangível    |
Gelo        | Frost Lucius  | Tangível      |
Água        | Hydro Mayne   | Tangível      |
Ar          | Aero Phyiron  | Intangível    |
Terra       | Geomagus Gaia | Tangível      |
Escuridão   | Eclipsy       | Intangível    |
Luz         | Illuminate    | Intangível    |
Magma       | Moltenfury    | Tangível      |
Trovão      | Thunderfury   | Intangível    |

##### <a name="combate_magias_fogo_skills"> Skills

Tecla de Atalho | Custo de Mana | Maestria  | Descrição
:-------------: | :-----------: | :------:  | :-------:
Z               | 250           | 1         | O usuário dispara uma bola de fogo que explode ao entrar em contato com algum sólido
X               | 500           | 50        | Descrição da Skill aqui
C               | 1000          | 100       | Descrição da Skill aqui
V               | 2500          | 150       | Descrição da Skill aqui
F               | 5000          | 200       | Descrição da Skill aqui

## <a name="racas"> Raças

### <a name="racas_habilidade_raca"> Habilidade de Raça
No mundo de Elementia, existem diversas raças, cada uma com suas especialidades em certas áreas mas todas possuem *Habilidades de Raça*.
Habilidades de Raça são habilidades exclusivas para cada raça, podendo ser passivas e/ou ativas

### <a name="racas_humanos"> Humanos
Humanos são uma raça equilibrada. Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 200
Mana        | 200
Força       | 10
Arma        | 10
Agilidade   | 10
Resistência | 10
Sorte       | 10
Percepção   | 10
Defesa      | 10
Magia       | 10

Habilidade de Raça  | Uso       | Duração(s)            | Cooldown(s)   | Descrição
:-----------------: | :------:  | :-------------------: | :-----------: | :-------:
Último Recurso      | Ativa     | 30                    | 30            | O usuário recebe 50% + Dano, Resistência, Defesa, Agilidade e Magia
Meditação           | Ativa     | 10                    | 30            | O usuário descansa seu corpo e mente, aumentando em 30% sua recuperação de HP e Mana

### <a name="racas_elfo"> Elfo
Elfos vindos da Grande Floresta de Elementia, tendo treinamento com arco e flecha e magias de agilidade há gerações são os melhores no que fazem
Raça focada em [Combate de Média Distância](#combate_fisico_equipamentos_medio). Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 300
Mana        | 300
Força       | 0
Arma        | 50
Agilidade   | 50
Resistência | 0
Sorte       | 10
Percepção   | 10
Defesa      | 0
Magia       | 20

Habilidade de Raça  | Uso       | Duração(s)            | Cooldown(s)   | Descrição
:-----------------: | :------:  | :-------------------: | :-------:     | :-------:
Chuva de Flechas    | Ativa     | 10                    | 30            | O cooldown do usuário para disparar flechas é diminuído em 80%, além de não ser mais necessário ter Mana para usar seu arco
Melhor Percepção    | Ativa     | 30                    | 30            | O usuário dobra sua capacidade de perceber inimigos


### <a name="racas_fada"> Fada
Fadas vindas da Árvore Sagrada de Elementia, seres que após milênios de gerações chegaram ao tamanho de um humano comum, essas amáveis criaturas se sobressaem em uso de magia.
Raça focada em suporte e [Ataque Mágico](#combate_magico). Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 300
Mana        | 500
Força       | 0
Arma        | 0
Agilidade   | 50
Resistência | 0
Sorte       | 10
Percepção   | 10
Defesa      | 0
Magia       | 50

Habilidade de Raça  | Uso       | Duração(s)            | Cooldown(s)   | Descrição
:-----------------: | :------:  | :-------------------: | :-----------: | :-------:
Invisibilidade      | Ativa     | 30                    | 30            | O usuário fica invisível e intocável
Último Suspiro      | Passiva   | 5                     | 30            | Ao morrer, o usuário cria um círculo mágico que cura seus aliados

### <a name="racas_fera"> Fera
Homens-Fera que têm sua origem desconhecida (ou será que não?). Uma mistura de Humanos com Lobos Mágicos, essas criaturas se estabeleceram e criaram sua civilização. Hoje vivem normalmente
Feras são uma raça focada em [Combates de Curta Distância](#combate_fisico_equipamentos_curto). Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 500
Mana        | 200
Força       | 100
Arma        | 0
Agilidade   | 50
Resistência | 50
Sorte       | 10
Percepção   | 10
Defesa      | 50
Magia       | 10

Habilidade de Raça  | Uso       | Duração(s)            | Cooldown(s)   | Descrição
:-----------------: | :------:  | :-------------------: | :-------:     | :-------:
Impenetrável        | Ativa     | 30                    | 30            | O usuário recebe 80% + Resistência
Marcado             | Passiva   | 30                    | 30            | Todos aqueles acertados pelo usuário serão marcados e estarão à vista enquanto a habilidade estiver ativa

### <a name="racas_necromante"> Necromante
Seres do antigo alto escalão do Rei Demônio, estes possuem, talvez, um dos conhecimentos mais cobiçados: o segredo da Ressureição
Necromantes são uma raça focada em [Ataque Mágico](#combate_magico), embora não participem integralmente das batalhas. Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 200
Mana        | 500
Força       | 0
Arma        | 0
Agilidade   | 10
Resistência | 0
Sorte       | 0
Percepção   | 50
Defesa      | 0
Magia       | 100

Habilidade de Raça  | Uso       | Duração(s)            | Cooldown(s)   | Descrição
:-----------------: | :------:  | :-------------------: | :-----------: | :-------:
Ressureição         | Ativa     | 60                    | 120           | O usuário invoca um exército de lacaios para lutar em seu nome(o nível do usuário e o horário influenciam na quantidade e força)
Transferência       | Ativa     | 1s                    | 300           | O usuário transfere sua consciência para um dos seus lacaios com 20% de seu HP e Mana totais
