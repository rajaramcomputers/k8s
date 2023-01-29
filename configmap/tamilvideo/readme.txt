The files are available in k8s/configmap/tamilvideo/props

1. How to create from a file.

k create configmap myconfig --from-file=game.properties

2. To Create from files in the folder

k create configmap myconfig --from-file=.

3. To create from the literal 

k create configmap literal-config --from-literal=mykey=myval1 --from-literal=myname=ramkumar
