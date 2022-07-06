# Model

{{ template "base" . }}

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
{{ range . }}
| Image:[{{ replace .sub "https://idr.openmicroscopy.org/webclient/img_detail/" "" 1 }}]({{ .sub }}) | {{ .gene }} | {{ .condition }} | {{ .age }} | {{ .sex }} |
{{ end }}
