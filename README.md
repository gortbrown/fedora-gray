# Fedora Gray
My own custom OSTree image based on Fedora Kinoite

## Installation
Run the commands below to apply to a Silverblue or Kinoite Installation
### Fresh Install
Run this first if starting with a fresh Silverblue or Kinoite install:

```sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/gortbrown/fedora-gray:latest```

Then reboot afterwards

### After first command/updating install

```sudo rpm-ostree rebase ostree-image-signed:docker://ghcr.io/gortbrown/fedora-gray:latest```
