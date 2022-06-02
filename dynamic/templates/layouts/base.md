{{ define "base" }}
    {{ block "content" . }}{{ end }}
    {{ include_text "includes/footer.md" . }}
{{ end }}
