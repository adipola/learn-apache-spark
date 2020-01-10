+++
date = "2014-07-11T10:54:24+02:00"
draft = false
title = "Authors"
slug = "authors"
tags = ["tag1","tag2"]
image = ""
comments = false	# set false to hide Disqus
share = false	# set false to hide share buttons
menu= "main"		# set "main" to add this content to the main menu
+++




<section class="authors">

        
            {{ range $index, $author := .Site.Data.authors }}
                    <ul>
                         <li><a href="{{ $baseurl }}authors/{{ $index.name | urlize | lower }}">$author.name</a></li>
                         <li><a href="https://example.com/quote/quotes-02/">Quote 2</a></li>
                     </ul>
            {{ end }}


</section>



