# Copyright (c) 2018 vargaconsulting, Toronto,ON Canada
# Author: Varga, Steven <steven@vargaconsulting.ca>


run:
	grunt serve


upload:
	grunt  	
	rsync -a  js osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  css osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  pix osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  cast osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  lib osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  plugin osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  pages osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  node_modules osaka.vargaconsulting.ca:/var/www/cluster/
	rsync -a  index.html osaka.vargaconsulting.ca:/var/www/cluster/
	
.PHONY: upload


