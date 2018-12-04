input=article.Rmd

all: article.docx article.html

$(subst Rmd,docx,$(input)): $(input)
	Rscript -e 'rmarkdown::render("$(input)", "word_document")'

$(subst Rmd,html,$(input)): $(input)
	Rscript -e 'rmarkdown::render("$(input)", "html_document")'
