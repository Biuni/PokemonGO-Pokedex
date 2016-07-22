# Pokémon GO Pokédex
Pokédex of Pokémon GO in JSON

# Elements
*   **id**: *Identification Number*
*   **num**: *Number of the Pokémon in the official Pokédex*
*   **name**: *Pokémon name*
*   **img**: *URL to an image of this Pokémon*
*   **type**: *Pokémon type*
*   **height**: *Pokémon height*
*   **weight**: *Pokémon weight*
*   **candy**: *Number of candy to evolve Pokémon*
*   **egg**: *Number of kilometers to travel to hatch the egg*
*   **multipliers**: *Multipler of Combat Power (CP) for calculating the CP after evolution* **(NEW)**  [See below](#multipliers)
*   **weakness**: *Types of Pokémon this Pokémon is weak to* **(NEW)**
*   **next_evolution**: *Number and Name of successive evolutions of Pokémon* **(NEW)**
*   **prev_evolution**: *Number and Name of previous evolutions of Pokémon* **(NEW)**

## Multipliers

The formula is `EvolvedCP = OriginalCP x multiplier`.

Example usage of multipliers:
I want to evolve my Bulbasaur with 200 CP. The future Ivysaur will have `365 = 200 x 1.58` CP.

If there are two or more values in `multipliers` is because there is a maximum and minimum of evolution CP possible.
