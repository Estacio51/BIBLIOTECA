# include <stdio.h>

//definindo a estrutura do tipo aluno 
typedef struct {
    char nome [50];
    int idade;
    flot média;
} Aluno;

int main () {
    //criando uma variável do tipo aluno
    Aluno aluno1 = {"João", 20, 8.5};

    //Exibindo os dados do aluno
    printf ("aluno: %s
    idade: %d
    média: %.2f
    "aluno1. nome, aluno1. idade, aluno1. média);
    return 0;

}
