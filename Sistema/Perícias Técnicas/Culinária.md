## Culinária

Comida nada mais é do que um item mundano que enche a barriga das pessoas. Os grandes mestres cozinheiros, contudo, conseguem preparar seus pratos de uma maneira especial, criando delícias que possuem efeitos considerados mágicos.

*Culinária* pode ser utilizada para preparar pratos que concedem *Condições de Status* positivas àquele que o consumir.

### Bases do Projeto

Comece definindo qual condição de status o prato ou bebida conferirá:

* [Agility Up](https://github.com/felipevfa/FFRPG3/blob/master/Sistema/Condições%20de%20Status.md#agility-up)
* [Armor Up](https://github.com/felipevfa/FFRPG3/blob/master/Sistema/Condições%20de%20Status.md#armor-up)
* [Magic Up](https://github.com/felipevfa/FFRPG3/blob/master/Sistema/Condições%20de%20Status.md#magic-up)
* [Power Up](https://github.com/felipevfa/FFRPG3/blob/master/Sistema/Condições%20de%20Status.md#power-up)
* [Spirit Up](https://github.com/felipevfa/FFRPG3/blob/master/Sistema/Condições%20de%20Status.md#spirit-up)

Depois, escolha a categoria do projeto:

* **Consumíveis fora de batalha**:    
    - **Ração**: confere um status positivo por (4).
    - **Refeição**: confere um status positivo por (6).
* **Consumíveis somente em batalha**:
    - **Petisco**: confere um status positivo por (4).
* **Consumíveis a qualquer momento**:
    - **Bebida**: confere um status positivo por (2).
    - **Lanche**: confere um status positivo por (4).

**Banquetes** são considerados *refeições* que alimentam o grupo inteiro.

### Materiais

Projetos de culinária usam *materiais especiais*. O Tier e a quantidade de material utilizado dependem do tipo de projeto:

| Tipo de Alimento | Tier | Pontos de Criação | Horas de trabalho |
|:----------------:|:----:|:-----------------:|:-----------------:|
| Bebida           | 1    | 60                | 0.5               |
| Ração            | 3    | 15                | 1                 |
| Petiscos         | 4    | 15                | 1                 |
| Lanche           | 5    | 18                | 1                 |
| Refeição         | 6    | 16                | 2                 |
| Banquete         | 7    | 50                | 4                 |

### Modificadores de Custo e Tempo

O custo e o tempo necessário para preparar o prato podem ser modificados pela condição de status que elas conferem, conforme a tabela a seguir:

| Status     | Custo | Horas | Modificador de Teste |
|:----------:|:-----:|:-----:|:--------------------:|
| Agility Up | n/a   | n/a   | 0                    |
| Armor Up   | +25%  | n/a   | -10                  |
| Magic Up   | +50%  | +25%  | -10                  |
| Mental Up  | +25%  | n/a   | -10                  |
| Power Up   | +50%  | +25%  | -10                  |
| Spirit Up  | n/a   | n/a   | 0                    |

### Verificação de Perícia

Enfim, com tudo decidido, o cozinheiro faz a verificação da perícia Culinária. O teste pode ser modificado da seguinte maneira:

* **Preparar Bebiba:** 0
* **Preparar Ração:** -10
* **Preparar Petisco:** -15
* **Preparar Lanche:** -20
* **Preparar Refeição:** -30
* **Preparar Banquete:** -40

Outros modificadores, como os de [trabalho em grupo](https://github.com/felipevfa/FFRPG3/blob/master/Sistema/Per%C3%ADcia%20T%C3%A9cnica.md#trabalho-em-grupo) e [condições de trabalho](https://github.com/felipevfa/FFRPG3/blob/master/Sistema/Per%C3%ADcia%20T%C3%A9cnica.md#teste-de-per%C3%ADcia) podem ser aplicados se forem pertinentes.

### Exemplos de Comida

**BOLHA DE CHOCOLATE**  
**Descrição**: Este Lanche consiste em uma bolsa de ar presa dentro de uma fina camada de chocolate. Se preparada corretamente, a bolha de chocolate será mais leve que o ar; um desatento poderá acabar vendo seu chocolate fugindo dele se ele não prestar atenção. *Confere a Condição de Status Magic Up (4)*.

**MITHKABOB**  
**Descrição**: Nome genérico para Rações feitas com aves domésticas e pescado, muito aprecido pela raça Mithra. *Confere a Condição de Status Power Up (4)*.