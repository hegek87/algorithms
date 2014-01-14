all:
	gcc -c -g -Wall graphs_as_list.c
	gcc -c -g -Wall ../../../Data-Structures/double_linked_list/double_linked_list.c
	
	gcc -o ./objects/graph_list double_linked_list.o graphs_as_list.o
	
	mv *.o ./objects
	rm -f *.o
