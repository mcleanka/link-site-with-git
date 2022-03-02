# link-site-with-git

Set ssh on any server to be controlled by git

```
  ssh-keygen -t rsa -b 4096 -C "github"
```
```
  Copy paste [/root/.ssh/id_server] && enter
```
- Will create to files in .ssh
```
  cd .ssh
```
Copy key
```
  cat id_server.pub | pbcopy
```
```
  nano authorized_keys
```
Go to github > repos > settings > deploy key
```
  paste the copied key
```
To the serve terminal run
```
  ssh -T git@github.com
```
