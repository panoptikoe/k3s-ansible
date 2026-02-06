# About this branch
With this, you get the extra option to deploy Longhorn. You can specify a version of Longhorn and it will deploy it in your cluster using kubectl. First, it will check if your nodes have all the required things in place. 
I've only tested this with nodes running Ubuntu 24.04 for now, on x86_64.

## Thanks 🤝

This repo is really standing on the shoulders of giants. Thank you to all those who have contributed and thanks to these repos for code and ideas:

- [k3s-io/k3s-ansible](https://github.com/k3s-io/k3s-ansible)
- [geerlingguy/turing-pi-cluster](https://github.com/geerlingguy/turing-pi-cluster)
- [212850a/k3s-ansible](https://github.com/212850a/k3s-ansible)
- [timothystewart6/k3s-ansible](https://github.com/timothystewart6/k3s-ansible)
