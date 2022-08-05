<h1 align="center">Observability with Prometheus</h1>

<p align="center">👀 Observability concepts using Prometheus and Grafana 👀</p>

---

Table of contents
=================
<!--ts-->
   * [About the project](#-about-the-project)
   * [Technologies](#-technologies)
   * [How to run](#-how-to-run)
   * [Author](#-author)
   * [License](#-license)
<!--te-->

---

## About the project <a name="-about-the-project" style="text-decoration:none"></a>

Project made with the objective of studying observability concepts using [Prometheus](https://prometheus.io/) and [Grafana](https://grafana.com/). 

---

## Technologies <a name="-technologies" style="text-decoration:none"></a>

- **[Docker](https://www.docker.com/)**
- **[Docker-compose](https://docs.docker.com/compose/)**
- **[Prometheus](https://prometheus.io/)**
- **[Grafana](https://grafana.com/)**

---

## How to run <a name="-how-to-run" style="text-decoration:none"></a>

### Prerequisites

Before starting, you will need to have the following tools installed on your machine: [Git](https://git-scm.com), [Docker](https://www.docker.com/) and [Docker-compose](https://docs.docker.com/compose/). To work with the code, it is recommended to use a good editor, such as the [VSCode](https://code.visualstudio.com/).

#### Running the application

```bash

# Clone this repository
$ git clone https://github.com/emanuelmassafera/observability-prometheus.git

# Access the project folder via the terminal/cmd
$ cd observability-prometheus

# Start the services
$ docker-compose up -d

# Access the app via the terminal/cmd
$ docker exec -it app sh

# Start the app
$ go run main.go

# The grafana dashboards will start at port:3000 (credentials: admin/admin)
# The app will start at port:8181

```
---

## Author <a name="-author" style="text-decoration:none"></a>

<img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/65625500?s=460&u=eb9e300de61698fc8531949a451ce2f0e9da46f9&v=4" width="100px;" alt=""/>
<sub>Emanuel Massafera</sub>

<b></b>

[![Badge](https://img.shields.io/static/v1?label=&message=Emanuel&color=blue&style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/emanuelmassafera/)](https://www.linkedin.com/in/emanuelmassafera/) [![Badge](https://img.shields.io/static/v1?label=&message=emanuel301@live.com&color=0078D4&style=flat-square&logo=Microsoft-Outlook&logoColor=white&link=mailto:emanuel301@live.com)](mailto:emanuel301@live.com)

---

## License <a name="-license" style="text-decoration:none"></a>

This repository is licensed by **MIT LICENSE**. For detailed information, read the file [LICENSE](https://github.com/emanuelmassafera/observability-prometheus/blob/master/LICENSE). 

Made with ♥ by Emanuel Massafera :wave: [Get in touch!](https://www.linkedin.com/in/emanuelmassafera/)
