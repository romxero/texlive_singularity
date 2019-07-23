Bootstrap: docker
From: debian:stretch-slim

%labels
Author "Randall Cab White - rcwhite@stanford.edu"


#########
#%setup
#########

#Downlaod packages
%post
  apt-get -ym update
  apt-get -ym install texlive texlive-base texlive-font-utils ghostscript lyx

%environment
  export IMAGE_NAME="tex_live_sherlock"
