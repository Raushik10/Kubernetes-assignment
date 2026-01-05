KUBERNETES ASSIGNMENT:-

This assignment contains frontend(express), backend, and YAML files.

Frontend has a form which contains name and email options which needs to be filled and after that there is a submit option which calls backend and save the data into the data.txt file which is present in backend.

YAML FILES:-

1. frontend.yaml :- To deploy frontend container in kubernetes cluster.
2. backend.yaml :- To deploy backend container in kubernetes cluster. It contains the PV and PVC also so, even though the pods gets deleted the data won't be lost.
3. ingree.yaml :- to deploy ingress through which we can access the application.
