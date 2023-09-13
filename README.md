# PiSearch
A program that finds the positions of a number pattern in the given decimals of Pi.

The script is a Python program that searches for a number pattern in the decimals of Pi with a given precision. The program first imports the mpmath library, which is a Python library for high-precision mathematics.

The program then defines a function called search_pi_all(), which takes two arguments: the pattern to search for and the desired precision of Pi. The function first sets the precision of Pi using the mp.dps function. Then, it gets the string representation of Pi with the desired precision using the str() function.

The function then initializes a list to store the positions where the pattern is found. It starts by finding the first occurrence of the pattern in the string representation of Pi using the find() function. If the pattern is found, the function appends the index of the occurrence to the list of positions. Then, it starts the next search after the previously found position.

The function continues searching for the pattern until it cannot find it anymore. It then returns the list of positions where the pattern was found.

The main function of the program first asks the user to enter the number pattern they want to search for in Pi. Then, it calls the search_pi_all() function with the number pattern and the desired precision (25000 decimal places).

If the pattern is found, the function prints the positions where the pattern was found and the total number of times it was found. Otherwise, the function prints a message saying that the pattern was not found.

Here is an Example Output for pattern 420 in the PiDecimals:

  ![image](https://github.com/Nielymmah/PiSearch/assets/103298455/18c19573-c7e1-4899-a3ad-cd6ced8ebca9)
