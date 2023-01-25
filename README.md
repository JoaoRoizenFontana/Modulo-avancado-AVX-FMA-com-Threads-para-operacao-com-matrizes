# AVX/FMA com Threads para operação com matrizes

O objetivo deste trabalho é aprimorar o módulo escrito em linguagem C, chamado matrix_lib.c, com a utilização de instruções vetoriais (AVX/FMA), usando a biblioteca Intel Intrinsics, e processamento paralelo, usando a biblioteca pthread. Ambas as operações aritméticas com matrizes devem ser implementadas com instruções vetoriais e processamento paralelo: produto de um escalar por uma matriz (scalar_matrix_mult) e produto de duas matrizes (matrix_matrix_mult). Também deve ser implementado um programa de teste deste módulo fazendo uso do módulo de cronômetro fornecido para medir o tempo global de execução do programa de teste, assim como os tempos parciais de execução de cada uma das funções implementadas.

Eng: The objective of this work is to improve the module written in C language, called matrix_lib.c, with the use of vector instructions (AVX/FMA), using the Intel Intrinsics library, and parallel processing, using the pthread library. Both arithmetic operations with matrices must be implemented with vector instructions and parallel processing: product of a scalar by a matrix (scalar_matrix_mult) and product of two matrices (matrix_matrix_mult). A test program for this module must also be implemented using the timer module provided to measure the global execution time of the test program, as well as the partial execution times of each of the implemented functions.
