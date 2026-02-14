# mine-server

## Instalação

~~~bash
helm repo add minecraft-server-charts https://itzg.github.io/minecraft-server-charts/
helm repo update
~~~

~~~bash
helm upgrade --install minecraft minecraft-server-charts/minecraft -n minecraft --create-namespace -f values.yaml
~~~
