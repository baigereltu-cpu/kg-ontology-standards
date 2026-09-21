# 按项目环节选标准（速查）

做知识图谱项目时，不必通读所有标准。按环节取用：

## 1. 立项 / 技术选型

- 国内项目：GB/T 42131-2022（技术框架） → GB/T 45628-2025（知识交换）
- 需要推理与跨系统互操作 → 选 RDF/OWL 路线（W3C 栈）
- 以关系网络分析、实时图遍历为主 → 选属性图路线（GQL / SQL-PGQ）

## 2. 本体建模

- 上层本体选型：BFO / DOLCE / SUMO / GFO（参考 ISO 21838 系列）
- 术语工作：ISO 704、ISO 1087
- 分类法/词表：SKOS、Dublin Core、ISO 25964
- 医疗：SNOMED CT、ICD、LOINC、Gene Ontology、OBO
- 金融：FIBO
- 文博：CIDOC CRM

## 3. 数据层

- RDF 数据模型与序列化：RDF / Turtle / JSON-LD
- 关系库导入：R2RML、Direct Mapping
- 元数据与目录：Dublin Core、DCAT、PROV-O
- 溯源：PROV-O

## 4. 查询与校验

- 图查询：SPARQL（RDF）、GQL（属性图）
- 约束校验：SHACL
- 本体一致性：OWL 2 + 推理机（HermiT、Pellet）

## 5. 平台与测试

- 性能要求与测试：GB/T 45923.2-2025
- 平台选型参考 IEEE P2807.5（在研）

## 6. 行业落地

- 电力：IEEE 2807.3、DL/T 2939-2025
- 工业：YD/T 6572-2025、ECLASS、IEC CDD
- 标准知识图谱：GB/T 46686.1、GB/T 48000 系列

## 7. 合规与交付

- 标准全文以 `std.samr.gov.cn`（国标）、`iso.org`（ISO）、`ieeexplore.ieee.org`（IEEE）为准
- 注意标准生效日期与过渡期
- 知识产权：标准原文受版权保护，引用时注明标准号与来源
