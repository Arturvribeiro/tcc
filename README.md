# Classificador de Defeitos em Máquinas de Chaves de Operação Ferroviária

# Sobre

Este site visa reunir os conteudos agregados da Tese de Conclusão do Curso de engenharia de computação de Artur Vieira Ribeiro, orientado pelos professores João Batista Camargo Junior, Lúcio Flavio Vismari, Jamil Kalil Naufal Júnior e Pedro Pinheiro Garcia.
A base de dados utilizada é secreta e protegida por segredo corporativo, por isso, serão disponibilizados apenas os códigos acerca do treinamento do classificador, tratamento de dados e visualização.

# Contexto e Motivação

A demanda por confiabilidade e segurança em sistemas críticos, como é o caso de aparelhos eletromecânicos em malhas ferroviárias cresceu muito na última decada. O principal fator é o constante ganho em otimização em diversas áreas utilizando técnicas mais modernas de analise de dados históricos.
A manutenção preventiva é significativamente mais barata que uma corretiva e foca principalmente em maximizar o uptime de operação do sistema. Estes fatores são suficientes para nortear o desenvolvimento de pesquisas a serem aplicadas no cenário brasileiro.

# Objetivo

O projeto tem como objetivo a concepção de uma ferramenta e técnicas que possibilitem a diferenciação de leituras da corrente de operação de uma máquina de chaves que tenham sido classificadas como defeitos que indiquem degradação, e assim, possibilitar o prosseguimento de manutenção preventiva à estas máquinas.

# Método

Para atingir o objetivo, foram desenvolvidas técnicas de tratamento de dados, no caso, conversão de leituras de corrente de operação em mapas de calor provenientes do produto gramiano destas. Essas imagens geradas foram utilizadas para alimentar e treinar um classificador baseado em redes neurais convolucionais. Estes classificador foram treinados com diferentes parâmetros que permitiu um estudo comparativo a fim de escolher o modelo com melhor generalização. Por fim, os dados e recomendações foram disponibilizados ao usuário para que auxilie a tomada de decisões.

# Arquitetura

O projeto é dividido em três partes primordiais, que são o tratamento de dados, a classificação e visualização. A partir destes é possível englobar um só script completo que seja capaz de receber uma leitura nova proveniente da transmissão de campo e produzir um relatório curto para validação do corpo técnico.
