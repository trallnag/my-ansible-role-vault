> This role is not meant to be shared. It is only used by myself.
> I use this role in my playbooks by adding the repo as a Git submodule.

# Ansibel Role `vault`

Role that installs the HashiCorp Vault CLI and setups completion for Bash and
Zsh.

- <https://github.com/hashicorp/vault>

## FAQ

### How to bump the version of Vault?

Go into [vars/main.yaml](vars/main.yaml) and bump the version in the
"Install Vault with asdf" task.
