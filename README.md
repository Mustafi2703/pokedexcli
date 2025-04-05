# **Pokedex CLI**

Pokedex CLI is an interactive command-line application written in Go that allows Pokémon trainers to explore, catch, and manage Pokémon. By utilizing the **[PokeAPI](https://pokeapi.co/)**, this CLI fetches real-time Pokémon data and provides a variety of commands to mimic the experience of being a Pokémon trainer.

---

## **Features**
- 🗺️ **Explore**: Look around to encounter random Pokémon.
- 🔍 **Inspect**: View detailed stats, abilities, and descriptions of caught Pokémon.
- 🎯 **Catch**: Attempt to catch encountered Pokémon by name.
- 📚 **Pokedex**: Keep track of all the Pokémon you’ve caught with their unique IDs.
- 🌍 **Map**: Get a summary of Pokémon found in specific areas (where implemented).
- 💡 **Help**: See detailed information about the available commands.
- 🚪 **Exit**: Quit the application.

---

## Commands

This is a repl Cli based application with the following commands.


1. help

  Description: Displays a help message with information about all available commands.
  Usage:
  > help

2. catch <pokemon_name>

  Description: Attempts to catch a Pokémon by its name.
  Usage:
  > catch pikachu
  Throwing a Pokeball at pikachu...
  pikachu was caught!

3. inspect <pokemon_name>

  Description: Displays detailed information about a Pokémon you've already caught.
  Usage:
  > inspect bulbasaur
  Name: bulbasaur
  Type: Grass/Poison
  Height: 0.7 m
  Weight: 6.9 kg
  Abilities: Overgrow, Chlorophyll

4. explore <location_name>

  Description: Explores the specified location for a chance to encounter a Pokémon.
  Usage:
  > explore forest
  Searching the forest...
  You encountered charmander! Type `catch charmander` to catch it.

5. map

  Description: Displays the next page of available Pokémon locations.
  Usage:
  > map
  Location Page 2:
    - Cave: zubat, geodude
    - Ocean: magikarp, lapras

6. mapb

  Description: Displays the previous page of available Pokémon locations.
  Usage:
  > mapb
  Location Page 1:
    - Forest: bulbasaur, pikachu
    - River: psyduck, slowpoke

7. pokedex

  Description: Lists all the Pokémon you've caught so far.
  Usage:
  > pokedex
  Your Pokedex:

## **Technical Requirements**

  Go version 1.22.5 +

---

## **Installation Instructions**

1. Clone the repository using `git`:
   
   git clone https://github.com/Mustafi2703/pokedexcli.git

   Install Dependencies
   go  mod download

3. Navigate to the project directory:

cd pokedexcli

3. Build the application:

go build

4. Run the program:

./your-program-name

## License 


