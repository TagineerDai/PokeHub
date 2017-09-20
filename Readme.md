### Step 0: Name List and Image Crawling
From the official web of PokemonGo~  
This is the first Pokemon in the [Pokedex](https://www.pokemon.com/us/pokedex/):    
https://www.pokemon.com/us/pokedex/bulbasaur  
![The web outline](Bulbasaur_web.png)

And we are going to crawl every name/picture/infomations/link_to_next_pokemon for all the 801 pokemons.

First lets try [beautiful soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/index.zh.html).

Now we have name and photo of Pokemons. From Google Image, with [icrawler](https://pypi.python.org/pypi/icrawler/0.2.2)'s built in module, we could crawl more photos of them. Every pokemon will have 50 photos of them.  

(Only the first pic from official website will be show in this repo.)

### Step 1: Origin Data Preprocessing  
A dataset class `POKE801` and its related dislist `([catenum]cates.txt)` is provided.    
The input and generated image will be `128 x 128 x 3`.  
Since the `filetype:jpg` didn't work properly, we add a `PIL` converter.

**TBC**
### Step 2: The Poke GAN
*The training set may be still too small....*  
After the toy version a `POKE801v2` with 10000img/category will be provided.
