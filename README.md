# Roteiro para reprodução de testes estatísticos

Para reprodução de análises estatísticas realizadas, siga estes passos:

1) Baixe o arquivo de resultados (*resultados_finais-estatistica.xlsx*), disponível neste repositório. Nessa planilha, há 3 abas: (a) **Resultados brutos**: contendo os resultados dos 460 experimentos realizados, considerando as medidas DM e RM (cada execução produziu resultado correto ou não, apresentado na última coluna); (b) **Desempenhos detalhados**: contendo o resumo da aba anterior, apresentando os percentuais de acerto de cada abordagem, para cada medida e em cada banco (ou em todos); (c) **Estatística detalhada**: contendo o valor de *p* para cada par de abordagens, analisadas contra cada banco (e também considerando todos os bancos juntos) - os valores de *p* apresentados nessa tabela podem ser alcançados seguindo as instruções seguintes
2) [Clique aqui]{https://colab.research.google.com/drive/1PxUbWwj7NAsbzB-CP8CnXin4ETYIvGSV?usp=sharing} para abrir o *notebook* no *Google Colab*
3) Faça o upload da planilha anteriormente baixada para o sistema de arquivos do *notebook* aberto
4) Nesse *notebook*, há quatro seções: (a) a primeira que carrega os dados da planilha; (b) a segunda que realiza os cálculos estatísticos para alcançar os valores de *p* considerando a medida DM; (c) a terceira que realiza os cálculos estatísticos para alcançar os valores de *p* considerando a medida RM; (d) e a quarta que analisa os valores de *p* e produz grafos representando as superioridades de desempenhos em termos estatísticos.
