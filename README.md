# ⚙️ | Projetos Digitais e Microprocessadores - Microprocessador MIPS simples

## Sobre o repositório
Esse repositório contém o trabalho desenvolvido para a disciplina de Projetos Digitais e Microprocessadores para o 2º semestre do curso de Ciência da Computação na Universidade Federal do Paraná. O objetivo era desenvolver um microprocessador simples inspirado na arquitetura MIPS através dos aprendizados durante as aulas. 

## Tecnologias e ferramentas utilizadas
 - Logisim Evolution v3.8.0

## Imagem do projeto
![microprocessador](https://github.com/user-attachments/assets/572e96d7-7fb9-480d-8325-f207cddaa8ab)

## Obs:
 - O programa de teste segue o seguinte programa exemplo:

```c
#include <stdio.h>

int main() {
    int N,      // Número de termos
        a,      // Termo inicial
        d,      // Razão
        soma;   // Soma da PA
    
    N = 10;    
    a = 7;     
    d = 18;    
    soma = 0;

    for (int i = 0; i < N; i++) {
        soma += a + i * d;
        printf("%d\n", soma);
    }

    printf("%d\n", soma);
    
    return 0;
}
```

- Nas memórias ROM coloque o arquivo .txt correspondente, cada um deles contém as informações em formato hexadecimal para o microprocessador operar corretamente

