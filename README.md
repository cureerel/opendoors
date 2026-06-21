# OpenDoors

<div align="center">

A modern business platform distributed as pre-built Docker images for quick deployment and easy scaling.

[![Docker Image Size](https://img.shields.io/docker/image-size/cureerel/opendoors?style=flat-square&color=2496ED)](https://hub.docker.com/r/cureerel/opendoors)
[![Platform](https://img.shields.io/badge/platform-linux%20%7C%20amd64%20%7C%20arm64-blue?style=flat-square)]()

</div>

---

##  Features

| Feature | Description |
|---------|-------------|
|  **Dockerized** | Pre-built images for instant deployment |
| **Responsive** | Optimized for all screen sizes |
|  **Fast** | Built on Next.js for blazing performance |
|  **Scalable** | Easy horizontal scaling |
|  **Cloud Ready** | Deploy anywhere Docker runs |
|  **Low Maintenance** | Simple setup and updates |

---

##  Showcase

<table>
  <tr>
    <td><img src=".github/assets/img-01.png" width="100%" /></td>
    <td><img src=".github/assets/img-02.png" width="100%" /></td>
  </tr>
  <tr>
    <td><img src=".github/assets/img-03.png" width="100%" /></td>
    <td><img src=".github/assets/img-04.png" width="100%" style="height: 300px; object-fit: cover;" /></td>
  </tr>
  <tr>
    <td><img src=".github/assets/img-05.png" width="100%" /></td>
    <td><img src=".github/assets/img-06.png" width="100%" /></td>
  </tr>
  <tr>
    <td><img src=".github/assets/img-07.png" width="100%" /></td>
    <td><img src=".github/assets/img-08.png" width="100%" /></td>
  </tr>
  <tr>
    <td><img src=".github/assets/img-09.png" width="100%" /></td>
    <td><img src=".github/assets/img-10.png" width="100%" /></td>
  </tr>
</table>

---

##  Docker Images

### amd64

> Recommended for VPS servers, Railway, AWS EC2, DigitalOcean, and most Linux servers.

```bash
docker pull cureerel/opendoors_amd64:latest
```

```bash
docker run -d -p 3000:3000 cureerel/opendoors_amd64:latest
```

### arm64

```bash
docker pull cureerel/opendoors:latest
```

```bash
docker run -d -p 3000:3000 cureerel/opendoors:latest
```

---

##  Quick Start

```bash
# Pull the image
docker pull cureerel/opendoors:latest

# Run the container
docker run -d \
  --name opendoors \
  -p 3000:3000 \
  --restart unless-stopped \
  cureerel/opendoors:latest
```

Open your browser:

```
http://localhost:3000
```

---

##  Deployment


Deploy on any platform that supports Docker containers:

- Railway
- AWS (ECS / EC2)
- DigitalOcean (App Platform / Droplets)
- Azure (Container Apps)
- Google Cloud (Cloud Run)
- Docker Desktop
- Self-hosted VPS
---

##  Built With

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

##  License

This project is provided as a Docker image for deployment and evaluation purposes.

---

<div align="center">

**Made by Cureerel**

</div>