# Jogabilidade 

## <a name="stats"> Stats

### <a name="stats_pontos"> Pontos de Stats
Pontos de Stats podem ser usados para melhorar suas estatísticas

Stats       | Aumento/ponto investido   | Descrição
:-----:     | :-----------------------: | :--------:
HP          | 5                         | Máximo de vida
Mana        | 5                         | Máximo de Mana
Força       | 5                         | Força de [Ataques Físicos](#combate_fisico)
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

### <a name="racas_humanos"> Humanos
Humanos são uma raça equilibrada. Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 200
Mana        | 200
Força       | 10
Agilidade   | 10
Resistência | 10
Sorte       | 10
Percepção   | 10
Defesa      | 10
Magia       | 10

### <a name="racas_elfo"> Elfo
Elfos vindos da Grande Floresta de Elementia, tendo treinamento com arco e flecha e magias de agilidade há gerações são os melhores no que fazem
Raça focada em [Combate de Média Distância](#combate_fisico_equipamentos_medio). Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 300
Mana        | 300
Força       | 0
Agilidade   | 50
Resistência | 0
Sorte       | 10
Percepção   | 10
Defesa      | 0
Magia       | 20

### <a name="racas_fada"> Fada
Fadas vindas da Árvore Sagrada de Elementia, seres que após milênios de gerações chegaram ao tamanho de um humano comum, essas amáveis criaturas se sobressaem em uso de magia.
Raça focada em suporte e [Ataque Mágico](#combate_magico). Seus stats iniciais são:

Stats       | Quantidade
:-----:     | :----:
HP          | 300
Mana        | 500
Força       | 0
Agilidade   | 50
Resistência | 0
Sorte       | 10
Percepção   | 10
Defesa      | 0
Magia       | 50

Habilidade de Raça  | Uso       | Descrição
:-----------------: | :------:  | :-------:
Invisibilidade      | Ativa     | O usuário fica invisível e intocável enquanto durar sua [Mana](#stats)
Último Suspiro      | Passiva   | Ao morrer, o usuário cria um círculo mágico que cura seus aliados


### <a name="racas_fera"> Fera
Feras são uma raça focada em [Combates de Curta Distância](#combate_fisico_equipamentos_curto)

Stats       | Quantidade
:-----:     | :----:
HP          | 300
Mana        | 500
Força       | 0
Agilidade   | 50
Resistência | 0
Sorte       | 10
Percepção   | 10
Defesa      | 0
Magia       | 50

