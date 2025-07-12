# petroleum-ontology

## Visão Geral

Este repositório contém o trabalho final da disciplina CMP 196 - Engenharia de Ontologias, focada na construção de uma ontologia de domínio para objetos geológicos de reservatório do pré-sal. [cite_start]A ontologia modela entidades e processos chave, visando demonstrar técnicas de análise ontológica e modelagem conceitual em OWL, baseada na Basic Formal Ontology (BFO)[cite: 1].

## Conteúdo do Repositório

* `ontologia.owx`: Arquivo OWL principal da ontologia (formato Protege OWL XML).
* `catalog-v001.xml`: Arquivo de catálogo para gerenciar imports.
* `ontology_image.png`: Imagem da hierarquia de classes da ontologia.

## Detalhes da Ontologia

A ontologia aborda a descrição de reservatórios de petróleo típicos do do pré-sal, incluindo:

* **Processos Modelados**: Dolomitização e Precipitação, exemplificando como modificam qualidades da rocha.
* [cite_start]**Base Ontológica**: Especializa a BFO [cite: 1] e utiliza `GEOCORE` e `GEOSPR` para conceitos e relações geológicas e espaciais.
* **Inferências**: Contém instâncias para validação e demonstração de inferências usando raciocinadores OWL.

## Uso e Validação

1.  Baixe os arquivos do repositório.
2.  Abra `ontologia.owx` no Protege (versão 5.x recomendada). O `catalog-v001.xml` auxiliará nos imports.
3.  Inicie o raciocinador HermiT (`Reasoner > Start reasoner`, depois `Synchronize reasoner`) para observar inferências e inconsistências.