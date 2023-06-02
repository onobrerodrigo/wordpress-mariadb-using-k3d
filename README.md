Em progresso...

# Como executar uma aplicação Wordpress com banco MariaDB 

Como executar uma aplicação Wordpress e um banco MariaDB em um cluster K3D.

## Requerimentos

- K3D
- MetalLB

Com o [**MetalLB**](https://metallb.universe.tf/) podemos utilizar o recurso de [`LoadBalancer`](https://kubernetes.io/docs/concepts/services-networking/ingress/#load-balancing) mesmo estando executando um cluster local ou em ambientes On-Premises.
