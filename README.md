# Workshops

This is the repository for the hands-on part of Data Console & Backstage workshops.

## Before begin

You have to configure Github integration to be able to login to the application and create PR and repositories.

You need to fetch Github client credentials from [bitwarden](https://passmanager.allegrogroup.com/#/vault?itemId=912f3ade-1d29-4848-8ec8-b08500c9bdae&cipherId=d0a6e284-1e15-4a3d-8dac-ad9e00d115c2) and
export two environment variables:

```
export AUTH_GITHUB_CLIENT_ID="<client-id-goes-here>"
export AUTH_GITHUB_SECRET="<client-secret-goes-here>"
```

You need to also fetch from [bitwarden](https://passmanager.allegrogroup.com/#/vault?itemId=447621ef-5b25-47f2-8950-b08500c81dc5&cipherId=5c8f6550-d051-4b31-a282-ad7400c9bb51) Github application credentials used for fetching users and teams in the background.
You have to save bitwarden note content in file named: `data-console/github-app-xwing-libra-workshops-credentials.yaml`

## Quick start

```bash
cd data-console
yarn install
yarn dev
```

## Prerequisites

Please ensure that you have nodejs installed (required version is at least 18).

If not you can install it with [nvm](https://github.com/nvm-sh/nvm).

## Agenda

To check the full agenda you can navigate to the [document](https://docs.google.com/document/d/1MQinhLy9vQCS8sh-_IkYuLu-rF7eNHx_Q-kcGKjMWxg/edit?usp=sharing).

## Miro Board

Miro board with design is available [here](https://miro.com/app/board/uXjVMycD8SU=/?share_link_id=11586697477).