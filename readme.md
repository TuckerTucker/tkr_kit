# Cloning
use the --recursive flag when cloning to ensure the submodules are initialized 

``` sh
git clone --recursive http://github.com/tuckertucker/tkr_kit

```

# Init after cloning
if --recursive ins't used when cloning the submodules can be initialized 

``` sh
git submodule update --init --recursive

```

# .env

Add a .env file with an openai api key

OPENAI_API_KEY="sk-proj-yK ... xx23"
