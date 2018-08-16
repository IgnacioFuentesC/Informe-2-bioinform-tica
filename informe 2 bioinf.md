### Parte 1: Colectar genes homólogos
# Informe 2

## Ignacio Fuentes Cáceres

**1.** ¿Qué función cumple el gen SRY? [2]

**R: Codifica para una proteína que es un factor determinante de testículos (TDF) que inicia la determinación del sexo masculino.**
**https://www.ncbi.nlm.nih.gov/gene/6736**

**2.** ¿Cuántos genes ortólogos están anotados en esa base de datos? [1]

**R: Hay 29 organismos con genes que son ortólogos con el gen SRY.**
**https://www.ncbi.nlm.nih.gov/gene/?Term=ortholog_gene_6736[group]**


### Parte 2: Alineamiento múltiple

**3.** ¿Qué es el EMBL-EBI? [2]

**R: Es un centro de investigación que ofrece gratuítamente datos biológicos a la comunidad científica, también ofrece servicios y herramientas.**
**https://www.ebi.ac.uk/about**

**4.** ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas? [2]

**R: MUSCLE es el mejor programa que ellos ofrecen para secuencia de proteínas.**
**https://www.ebi.ac.uk/Tools/msa/**

**5.** ¿Qué otros tipo de herramientas ofrece EMBL-EBI? [2]

**R: Ofrecen herramientas de multiple alineación para secuencias de distintos tamaños pero algunas son ùtiles para árboles de guía de sembrados y técnicas de perfil de HMM, otras para transformar un resultado de búsqueda de similitud de secuencia en una alineación de secuencia múltiple, además ofrece una herramienta que intenta mitigar los riesgos de los métodos de alineación progresiva, entre otras.**
**https://www.ebi.ac.uk/Tools/msa/**


**6.** ¿Cuál es el costo de abrir un gap? [1]

**R:1,53 es el costo de abrir un gap.**
**https://www.ebi.ac.uk/Tools/msa/mafft/**


**7.** ¿Cuál es el costo de extender un gap? [1]

**R:0,123 es el costo de extender un gap.**
**https://www.ebi.ac.uk/Tools/msa/mafft/**


**8.** ¿Cuál es la longitud total del alineamiento? [1]

**R: La longitud del alineamiento es 1934 pares de bases.**
![imagen](https://raw.githubusercontent.com/IgnacioFuentesC/AAAAAAAAAAAAAAAAAAAAA/master/jalview.png)


**9.** ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos? [2]

**R: La especie que posee el gen SRY más relacionado con el de humanos es *Piliocolobus tephrosceles*.**
**https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180810-210512-0744-37027629-p2m&analysis=phylotree**


**10.** ¿Cuál es el más lejano? [2]

**R: El más lejano es *Desmodus rotundus*.**
**https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-163541-0037-85111323-p2m&analysis=phylotree**


**11.** ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro? [2]

**R: La especie cuyo gen SRY es más cercana a la del burro es *Equus przewalskii*.**
**https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-163541-0037-85111323-p2m&analysis=phylotree**


**12.** ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye? [3]

**R: Si el costo de abrir un gap aumenta, el sistema va a preferir dejar mismatch para obtener un score más alto dejando el alineamiento más corto. Y si el costo de abrir un gap disminuye, el sistema va a preferir abrir gaps para tener un score más alto en vez de dejar mismatch, por lo que el alineamiento sería más largo.**


**13.** ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye? [3]

**R: Si el costo de costo de extender un gap aumenta, el sistema va a preferir abrir uno nuevo por lo que alineamiento sería más largo. Y si el costo de extender un gap disminuye, el sistema va a preferir extender un gap por lo que alineamiento sería más largo.**

**14.** ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? [2]

**R: Disminuyó el largo de la cadena a 1895 pares de bases.**
![imagen2](https://raw.githubusercontent.com/IgnacioFuentesC/AAAAAAAAAAAAAAAAAAAAA/master/jalview2.png)

**15.** Prueba lo mismo, pero esta vez **disminuyendo al mínimo el costo de extender un gap**. Describe cómo cambia el alineamiento. [2]

**R: El largo del alineamiento aumenta a 1989 pares bases.**

![imagen3](https://raw.githubusercontent.com/IgnacioFuentesC/AAAAAAAAAAAAAAAAAAAAA/master/jalview3.png)


#### Parte 3: Diseño de partidores


**16.** Agrega a tu informe una lista de los "*LEFT PRIMER*" y "*RIGHT PRIMER*" que obtuviste usando Primer3. [3]

**Primer izquierdo**:

-AGAGTGAAGCGACCCATGAA

-TTACAGGCCATGCACAGAGA

-GGATAGAGTGAAGCGACCCA

-AGATGCTGCCGAAGAATTGC

-CGAAGATGCTGCCGAAGAAT


**Primer derecho**:

-TCTCTGTGCATGGCCTGTAA

-CTTGAGTGTGTGGCTTTCGT

-TTTCTCTCTGTGCATGGCCT

-GCTTTGTCCAGTGGCTGTAG

-CTACAGCTTTGTCCAGTGGC



**17.** Indica los partidores *forward* y *reverse* que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano. [5]

**R: Escogí como partidores AGAGTGAAGCGACCCATGAA (el primero de los izquierdos) y CTTGAGTGTGTGGCTTTCGT (el segundo de los derechos) porque tienen una TM adecuada, porcentaje de GC adecuado y tienen baja tendencia a formar estructuras secundarias y dímeros.**

**18.** ¿Cuál es el largo del amplicón? ¿Y la temperatura de *annealing* sugerida? [3]

**R: El largo del amplicón es 350 nucleótidos y la temperatura de alineamiento sugerida es 55%.**