<!-- DO NOT EDIT THIS FILE MANUALLY  -->
<!-- Please read the CONTRIBUTING.md -->

[![linuxserver.io](https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/linuxserver_medium.png)](https://linuxserver.io)

[![Blog](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Blog)](https://blog.linuxserver.io "all the things you can do with our containers including How-To guides, opinions and much more!")
[![Discord](https://img.shields.io/discord/354974912613449730.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Discord&logo=discord)](https://discord.gg/YWrKVTn "realtime support / chat with the community and the team.")
[![Discourse](https://img.shields.io/discourse/https/discourse.linuxserver.io/topics.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=discourse)](https://discourse.linuxserver.io "post on our community forum.")
[![Fleet](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Fleet)](https://fleet.linuxserver.io "an online web interface which displays all of our maintained images.")
[![GitHub](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub&logo=github)](https://github.com/linuxserver "view the source for all of our repositories.")
[![Open Collective](https://img.shields.io/opencollective/all/linuxserver.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Supporters&logo=open%20collective)](https://opencollective.com/linuxserver "please consider helping us by either donating or contributing to our budget")

The [LinuxServer.io](https://linuxserver.io) team brings you another container release featuring:

 * regular and timely application updates
 * easy user mappings (PGID, PUID)
 * custom base image with s6 overlay
 * weekly base OS updates with common layers across the entire LinuxServer.io ecosystem to minimise space usage, down time and bandwidth
 * regular security updates

Find us at:
* [Blog](https://blog.linuxserver.io) - all the things you can do with our containers including How-To guides, opinions and much more!
* [Discord](https://discord.gg/YWrKVTn) - realtime support / chat with the community and the team.
* [Discourse](https://discourse.linuxserver.io) - post on our community forum.
* [Fleet](https://fleet.linuxserver.io) - an online web interface which displays all of our maintained images.
* [GitHub](https://github.com/linuxserver) - view the source for all of our repositories.
* [Open Collective](https://opencollective.com/linuxserver) - please consider helping us by either donating or contributing to our budget

# [linuxserver/swag](https://github.com/linuxserver/docker-swag)

[![GitHub Stars](https://img.shields.io/github/stars/linuxserver/docker-swag.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-swag)
[![GitHub Release](https://img.shields.io/github/release/linuxserver/docker-swag.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-swag/releases)
[![GitHub Package Repository](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub%20Package&logo=github)](https://github.com/linuxserver/docker-swag/packages)
[![GitLab Container Registry](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitLab%20Registry&logo=gitlab)](https://gitlab.com/Linuxserver.io/docker-swag/container_registry)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/linuxserver/swag.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge)](https://microbadger.com/images/linuxserver/swag "Get your own version badge on microbadger.com")
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/swag.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=pulls&logo=docker)](https://hub.docker.com/r/linuxserver/swag)
[![Docker Stars](https://img.shields.io/docker/stars/linuxserver/swag.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=stars&logo=docker)](https://hub.docker.com/r/linuxserver/swag)
[![Jenkins Build](https://img.shields.io/jenkins/build?labelColor=555555&logoColor=ffffff&style=for-the-badge&jobUrl=https%3A%2F%2Fci.linuxserver.io%2Fjob%2FDocker-Pipeline-Builders%2Fjob%2Fdocker-swag%2Fjob%2Fmaster%2F&logo=jenkins)](https://ci.linuxserver.io/job/Docker-Pipeline-Builders/job/docker-swag/job/master/)
[![LSIO CI](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=CI&query=CI&url=https%3A%2F%2Fci-tests.linuxserver.io%2Flinuxserver%2Fswag%2Flatest%2Fci-status.yml)](https://ci-tests.linuxserver.io/linuxserver/swag/latest/index.html)

SWAG - Secure Web Application Gateway (formerly known as letsencrypt, no relation to Let's Encrypt™) sets up an Nginx webserver and reverse proxy with php support and a built-in certbot client that automates free SSL server certificate generation and renewal processes. It also contains fail2ban for intrusion prevention.

[![swag](https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/swag.gif)](https://linuxserver.io)

## Supported Architectures

Our images support multiple architectures such as `x86-64`, `arm64` and `armhf`. We utilise the docker manifest for multi-platform awareness. More information is available from docker [here](https://github.com/docker/distribution/blob/master/docs/spec/manifest-v2-2.md#manifest-list) and our announcement [here](https://blog.linuxserver.io/2019/02/21/the-lsio-pipeline-project/).

Simply pulling `ghcr.io/linuxserver/swag` should retrieve the correct image for your arch, but you can also pull specific arch images via tags.

The architectures supported by this image are:

| Architecture | Tag |
| :----: | --- |
| x86-64 | amd64-latest |
| arm64 | arm64v8-latest |
| armhf | arm32v7-latest |


## Usage

Here are some example snippets to help you get started creating a container.

### docker-compose ([recommended](https://docs.linuxserver.io/general/docker-compose))

Compatible with docker-compose v2 schemas.

```yaml
---
version: "2.1"
services:
  swag:
    image: ghcr.io/linuxserver/swag
    container_name: swag
    cap_add:
      - NET_ADMIN
    environment:
      - PUID=1000
      - PGID=1000
      - TZ=Europe/London
      - URL=yourdomain.url
      - SUBDOMAINS=www,
      - VALIDATION=http
      - DNSPLUGIN=cloudflare #optional
      - PROPAGATION= #optional
      - DUCKDNSTOKEN= #optional
      - EMAIL= #optional
      - ONLY_SUBDOMAINS=false #optional
      - EXTRA_DOMAINS= #optional
      - STAGING=false #optional
      - MAXMINDDB_LICENSE_KEY= #optional
    volumes:
      - /path/to/appdata/config:/config
    ports:
      - 443:443
      - 80:80 #optional
    restart: unless-stopped
```

### docker cli

```
docker run -d \
  --name=swag \
  --cap-add=NET_ADMIN \
  -e PUID=1000 \
  -e PGID=1000 \
  -e TZ=Europe/London \
  -e URL=yourdomain.url \
  -e SUBDOMAINS=www, \
  -e VALIDATION=http \
  -e DNSPLUGIN=cloudflare `#optional` \
  -e PROPAGATION= `#optional` \
  -e DUCKDNSTOKEN= `#optional` \
  -e EMAIL= `#optional` \
  -e ONLY_SUBDOMAINS=false `#optional` \
  -e EXTRA_DOMAINS= `#optional` \
  -e STAGING=false `#optional` \
  -e MAXMINDDB_LICENSE_KEY= `#optional` \
  -p 443:443 \
  -p 80:80 `#optional` \
  -v /path/to/appdata/config:/config \
  --restart unless-stopped \
  ghcr.io/linuxserver/swag
```


## Parameters

Container images are configured using parameters passed at runtime (such as those above). These parameters are separated by a colon and indicate `<external>:<internal>` respectively. For example, `-p 8080:80` would expose port `80` from inside the container to be accessible from the host's IP on port `8080` outside the container.

| Parameter | Function |
| :----: | --- |
| `-p 443` | Https port |
| `-p 80` | Http port (required for http validation and http -> https redirect) |
| `-e PUID=1000` | for UserID - see below for explanation |
| `-e PGID=1000` | for GroupID - see below for explanation |
| `-e TZ=Europe/London` | Specify a timezone to use EG Europe/London. |
| `-e URL=yourdomain.url` | Top url you have control over (`customdomain.com` if you own it, or `customsubdomain.ddnsprovider.com` if dynamic dns). |
| `-e SUBDOMAINS=www,` | Subdomains you'd like the cert to cover (comma separated, no spaces) ie. `www,ftp,cloud`. For a wildcard cert, set this _exactly_ to `wildcard` (wildcard cert is available via `dns` and `duckdns` validation only) |
| `-e VALIDATION=http` | Certbot validation method to use, options are `http`, `dns` or `duckdns` (`dns` method also requires `DNSPLUGIN` variable set) (`duckdns` method requires `DUCKDNSTOKEN` variable set, and the `SUBDOMAINS` variable must be either empty or set to `wildcard`). |
| `-e DNSPLUGIN=cloudflare` | Required if `VALIDATION` is set to `dns`. Options are `aliyun`, `cloudflare`, `cloudxns`, `cpanel`, `digitalocean`, `dnsimple`, `dnsmadeeasy`, `domeneshop`, `gandi`,`gehirn`, `google`, `inwx`, `linode`, `luadns`, `netcup`, `nsone`, `ovh`, `rfc2136`, `route53`, `sakuracloud` and `transip`. Also need to enter the credentials into the corresponding ini (or json for some plugins) file under `/config/dns-conf`. |
| `-e PROPAGATION=` | Optionally override (in seconds) the default propagation time for the dns plugins. |
| `-e DUCKDNSTOKEN=` | Required if `VALIDATION` is set to `duckdns`. Retrieve your token from https://www.duckdns.org |
| `-e EMAIL=` | Optional e-mail address used for cert expiration notifications. |
| `-e ONLY_SUBDOMAINS=false` | If you wish to get certs only for certain subdomains, but not the main domain (main domain may be hosted on another machine and cannot be validated), set this to `true` |
| `-e EXTRA_DOMAINS=` | Additional fully qualified domain names (comma separated, no spaces) ie. `extradomain.com,subdomain.anotherdomain.org,*.anotherdomain.org` |
| `-e STAGING=false` | Set to `true` to retrieve certs in staging mode. Rate limits will be much higher, but the resulting cert will not pass the browser's security test. Only to be used for testing purposes. |
| `-e MAXMINDDB_LICENSE_KEY=` | Add your MaxmindDB license key to automatically download the GeoLite2-City.mmdb database. Download location is /config/geoip2db. The database is updated weekly. |
| `-v /config` | All the config files including the webroot reside here. |

## Environment variables from files (Docker secrets)

You can set any environment variable from a file by using a special prepend `FILE__`.

As an example:

```
-e FILE__PASSWORD=/run/secrets/mysecretpassword
```

Will set the environment variable `PASSWORD` based on the contents of the `/run/secrets/mysecretpassword` file.

## Umask for running applications

For all of our images we provide the ability to override the default umask settings for services started within the containers using the optional `-e UMASK=022` setting.
Keep in mind umask is not chmod it subtracts from permissions based on it's value it does not add. Please read up [here](https://en.wikipedia.org/wiki/Umask) before asking for support.

## User / Group Identifiers

When using volumes (`-v` flags) permissions issues can arise between the host OS and the container, we avoid this issue by allowing you to specify the user `PUID` and group `PGID`.

Ensure any volume directories on the host are owned by the same user you specify and any permissions issues will vanish like magic.

In this instance `PUID=1000` and `PGID=1000`, to find yours use `id user` as below:

```
  $ id username
    uid=1000(dockeruser) gid=1000(dockergroup) groups=1000(dockergroup)
```


&nbsp;
## Application Setup

> ### Migrating from the old `linuxserver/letsencrypt` image
> * If using docker cli:
>   * Stop and remove existing container via `docker stop letsencrypt` and `docker rm letsencrypt`
>   * Create new container using the sample on this page (container name: `swag`, image name: `linuxserver/swag`)
> * If using docker compose:
>   * Edit the compose yaml to change the image to `linuxserver/swag` and change the service and container names to `swag`
>   * Issue `docker-compose up -d --remove-orphans`
>   * If you don't want to or can't use the option `--remove-orphans`, then you can first do `docker-compose down`, then edit the compose yaml as above, and then issue `docker-compose up -d`

> Make sure to also update any references to this container by name. For instance, Nextcloud's `config.php` references this container in its `trusted_proxies` directive, which would have to be updated to `swag`.
### Validation and initial setup
* Before running this container, make sure that the url and subdomains are properly forwarded to this container's host, and that port 443 (and/or 80) is not being used by another service on the host (NAS gui, another webserver, etc.).
* For `http` validation, port 80 on the internet side of the router should be forwarded to this container's port 80
* For `dns` validation, make sure to enter your credentials into the corresponding ini (or json for some plugins) file under `/config/dns-conf`
  * Cloudflare provides free accounts for managing dns and is very easy to use with this image. Make sure that it is set up for "dns only" instead of "dns + proxy"
  * Google dns plugin is meant to be used with "Google Cloud DNS", a paid enterprise product, and not for "Google Domains DNS"
* For `duckdns` validation, either leave the `SUBDOMAINS` variable empty or set it to `wildcard`, and set the `DUCKDNSTOKEN` variable with your duckdns token. Due to a limitation of duckdns, the resulting cert will only cover either main subdomain (ie. `yoursubdomain.duckdns.org`), or sub-subdomains (ie. `*.yoursubdomain.duckdns.org`), but will not both at the same time. You can use our [duckdns image](https://hub.docker.com/r/linuxserver/duckdns/) to update your IP on duckdns.org.
* `--cap-add=NET_ADMIN` is required for fail2ban to modify iptables
* If you need a dynamic dns provider, you can use the free provider duckdns.org where the `URL` will be `yoursubdomain.duckdns.org` and the `SUBDOMAINS` can be `www,ftp,cloud` with http validation, or `wildcard` with dns validation.
* After setup, navigate to `https://yourdomain.url` to access the default homepage (http access through port 80 is disabled by default, you can enable it by editing the default site config at `/config/nginx/site-confs/default`).
* Certs are checked nightly and if expiration is within 30 days, renewal is attempted. If your cert is about to expire in less than 30 days, check the logs under `/config/log/letsencrypt` to see why the renewals have been failing. It is recommended to input your e-mail in docker parameters so you receive expiration notices from Let's Encrypt in those circumstances.
### Security and password protection
* The container detects changes to url and subdomains, revokes existing certs and generates new ones during start.
* The container provides a pre-generated 4096-bit dhparams.pem (rotated weekly via [Jenkins job](https://ci.linuxserver.io/blue/organizations/jenkins/Xtras-Builders-Etc%2Fdhparams-uploader/activity)) for new instances, however you may generate your own by running `docker exec swag openssl dhparam -out /config/nginx/dhparams.pem 4096` WARNING: This takes a very long time
* If you'd like to password protect your sites, you can use htpasswd. Run the following command on your host to generate the htpasswd file `docker exec -it swag htpasswd -c /config/nginx/.htpasswd <username>`
* You can add multiple user:pass to `.htpasswd`. For the first user, use the above command, for others, use the above command without the `-c` flag, as it will force deletion of the existing `.htpasswd` and creation of a new one
* You can also use ldap auth for security and access control. A sample, user configurable ldap.conf is provided, and it requires the separate image [linuxserver/ldap-auth](https://hub.docker.com/r/linuxserver/ldap-auth/) to communicate with an ldap server.
### Site config and reverse proxy
* The default site config resides at `/config/nginx/site-confs/default`. Feel free to modify this file, and you can add other conf files to this directory. However, if you delete the `default` file, a new default will be created on container start.
* Preset reverse proxy config files are added for popular apps. See the `README.md` file under `/config/nginx/proxy_confs` for instructions on how to enable them. The preset confs reside in and get imported from [this repo](https://github.com/linuxserver/reverse-proxy-confs).
* If you wish to hide your site from search engine crawlers, you may find it useful to add this configuration line to your site config, within the server block, above the line where ssl.conf is included
`add_header X-Robots-Tag "noindex, nofollow, nosnippet, noarchive";`
This will *ask* Google et al not to index and list your site. Be careful with this, as you will eventually be de-listed if you leave this line in on a site you wish to be present on search engines
* If you wish to redirect http to https, you must expose port 80
### Using certs in other containers
* This container includes auto-generated pfx and private-fullchain-bundle pem certs that are needed by other apps like Emby and Znc.
  * To use these certs in other containers, do either of the following:
  1. *(Easier)* Mount the container's config folder in other containers (ie. `-v /path-to-le-config:/le-ssl`) and in the other containers, use the cert location `/le-ssl/keys/letsencrypt/`
  2. *(More secure)* Mount the SWAG folder `etc` that resides under `/config` in other containers (ie. `-v /path-to-le-config/etc:/le-ssl`) and in the other containers, use the cert location `/le-ssl/letsencrypt/live/<your.domain.url>/` (This is more secure because the first method shares the entire SWAG config folder with other containers, including the www files, whereas the second method only shares the ssl certs)
  * These certs include:
  1. `cert.pem`, `chain.pem`, `fullchain.pem` and `privkey.pem`, which are generated by Let's Encrypt and used by nginx and various other apps
  2. `privkey.pfx`, a format supported by Microsoft and commonly used by dotnet apps such as Emby Server (no password)
  3. `priv-fullchain-bundle.pem`, a pem cert that bundles the private key and the fullchain, used by apps like ZNC
### Using fail2ban
* This container includes fail2ban set up with 4 jails by default:
  1. nginx-http-auth
  2. nginx-badbots
  3. nginx-botsearch
  4. nginx-deny
* To enable or disable other jails, modify the file `/config/fail2ban/jail.local`
* To modify filters and actions, instead of editing the `.conf` files, create `.local` files with the same name and edit those because .conf files get overwritten when the actions and filters are updated. `.local` files will append whatever's in the `.conf` files (ie. `nginx-http-auth.conf` --> `nginx-http-auth.local`)
* You can check which jails are active via `docker exec -it swag fail2ban-client status`
* You can check the status of a specific jail via `docker exec -it swag fail2ban-client status <jail name>`
* You can unban an IP via `docker exec -it swag fail2ban-client set <jail name> unbanip <IP>`
* A list of commands can be found here: https://www.fail2ban.org/wiki/index.php/Commands
### Updating configs
* This container creates a number of configs for nginx, proxy samples, etc.
* Config updates are noted in the changelog but not automatically applied to your files.
* If you have modified a file with noted changes in the changelog:
  1. Keep your existing configs as is (not broken, don't fix)
  2. Review our repository commits and apply the new changes yourself
  3. Delete the modified config file with listed updates, restart the container, reapply your changes
* If you have NOT modified a file with noted changes in the changelog:
  1. Delete the config file with listed updates, restart the container
* Proxy sample updates are not listed in the changelog. See the changes here: [https://github.com/linuxserver/reverse-proxy-confs/commits/master](https://github.com/linuxserver/reverse-proxy-confs/commits/master)
* Proxy sample files WILL be updated, however your renamed (enabled) proxy files will not.
* You can check the new sample and adjust your active config as needed.


## Docker Mods
[![Docker Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=swag&query=%24.mods%5B%27swag%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=swag "view available mods for this container.") [![Docker Universal Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=universal&query=%24.mods%5B%27universal%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=universal "view available universal mods.")

We publish various [Docker Mods](https://github.com/linuxserver/docker-mods) to enable additional functionality within the containers. The list of Mods available for this image (if any) as well as universal mods that can be applied to any one of our images can be accessed via the dynamic badges above.


## Support Info

* Shell access whilst the container is running: `docker exec -it swag /bin/bash`
* To monitor the logs of the container in realtime: `docker logs -f swag`
* container version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' swag`
* image version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' ghcr.io/linuxserver/swag`

## Updating Info

Most of our images are static, versioned, and require an image update and container recreation to update the app inside. With some exceptions (ie. nextcloud, plex), we do not recommend or support updating apps inside the container. Please consult the [Application Setup](#application-setup) section above to see if it is recommended for the image.

Below are the instructions for updating containers:

### Via Docker Compose
* Update all images: `docker-compose pull`
  * or update a single image: `docker-compose pull swag`
* Let compose update all containers as necessary: `docker-compose up -d`
  * or update a single container: `docker-compose up -d swag`
* You can also remove the old dangling images: `docker image prune`

### Via Docker Run
* Update the image: `docker pull ghcr.io/linuxserver/swag`
* Stop the running container: `docker stop swag`
* Delete the container: `docker rm swag`
* Recreate a new container with the same docker run parameters as instructed above (if mapped correctly to a host folder, your `/config` folder and settings will be preserved)
* You can also remove the old dangling images: `docker image prune`

### Via Watchtower auto-updater (only use if you don't remember the original parameters)
* Pull the latest image at its tag and replace it with the same env variables in one run:
  ```
  docker run --rm \
  -v /var/run/docker.sock:/var/run/docker.sock \
  containrrr/watchtower \
  --run-once swag
  ```
* You can also remove the old dangling images: `docker image prune`

**Note:** We do not endorse the use of Watchtower as a solution to automated updates of existing Docker containers. In fact we generally discourage automated updates. However, this is a useful tool for one-time manual updates of containers where you have forgotten the original parameters. In the long term, we highly recommend using [Docker Compose](https://docs.linuxserver.io/general/docker-compose).

### Image Update Notifications - Diun (Docker Image Update Notifier)
* We recommend [Diun](https://crazymax.dev/diun/) for update notifications. Other tools that automatically update containers unattended are not recommended or supported.

## Building locally

If you want to make local modifications to these images for development purposes or just to customize the logic:
```
git clone https://github.com/linuxserver/docker-swag.git
cd docker-swag
docker build \
  --no-cache \
  --pull \
  -t ghcr.io/linuxserver/swag:latest .
```

The ARM variants can be built on x86_64 hardware using `multiarch/qemu-user-static`
```
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```

Once registered you can define the dockerfile to use with `-f Dockerfile.aarch64`.

## Versions

* **09.11.20:** - Check for template/conf updates and notify in the log. Add support for gehirn and sakuracloud dns validation.
* **01.11.20:** - Add support for netcup dns validation
* **29.10.20:** - [Existing users should update:](https://github.com/linuxserver/docker-swag/blob/master/README.md#updating-configs) ssl.conf - Add frame-ancestors to Content-Security-Policy.
* **04.10.20:** - [Existing users should update:](https://github.com/linuxserver/docker-swag/blob/master/README.md#updating-configs) nginx.conf, proxy.conf, and ssl.conf - Minor cleanups and reordering.
* **20.09.20:** - [Existing users should update:](https://github.com/linuxserver/docker-swag/blob/master/README.md#updating-configs) nginx.conf - Added geoip2 configs. Added MAXMINDDB_LICENSE_KEY variable to readme.
* **08.09.20:** - Add php7-xsl.
* **01.09.20:** - [Existing users should update:](https://github.com/linuxserver/docker-swag/blob/master/README.md#updating-configs) nginx.conf, proxy.conf, and various proxy samples - Global websockets across all configs.
* **03.08.20:** - Initial release.
