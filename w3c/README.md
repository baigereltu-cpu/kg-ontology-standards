# W3C 语义网与知识图谱基础标准

W3C 语义网技术栈是知识图谱领域事实上的基础规范体系，覆盖数据模型、序列化、本体语言、查询、约束校验与数据映射。

## 总入口

- [W3C Semantic Web Activity](https://www.w3.org/2001/sw/)

## 数据模型与序列化

| 标准 | 名称 | 链接 | 说明 |
|---|---|---|---|
| RDF 1.1 / 1.2 | Resource Description Framework | https://www.w3.org/RDF/ | 三元组数据模型 |
| RDFS | RDF Schema | https://www.w3.org/TR/rdf-schema/ | 类、属性、层次关系 |
| Turtle | Terse RDF Triple Language | https://www.w3.org/TR/turtle/ | RDF 人类可读序列化 |
| N-Triples / N-Quads | 行式序列化 | https://www.w3.org/TR/n-triples/ | 大数据交换常用 |
| Trig / TriG | 命名图序列化 | https://www.w3.org/TR/trig/ | 带图名的 RDF |
| JSON-LD 1.1 | JSON-based Linked Data | https://www.w3.org/TR/json-ld11/ | JSON 化关联数据 |

## 本体语言

| 标准 | 名称 | 链接 | 说明 |
|---|---|---|---|
| OWL 2 | Web Ontology Language | https://www.w3.org/OWL/ | 形式化本体，支持推理 |
| OWL 2 Profiles | EL / QL / RL 子集 | https://www.w3.org/TR/owl2-profiles/ | 按需取舍表达力与可计算性 |

## 查询与校验

| 标准 | 名称 | 链接 | 说明 |
|---|---|---|---|
| SPARQL 1.1 | Query Language & Protocol | https://www.w3.org/TR/sparql11-overview/ | RDF 图查询 |
| SHACL | Shapes Constraint Language | https://www.w3.org/TR/shacl/ | RDF 图约束与校验 |
| SHACL Advanced Features | SHACL-AF | https://www.w3.org/TR/shacl-af/ | 规则扩展 |

## 映射与交换

| 标准 | 名称 | 链接 | 说明 |
|---|---|---|---|
| R2RML | RDB to RDF Mapping | https://www.w3.org/TR/r2rml/ | 关系库到 RDF 映射 |
| Direct Mapping | Direct Mapping of RDB | https://www.w3.org/TR/rdb-direct-mapping/ | 自动映射 |
| RDF 1.1 XML | XML 语法 | https://www.w3.org/TR/rdf-syntax-grammar/ | 传统 XML 载体 |

## 元数据与词汇

| 标准 | 名称 | 链接 | 说明 |
|---|---|---|---|
| SKOS | Simple Knowledge Organization System | https://www.w3.org/TR/skos-reference/ | 分类法/叙词表 |
| DCAT 3 | Data Catalog Vocabulary | https://www.w3.org/TR/vocab-dcat-3/ | 数据集目录 |
| Dublin Core | DCMI Metadata Terms | https://www.dublincore.org/specifications/dublin-core/dcmi-terms/ | 通用元数据 |
| PROV-O | Provenance Ontology | https://www.w3.org/TR/prov-o/ | 数据溯源 |
| FOAF | Friend of a Friend | http://xmlns.com/foaf/spec/ | 人/社交 |
| ORG | Organization Ontology | https://www.w3.org/TR/vocab-org/ | 组织架构 |
| OWL-Time | Time Ontology | https://www.w3.org/TR/owl-time/ | 时间表达 |
| SSN / SOSA | Semantic Sensor Network | https://www.w3.org/TR/vocab-ssn/ | 传感器/观测 |

## 通用 Web Schema

- [Schema.org](https://schema.org/) —— 网页结构化数据通用词表
- [Linked Open Vocabularies (LOV)](https://lov.linkeddata.es/) —— RDF 词表检索目录
- [Linked Open Data Cloud](https://lod-cloud.net/) —— 公开 RDF 数据集图谱
