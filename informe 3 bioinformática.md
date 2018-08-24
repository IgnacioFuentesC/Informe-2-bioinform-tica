### Ignacio Fuentes Cáceres ###

### Parte 1: El artículo genoma


**1.** ¿Cuántos *Sequencing Projects* y *Analysis Projects* hay depositados en GOLD? ¿Cuál es la diferencia entre ambos? [2]

**R: Hay 251.124 Sequencing Projects y 174.491 Analysis Projects. Sequencing Projects es la secuenciación de un organismo individual o una muestra, mientras que Analysis Projects describe cómo se realizó el ensamblaje y la anotación del proyecto de secuenciación.**

**https://gold.jgi.doe.gov/**

**2.** ¿Cuál es el dominio más representado en la base de datos, *archea*, *bacteria*, *eukaryote*, o *virus*? [1]

**R: Bacteria es el dominio más representado en la base de datos.**

**https://gold.jgi.doe.gov/statistics**

**3.** ¿Cuáles son los *phyla* más representados entre los proyectos de genomas bacterianos en la base de datos? [1]

**R: Los más representados son Proteobacteria y Firmicutes.**

**https://gold.jgi.doe.gov/statistics**

**4.** ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.) [1]

**R: Pertenece a proyectos médicos.**

**https://gold.jgi.doe.gov/statistics**

**5.** ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma) [2]

**R: El artículo original es Prüfer, K., Munch, K., Hellmann, I., Akagi, K., Miller, J. R., Walenz, B., … Pääbo, S. (2012). The bonobo genome compared with the chimpanzee and human genomes. Nature, 486(7404), 527–531.** 

**http://doi.org/10.1038/nature11128**

**6.** Explica, qué es el N50, L50, y NG50. [3]

**R: N50 puede describirse como una estadística mediana ponderada de tal manera que el 50% de todo el conjunto está contenido en contigs o andamios iguales o mayores que este valor.**

**Dado un conjunto de contigs, cada uno con su propia longitud, el conteo L50 se define como el menor número de contigs cuya suma de longitud produce N50.**

**La estadística NG50 es igual a N50, excepto que es el 50% del tamaño del genoma conocido o estimado que debe ser de la longitud NG50 o más. Esto permite comparaciones significativas entre diferentes conjuntos.**

**7.** ¿Cuál es el propósito de calcular estas estadísticas? [3]

**R: Se usa principalmente para el ensamblaje del genoma. Con estas estadísticas se puede saber las longitudes del contig dentro de un ensamblaje en borrador.**

**8.** ¿Cuántos *contigs* conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los *contigs*) [3]

**R: 121,356 contigs conforman el genoma del Bonobo. El N50 es 66,676 y el L50 es 11,048.**

**https://www.ncbi.nlm.nih.gov/assembly/GCF_000258655.2**

**9.** ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?

**R: El largo total del genoma del Bonobo es 3286.64 Mb y su porcentaje de GC es 42.3185 %. El porcentaje de GC es una característica del genoma que indica el porcentaje de guanina y citocina del organismo. Se calcula a partir del largo total del genoma, el cual representa la totalidad del material genético. La diferencia del porcentaje de GC es el porcentaje de adenina y timina. De esto se pueden inferir carácterísticas propias del organismo, como por ejemplo, si el organismo es hipertermófilo.**

**https://www.ncbi.nlm.nih.gov/genome/?term=bonobo**

**10.** ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?

**R: Para secuenciar el genomba del bonobo se utilizó Illumina GAIIx. Para ensamblar el genoma de Bonobo se utilizó Celera Assembler software.**

**https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3498939/**


### Parte 2: Predicción de genes


**11.** Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [*start*] y término [*stop*])? [3]

**R: Se observan los ORFs, con sus respectivos largos. Se encontraron 7 ORFs. 3 de ellos están en la hebra conductora (ORF 1, 2 y 3) y 4 en la retrasada (ORF 4, 5, 6, 7). Los ORFs 1, 2, 3, 4, 5, 6, 7 tienen un largo, en nucleótidos de: 909, 78, 99, 441, 405, 84 y 114 respectivamente. Sí, se superponen el 1 con el 7, el 3 con el 5 y el 4 con 6 y 2.**

**https://www.ncbi.nlm.nih.gov/orffinder/**

**12.** ¿Qué tipo de programa es ORFfinder, *Ab initio* o por homología? [2]

**R: Es ab initio ya que sólo a partir de la secuencia de DNA busca señales de presencia de la región de interés, en este caso, ORFs.**

**13.** ¿A qué organismo pertenece la secuencia en cuestión? [2]

**R: Pertenece a *Haemophilus influenzae*.**

**https://blast.ncbi.nlm.nih.gov/Blast.cgi**

**14.** ¿Qué gen(s) está(n) codificados en la secuencia? [2]

**R: Están coficados los genes para formate dehydrogenase accessory protein FdhE, ribosomal-protein-alanine N-acetyltransferase y DNA polymerase III, psi subunit. **

**https://www.ncbi.nlm.nih.gov/protein/WP_005693890.1?report=genbank&log$=prottop&blast_rank=1&RID=RYCMFXPM015**

**https://www.ncbi.nlm.nih.gov/protein/PRI72323.1?report=genbank&log$=prottop&blast_rank=1&RID=RYECAB97015**

**https://www.ncbi.nlm.nih.gov/protein/AVJ09519.1?report=genbank&log$=prottop&blast_rank=1&RID=RYEBDTVT014**

**15.** Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)? [3]

**R: Diría que son correctos ORF1 y ORF4 y ORF5 ya que son los que tienen mayor score respectivamente el gen que codifican.**