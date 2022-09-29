# docker-compose-yx

[docker compose](https://docs.docker.com/compose/)仓库，拉取到本地提供用户快速部署docker项目

## 环境准备

### 安装docker
安装Docker:[https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)

### 安装docker-compose
您可以在macOS，Windows和64位Linux上运行[docker-compose](https://docs.docker.com/compose/)

#### Docker Desktop安装

Docker Desktop安装包括Docker Engine ，Docker CLI客户端， Docker Compose ， Docker Machine和Kitematic 。

#### Pip安装

```bash
pip install docker-compose
```

#### 测试安装

```bash
docker-compose --version
```

## 使用方法

### docker-compose-yx

克隆仓库或下载[Releases](https://github.com/JingyuanR/docker-compose-yx/releases)

```bash
git clone https://github.com/JingyuanR/docker-compose-yx.git
```

### 部署docker项目

进入需要部署的项目目录下执行，确认目录下包含`docker-compose.yml`文件

```bash
docker-compose up
```

## 支持Docker项目

TODO 