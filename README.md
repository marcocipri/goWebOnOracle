goWebOnOracle

in order to generate the container, download from 
 http://www.oracle.com/technetwork/topics/linuxx86-64soft-092277.html
the following three RPMs:
    - oracle-instantclient12.2-basic-12.2.0.1.0-1.x86_64.rpm
    - oracle-instantclient12.2-devel-12.2.0.1.0-1.x86_64.rpm
    - oracle-instantclient12.2-sqlplus-12.2.0.1.0-1.x86_64.rpm 

and put oin the same directory of the docker file 
from vscode invoke :
Remote-Containers: reopen in Container

or from shell
      docker build --pull -t oracle/instantclient:12.2.0.1 .

