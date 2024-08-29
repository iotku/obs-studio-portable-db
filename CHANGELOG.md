# Changelog

## 1.0.0 (2024-08-29)


### ⚠ BREAKING CHANGES

* try 23.10 again
* Upgrade container to Noble (24.04)
* Point Container file to my fork instead
* use ubuntu 23.10 to match my ubuntu build version
* Update public signing key to my key
* drop software-properties common from extra-packages

### Features

* add age package ([#30](https://github.com/iotku/obs-studio-portable-db/issues/30)) ([b0989a9](https://github.com/iotku/obs-studio-portable-db/commit/b0989a9f791771999c105122b64cbf8687574650)), closes [#29](https://github.com/iotku/obs-studio-portable-db/issues/29)
* add bat and exa ([#27](https://github.com/iotku/obs-studio-portable-db/issues/27)) ([011241e](https://github.com/iotku/obs-studio-portable-db/commit/011241e4ac1fdee5f3fbe8b8321e44ba8a0cb561))
* add bind moun to fix obs configuration issue ([10d52c1](https://github.com/iotku/obs-studio-portable-db/commit/10d52c106d09f70f6f68973626419c3ff6bcf0c9))
* add clipboard ([ebc22bf](https://github.com/iotku/obs-studio-portable-db/commit/ebc22bf72a10043ebec55c285dfe5274f1378cc5))
* add conventional commits linter and changelog generator ([#5](https://github.com/iotku/obs-studio-portable-db/issues/5)) ([0bc283d](https://github.com/iotku/obs-studio-portable-db/commit/0bc283d271878071ef50a413bab48f3bfc1ab312))
* add dependabot for actions ([#18](https://github.com/iotku/obs-studio-portable-db/issues/18)) ([cc17ca5](https://github.com/iotku/obs-studio-portable-db/commit/cc17ca5202c1777d5e64799b00cb235b72027e24))
* add make ([#10](https://github.com/iotku/obs-studio-portable-db/issues/10)) ([0cb4b59](https://github.com/iotku/obs-studio-portable-db/commit/0cb4b59cdd98c47d2f6bfa21f801b99b045d5e40))
* add npm ([#8](https://github.com/iotku/obs-studio-portable-db/issues/8)) ([9f91bd0](https://github.com/iotku/obs-studio-portable-db/commit/9f91bd09272617c7b9203014222353265dc24947))
* add packages so that launch is faster ([6e3d258](https://github.com/iotku/obs-studio-portable-db/commit/6e3d258b616b8770d8c6997b6aa94276277d534f))
* add vimdiff ([#12](https://github.com/iotku/obs-studio-portable-db/issues/12)) ([cf4202f](https://github.com/iotku/obs-studio-portable-db/commit/cf4202f76752561d9b926c81933342a119e8a258))
* add wl-clipboard ([#16](https://github.com/iotku/obs-studio-portable-db/issues/16)) ([347647e](https://github.com/iotku/obs-studio-portable-db/commit/347647ea7f9f7bdb3b42d2a565df866f027a7ade))
* Create CODE_OF_CONDUCT.md ([#4](https://github.com/iotku/obs-studio-portable-db/issues/4)) ([f433b89](https://github.com/iotku/obs-studio-portable-db/commit/f433b89a1ed125c6c0a251c1eec60525cfe35820))
* nicer filter to allow commenting out apps ([#15](https://github.com/iotku/obs-studio-portable-db/issues/15)) ([61d3e33](https://github.com/iotku/obs-studio-portable-db/commit/61d3e330beb9c2a8bd557ef3872aa6595c76b1b2))
* switch to alpine edge ([#22](https://github.com/iotku/obs-studio-portable-db/issues/22)) ([cf396c3](https://github.com/iotku/obs-studio-portable-db/commit/cf396c369ae8d8bb052df9b0c39d392f61b909ba))
* use --no-install-recommends when installing extra-packages ([3102d37](https://github.com/iotku/obs-studio-portable-db/commit/3102d37817f017a596e9b5177fb00ce85d9f0410))
* use the optimised obs-container-dependencies install script ([738f7f7](https://github.com/iotku/obs-studio-portable-db/commit/738f7f7804a993479441ec9e2edb0a416866ef8e))


### Bug Fixes

* (HACK) - Move config directory to home folder ([da9a4ce](https://github.com/iotku/obs-studio-portable-db/commit/da9a4ce4f61a3ac7bfc95b285605901811c245f1))
* base on Ubuntu 23.04 so Gstreamer and VA-API work ([b8dc34b](https://github.com/iotku/obs-studio-portable-db/commit/b8dc34b6488a7f8a5167fa196af7a966e494f137))
* **ci:** obs-container-dependencies requires software-properties-common ([9246556](https://github.com/iotku/obs-studio-portable-db/commit/9246556ae8ddffd1ef5c28a3bc88891e50f20ff2))
* constrain browser_download_url to just the tarballs of obs-portable ([f404a5f](https://github.com/iotku/obs-studio-portable-db/commit/f404a5fca61304d4f51d848470f3e0a55fb3570e))
* Correct typo in obs-config-fix.sh ([6ead05e](https://github.com/iotku/obs-studio-portable-db/commit/6ead05e1c02d115cd861762f143e9e6521f34b93))
* Don't create link in Containerfile ([9b4ecc8](https://github.com/iotku/obs-studio-portable-db/commit/9b4ecc82bb1e2c1a99139938967399060211ef26))
* fix typo ([8addf9e](https://github.com/iotku/obs-studio-portable-db/commit/8addf9e4499a83b2b9b591e9808470f3e3f6a46e))
* Move config to ~/.config directory ([edef524](https://github.com/iotku/obs-studio-portable-db/commit/edef5248cc632192c85a628d2b2edea9a2380863))
* remove xhost line ([ba03596](https://github.com/iotku/obs-studio-portable-db/commit/ba03596ab20647b56bf40dde28d0c89209154fc8))
* replace outdated transitional packages with modern equivelents ([c807987](https://github.com/iotku/obs-studio-portable-db/commit/c8079877fdfb64815ef267d4980d7c9b45bea711))
* typos in obs-config-fix.sh ([6f40878](https://github.com/iotku/obs-studio-portable-db/commit/6f408789cae0fb4cc6642a9eea4d4938558453af))
* update containerfile ([003e7f3](https://github.com/iotku/obs-studio-portable-db/commit/003e7f32956c379c4e9f7203b88fc9dde5c5e537))
* update dependabot ([#19](https://github.com/iotku/obs-studio-portable-db/issues/19)) ([0c388c9](https://github.com/iotku/obs-studio-portable-db/commit/0c388c958985cdc7d3c2d3de5d6d58de09472edf))
* update maintainer field ([#37](https://github.com/iotku/obs-studio-portable-db/issues/37)) ([e94a8a6](https://github.com/iotku/obs-studio-portable-db/commit/e94a8a69c34f5692514ebcc8c3ac21e2f33aa947))
* update path for .desktop and icons ([9d8694a](https://github.com/iotku/obs-studio-portable-db/commit/9d8694a253670716141473b2b362fe487056b3c8))
* update signing key ([52facd0](https://github.com/iotku/obs-studio-portable-db/commit/52facd0a059403e6125e7904755cccf356ec40bb)), closes [#25](https://github.com/iotku/obs-studio-portable-db/issues/25)
* update ubuntu 23.04 container URL ([1ed4028](https://github.com/iotku/obs-studio-portable-db/commit/1ed4028d39d47b60de7b4a62ba7c0014471e9c5e))
* Use master branch for icons ([0f7367e](https://github.com/iotku/obs-studio-portable-db/commit/0f7367e095141ef8d7a75b0d9c0cad9bc8dfe111))
* we don't need these packages ([7bf73b6](https://github.com/iotku/obs-studio-portable-db/commit/7bf73b6bfe1bd9db67ccaa6b024869d2ff9061e1))


### Miscellaneous Chores

* drop software-properties common from extra-packages ([0251d6e](https://github.com/iotku/obs-studio-portable-db/commit/0251d6e57ebfd0670c042da845a0cb1bd5b17ddf))


### Build System

* Point Container file to my fork instead ([e18219e](https://github.com/iotku/obs-studio-portable-db/commit/e18219e5dbb9f2f455460aecdaad506d8797d26f))
* try 23.10 again ([ffe3916](https://github.com/iotku/obs-studio-portable-db/commit/ffe39164e567eee28aa3f45b160fb787fd4615ae))
* Update public signing key to my key ([d16bfb4](https://github.com/iotku/obs-studio-portable-db/commit/d16bfb42f4c0ee1869b7dd2f94a3a28fa39c211a))
* Upgrade container to Noble (24.04) ([0ff20f3](https://github.com/iotku/obs-studio-portable-db/commit/0ff20f377200ae54d6352a8c87f76094cd61539a))
* use ubuntu 23.10 to match my ubuntu build version ([485ce37](https://github.com/iotku/obs-studio-portable-db/commit/485ce3799112b2495d0e47c0c1709dcc9cad8e15))

## 1.0.0 (2023-02-04)


### Features

* add conventional commits linter and changelog generator ([#5](https://github.com/ublue-os/boxkit/issues/5)) ([0bc283d](https://github.com/ublue-os/boxkit/commit/0bc283d271878071ef50a413bab48f3bfc1ab312))
* Create CODE_OF_CONDUCT.md ([#4](https://github.com/ublue-os/boxkit/issues/4)) ([f433b89](https://github.com/ublue-os/boxkit/commit/f433b89a1ed125c6c0a251c1eec60525cfe35820))
