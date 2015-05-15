FROM fedora
MAINTAINER Casey Link <unnamedrambler@gmail.com>

# Update the image with the latest packages (recommended)

RUN yum update -y; yum clean all
RUN yum install -y vim vim-common curl wget git jwhois bind-utils tmux zip unzip rsync 

WORKDIR /space

CMD ["/bin/bash"]
