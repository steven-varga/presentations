# Copyright (c) 2020 vargaconsulting, Toronto,ON Canada
# Author: Varga, Steven <steven@vargaconsulting.ca>

view:
	grunt serve

speaker-view:
	node plugin/notes-server

upload:
	grunt
	grunt zip
	unzip cppto.zip -d upload	
	aws s3 sync upload s3://cppto.h5cpp.org
	rm -rf upload
.PHONY: upload


