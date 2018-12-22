# kubevm
Manage local Kubernetes client versions

<p align="center">
  <img width="600" src="https://github.com/containership/kubevm/blob/assets/kubevm.svg">
</p>

## Installation
```
sudo git clone https://github.com/containership/kubevm /opt/kubevm
sudo ln -s /opt/kubevm/kubevm /usr/local/bin/kubevm
```

## Usage
```
❯ kubevm --help
USAGE:
  kubevm                       : list & set the available kubectl versions
  kubevm <VERSION>             : download & set a kubectl version
  kubevm -d,--delete <VERSION> : remove a kubectl version
  kubevm -h,--help             : show this message
```

## Contributing
Thank you for your interest in this project and for your interest in contributing! Feel free to open issues for feature requests, bugs, or even just questions - we love feedback and want to hear from you.

Pull requests are also always welcome! However, if the feature you're considering adding is fairly large in scope, please consider opening an issue for discussion first.
