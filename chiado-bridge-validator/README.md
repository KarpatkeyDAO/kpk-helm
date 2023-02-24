### Chiado Bridge Validator Helm Chart

- For more info please visit [here](https://github.com/gnosischain/chiado-ansible-bridges/tree/feature/deployment) or [xdai](https://gist.github.com/LaimeJesus/4deb38f19e714f90e80527d1971ce1d9) / [amb](https://gist.github.com/LaimeJesus/e6d4afd4fe2a70bb3be07182c67ad826)



Steps:

- 1: git clone https://github.com/KarpatkeyDAO/kpk-helm

- 2: copy the values.yaml to override.yaml and paste the env values into that

- 3: kubectl create ns bridge-validator

- 4: helm install -n bridge-validator chiado ./chiado-bridge-validator/ -f override.yaml

- 5: check the pod logs!
