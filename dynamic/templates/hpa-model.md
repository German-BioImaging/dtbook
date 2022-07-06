# Model

{{ template "base" . }}

{{ range . }}
* {{ .sub }} {{ .condition }} {{ .age }} {{ .sex }}
{{ end }}
