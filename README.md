# Experimento 001 — Quantas estrelas existem em uma fotografia de 1951?

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JOICEMARTINS84/Experimento_001_M67.ipynb/blob/main/Experimento_001_M67.ipynb)

Investigação matemática e computacional da região do aglomerado estelar Messier 67 (M67), a partir de uma imagem FITS registrada pelo Observatório Palomar em 29 de novembro de 1951. O experimento utiliza Python, Astropy, Photutils e Gaia DR3 para detectar fontes luminosas, analisar ruído, estudar a distribuição espacial e estabelecer correspondências astrométricas.

## Resultados experimentais

| Indicador | Resultado |
|---|---:|
| Pixels analisados | 1.121.481 |
| Detecções a 7σ | 1.729 |
| Correspondências com Gaia DR3 até 3″ | 1.521 |
| Identificadores Gaia distintos até 3″ | 1.427 |
| Separação angular mediana das correspondências até 3″ | 0,4072″ |
| Média de correspondências nos 16 controles deslocados | 37,25 |

Os números representam resultados experimentais sob critérios específicos de detecção e associação. Não constituem uma contagem absoluta de estrelas nem confirmam sua pertença física ao aglomerado.

## Metodologia

- Processamento de imagem FITS e análise estatística do fundo.
- Detecção automatizada com DAOStarFinder e análise de sensibilidade.
- Distribuição espacial em uma matriz 10 × 10 e distâncias entre fontes.
- Conversão de coordenadas com WCS e cruzamento com Gaia DR3, considerando o movimento próprio.
- Controle de coincidências posicionais por deslocamentos artificiais.

## Reprodução

Abra o notebook pelo botão do Google Colab e execute as células na ordem apresentada. A consulta ao catálogo requer acesso à internet.

## Fontes e ferramentas

- [Digitized Sky Survey](https://archive.stsci.edu/dss/)
- [Astropy](https://www.astropy.org/)
- [Photutils](https://photutils.readthedocs.io/)
- [Gaia DR3 — ESA](https://www.cosmos.esa.int/web/gaia/dr3)

## Autoria

**Joice Souza Martins Santos** — professora de Matemática e pesquisadora independente.

Projeto [Matemática & Contexto](https://matematicacontexto.wpcomstaging.com/) · Série Matemática através do Universo.

17 de novembro de 2026.
