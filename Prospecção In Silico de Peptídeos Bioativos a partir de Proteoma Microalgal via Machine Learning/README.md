Desenvolvimento de um pipeline bioinformático e de inteligência artificial de ponta a ponta para filtragem, caracterização e triagem de peptídeos bioativos (antimicrobianos, antioxidantes e anti-hipertensivos)
derivados do proteoma de microalgas (Auxenochlorella protothecoides).

⚙️ Metodologia e Pipeline de Dados (Etapas 1 a 6):

Data Cleaning & Deduplicação: Remoção de sequências ambíguas e redundâncias proteicas (CD-HIT).

Digestão In Silico: Mimetização de clivagem enzimática para geração de biblioteca de peptídeos curtos.

Engenharia de Atributos (Feature Engineering): Extração de k-mers e propriedades físico-químicas (Massa Molar, pI, Carga Líquida pH 7.0, Escala GRAVY).

Machine Learning & Triagem: Aplicação de PCA para redução de dimensionalidade, k-Means para agrupamento de padrões biofísicos e filtros determinísticos para seleção de candidatas.

Validação & Ineditismo: Mapeamento de genoma de origem (NCBI BLASTp) e checagem de toxicidade e alérgenos (ToxinPred / BIOPEP).

Modelagem Estrutural 3D: Integração com a API do ESMFold (Meta AI) para predição conformacional e geração de arquivos .pdb.

📊 Principais Resultados:

Redução de um dataset bruto de milhares de sequências para X peptídeos líderes inéditos.

Identificação de candidatos com alto potencial biológico e perfis de segurança validados (Non-Toxin / Non-Allergen).

Modelagem 3D automatizada para análise de amfipaticidade e helicidade.
