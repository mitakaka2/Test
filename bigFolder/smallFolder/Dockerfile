FROM mcr.microsoft.com/mssql/server:2019-CU5-ubuntu-18.04
 
USER root
 
RUN mkdir /var/opt/sqlserver
RUN mkdir /var/opt/sqlserver/sqldata
RUN mkdir /var/opt/sqlserver/sqllog
RUN mkdir /var/opt/sqlserver/sqlbackups
 
RUN chown -R mssql /var/opt/sqlserver
 
USER mssql
 
CMD /opt/mssql/bin/sqlservr
