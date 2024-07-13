# Principais nomes brasileiros
Arquivo .json contendo os principais nomes brasileiros e o gênero, de acordo com o IBGE.

Os dados foram extraidos do site [Brasil.io](https://brasil.io/), que utiliza dados do IBGE.
- Baixei um arquivo .csv gigante contendo várias métricas e nomes;
- Converti para .json;
- Utilizei o Node para:
  -  Excluir nomes com menos de 9.000 registros;
  -  Excluir outras métricas desnecessárias;
  -  Captalizar os nomes.

O resultado foi um arquivo .json de apenas 112KB contendo os 1806 principais nomes brasileiros e seu gênero.

Ex:
```
  {
    "first_name": "Yago",
    "classification": "M"
  },
  {
    "first_name": "Yan",
    "classification": "M"
  },
  {
    "first_name": "Yara",
    "classification": "F"
  },
```

Bom proveito no seu projeto.
