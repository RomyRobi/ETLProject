# ETLProject
Extract, Transform, Load for Bulbapedia and pokemondb.net data

## File Run Sequence
Run files in the following sequence:
1. Pokemon Pandas Pkmn List (Extract from https://bulbapedia.bulbagarden.net/wiki/List_of_Pok%C3%A9mon_by_National_Pok%C3%A9dex_number and clean for better merge with abilities list)

2. Pokemon Pandas Pkmn Abilities (Extract from https://bulbapedia.bulbagarden.net/wiki/List_of_Pok%C3%A9mon_by_Ability, merge with types, and clean for calculations)

3. Combine PokeTable and TypeTable (Extract from https://pokemondb.net/type and custom AbilityTypeEff.csv, perform calculations of type effectiveness, clean for loading into MySQL, load into MySQL)

