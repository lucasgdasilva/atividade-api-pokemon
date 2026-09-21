# Buscador Pokémon

Esse projeto utiliza a PokéAPI (https://pokeapi.co/) para retornar dados de qualquer Pokémon.

A documentação da PokéAPI pode ser encontrada em: https://pokeapi.co/docs/v2.

Ao pesquisar pelo nome de um Pokémon ou clicar no botão "Aleatório", o programa irá buscar os dados na API e retornar as seguintes informações:
- Nome do Pokémon
- ID Do Pokémon na Pokédex
- Peso
- Altura
- Nível de experiência base
- Imagem do Pokémon

Tanto o nome quanto o ID do Pokémon podem ser utilizados na busca.

Por exemplo, o seguinte endereço consulta os dados do meu Pokémon favorito, o Piplup: https://pokeapi.co/api/v2/pokemon/393.

# Como rodar?

Clone esse repositório ou extraia todos os arquivos, e execute "index.html"

Insira o nome ou o ID de um Pokémon na barra de pesquisa e aperte em "Pesquisar". Qualquer ID de 1 a 1025 é válido. 

Se preferir, pressione o botão "Aleatório", que retornará um Pokémon qualquer.

# Problemas enfrentados

Durante o desenvolvimento, o principal problema que tive foi obter os dados das imagens do Pokémon. Isso porque na PokéAPI, várias imagens de diversos tipos de Pokémon são fornecidas.
Para resolver, eu busquei mais a fundo e consegui identificar qual imagem eu precisava, e com a ajuda do Professor Éwerton, consegui implementar o código que busca a imagem corretamente.

![Print da tela funcionando](imagem.png)
