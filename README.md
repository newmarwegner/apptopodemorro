# APP Topo de Morro
Todos os procedimentos realizados para identificação de app de topo de morro consideraram:

1 - Classificação de Morros (considerando o ponto de sela e amplitude)
2 - Declividade média (>=25º)
3 - Definição do terço superior para morros individuais
4 - Definição de altimetrias >= 1800 como app de altitude.


## SQLs para geração de Topo de Morro
Durante a definição da metodologia foram gerados códigos sql no postgresql + postgis para geração de tabelas que subsidiaram a definição de áreas de preservação permanente de topo de morro. Tais códigos podem ser utilizados para realização de identificação em outras regiões.
[[Demonstração de execução]](https://youtu.be/N1ltCct_fHw)

## Modelador Gráfico para geração de Topo de Morro no QGIS
A fim de automatizar os processos gerados anteriormente, foi utilizado o modelador gráfico do QIS 3.10, possibilitando assim tornar menos oneroso o processo de execução dos procedimentos.
Cabe ressaltar que todas as conexões com banco de dados está sendo realizado no modelo com apontamentos para um banco postgresql localhost denominado "invasao", logo deve-se ter atenção a isto para a correta execução do modelo.
[[Demonstração de execução]](https://youtu.be/hGXahGdcJ9I)
