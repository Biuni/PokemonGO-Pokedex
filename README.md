# Pokémon GO Pokédex
Pokédex of Pokémon GO in JSON

# Elements
*   **id**: *Identification Number*
*   **num**: *Number of the Pokémon in the official Pokédex*
*   **name**: *Pokémon name*
*   **img**: *Pokémon image*
*   **type**: *Pokémon type*
*   **height**: *Pokémon height*
*   **weight**: *Pokémon weight*
*   **candy**: *Number of candy to evolve Pokémon*
*   **egg**: *Number of kilometers to travel to hatch the egg*
*   **multipliers**: *Multipler of Combat Power (CP) for calculating the CP after evolution* **(NEW)**  [See below for an example]
*   **weakness**: *Types of Pokémon this Pokémon is weak to* **(NEW)**
*   **next_evolution**: *Number and Name of successive evolutions of Pokémon* **(NEW)**
*   **prev_evolution**: *Number and Name of previous evolutions of Pokémon* **(NEW)**

<hr>

\* Example: I want to evolve my Bulbasaur with 200 CP. The calculation to know the CP of my future Ivysaur is: 200 * multiplier (in this case 1.58) = 356 CP. 
If there are two or more values in "multipliers" is because there is a maximum and minimum of evolution CP possible.
