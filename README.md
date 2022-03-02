# link-site-with-git

Set ssh on any server to be controlled by git

```
  - ssh-keygen -t rsa -b 4096 -C "server"
  - Copy paste [/root/.ssh/id_server] && enter
  - cd .ssh
  - cat id_server.pub | pbcopy 
  - nano authorized_keys
  - paste the copied key
  - ssh -T git@github.com
```
