# Compilación

` mpicc -o exec main.c structs.c utils.c io.c algorithms.c `

# Ejecución

` mpirun -np 8 --oversubscribe exec`

numero minimo de nodos: 2
