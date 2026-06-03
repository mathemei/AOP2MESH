# AOP2MESH

MeSH-annotated version of AOP Key Events from [AOP-Wiki RDF](https://aopwiki.rdf.bigcat-bioinformatics.org/).

## Repo content

- **AOP2MESH.ipynb** : Jupyter notebook containing all the code needed to match MeSH descriptors to AOP KEs with the [WellcomeBertMesh](https://huggingface.co/Wellcome/WellcomeBertMesh) indexer.
- **AOP-MeSH_tests_validation.ipynb** : Jupyter notebook testing different mapping approaches and comparing them with indexing results.
- **aop_mesh_mappings.rdf** and **aop_mesh_mappings.tsv** : mapping results in RDF and TSV formats.
- **aop_mesh_mappings_KERs.rdf** : mapping results enriched with Key Event Relationships from AOP-Wiki, in RDF format.
- **mesh_embeddings.txt.gz** and **mesh_ui_to_id.pickle** : MeSH descriptors embeddings with Node2Vec from [MeSH Embeddings](https://github.com/helboukkouri/mesh-embeddings)
- **similarity_based_evaluation.ipynb** : Jupyter notebook to evaluate mapping results based on semantic similarity instead of exact match
