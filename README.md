# Computing Disease-Specific Gene Embeddings via Constrained Optimization

This folder contains data for the paper "Computing disease-specific gene embeddings via constrained optimization", submitted to CPAIOR 2022.

Notebook with the interesting code part is available at [this link](https://colab.research.google.com/drive/1ozgaBJ-4F2nmmDWGwcWHQS_P56JtiZWl?usp=sharing)

The generated embedding can be viewed on [Tensorboard](https://projector.tensorflow.org/?config=https://gist.githubusercontent.com/eleonoravercesi/0772e33c6f898539cb397029730a3a1e/raw/e2d8780ed78e034a97691553d4409f548dab8fba/projector_config.json)

`PCG_AML.csv` : information on genes that relate with Acute Myeloid Leukemia cells funcional states. Data re-arranged from [CancerSEA](http://biocc.hrbmu.edu.cn/CancerSEA/home.jsp).

`E_sim.npy` : edges related to similar genes; information derived from metabolic pathway. Information derived from [KEGG](https://www.kegg.jp)

`genes_pathways.txt` : genes for which we know at least one matabolic pathway.

`count_only_mal_D0_small.npy.zip` : count matrix related only to genes for which we know any relation with an AML cells functional state. Data re-arranged from [GSE116256](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE116256).

`genes_only_mal_D0_small.txt` : genes associated with the count matrix related only to genes for which we know any relation with an AML functional state.

`count_only_mal_D0.npy.zip` : count matrix related to all the genes availble in the consider GEO series.  Data re-arranged from [GSE116256](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE116256).

`genes_only_mal_D0.txt`: genes associated with the count matrix related to all the genes availble in the considered GEO series.
