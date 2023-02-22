all: hello_world arguments fork_test wait_test zombie

hello_world: hello_world.c
	gcc hello_world.c -Wall -Wextra -pedantic -o hello_world

arguments: arguments.c
	gcc arguments.c -Wall -Wextra -pedantic -o arguments

fork_test: fork_test.c
	gcc fork_test.c -Wall -Wextra -pedantic -o fork_test

wait_test: wait_test.c
	gcc wait_test.c -Wall -Wextra -pedantic -o wait_test

zombie: zombie.c
	gcc zombie.c -Wall -Wextra -pedantic -o zombie
clean:
	rm -f hello_world
	rm -f arguments
	rm -f fork_test
	rm -f wait_test
	rm -f zombie
