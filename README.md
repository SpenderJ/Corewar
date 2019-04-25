# Corewar
42 2018 - Algorithmic project with sgauguet, jebossue and aserguie

### What is Corewar

Corewar is the last algorithmic project in the algorithm's cirle branch at 42.

The goal of the project is to implement a VM and an ASM able to handle champions, and let them fight in a defined memory zone.

## Running the tests

Our project mark is : 125 / 100

If you want to test our project, you just have to

We have an error management.

```
./asm [-va] <source-file.s>
-v : Instead of creating a .cor file, print the code.
-a : Create the .cor file and print the result
in hexadecimal.
-b : Create the .cor file and print evry lines &
the hexa code corresponding

/corewar [-a -d N -s N -v N | -visu] [-n N] <champion1.cor> [-n N] <champion2.cor> <...>
	-a        : Prints output from "aff" (Default is to hide it)
#### TEXT OUTPUT MODE #################################################
	-d N      : Dumps memory after N cycles then exits
	-s N      : Runs N cycles, dumps memory, pauses, then repeats
	-v N      : Verbosity levels
		- -1 : Show everything
		- 0  : Show only essentials
		- 1  : Show lives
		- 2  : Show cycles
		- 4  : Show operations (Params are NOT litteral ...)
		- 8  : Show deaths
		- 16 : Show PC movements (Except for jumps)
#### CHANGE PLAYER ORDER ##############################################
	-n N      : Attributes Nth place to following champion  if available.
#### NCURSES OUTPUT MODE ##############################################
	-visu     : Ncurses output mode
#######################################################################
```

## Contributing

Jules Spender
Simon Gauguet
Jean Bossuet Tiercelin
Adrien Serguier

## Authors

* **Simon Gauguet** - *Initial work*
* **Jean Bossuet Tiercelin** - *Initial work*
* **Adrien Serguier** - *Initial work*
* **Jules Spender** - *Initial work* - https://github.com/SpenderJ

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Memory management.
* Speed.
* Error Handling.
* Visualisator.
