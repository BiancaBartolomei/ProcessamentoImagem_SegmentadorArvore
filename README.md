# SegmentadorArvore

Deve-se desenvolver métodos em Python para detectar (segmentar) as
árvores de eucalipto e realizar a sua contagem. Abaixo, seguem as etapas a serem
implementadas.
  
**1. Leitura de metadados da imagem RGB**
  - Carregar o sistema de coordenadas (EPSG) e a resolução espacial (GSD) em cm/px da imagem RGB georreferenciada
  - Input: Arquivo TIFF da imagem RGB georreferenciada.
  - Output: Arquivo TXT (ou como print no terminal) com as informações extraídas.

**2. Segmentação da imagem RGB**
  - Realizar a segmentação da imagem RGB com objetivo de identificar árvores de eucalipto.
  - Input: Arquivo TIFF da imagem RGB georreferenciada.
  - Output: Arquivo TIFF da máscara de segmentação.

**3. Vetorização das regiões segmentadas**
  - Transformar as regiões segmentadas em polígonos vetorizados e exportá-los em arquivo shapefile ou geojson.
  - Input: Arquivo TIFF do resultado da segmentação.
  - Output: Arquivo shapefile ou geojson da vetorização do output da etapa anterior.

**4. Contagem de árvores**
  - Por fim, realizar a contagem de árvores na imagem RGB fornecida e salvar o resultado em arquivo de texto (TXT) ou como print no terminal.
  - Input: Arquivo shapefile ou geojson.
  - Output: Arquivo TXT ou como print no terminal.
