# Windows.ssh-copy-id
sch: https://www.google.com/search?q=windows+ssh-copy-id , https://www.google.com/search?q=windows+install+ssh-copy-id

# Solution:
- https://superuser.com/questions/1747549/alternative-to-ssh-copy-id-on-windows

## manually:
https://chrisjhart.com/Windows-10-ssh-copy-id/

```ps1
type $env:USERPROFILE\.ssh\id_rsa.pub | ssh {IP-ADDRESS-OR-FQDN} "cat >> .ssh/authorized_keys"
```

## Cygwin
```
choco install cygwin
```
sch: https://www.google.com/search?q=cygwin+install+ssh-copy-id

https://www.cygwin.com/install.html
