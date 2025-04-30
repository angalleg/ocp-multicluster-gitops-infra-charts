# Infrastructure Charts

This repository includes a set of Helm Charts to generate a GitOps strategy for managing multiple Openshift clusters from an infrastructure management perspective using Red Hat Advantage Cluster Management (ACM).

Please review the _charts_ folder to find the different charts generated.

1- Cambiar changelog
2- Cambiar version chart.yaml
3- Execute
helm package infra-acm
helm registry login 
helm push infra-acm-0.1.4.tgz oci://quay.io

## Author

Asier Cidon @RedHat
Andrea García
David Luelmo