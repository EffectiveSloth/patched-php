# Patched PHP

`ghcr.io/effectivesloth/patched-php` — `linux/amd64` and `linux/arm64`.

| PHP | Debian tags | Alpine tags |
| --- | --- | --- |
| 7.4.33 | `7.4-cli-debian`, `7.4-fpm-debian` | `7.4-cli-alpine`, `7.4-fpm-alpine` |
| 8.0.30 | `8.0-cli-debian`, `8.0-fpm-debian` | `8.0-cli-alpine`, `8.0-fpm-alpine` |
| 8.1.34 | `8.1-cli-debian`, `8.1-fpm-debian` | `8.1-cli-alpine`, `8.1-fpm-alpine` |

Each tag also has a `<tag>-<git-commit>` tag.

Official [Dockerfiles](https://github.com/docker-library/php) with PHP's
CVE-2026-109618 / CVE-2026-109619 mitigation applied before compilation:
[PHP 7.4 patch](https://github.com/php/php-src/commit/712e60f9edfd03f0960fc4fc3c2c375f42b90aa2),
[PHP 8.0 patch](https://github.com/php/php-src/commit/82f8f31b16a035c1b67cc253e79f7cc288f4cc20),
[PHP 8.1 patch](https://github.com/php/php-src/commit/1d7dec178a094e6e75b229ce22754045f8c6070a).
