# [0.15.0](https://github.com/binary-braids/docker-homelab/compare/v0.14.2...v0.15.0) (2025-07-12)


### Features

* **docker-compose:** add new Prometheus scrape target for vm-br-prod-fra1-001 ([43d4e3b](https://github.com/binary-braids/docker-homelab/commit/43d4e3b88c77a301219c72dcf9115ebd7510c94f))



## [0.14.2](https://github.com/binary-braids/docker-homelab/compare/v0.14.1...v0.14.2) (2025-07-02)


### Bug Fixes

* **docker-compose:** update image name for secure-swarmui service ([337eb58](https://github.com/binary-braids/docker-homelab/commit/337eb58732a2d984db1754edc3720b88e060c3af))



## [0.14.1](https://github.com/binary-braids/docker-homelab/compare/v0.14.0...v0.14.1) (2025-07-02)


### Bug Fixes

* **docker-compose:** rename swarm-ui service to secure-swarmui and update Traefik labels ([ddb19c0](https://github.com/binary-braids/docker-homelab/commit/ddb19c08a5a0fe1c7ec56be17ebc69ff545d81c8))



# [0.14.0](https://github.com/binary-braids/docker-homelab/compare/v0.13.2...v0.14.0) (2025-07-02)


### Features

* **docker-compose:** add swarm-ui service configuration with Traefik labels ([53d4f3a](https://github.com/binary-braids/docker-homelab/commit/53d4f3ab08320ced4f37b320b365df76f762f7f0))



## [0.13.2](https://github.com/binary-braids/docker-homelab/compare/v0.13.1...v0.13.2) (2025-07-02)


### Bug Fixes

* **docker-compose:** remove INVOKEAI_ENABLE_PARTIAL_LOADING environment variable and clean up secure-invoke-ai service configuration ([940bbd3](https://github.com/binary-braids/docker-homelab/commit/940bbd3f8c2b57fdaa5f74d74a9a90fe9da2ba8a))



## [0.13.1](https://github.com/binary-braids/docker-homelab/compare/v0.13.0...v0.13.1) (2025-07-02)


### Bug Fixes

* **authentication:** remove users_database.yml configuration from docker-compose ([76b7985](https://github.com/binary-braids/docker-homelab/commit/76b7985d3388cefdfa79b40bde814930aff03e47))



# [0.13.0](https://github.com/binary-braids/docker-homelab/compare/v0.12.0...v0.13.0) (2025-07-02)


### Bug Fixes

* **authentication:** correct access control subject key in LDAP configuration ([335d68f](https://github.com/binary-braids/docker-homelab/commit/335d68fcd900fe67d84e783d64cf6471934e35d8))
* **authentication:** correct group name for access control rules ([2dc6da8](https://github.com/binary-braids/docker-homelab/commit/2dc6da8f16f16e2d3b34a777204d778d58db6896))
* **authentication:** correct syntax for group search mode in LDAP configuration ([42940ee](https://github.com/binary-braids/docker-homelab/commit/42940eede12289d5885d903c1923ac4c1945a5cc))
* **authentication:** remove file-based authentication configuration ([86fa9ff](https://github.com/binary-braids/docker-homelab/commit/86fa9ff6db55845f2d386219f66e3dce916aa883))
* **authentication:** remove unnecessary logs_level configuration and clean up users_database.yml ([a7da4d2](https://github.com/binary-braids/docker-homelab/commit/a7da4d267b8f7db5fe887ae32249c6e4375afd59))
* **authentication:** update access control rules to allow subdomains for binarybraids.com ([585fa22](https://github.com/binary-braids/docker-homelab/commit/585fa22a89621218222af9c9ffd552c63842ce7b))
* **authentication:** update access control subject key for Authelia Users ([6f0b02c](https://github.com/binary-braids/docker-homelab/commit/6f0b02c1ba2e45bedb5d366d35e1a861b4a3d89f))
* **authentication:** update access control subject key to include organizational unit for Authelia Users ([1a4ff24](https://github.com/binary-braids/docker-homelab/commit/1a4ff2427e2c675b76f08c85db60f23b6938e9cf))
* **authentication:** update display name attribute key in LDAP configuration ([1e03ae2](https://github.com/binary-braids/docker-homelab/commit/1e03ae2f24fb8d07908ced937aec7b76f3bd6c2c))
* **authentication:** update LDAP configuration to include TLS settings ([3e91d09](https://github.com/binary-braids/docker-homelab/commit/3e91d099af8347657d38e53c4f0e33bbb1faa292))
* **authentication:** update LDAP configuration to simplify user and group filters ([edc3179](https://github.com/binary-braids/docker-homelab/commit/edc3179a13ad75b20c6d17ab41112f80d9440bd6))
* **authentication:** update LDAP configuration to use structured attributes for user and group details ([bad2e15](https://github.com/binary-braids/docker-homelab/commit/bad2e151460a30592751e5077fa37c696622b9fb))


### Features

* **authentication:** add LDAP configuration and update access control policy ([8568465](https://github.com/binary-braids/docker-homelab/commit/856846546e4039de0f9c9e1b1f44ebce1b408bce))



# [0.12.0](https://github.com/binary-braids/docker-homelab/compare/v0.11.1...v0.12.0) (2025-07-02)


### Bug Fixes

* **authentication:** update session configuration for authelia service ([3d41a64](https://github.com/binary-braids/docker-homelab/commit/3d41a6428b8968d88f1d9b18ef3d20970fbfa279))
* **docker-compose:** remove stable-diffusion-forge-webui service configuration ([eb777a4](https://github.com/binary-braids/docker-homelab/commit/eb777a4d950f2fd2e1a005be1ee40922d8b2ae1b))


### Features

* **docker-compose:** add stable-diffusion-forge-webui service configuration ([47f8d02](https://github.com/binary-braids/docker-homelab/commit/47f8d0265758f62db1c851800c560d69a8274a49))



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



