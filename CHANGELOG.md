## [0.11.1](https://github.com/binary-braids/docker-homelab/compare/v0.11.0...v0.11.1) (2025-06-29)


### Bug Fixes

* **authentication:** remove port mapping and update server configuration in docker-compose ([89f09e1](https://github.com/binary-braids/docker-homelab/commit/89f09e10d78f4fa1f4040a4cc3de74da993facba))
* **docker-compose:** add missing port mapping and update forwardAuth address for authelia service ([d4c9142](https://github.com/binary-braids/docker-homelab/commit/d4c91422cf5a93f0b922157c2c35bed90f92aef6))



# [0.11.0](https://github.com/binary-braids/docker-homelab/compare/v0.10.5...v0.11.0) (2025-06-29)


### Bug Fixes

* **authentication:** add quotes around AUTHELIA_ADMIN_PASSWORD in users_database.yml ([2663fcf](https://github.com/binary-braids/docker-homelab/commit/2663fcf3ba5eb593283ef0ed2eadbdbede0517c6))
* **authentication:** change default access control policy from two_factor to one_factor ([e9c22eb](https://github.com/binary-braids/docker-homelab/commit/e9c22eb08d95d2dafc581d4dc1a7c7454feb7f43))
* **authentication:** remove quotes around AUTHELIA_ADMIN_PASSWORD in users_database.yml ([d209f05](https://github.com/binary-braids/docker-homelab/commit/d209f0541440972377f2b26226f55376bc6d119a))
* **docker-compose:** correct service reference for secure-invoke-ai in Traefik configuration ([715a9d9](https://github.com/binary-braids/docker-homelab/commit/715a9d94d5311c35156c2a0e95ab51a381a8bae0))
* **docker-compose:** update invoke-ai image to specific version with CUDA support ([887320d](https://github.com/binary-braids/docker-homelab/commit/887320ded76c061cedd136f1215b7bf2d3cdcb3d))
* **docker-compose:** update invoke-ai service to include GPU resource reservations ([e06537d](https://github.com/binary-braids/docker-homelab/commit/e06537dc7505f373c99706b43adb471e7307c8c0))


### Features

* **authentication:** add Authelia service with configuration and middleware support ([702aaea](https://github.com/binary-braids/docker-homelab/commit/702aaeab2e462d2815a43ffc30378fb99f0fbf41))
* **authentication:** add JWT secret configuration and remove domain from session settings ([932a0b9](https://github.com/binary-braids/docker-homelab/commit/932a0b98974a0a23a08f504067d7e4506fa1b31c))
* **authentication:** enhance authentication backend with Argon2 password hashing and search options ([f860dc1](https://github.com/binary-braids/docker-homelab/commit/f860dc11ad6fd5653fe5478fdbd83c6b7e334de5))
* **authentication:** restructure JWT secret and session cookie configuration in Authelia ([5044d6d](https://github.com/binary-braids/docker-homelab/commit/5044d6d354fc1b1422b1b7fdcf91690f79c08b7f))
* **authentication:** update Authelia configuration with server settings and session parameters ([3160bc1](https://github.com/binary-braids/docker-homelab/commit/3160bc16cd8e9b2c69367702cdd0a62a4b5f7fef))
* **authentication:** update session configuration with domain and Authelia URL ([4401e13](https://github.com/binary-braids/docker-homelab/commit/4401e13ff92a319b1d27830e57098263745889f1))
* **authentication:** update session configuration with domain and Authelia URL ([a62c159](https://github.com/binary-braids/docker-homelab/commit/a62c159df5ad39c19b129fcd824ee221aae36880))
* **docker-compose:** add INVOKE_DEVICE environment variable for CUDA support ([74bede2](https://github.com/binary-braids/docker-homelab/commit/74bede294bec9f313356fb4735b6b1f441087a49))
* **docker-compose:** add invoke-ai service with necessary configurations ([e3670f4](https://github.com/binary-braids/docker-homelab/commit/e3670f4e6af9aea7eff7e56629e85d175ea0fe72))
* **docker-compose:** update invoke-ai service configuration and add secure-invoke-ai service ([fdca03d](https://github.com/binary-braids/docker-homelab/commit/fdca03d928a7f9135372f58f7825c310ba017060))



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



