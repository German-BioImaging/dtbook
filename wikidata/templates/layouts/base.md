{{ define "base" }}
    {{ block "content" . }}{{ end }}
    {{ include "includes/footer.md" . }}
{{ end }}
