This project is a sample project to set up Nginx Unit as an application
server.

> NGINX is one of the most popular web servers and reverse proxies
available today. It offers high performance, almost infinite
configurability, and is a commonly used component in modern stacks
like Kubernetes. Now the NGINX team has a new offering called
NGINX Unit, which is aimed at solving some common challenges of
modern development processes.

The best part about Nginx Unit that it provides a consistent abstraction
over all the multitude of languages and frameworks available today.

Node.js itself doesn't really provide a solution here, which has spawned a host of
solutions like PM2, forever. PHP as well has ended up with a plethora of
options [Swoole](https://openswoole.com/), [Roadrunner](https://roadrunner.dev/)
[FrankenPHP](https://frankenphp.dev/).

If you're in a polyglot engineering team, you're battling a mix of different
application servers. While it is true, that certain application servers
may be drastically snappier than Nginx Unit, I'm feel that Nginx Unit is
spiffy enough. The productivity gains from a standardised application
server and the benefits of a harmonised setup, outweigh the other shortcomings.

## Usage

To get this sample project up and running, you'll need to first build the
containers. The project has been configured to demo the Nginx Unit usage
across multiple languages. Begin by starting the compose stack, which in
turn wil build the containers.

```sh
docker compose up --detach
```

Once the containers have been built, you access the application at
http://localhost:8081.

## Contributing

If you have suggestions for how this app could be improved, or
want to report a bug, open an issue - we'd love all and any
contributions.

## License

Apache License 2.0 © 2024 Mridang Agarwalla
