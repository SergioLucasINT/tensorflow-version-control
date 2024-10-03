# Controle de Versão no Tensorflow
Ao seguir o tutorial oficial do Tensorflow, foram identificados alguns problemas tanto no Colab disponibilizado quanto na tentativa de copiar e colar o código, que não executou corretamente. A avaliação dos pontos positivos e negativos baseia-se nas alterações realizadas no código original. Seguem os principais aspectos observados:

## Pontos Positivos
- **Rapidez no treinamento:** Com os parâmetros padrão, o modelo levou aproximadamente 60 segundos por época, tornando o processo de treinamento ágil e eficiente.
- **Facilidade na modificação de parâmetros:** O código foi estruturado de maneira a permitir ajustes fáceis e rápidos nos parâmetros, facilitando a experimentação e a otimização contínua do modelo.
- **Gráficos explicativos e informativos:** As visualizações geradas foram interessantes e não convencionais, proporcionando insights claros sobre o desempenho do modelo e auxiliando na interpretação dos resultados.

## Pontos Negativos
- **Desempenho insatisfatório do modelo:** As predições iniciais foram ininteligíveis devido à acurácia zero alcançada, indicando que o modelo não estava capturando adequadamente os padrões dos dados.
- **Baixa acurácia inicial:** O primeiro treinamento resultou em uma acurácia de zero, o que exigiu alterações na estrutura da rede neural para melhorar o desempenho.