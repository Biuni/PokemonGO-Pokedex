# Pokémon GO Pokédex
Pokédex of Pokémon GO in JSON. **(1st generation)**

# Elements
*   **id**: *Identification Number*
*   **num**: *Number of the Pokémon in the official Pokédex*
*   **name**: *Pokémon name*
*   **img**: *URL to an image of this Pokémon*
*   **type**: *Pokémon type*
*   **height**: *Pokémon height*
*   **weight**: *Pokémon weight*
*   **candy**: *type of candy used to evolve Pokémon or given when transfered*
*   **candy_count**: *amount of candies required to evolve*
*   **egg**: *Number of kilometers to travel to hatch the egg*
*   **spawn_chance**: *Percentage of spawn chance* **(NEW)**
*   **avg_spawns**: *Number of this pokemon on 10.000 spawns* **(NEW)**
*   **spawn_time**: *Spawns most active at the time on this field. Spawn times are the same for all time zones and are expressed in local time.* **(NEW)**
*   **multipliers**: *Multipler of Combat Power (CP) for calculating the CP after evolution*  [See below](#multipliers)
*   **weakness**: *Types of Pokémon this Pokémon is weak to*
*   **next_evolution**: *Number and Name of successive evolutions of Pokémon*
*   **prev_evolution**: *Number and Name of previous evolutions of Pokémon*

## Multipliers

The formula is `EvolvedCP = OriginalCP x multiplier`.

Example usage of multipliers:
I want to evolve my Bulbasaur with 200 CP. The future Ivysaur will have `365 = 200 x 1.58` CP.

If there are two or more values in `multipliers` is because there is a maximum and minimum of evolution CP possible.
