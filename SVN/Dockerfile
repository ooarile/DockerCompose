FROM garethflowers/svn-server

RUN mkdir -p /var/opt/svn/myrepo/conf
RUN rm -f /var/opt/svn/myrepo/conf/svnserve.conf
RUN rm -f /var/opt/svn/myrepo/conf/passwd
RUN rm -f /var/opt/svn/myrepo/conf/authz

COPY svnserve.conf /var/opt/svn/myrepo/conf/svnserve.conf
COPY passwd /var/opt/svn/myrepo/conf/passwd
COPY authz /var/opt/svn/myrepo/conf/authz