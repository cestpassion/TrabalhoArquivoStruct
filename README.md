# Programa de Cadastro de Colaboradores

Bem-vindo! Este repositório contém um programa para cadastro de colaboradores, nele foi usado arquivo e struct na linguagem de programação C.

## Sobre📃:

Este repositório foi criado com o intuito de compartilhar meu projeto, e também, para ajudar estudantes interessados pelo assunto.

## Funcionalidades:

Uma empresa deseja fazer o cadastro dos colaboradores. Os dados que deverão ser persistidos (arquivo) são: código, nome, email e salário.

O programa permite as seguintes funcionalidades:

1) Cadastrar colaborador
2) Consultar colaborador por nome
3) Consultar colaborador por código
4) Alterar salário
5) Remover colaborador
6) Mostrar soma dos salários
7) Mostrar todos os colaboradores
0) Sair

## Struct:
```c
typedef struct Colaborador{
    int codigo;
    char nome[50];
    char email[50];
    double salario;
} Colaborador;
```

## Funções:
```c
void carregarMenu();
void salvarcolab();
void cadastrarColab(char*, char*, double);
int criarcodigo();
int verificaRepeticao(int);
void consultColabPorNome(char*);
void consultColabPorCodigo(int);
void alterarSalario(int);
void removColab(int);
void mostrarSomaSal();
void mostrarcolab(int);
void str(char **);
void mostrarTodosColab();
void pressioneparaVoltar();
void pressioneEnter();
```
> ###
