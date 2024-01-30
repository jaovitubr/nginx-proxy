# nginx-proxy

<p align="left">
  <a href="https://shields.io/" target="_blank">
    <img src="https://img.shields.io/github/languages/top/jaovitubr/nginx-proxy?color=brightgreenn" alt="Main Lang"/>
  </a>
  <a href="https://github.com/bwhybrow23" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-jaovitubr-blue.svg?logo=github&logoColor=FFF" alt="GitHub"/>
  </a>
</p>

## Description

`nginx-proxy` allows you to run Nginx portably. It simplifies the process of starting Nginx with a portable configuration file.

## Usage

By default, the package looks for the Nginx configuration file at `./nginx.conf` relative to the directory where the command is executed. You can specify a different configuration file using the `-c` option:

```bash
npx nginx-proxy
```

### Options

- `-c`: Specify the path to the Nginx configuration file (default: `./nginx.conf`).
- [Command-line parameters documentation](https://nginx.org/en/docs/switches.html)
- [Configuration documentation](https://www.nginx.com/resources/wiki/start/topics/examples/full/)

## Acknowledgments

- [Nginx](https://nginx.org/): The high-performance HTTP server and reverse proxy server.