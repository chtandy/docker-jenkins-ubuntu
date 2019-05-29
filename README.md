# docker-jenkins-ubuntu
- 第一次進 container 內執行
```
sudo cp /root/.bashrc ~/
sudo cp /root/.profile ~/
sudo chown jenkins:jenkins .docker
```
- 之後每次登入container 用jenkins身份執行`source ~/.bashrc`

- jenkins job 第一行加入`source ~/.bashrc`
- jenkins job 有關docker 命令都需要用`sudo docker`
