Esse aplicativo consiste em um CRUD (Create, Read, Update e Delete) construído no Power Apps e automatizado via Power Automate. 
Pensando em um sistema dentro de uma empresa em que precisamos ter controle ou fazer algumas operações dentro de 
um banco de dados, decidi criar um CRUD personalizado. Apenas pessoas previamente cadastradas no banco de dados podem ter acesso.
Além disso, temos 4 funções, ou seja, se você está cadastrado apenas como editor ou exclusor poderá realizar apenas essas funções e não terá acesso às demais. Por exemplo, um usuário previamente cadastrado e com todas as funcionalidades liberadas verá o aplicativo assim: 
<div align="center">
<img src="https://github.com/kelymurta/CRUD-em-Power-Apps/assets/131712179/667d1478-7a26-4a20-b5bc-921cb641765e" width="400px" />
</div>
Caso o usuário possa apenas fazer consultas verá a primeira tela assim:
<div align="center">
<img src="https://github.com/kelymurta/CRUD-em-Power-Apps/assets/131712179/1df6e227-44cf-4087-ba43-7401795aae36" width="400px" />
</div>
Esse controle é adequado pois nem todo funcionário pode editar ou excluir registros de um banco de dados, na verdade, essa prática é muito perigosa e pode colocar em risco a integridade dos dados de uma empresa. As telas para as funcionalidades desse aplicativo são:

#### Cadastro:
<div align="center">
<img src="https://github.com/kelymurta/CRUD-em-Power-Apps/assets/131712179/14841dc6-63f9-4221-8e82-61ebbd4b8d83" width="400px" />
</div>

#### Consulta:
Além de consultar o usuário pode exportar os dados do usuário em um PDF encaminhado diretamente ao Outlook via fluxo do Power Automate.
<div align="center">
<img src="https://github.com/kelymurta/CRUD-em-Power-Apps/assets/131712179/a4e42fc2-2001-471a-9770-35ce3d0dea2d" width="400px" />

</div>

#### Edição:
Aqui é possível ativar um fluxo para que as edições sejam controladas por uma equipe que recebe as solicitações de edição via Microsoft Teams e aprova ou não essa operação. 
<div align="center">>
<img src="https://github.com/kelymurta/CRUD-em-Power-Apps/assets/131712179/16d9a740-1984-4817-a982-a27031ff79bb" width="350px" />
<img src="https://github.com/kelymurta/CRUD-em-Power-Apps/assets/131712179/24dcfbb0-74f1-4cf9-8632-0491b3a95fed" width="350px" />
</div>

#### Exclusão:
Para a exclusão de um registro é preciso autorização do desenvolvedor do banco de dados, sendo assim, ao clicar em excluir, a permissão deve ser concedida via fluxo antes que o registro desapareça.
<div align="center">
<img src="https://github.com/kelymurta/CRUD-em-Power-Apps/assets/131712179/59985b2b-8ab1-406e-b2c9-206f01ec0283" width="400px" />
</div>
