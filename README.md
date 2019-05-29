# docker-jenkins-ubuntu
- container 內執行
```
sudo cp /root/.bashrc ~/
sudo cp /root/.profile ~/
sudo chown jenkins:jenkins .docker
```
- jenkins job 第一行加入`source ~/.bashrc`
