# Kubernetes

<p align="center">
    <img src="images/k8s.png" width="400">
</p>


---

Criado pelo Google e hoje OpenSource é a ferramenta de orquestrão de container mais utilizada do mercado, apresenta mais complexidade de configuração do que os concorrentes, porém tem mais funcionalidades.

## Arquitetura Básica do K8S

### Pod

É a menor unidade de computação publicável em um computador que podemos criar e gerenciar, o **K8S** não faz acesso direto aos containers e sim nos Pods, um pod é uma instância unica de uma app.

<p align="left">
    <img src="images/pods.png" width="300">
</p>

### Node

É uma máquina física ou virtual, onde o K8S está instalado

### Cluster

Conjuntos de Nodes agrupados

#### Master

Gerencia o Cluster e seus nodes, monitora para tomar alguma decisão.

<p align="left">
    <img src="images/cluster.png" width="300">
</p>



