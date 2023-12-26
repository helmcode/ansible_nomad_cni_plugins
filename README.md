# Setup Nomad after install
### CNI Plugins
Doc: https://developer.hashicorp.com/nomad/docs/install#post-installation-steps
Verify architecture:
`echo "$( [ $(uname -m) = aarch64 ] && echo arm64 || echo amd64)"`

