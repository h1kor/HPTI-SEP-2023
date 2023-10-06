# HPTI-SEP-2023

intern id = HPTI-SEP23-255

#GAU (GET ALL URLS TOOL )

#aout
getallurls (gau) fetches known URLs from Open Threat Exchange, the Wayback Machine, Common Crawl, and URLScan for any given domain. Inspired by Tomnomnom's waybackurls.
this tool really amazing to helping pentesting with urls.

#installation

$ go install github.com/lc/gau/v2/cmd/gau@latest

#Examples:

$ printf example.com | gau
$ cat domains.txt | gau --threads 5
$ gau example.com google.com
$ gau --o example-urls.txt example.com
$ gau --blacklist png,jpg,gif example.com
