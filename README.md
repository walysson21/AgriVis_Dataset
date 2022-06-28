# AgriVis Dataset
Dataset com imagens do satélite Sentinel-2 de regiões de plantações do Norderte Brasileiro e aberto para colaboração

O conjunto de dados possui 8 classes:
- Área de preparo de plantação (classe 1) que se trata da região de solo preparada para receber o plantio, 
- Plantação jovem (classe 2) que é o estágio inicial da plantação que mescla áreas verdes com áreas ainda de solo,
- Plantação madura (classe 3) que são regiões onde a plantação está desenvolvida. Julgouse
- Os caminhos que normalmente delimitam as plantações foram nomeadas como Linhas de divisão das plantações (classe 4). 
- A quinta classe representa as áreas de vegetação naturais, as áreas verdes que não são cultivadas, chamadas de Áreas
de relva ou floresta (classe 5). 
- As demais classes são Áreas de solo ou rochas (classe 6),
- Água (Áreas alagadas, lagos, rios e etc.) (classe 7) e 
- Áreas de habitação (classe 8) que são casas ou construções artificiais nas regiões das fazendas.

### Download
Disponível para download [neste link.](https://drive.google.com/drive/folders/1B1EUAo5_-6Kdl_az3tkn-hICF720wQJY?usp=sharing)

### Região de aquisição das imagens
a) Região de Aquisição. b) Imagem inteira. c) 4 blocos de imagem.
<br/>
<img src="images/area_aquisicao_imagens2.png" width="800" title="a) Região de Aquisição. b) Imagem inteira. c) 4 blocos de imagem."> 

### Concentração de plantações na região de aquisição
Concentração de plantação de soja na Região de Estudo.
<br/>
<img src="images/area_de_estudo2.PNG" width="500" title="Concentração de plantação de soja na Região de Estudo.">

### Anotação das imagens
Exemplos de anotação das imagens com o Labelme. As imagens à esquerda
são de uma área de vegetação sem plantação e apresentam as classes Relva
ou Floresta e Água. As imagens à direita são de uma área de plantação e
apresentam todas as demais classes.
<br/>
<img src="images/marcacoes.PNG" width="600" title="Exemplos de anotação das imagens com o Labelme. As imagens à esquerda
são de uma área de vegetação sem plantação e apresentam as classes Relva
ou Floresta e Água. As imagens à direita são de uma área de plantação e
apresentam todas as demais classes.">
<br/><br/>

a), b), c) e d) são imagens em RGB do conjunto de dados e e), f), g) e h) são,
respectivamente, suas anotações.
<br/>
<img src="images/imagens_marcadas.png" width="800" title="a), b), c) e d) são imagens em RGB do conjunto de dados e e), f), g) e h) são,
respectivamente, suas anotações.">

## Citações:
International Conference on Image Analysis and Processing <br/>
Image Analysis and Processing – ICIAP 2022 pp 346–357, Disponível em https://link.springer.com/chapter/10.1007/978-3-031-06427-2_29.
```BibTex
@inproceedings{dos2022two,
  title={A Two-Stage U-Net to Estimate the Cultivated Area of Plantations},
  author={dos Santos Oliveira, Walysson Carlos and Braz Junior, Geraldo and Lima Gomes Junior, Daniel and Cardoso de Paiva, Anselmo and Sousa de Almeida, Joao Dallyson},
  booktitle={International Conference on Image Analysis and Processing},
  pages={346--357},
  year={2022},
  organization={Springer}
}
```
