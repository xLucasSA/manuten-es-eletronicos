---
---

<img src="assets/css/style.svg" width="0" height="0" alt="css-in-readme">

# Sistema de Manutenções

Deverá conter área para que os clientes possam acompanhar manutenções e possivelmente terá dashborads. Pode receber vários clientes e também vários produtos com características diferentes

Sistema baseado em estrutura de classes. 

### Manutenções
1. Será possível lançar manutenções realizadas em diversos equimantos.
2. Essas manunteções deverão conter informações do que foi executado para que possa ser acompanhado pelas diretorias;
3. O que foi executado deverá conter detalhes de acordo com o tipo de equipamento;
4. Clientes poderão lançar pedidos de manutenção em equipamentos;
5. Campos essenciais para o controle:
    - Código Cliente;
    - Tipo de equipamento;
    - Data manutenção;
    - Registros;
    - Status equipamento;
    - Código do equipamento;
    - Código Solicitação;


### Equipamentos
1. As características dos equipamentos deverá ser uma estrutura modular para que se possa fazer os registros e acrescentar novas características;
2. Deverá ser possível editar internamente as características de um determinado equipamento;
3. Cada característica deverá ser associada a uma categoria de característica para facilitar o controle de saídas para usuários;
4. Essa categoria estará ligada aos componentes padrões de todos os equipamentos e não poderá ser editada;
5. Campos essenciais:
    - Categorias;
    - Característica;
    - Tipo de Equipamento;
    - Nome do Equipamento
    - Código Equipamento;


### Empresas
1. Campos:
    - Nome do Cliente;
    - Código do Cliente;
    - Acessos (Login e Senha)

### Solicitações
1. Campos:
    - Codigo Cliente;
    - Nome do Solicitante;
    - Código Equipamento;
    - Descrição do Problema;
    - Código Solicitação;
