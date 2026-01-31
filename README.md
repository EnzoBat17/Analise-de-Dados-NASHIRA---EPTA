Projeto com o objetivo de aalisar os dados de simulação de vôo com os dados reais obtidos pelo foguete NASHIRA durante a LASC 2025 na categoria de 500m e compará-los com os dados de uma simulação feita em condições semelhantes.
Tecnologias utilizadas:
- Rocketpy
- Pandas
- Matplotlib

Como os dados construtivos do Nashira não foram disponibilizados foram utilizados os dados do foguete calisto disponpiveis no passo a passo: https://docs.rocketpy.org/en/latest/user/first_simulation.html.
Ademais, para links de arquivos específicos utilizados no na análise, consultar o próprio notebook.

Por se tratarem de dados sensíveis, os dados de vôo do foguete não serão disponibilizados no repositório público. Portanto cabe ao usuário, possuir na mesma pasta o arquivo "nashira_telemetry.csv" para que o notebook ipynb funcione corretamente.

As bibliotecas utilizadas estão disponíveis em requirements.txt e instaladas facilmente (de preferência num ambiente virtual) com: pip install -r requirements.txt

*Atenção!
O histórico de commits apresenta datas confusas. Isso decorre do fato de que após uma análise minunciosa no fim do projeto, foram constatados alguns commits em que os gráficos do matplotlib não foram "limpados" do notebook, podendo deixar expostas informações. Dessa forma, foram feitos rebases a fim de remover esses commits do histórico

Enzo Oliveira Batista - 12411ECP009
