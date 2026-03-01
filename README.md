# Desafio-Movimenta-o-de-Pe-as-de-Xadrez---Tema-4
#include <stdio.h>

/*
 * DESAFIO TEMA 4 - MOVIMENTAÇÃO DE PEÇAS DE XADREZ
 * Objetivo: Simular o movimento de Torre, Bispo e Rainha usando loops.
 * Nível: Novato
 */

int main() {
    // Definição do número de casas para cada peça conforme o requisito
    int casasTorre = 5;
    int casasBispo = 5;
    int casasRainha = 8;

    // --- MOVIMENTAÇÃO DA TORRE (Usando FOR) ---
    // A Torre deve se mover 5 casas para a direita
    printf("### Movimentação da Torre ###\n");
    for (int i = 1; i <= casasTorre; i++) {
        printf("Direita\n");
    }
    printf("\n");

    // --- MOVIMENTAÇÃO DO BISPO (Usando WHILE) ---
    // O Bispo deve se mover 5 casas na diagonal (Cima e Direita)
    printf("### Movimentação do Bispo ###\n");
    int b = 1;
    while (b <= casasBispo) {
        printf("Cima, Direita\n");
        b++;
    }
    printf("\n");

    // --- MOVIMENTAÇÃO DA RAINHA (Usando DO-WHILE) ---
    // A Rainha deve se mover 8 casas para a esquerda
    printf("### Movimentação da Rainha ###\n");
    int r = 1;
    do {
        printf("Esquerda\n");
        r++;
    } while (r <= casasRainha);
    printf("\n");

    return 0;
}
