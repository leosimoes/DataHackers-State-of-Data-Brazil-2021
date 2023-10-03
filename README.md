# DataHackers-State-of-Data-Brazil-2021
Análise dos dados do State of Data Brazil 2021.

Para visualizar os gráficos utilize o `Kaggle-DataHackers-StateOfData-2021.html` 
e não o `Kaggle-DataHackers-StateOfData-2021.ipynb`

## Gráficos gerados
![](/imgs/Quantidade_por_Atuacao.png)

![](/imgs/Quantidade_por_Cargo_Atual.png)

![](/imgs/Distribuicao_de_Idades_por_Atuacao.png)

![](/imgs/Quantidade_por_faixa_salarial.png)

![](/imgs/Quantidade_por_faixa_salarial_e_cargo.png)

![](/imgs/Engenheiros_de_Dados_por_Nivel_e_Nivel_de_Ensino.png)

![](/imgs/Quantidade_de_Engenheiros_de_Dados_por_Faixa_Salarial_e_Nivel.png)

![](/imgs/Ferramentas_usadas_por_Engenheiros_de_Dados.png)

![](/imgs/Plataformas_usadas_por_Engenheiros_de_Dados.png)

![](/imgs/Analistas_de_BI_por_Nivel_e_Nivel_de_Ensino.png)

![](/imgs/Quantidade_de_Analistas_de_BI_por_Faixa_Salarial_e_Nivel.png)

![](/imgs/Ferramentas_usadas_por_Analistas_de_BI.png)

![](/imgs/Analistas_de_Dados_por_Nivel_e_Nivel_de_Ensino.png)

![](/imgs/Quantidade_de_Analistas_de_Dados_por_Faixa_Salarial_e_Nivel.png)

![](/imgs/Ferramentas_usadas_por_Analistas_de_Dados.png)

![](/imgs/_Linguagens_e_Fontes_de_Dados_usadas_por_Analistas_de_BI.png)

![](/imgs/_Linguagens_e_Fontes_de_Dados_usadas_por_Analistas_de_dados.png)

![](/imgs/Cientistas_de_Dados_por_Nivel_e_Nivel_de_Ensino.png)

![](/imgs/Quantidade_de_Cientistas_de_Dados_por_Faixa_Salarial_e_Nivel.png)

![](/imgs/_Linguagens_Tecnicas_e_Metodos_usados_por_Cientistas_de_Dados.png)


## Anotações de códigos usados
`pip install kaleido`

```
import plotly.offline as py
import plotly.io as pio
py.init_notebook_mode(connected=True)
pio.write_image(fig, caminho_imagem)
```

## Referências
Kaggle - datasets - DataHackers - State of Data 2021:
https://www.kaggle.com/datasets/datahackers/state-of-data-2021