#Azure-RecursosCopilot

Este projeto faz parte da Prática 3 do curso Serviços Cloud com foco em IA: Explorando os Recursos de IA Generativa com Copilot e OpenAI.

#Descrição

Este projeto explora a utilização do Chat Copilot, uma ferramenta baseada em IA generativa, para responder a solicitações do usuário e gerar conteúdos diversos.

#Entradas e Saídas

##Inputs (Solicitações realizadas para o Chat Copilot):

Me indique os melhores destinos de viagem no Nordeste do Brasil.

Gere uma imagem de um casal viajando nos Lençóis Maranhenses (MA).

Faça um código simples de uma calculadora usando a linguagem C.

##Outputs (Respostas fornecidas pelo serviço de IA Copilot):

1. Melhores destinos de viagem no Nordeste do Brasil:

O Nordeste do Brasil é um verdadeiro paraíso com destinos incríveis! Aqui estão alguns dos melhores lugares para visitar:

Fernando de Noronha (PE): Arquipélago paradisíaco com praias de águas cristalinas, perfeito para mergulho e contato com a natureza.

Lençóis Maranhenses (MA): Dunas e lagoas de água doce que formam um cenário único no mundo.

Porto de Galinhas (PE): Famoso por suas piscinas naturais e praias de areia branca.

Jericoacoara (CE): Conhecida como "Jeri", oferece lagoas de água doce, dunas e um pôr do sol espetacular.

Chapada Diamantina (BA): Ideal para quem ama ecoturismo, com cachoeiras, grutas e trilhas incríveis.

Maceió (AL): Praias urbanas e piscinas naturais que encantam qualquer visitante.

Esses destinos combinam beleza natural, cultura rica e hospitalidade calorosa. Qual deles chamou mais a sua atenção? 😊

2. Geração de imagem:
![um casal viajando nos lençóis maranhenses (1)](https://github.com/user-attachments/assets/9c0fe159-59e3-4af7-ba1e-1197b250a549)

3. Código em C - Calculadora Simples:

#include <stdio.h>

int main() {
    char operacao;
    double num1, num2, resultado;

    printf("Escolha uma operação (+, -, *, /): ");
    scanf(" %c", &operacao);

    printf("Digite o primeiro número: ");
    scanf("%lf", &num1);

    printf("Digite o segundo número: ");
    scanf("%lf", &num2);

    switch (operacao) {
        case '+':
            resultado = num1 + num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '-':
            resultado = num1 - num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '*':
            resultado = num1 * num2;
            printf("Resultado: %.2lf\n", resultado);
            break;
        case '/':
            if (num2 != 0) {
                resultado = num1 / num2;
                printf("Resultado: %.2lf\n", resultado);
            } else {
                printf("Erro: Divisão por zero!\n");
            }
            break;
        default:
            printf("Operação inválida!\n");
    }
    return 0;
}

#Insights obtidos com o projeto

A IA generativa pode auxiliar na criação de conteúdos diversos, desde textos informativos até códigos de programação.

O Chat Copilot pode ser usado para gerar imagens a partir de descrições textuais.

A ferramenta proporciona rapidez e eficiência na obtenção de informações e soluções técnicas.

A interação com IA pode ser aprimorada ao fornecer solicitações bem detalhadas, garantindo respostas mais precisas e úteis.
