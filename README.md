# Simonyi Mattermost - simonyi-mm

## Deployment

To establish a mattermost deployment:

1. Copy .env.example after cloning, name it .env
2. Change env vars to your liking, modify the postgres connection url according to your settings
3. `docker-compose up`

> The first user created with the given username (admin) won't have their email address activated, keep it in mind.

## Maintenance

This repository and the deployment will be provisioned by the [Kir-Dev](https://kir-dev.sch.bme.hu) team. Contact them for further help and information.

It's a good practise to keep notes of how we manage the Mattermost server, so that next time someone is appointed to manage the server, they'll know the most important policies and practises we used before. E.g. server settings, import flow etc. This knowledge base can be incrementally stored in the [GOODTOKNOW.md](GOODTOKNOW.md) file.
