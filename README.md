# Name

Overview

## Description

## Demo

```shell
multipass launch --name primary --disk 3G --cloud-init cloud-config.yml
```

```shell
ssh-keygen -t ed25519 -C "your_email@example.com"
```

```shell
Enter file in which to save the key (~/.ssh/id_ed25519): ~/.ssh/remote
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in ~/.ssh/remote
Your public key has been saved in ~/.ssh/remote.pub
The key fingerprint is:
SHA256:Iad3RPfMAkI2iNkTszXPaV+EpQu54+UhRzZTJTplHNw your_email@example.com
The key's randomart image is:
+--[ED25519 256]--+
|     +o+B o .=O+.|
|    o += B =.@o.E|
|      o.o O X =  |
|       + + * B   |
|      . S = *    |
|       . o * .   |
|          . .    |
|                 |
|                 |
+----[SHA256]-----+
```

```shell
multipass list
```

```shell
Name                    State             IPv4             Image
primary                 Running           172.26.54.99     Ubuntu 22.04 LTS
```

Copy Public key: `~/.ssh/remote.pub`

## Features

- feature:1
- feature:2

## Requirement

## Usage

## Installation

## References

## Licence

Released under the [MIT license](https://gist.githubusercontent.com/shinyay/56e54ee4c0e22db8211e05e70a63247e/raw/34c6fdd50d54aa8e23560c296424aeb61599aa71/LICENSE)

## Author

- github: <https://github.com/shinyay>
- twitter: <https://twitter.com/yanashin18618>
- mastodon: <https://mastodon.social/@yanashin>
