## [0.1.1](https://github.com/binary-braids/docker-homelab/compare/v0.1.0...v0.1.1) (2024-09-15)


### Bug Fixes

* add relabel config for prometheus to remove port numbers ([db887b9](https://github.com/binary-braids/docker-homelab/commit/db887b9f2e174d3953f93fc21e4ae580833cd332))
* enable remote write and add relabel config for node exporter ([e4bd9d5](https://github.com/binary-braids/docker-homelab/commit/e4bd9d51942d1eb23e9cff9ff48de79f34011c8a))



# [0.1.0](https://github.com/binary-braids/docker-homelab/compare/f488fb61f513c95aa04590766c90d0497841668d...v0.1.0) (2024-09-14)


### Bug Fixes

* add `.gitattributes` file for language detection ([f1e2852](https://github.com/binary-braids/docker-homelab/commit/f1e285284089d133b9a8c3d53dcb6d26143b10b2))
* add basic set of alerts ([7886803](https://github.com/binary-braids/docker-homelab/commit/7886803fe2fa28cfd554912b05c70bb642f15251))
* add escape characters for alert rules ([a5c454a](https://github.com/binary-braids/docker-homelab/commit/a5c454ac32bc4e1a7bfc0dd5ffb209faa9425e4e))
* add min required alertmanager config ([35e3b88](https://github.com/binary-braids/docker-homelab/commit/35e3b88a73a9fd1a7b001dc754983b8cee35d45c))
* add persistent volume for grafana ([aa45270](https://github.com/binary-braids/docker-homelab/commit/aa452706c819f343176b1459307db9f645abc92e))
* add quotation to alert summary ([f890c0d](https://github.com/binary-braids/docker-homelab/commit/f890c0da27ba74ccd46c990012f4516a33b32030))
* add relabel config ([9f85248](https://github.com/binary-braids/docker-homelab/commit/9f85248d5006a100462fe1b411dca92bbebf5310))
* add windows exporter port ([484a080](https://github.com/binary-braids/docker-homelab/commit/484a080d92aafacd3d4d60e6a77b265d4dc2b3ff))
* address variable substitution ([b5748ca](https://github.com/binary-braids/docker-homelab/commit/b5748ca30ac98bedac2fa23cbcc245461e1f9d39))
* alertmanager remove notifications ([66fc1c5](https://github.com/binary-braids/docker-homelab/commit/66fc1c58c33cb52b5c34ced9c9d1bf6294c5e758))
* another pve fix ([9f278d4](https://github.com/binary-braids/docker-homelab/commit/9f278d483987fc95a4738976dc6b513982f7726e))
* change proxmox pve exporter to password auth ([06a2fe9](https://github.com/binary-braids/docker-homelab/commit/06a2fe9925567dd6589a3b2735a27927d346c0e8))
* change pve exporter configuration ([4a9ba46](https://github.com/binary-braids/docker-homelab/commit/4a9ba4689fc07e821565d8e9d513f191ce255729))
* change scrape interval and rules yaml file reference ([b46d103](https://github.com/binary-braids/docker-homelab/commit/b46d103d0a42b119c5e6f280416735cf2b4fd90c))
* change target references ([4ec7767](https://github.com/binary-braids/docker-homelab/commit/4ec7767fd55b920c95ce773f1de6b06f2f5bff23))
* change to self hosted semaphore container ([22fe1b2](https://github.com/binary-braids/docker-homelab/commit/22fe1b29f86adbc9cbd2a655c19034cf878f842f))
* change yaml file naming convention ([148821d](https://github.com/binary-braids/docker-homelab/commit/148821d84146f89d15bf72e9af85081788469bcf))
* combine pve target scrape config ([afa1842](https://github.com/binary-braids/docker-homelab/commit/afa1842da46691f6d6fe4eea5434c4293725e2fd))
* correct CI workflow ([3467606](https://github.com/binary-braids/docker-homelab/commit/3467606c5b10a77e6e20c398620761ec183bc917))
* correct config references ([7d1bf7a](https://github.com/binary-braids/docker-homelab/commit/7d1bf7ab77b248c3db17aed1b2b884863a0042e6))
* correct disk space alert and add alertmanager notification ([8bfd1b6](https://github.com/binary-braids/docker-homelab/commit/8bfd1b68b4aa919eb66db2bee0484780896269a1))
* correct prometheus ref ([f488fb6](https://github.com/binary-braids/docker-homelab/commit/f488fb61f513c95aa04590766c90d0497841668d))
* correct pve exporter path ([618e558](https://github.com/binary-braids/docker-homelab/commit/618e55801036db758b2c542087bed80fe341fa46))
* correct scrape targets ([1670a90](https://github.com/binary-braids/docker-homelab/commit/1670a90598e03718c1c798f981d9382e365ff1ae))
* correct workflow file location ([557c2b0](https://github.com/binary-braids/docker-homelab/commit/557c2b0b0613b63275f566cf3b47e27de57e3a6a))
* fix semaphore ([c10d747](https://github.com/binary-braids/docker-homelab/commit/c10d74797be19ab3f0fa1883ff625e2a091ec209))
* modify alert thresholds ([f8afb5a](https://github.com/binary-braids/docker-homelab/commit/f8afb5a1f95cb48ce9709fcd7d340d5b15e92cd9))
* mysql reference ([563bb07](https://github.com/binary-braids/docker-homelab/commit/563bb079316983f976d72f9b54eb85d080dbacda))
* remove kerberos requirement ([0c53b8c](https://github.com/binary-braids/docker-homelab/commit/0c53b8c26594c977ce7ec454d51b7190d68182ea))
* remove requirements config ([9436f24](https://github.com/binary-braids/docker-homelab/commit/9436f2472a685ef055e16a716ff6203c37d17ca3))
* split pve targets ([d505404](https://github.com/binary-braids/docker-homelab/commit/d505404c1a643209123e36cadcf03ec635546399))
* switch grafana to volume ([d15e47c](https://github.com/binary-braids/docker-homelab/commit/d15e47c05f42a35304e3bc9b6acbe4416b1a00e2))


### Features

* add Github Actions workflow for releases ([404e926](https://github.com/binary-braids/docker-homelab/commit/404e926e9ed02110141e49eacf077f2d67d524ee))
* add pve-exporter container ([fafaff3](https://github.com/binary-braids/docker-homelab/commit/fafaff3fcf829a9fd1528afa7ce1b809cdf2e8b2))
* add semaphore stack ([d968d46](https://github.com/binary-braids/docker-homelab/commit/d968d46c5d593d2433bf743b278f4a9d68bafd6a))
* add windows scrape targets ([f24506b](https://github.com/binary-braids/docker-homelab/commit/f24506b351dd002afb7e5e8ba84262e6eadbb5e7))
* include `rules.yml` ([4aa8112](https://github.com/binary-braids/docker-homelab/commit/4aa8112e61485a3d4af810ede77446d55f9e77ad))
* limit prometheus retention to save on that precious storage space ([f7e1880](https://github.com/binary-braids/docker-homelab/commit/f7e188020c484238c15a9fef0f20e42a83b8493b))



