# Loja_de_Cartas_Virtual

## desenvolvedores:

Gabriel Arruda Guia RA:0791811005

Igor Bento de Brito RA: 0791811036

Lucas Soiti da Silva Ganaka RA: 0791811004


## Descrição do Projeto
<p align="justify"> Sistema de armazenamento de dados de cartas, que permite o cadastro, visualização e alteração dos dados armazenados </p>

<p align="justify"> Os dados que devem ser armazenados em cada registro são: </p>

- URL da imagem da carta 
- Id da carta
- Nome da carta 
- Raridade da carta
- Série da carta
- Coleção da carta

## Descrição do código
<p align="justify"> Primeiro criamos a class Pokemon com os atributos referêntes aos dados das cartas que serão armazenados.</p>

<p align="justify"> A class PokemonDAO  vai fazer a interação entre o banco de dados e o sistema. A função PokemonCatchAll busca todos os dados que estão armazenados no banco de dados, a função PokemonUpDate atualiza os dados de uma carta já inserida no banco de dados apartir do nome da carta e do dado a ser alterado, a função PokemonAdd adiciona uma carta ao banco de dados</p>

<p align="justify"> Dentro do sistema temos a função menuzinho que exibe as opções para o usúario, a função CadastrarCarta pega os dados a serem cadastrados e chama a função que adiciona uma nova carta, a função Updatecarta pega os dados a serem atualizados e chama a função que atualiza os dados cadastrados, a função PokemonMyDeck exibe todos os dados cadastrados. E por fim o loop infinito roda o sistema para o usuario </p>


