# Model


    


The current model used in the DTDP is to collect all of the
properties from the key-value pairs in the IDR and attach
them to the image via a b-node using the "depicts" predicate:

`:SomeImage` is a [Wikidata:Image](http://www.wikidata.org/entity/Q478798)
that [depicts](https://www.wikidata.org/wiki/Property:P180) something
 * with a [gene symbol](http://www.wikidata.org/prop/direct/P353)
 * with a [medical condition](http://www.wikidata.org/prop/direct/P1050)
 * with [age at event](http://www.wikidata.org/prop/direct/P3629)
 * and [sex](http://www.wikidata.org/prop/direct/P21).

| Image | Gene | Condition | Age | Sex |
| ----- | ---- | --------- | --- | --- |
| Image:11748077 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 84 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748077 | BCR | http://www.wikidata.org/entity/Q356033 | 84 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748078 | BCR | http://www.wikidata.org/entity/Q356033 | 66 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748078 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 66 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748079 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 46 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748079 | BCR | http://www.wikidata.org/entity/Q356033 | 46 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748080 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 46 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748080 | BCR | http://www.wikidata.org/entity/Q356033 | 46 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748081 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 63 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748081 | BCR | http://www.wikidata.org/entity/Q356033 | 63 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748082 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 84 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748082 | BCR | http://www.wikidata.org/entity/Q356033 | 84 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748083 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 84 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748083 | BCR | http://www.wikidata.org/entity/Q356033 | 84 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748084 | BCR | http://www.wikidata.org/entity/Q356033 | 71 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748084 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 71 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748085 | BCR | http://www.wikidata.org/entity/Q356033 | 84 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748085 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 84 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748086 | BCR | http://www.wikidata.org/entity/Q356033 | 71 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748086 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 71 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748087 | BCR | http://www.wikidata.org/entity/Q356033 | 66 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748087 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 66 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748088 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 67 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748088 | BCR | http://www.wikidata.org/entity/Q356033 | 67 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748089 | BCR | http://www.wikidata.org/entity/Q356033 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748089 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748089 | BCR | http://purl.bioontology.org/ontology/SNMI/M-00100 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748090 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748090 | BCR | http://purl.bioontology.org/ontology/SNMI/M-00100 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748090 | BCR | http://www.wikidata.org/entity/Q356033 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748091 | BCR | http://purl.bioontology.org/ontology/SNMI/M-00100 | 65 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748091 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 65 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748091 | BCR | http://www.wikidata.org/entity/Q356033 | 65 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748092 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748092 | BCR | http://www.wikidata.org/entity/Q356033 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748093 | BCR | http://www.wikidata.org/entity/Q356033 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748093 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748094 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 65 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748094 | BCR | http://purl.bioontology.org/ontology/SNMI/M-00100 | 65 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748094 | BCR | http://www.wikidata.org/entity/Q356033 | 65 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748095 | BCR | http://www.wikidata.org/entity/Q3658404 | 62 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748095 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 62 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748096 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85203 | 51 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748096 | BCR | http://www.wikidata.org/entity/Q18553580 | 51 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748097 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85203 | 51 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748097 | BCR | http://www.wikidata.org/entity/Q18553580 | 51 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748098 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 62 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748098 | BCR | http://www.wikidata.org/entity/Q3658404 | 62 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748099 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 83 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748099 | BCR | http://www.wikidata.org/entity/Q3658404 | 83 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748100 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85203 | 58 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748100 | BCR | http://www.wikidata.org/entity/Q18553580 | 58 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748101 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85203 | 58 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748101 | BCR | http://www.wikidata.org/entity/Q18553580 | 58 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748102 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748102 | BCR | http://www.wikidata.org/entity/Q3658404 | 75 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748103 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 83 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748103 | BCR | http://www.wikidata.org/entity/Q3658404 | 83 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748104 | BCR | http://www.wikidata.org/entity/Q18553580 | 59 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748104 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85203 | 59 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748105 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 55 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748105 | BCR | http://www.wikidata.org/entity/Q3658404 | 55 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748106 | BCR | http://www.wikidata.org/entity/Q3658404 | 80 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748106 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 80 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748107 | BCR | http://www.wikidata.org/entity/Q3658404 | 55 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748107 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 55 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748108 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 80 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748108 | BCR | http://www.wikidata.org/entity/Q3658404 | 80 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748109 | BCR | http://www.wikidata.org/entity/Q3658404 | 40 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748109 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 40 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748110 | BCR | http://www.wikidata.org/entity/Q3658404 | 87 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748110 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 87 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748111 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 40 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748111 | BCR | http://www.wikidata.org/entity/Q3658404 | 40 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748112 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 87 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748112 | BCR | http://www.wikidata.org/entity/Q3658404 | 87 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748113 | BCR | http://www.wikidata.org/entity/Q3658404 | 61 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748113 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 61 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748114 | BCR | http://www.wikidata.org/entity/Q3658404 | 61 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748114 | BCR | http://purl.bioontology.org/ontology/SNMI/M-85003 | 61 | http://www.wikidata.org/entity/Q6581072 |
| Image:11748115 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 64 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748116 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 79 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748116 | BCR | http://www.wikidata.org/entity/Q356033 | 79 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748117 | BCR | http://www.wikidata.org/entity/Q356033 | 79 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748117 | BCR | http://purl.bioontology.org/ontology/SNMI/M-81403 | 79 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748118 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 64 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748119 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 72 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748120 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 72 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748121 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 63 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748122 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 63 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748123 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 68 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748124 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 68 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748125 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 69 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748126 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814031 | 74 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748127 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 69 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748128 | BCR | http://purl.bioontology.org/ontology/SNMI/M-00100 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748128 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748129 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814033 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748129 | BCR | http://purl.bioontology.org/ontology/SNMI/M-00100 | 83 | http://www.wikidata.org/entity/Q6581097 |
| Image:11748130 | BCR | http://purl.bioontology.org/ontology/SNMI/M-814031 | 74 | http://www.wikidata.org/entity/Q6581097 |

