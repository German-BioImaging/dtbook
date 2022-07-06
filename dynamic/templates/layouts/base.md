{{ define "base" }}
    {{ block "content" . }}{{ end }}
    {{ include_text "footer.md" . }}
{{ end }}
