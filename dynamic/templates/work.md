# {{ .workLabel }}

{{ template "base" . }}

{{ define "title" }}{{ .workLabel }}{{ end }}

{{ define "content" }}
  This is content.
{{ end }}
