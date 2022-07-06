# Genes

{{ template "base" . }}

The following is a partial list of genes which are
found in the HPA images along with the number of
distinct [conditions](https://www.wikidata.org/wiki/Property:P1050)
that they represent:

| Gene | Condition |
| ---- | --------- |
{{ range . }}| {{ .gene }} | {{ .condition }} |
{{ end }}
