                      Sorteador de Números Aleatórios
========================================================================


DESCRIÇÃO
---------
Este projeto consiste em uma ferramenta simples e eficaz para a geração 
de números aleatórios sem repetição dentro de um intervalo definido pelo 
usuário. O script valida as entradas para garantir a consistência dos 
dados (como impedir intervalos inválidos ou requisições de quantidade 
superiores ao espaço amostral disponível) e atualiza dinamicamente a 
interface do usuário.

FUNCIONALIDADES
---------------
1. Sorteio de múltiplos números inteiros simultaneamente.
2. Garantia de não repetição de números dentro do mesmo sorteio.
3. Validação de intervalos numéricos (mínimo vs. máximo).
4. Validação de consistência de tamanho (quantidade vs. intervalo disponível).
5. Interface dinâmica com ativação/desativação do botão de reinício.
6. Função de reset completo dos campos e do estado da tela.

ESTRUTURA DO CÓDIGO FONTE
-------------------------
* `sortear()`: Função principal que gerencia o fluxo de captura de dados do 
  HTML, executa as validações lógicas, preenche a lista de sorteados 
  garantindo a exclusividade de cada número, renderiza o resultado na tela 
  e alterna o status dos controles de interface.
* `obterNumeroAleatorio(min, max)`: Função utilitária que implementa a lógica 
  matemática para geração de um número pseudoaleatório uniformemente 
  distribuído dentro do intervalo inclusivo [min, max].
* `alterarStatusBotao()`: Modifica dinamicamente as classes CSS do botão de 
  reinicialização para prover feedback visual sobre o estado da aplicação.
* `reiniciar()`: Restaura o estado inicial do sistema, limpando os campos de 
  entrada de dados e o contêiner de exibição dos resultados.

TAGS
----
#javaScript #HTML #CSS

REFERÊNCIA DO PROJETO
---------------------
Este projeto foi baseado no curso da Alura intitulado:
"Lógica de programação: Praticando com desafios".
========================================================================
