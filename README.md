# Acuparse Automated Installation Script

See the [Acuparse Install Guide](https://docs.acuparse.com/INSTALL) for further install details.

> **NOTICE:** ONLY Supports Debian/Rasbian Buster(10), Ubuntu Bionic(18.04) and Ubuntu Focal(20.04).

## Usage

Install your base Debian/Ubuntu based operating system. Then, run this installer:

```bash
curl -O https://gitlab.com/acuparse/installer/raw/master/install && sudo bash install | tee ~/acuparse.log
```

If that fails, try:

```bash
wget https://gitlab.com/acuparse/installer/raw/master/install && sudo bash install | tee ~/acuparse.log
```

### Docker Compose

See [docs/DOCKER.md](https://docs.acuparse.com/DOCKER) for detailed installation instructions.

On a newly installed Debian/Ubuntu System

- Download and run the installer.
    - If you already have Docker installed, see the Docker guide.

    ```bash
    curl -O https://gitlab.com/acuparse/installer/raw/master/install_docker && \
    sudo bash install_docker full | tee ~/acuparse.log
    ```

## Licencing

This automated installer licensed under the MIT license.

See [LICENSE](LICENSE) for more details.

## Release Notes

See [CHANGELOG.md](CHANGELOG.md) for detailed release notes.
