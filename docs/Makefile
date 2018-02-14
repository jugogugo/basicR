all:
	rm -rf docs
	R -f buildSite.R
	mv _site docs
	rm docs/README.html

publish:
	git add docs
	git commit -am "Automatic generation of website"
	git push
