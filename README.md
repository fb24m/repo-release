# repo-release

```bash
printf '%s\n' '[logical-os]' 'name=Logical OS' 'baseurl=https://fb24m.github.io/repo-release/' 'enabled=1' 'gpgcheck=0' | sudo tee /etc/yum.repos.d/logical-os.repo > /dev/null
sudo dnf update
```
