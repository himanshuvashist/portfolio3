---
title: "Docker: installation steps for Debian/Ubuntu"
date: "2021-09-06"
draft: false
path: "/blog/getting-started-with-docker"
---

#### first uninstall old versions

```sh
sudo apt-get remove docker docker-engine docker.io containerd runc
```

---

#### update package index

```sh
sudo apt-get update
```

---

#### install packages

```sh
 sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```

---

#### add Docker's official GPG key:

```sh
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
```

---

#### run the following command to add the stable repository

```sh
echo \
  "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```

---

#### finally , Install Docker engine

```sh
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
```

---

#### Verify

```sh
sudo docker run hello-world
```

---

#### **_Optional : if you want to run docker without sudo_**

```sh
sudo usermod -aG docker $USER
sudo chmod 666 /var/run/docker.sock
```

---

#### For official Docker installation guide, <a href="https://docs.docker.com/engine/install/" target="_blank">Click here</a>
