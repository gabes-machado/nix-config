# nix-config

## installation
for installing and using the configs first install the nix package manager [Nix Page](https://nixos.org/download/)

or run this command (up to 28/05/2025):
```
$ sh <(curl --proto '=https' --tlsv1.2 -L https://nixos.org/nix/install)
```
after that you can head to the [nix-darwin](https://github.com/nix-darwin/nix-darwin) documentation

## note to self
install node

```
# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 22

# Verify the Node.js version:
node -v # Should print "v22.16.0".
nvm current # Should print "v22.16.0".

# Verify npm version:
npm -v # Should print "10.9.2".
```
