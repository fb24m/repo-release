# repo-release

The `logical-os` repository contains official [Logical OS](https://github.com/the-logical-os/logical-os) packages, including system components, themes, utilities, and desktop customizations.

Enable the repository on your Fedora system:

```bash
printf '%s\n' '[logical-os]' 'name=Logical OS' 'baseurl=https://the-logical-os.github.io/repo-release/' 'enabled=1' 'gpgcheck=0' | sudo tee /etc/yum.repos.d/logical-os.repo > /dev/null
sudo dnf update
```
