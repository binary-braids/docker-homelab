## [0.10.5](https://github.com/binary-braids/docker-homelab/compare/v0.10.4...v0.10.5) (2025-06-28)


### Bug Fixes

* **docker-compose:** add missing volume mapping for searxng service ([cf2ea52](https://github.com/binary-braids/docker-homelab/commit/cf2ea522a7f017e11b1259701b399a24bb4b062c))



## [0.10.4](https://github.com/binary-braids/docker-homelab/compare/v0.10.3...v0.10.4) (2025-06-28)


### Bug Fixes

* **docker-compose:** update MinIO image to RELEASE.2025-06-13T11-33-47Z-cpuv1 ([c11bcd9](https://github.com/binary-braids/docker-homelab/commit/c11bcd9c896bfc4004ff93f02bcfe74d867acd6f))



## [0.10.3](https://github.com/binary-braids/docker-homelab/compare/v0.10.2...v0.10.3) (2025-06-28)


### Bug Fixes

* **docker-compose:** enable insecure extension access for stable-diffusion-forge-webui ([ab36e30](https://github.com/binary-braids/docker-homelab/commit/ab36e302b4349b5d6620aec599d460023ba188c0))



## [0.10.2](https://github.com/binary-braids/docker-homelab/compare/v0.10.1...v0.10.2) (2025-06-28)


### Bug Fixes

* **docker-compose:** remove platform specification for pve-exporter service ([55bce30](https://github.com/binary-braids/docker-homelab/commit/55bce30aa5828dc6cbb952b20fc80aaf66e00030))



## [0.10.1](https://github.com/binary-braids/docker-homelab/compare/v0.10.0...v0.10.1) (2025-06-28)


### Bug Fixes

* **docker-compose:** add external volume definitions for prometheus, grafana, and alertmanager ([6e819f2](https://github.com/binary-braids/docker-homelab/commit/6e819f2428753c4a2cf7a35d9357aabeb7179272))



# [0.10.0](https://github.com/binary-braids/docker-homelab/compare/v0.9.0...v0.10.0) (2025-06-28)


### Bug Fixes

* **docker-compose:** correct grafana volume name in docker-compose configuration ([f2799b4](https://github.com/binary-braids/docker-homelab/commit/f2799b42b9ba0f982b0e9cf7e7ec827080e1231c))
* **docker-compose:** correct grafana volume reference and clean up network/volume definitions ([008bd8b](https://github.com/binary-braids/docker-homelab/commit/008bd8bd94037ab8fea3bf60ccb8bc2e28ff94b4))
* **docker-compose:** update entrypoints to use 'websecure' for Traefik routers ([36474d5](https://github.com/binary-braids/docker-homelab/commit/36474d5d6d96315769e91f81ff981f7994270a5f))
* **docker-compose:** update volume definitions for prometheus and alertmanager services ([cdd8f61](https://github.com/binary-braids/docker-homelab/commit/cdd8f610725d86f2bd0943e5c3178aadca3369e7))


### Features

* **docker-compose:** specify platform for pve-exporter service ([47c187e](https://github.com/binary-braids/docker-homelab/commit/47c187e06d0ec7421c7370bab97c4d625b5ca971))



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



