# PokeHub
Aonsciousness of a pokemon fans.

### Step 0: Name List and Image Crawling
From the official web of PokemonGo~  
This is the first Pokemon in the [Pokedex](https://www.pokemon.com/us/pokedex/):    
https://www.pokemon.com/us/pokedex/bulbasaur  
![The web outline](https://github.com/TagineerDai/PokeHub/blob/master/bulbasaur_web.png)

And we are going to crawl every name/picture/infomations/link_to_next_pokemon for all the 801 pokemons.

First lets try [beautiful soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/index.zh.html).

Now we have name and photo of Pokemons. From Google Image, with [icrawler](https://pypi.python.org/pypi/icrawler/0.2.2)'s built in module, we could crawl more photos of them. Every pokemon will have 50 photos of them.  

(Only the first pic from official website will be show in this repo.)
