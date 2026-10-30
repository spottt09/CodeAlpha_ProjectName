# Environment Setup

- **Target** : **OWASP Juice Shop**
- **Objective** : **Assess eight selected security challenge scenarios**
- **Authorization** : **Testing is restricted to your own local lab**
- **Out of Scope** : **External systems, other user's real data, and disruptive testing**
- **Limitation** : **Only three challenges have screen recordings**

# Commands for docker setup
## 1. docker installation
  sudo apt install docker

## 2. start docker
  sudo systemctl enable docker --now

## 3. set user
  sudo usermod -aG docker $USER

## 4. start new group
  newgrp docker

## 5. check it
  docker ps

## 6. pull juice shop
  docker pull bkimminich/juice-shop

## 7. start hosting web
  docker run --rm -p 3000:3000 bkimminich/juice-shop
