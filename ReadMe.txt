In this file you can find tow deployments that:
1.run apache
2.run sql
and tow service:
1.open port 80 to apache
2.open port 3036 to sql

Prerequisites:
In order to run the deployments and the services you should have kubernetes downloaded in your computer, Also you should
have the kubectl cli.

How to run:
1.Open a new terminal 
2.run the command: "kubectl apply -f ." where . (dot) represents the current directory where all the files exist.