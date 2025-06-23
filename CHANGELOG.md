# [0.9.0](https://github.com/binary-braids/docker-homelab/compare/v0.8.0...v0.9.0) (2025-06-23)


### Features

* **searxng:** add SEARXNG_BASE_URL environment variable ([2f1ab99](https://github.com/binary-braids/docker-homelab/commit/2f1ab9908783c4e8ee74474b240ddf89f91b24a2))



# [0.8.0](https://github.com/binary-braids/docker-homelab/compare/v0.7.0...v0.8.0) (2025-06-22)


### Bug Fixes

* correct environment variable name for S3 bucket in docker-compose ([3407754](https://github.com/binary-braids/docker-homelab/commit/3407754643e7ff92e404b6b2eaa9e51f232250b7))
* update AWS_ENDPOINT to remove protocol in docker-compose ([6d75480](https://github.com/binary-braids/docker-homelab/commit/6d75480f4d1edd23bb4b7e6126ed5a34459c0717))


### Features

* add docker-compose configuration for volume backup service ([60d0d87](https://github.com/binary-braids/docker-homelab/commit/60d0d876928437721de7874974012d512d21c4c9))
* add isolated network configuration to docker-compose for volume backup service ([8285862](https://github.com/binary-braids/docker-homelab/commit/82858629360711cb78ffdd4e1065dd62c742a35a))
* ensure docker-volume-backup service is connected to the isolated network ([a3ff4cd](https://github.com/binary-braids/docker-homelab/commit/a3ff4cd614bb7f9c3c7c5ceaaed748c9db5bf2cc))



# [0.7.0](https://github.com/binary-braids/docker-homelab/compare/v0.6.0...v0.7.0) (2025-06-22)


### Bug Fixes

* **docker-compose:** add additional volume mounts for stable-diffusion-webui service ([f5af2fa](https://github.com/binary-braids/docker-homelab/commit/f5af2faeca835f5284ec54e8ff7cac0293e97af7))
* **docker-compose:** add missing API flag to stable-diffusion-webui command ([cf571fa](https://github.com/binary-braids/docker-homelab/commit/cf571faaad36ed594b477fa05d1bd124cdee7c6c))
* **docker-compose:** add resource limits for stable-diffusion-webui service ([7e117d9](https://github.com/binary-braids/docker-homelab/commit/7e117d9d6c850a680f7c32af89fabc955e9a7421))
* **docker-compose:** add runtime specification for stable-diffusion-webui service ([2e14242](https://github.com/binary-braids/docker-homelab/commit/2e1424225c5e381fd5f7f1a01f1f03d855d89a2d))
* **docker-compose:** correct Traefik router rule for stable-diffusion-webui service ([c9eec4f](https://github.com/binary-braids/docker-homelab/commit/c9eec4fa71697c59ade519615fe81a650129cd01))
* **docker-compose:** correct typo in Traefik router rule for stable-diffusion-webui ([d7bf13e](https://github.com/binary-braids/docker-homelab/commit/d7bf13ee148ae1f1cc971ae709646b097e24b4b3))
* **docker-compose:** enhance command for stable-diffusion-webui with additional options ([0bf394c](https://github.com/binary-braids/docker-homelab/commit/0bf394c350b8d0fe22a6da1f40113c0f749cb799))
* **docker-compose:** increase resource limits for stable-diffusion-webui service ([ee50c8d](https://github.com/binary-braids/docker-homelab/commit/ee50c8d75687da5ce62624a0d50c30f7d0cc592d))
* **docker-compose:** remove unnecessary option from stable-diffusion-webui command ([60fb33d](https://github.com/binary-braids/docker-homelab/commit/60fb33dddcdbde4dc66287b0dbd2d3d33828caa8))
* **docker-compose:** rename stable-diffusion-webui to stable-diffusion-forge-webui and update configuration ([c86b256](https://github.com/binary-braids/docker-homelab/commit/c86b256eb117a6cacbf68077554921c108a3fdbc))
* **docker-compose:** rename stable-diffusion-webui to stable-diffusion-forge-webui and update resource limits ([af4fa08](https://github.com/binary-braids/docker-homelab/commit/af4fa08f6f25550d015dd7ba70ad7b0e867cb032))
* **docker-compose:** rename stable-diffusion-webui-data volume to stable-diffusion-forge-webui-data ([7aed123](https://github.com/binary-braids/docker-homelab/commit/7aed1238c6bcc8101a9e42e77736894edf943b07))
* **docker-compose:** revert stable-diffusion-forge-webui volume to stable-diffusion-webui ([4d1503a](https://github.com/binary-braids/docker-homelab/commit/4d1503a8cedf8e86240a077b725e6ce0a2cd2beb))
* **docker-compose:** simplify command for stable-diffusion-webui service ([2439d97](https://github.com/binary-braids/docker-homelab/commit/2439d977a685e4151d6ccd4ebb64c43d1b58a354))
* **docker-compose:** update network configuration to use proxy for Traefik services ([dc4b77d](https://github.com/binary-braids/docker-homelab/commit/dc4b77d736cab5db3dc3556aa9f9fd32e412ac85))
* **docker-compose:** update service networks to use proxy instead of ai ([ce93b6a](https://github.com/binary-braids/docker-homelab/commit/ce93b6a52828faaeb8233536987b1f35a379d79a))
* **docker-compose:** update stable-diffusion-webui image and adjust volume mappings ([e45f920](https://github.com/binary-braids/docker-homelab/commit/e45f9209290b2578016c0fe2db94f15cdd4f0403))
* **docker-compose:** update stable-diffusion-webui service configuration and adjust volume mappings ([eed3f7b](https://github.com/binary-braids/docker-homelab/commit/eed3f7b3185bd61912a5abddd4c81e9be196148b))


### Features

* **docker-compose:** add docker-compose configuration for AI services including ollama, searxng, and open-webui ([08b3cf5](https://github.com/binary-braids/docker-homelab/commit/08b3cf586a472043f2878659c0e3af42120b1cb7))
* **docker-compose:** add environment variables for image generation in open-webui service ([45bd240](https://github.com/binary-braids/docker-homelab/commit/45bd240c1bbe16c71478d422a92f02ebad9412b1))
* **docker-compose:** add GPU resource reservations for ollama service ([fd8f8ca](https://github.com/binary-braids/docker-homelab/commit/fd8f8ca4aca11719d6322d93878aa8da665d93a0))
* **docker-compose:** add stable-diffusion-webui service configuration ([b458ab2](https://github.com/binary-braids/docker-homelab/commit/b458ab28ac8c6550c901c435c7d68d99ec464f5e))



# [0.6.0](https://github.com/binary-braids/docker-homelab/compare/v0.5.0...v0.6.0) (2025-05-05)


### Features

* **config:** add history configuration to docker-compose ([3508d50](https://github.com/binary-braids/docker-homelab/commit/3508d503c0a3dfe60132a51044791b414544961f))



# [0.5.0](https://github.com/binary-braids/docker-homelab/compare/v0.4.0...v0.5.0) (2025-04-28)


### Features

* **config:** add lovelace configuration and resources for HaCasa dashboard ([109477d](https://github.com/binary-braids/docker-homelab/commit/109477d7d40a041a5a979ae02124d5621eb4297e))



# [0.4.0](https://github.com/binary-braids/docker-homelab/compare/v0.3.6...v0.4.0) (2025-04-28)


### Features

* **config:** add frontend themes configuration to mobile_app ([11a8b1a](https://github.com/binary-braids/docker-homelab/commit/11a8b1a8e3b6715d14c3c6aa8e7a81bc85d2433d))



## [0.3.6](https://github.com/binary-braids/docker-homelab/compare/v0.3.5...v0.3.6) (2025-03-29)


### Bug Fixes

* remove TLS certresolver from Home Assistant Traefik router configuration ([67ea57b](https://github.com/binary-braids/docker-homelab/commit/67ea57b3a323e9786007429092232e6f0187483a))



## [0.3.5](https://github.com/binary-braids/docker-homelab/compare/v0.3.4...v0.3.5) (2025-03-29)


### Bug Fixes

* update Traefik router rule to use subdomain for Home Assistant ([7d21f22](https://github.com/binary-braids/docker-homelab/commit/7d21f22d3f535f3a632577236f24afe50c9a374e))



## [0.3.4](https://github.com/binary-braids/docker-homelab/compare/v0.3.3...v0.3.4) (2025-03-29)


### Bug Fixes

* add TLS certresolver for Home Assistant Traefik router ([71907a6](https://github.com/binary-braids/docker-homelab/commit/71907a67c524de0ba644869431349dd8b8d59828))



## [0.3.3](https://github.com/binary-braids/docker-homelab/compare/v0.3.2...v0.3.3) (2025-03-29)


### Bug Fixes

* update trusted_proxies CIDR range in Home Assistant docker-compose ([cb1daf8](https://github.com/binary-braids/docker-homelab/commit/cb1daf8c2dabda32dc9b14b5ef71dbb7f8dbd897))



