+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"

#
# description is optional
#
# description = "An optional description for SEO. If not provided, an automatically created summary will be used."

tags = [{{ range $plural, $terms := .Site.Taxonomies }}{{ range $term, $val := $terms }}"{{ printf "%s" $term }}",{{ end }}{{ end }}]
+++

This is a page about "{{ replace .Name "-" " " | title }}".

---

If you have any comments, feel free to send a DM through [Mastodon](.Site.Params.mastodonUrl) or an [email]({{.Site.Params.email}}).
