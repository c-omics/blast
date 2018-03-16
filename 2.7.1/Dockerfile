FROM comics/centos
MAINTAINER Ian Merrick <MerrickI@Cardiff.ac.uk>

##############################################################
# Software:             ncbi-blast+
# Software Version:     2.7.1
# Software Website:     http://blast.ncbi.nlm.nih.gov
# Description:          ncbi-blast+
##############################################################

ENV VERSION=2.7.1

RUN yum install -y \
       parallel \
       ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/${VERSION}/ncbi-blast-${VERSION}+-1.x86_64.rpm
CMD ["/bin/bash"]

