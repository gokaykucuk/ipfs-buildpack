# 🎒 IPFS-Buildpack

An IPFS client buildpack for decentralized web. NOTE: tested only on a dokku installation, I'll update the instructions when again after testing it on a heroku dyno.

## ⭐ Features

- Easily integrate IPFS executable to your heroku/dokku application.
- `ipfs get` to download ipfs files.

## 🛠️ Installation

Add the following line to your `.buildpacks` file.

## ⚠️ Known Issues

- IPFS daemon might not work as expected due to being run on another dyno.
