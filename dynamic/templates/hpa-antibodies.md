# Antibodies

{{ template "base" . }}

| Antibody | Image Count |
| -------- | ----------- |
{{ range . }}| [{{ replace .sub "http://www.proteinatlas.org/search/" "" 1 }}]( {{ replace .sub "http://www.proteinatlas.org/search/" "" 1 }}.html ) | {{ .images }} |
{{ end }}
