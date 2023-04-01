# Preparation

```sh
# install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
# install xcode
xcode-select --install
```

# How to Use
```sh
./homebrew.sh
```

# Other Dependencies
```sh
# kubectl authentication
## ref: https://cloud.google.com/blog/products/containers-kubernetes/kubectl-auth-changes-in-gke?hl=en
gcloud components install gke-gcloud-auth-plugin
```

# Reference
- https://zenn.dev/karaage0703/articles/665e0cbdbd69f0
