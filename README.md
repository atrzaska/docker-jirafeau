[![](https://images.microbadger.com/badges/image/jgeusebroek/jirafeau.svg)](https://microbadger.com/images/jgeusebroek/jirafeau "Get your own image badge on microbadger.com")
# Docker Jirafeau image

A tiny image running [alpine](https://github.com/gliderlabs/docker-alpine) Linux and [jirafeau](https://gitlab.com/mojo42/Jirafeau).

## Usage

	docker run --restart=always -d \
		-p 0.0.0.0:80:80 \
		--hostname=jirafeau \
		--name=jirafeau \
		-v /<host_data_directory>:/data \
		-v /<host_cfg_directory>:/cfg \
		andrzejtrzaska/jirafeau

## License

MIT / BSD

## Author Information

[Jeroen Geusebroek](http://jeroengeusebroek.nl/)
