# repo-release

```bash
printf '%s\n' '[logical-os]' 'name=Logical OS Repository' 'baseurl=https://repo.logical-os.org/' 'enabled=1' 'gpgcheck=0' | sudo tee /etc/yum.repos.d/logical-os.repo > /dev/null
sudo dnf update
```
