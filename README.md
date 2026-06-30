# personal-ebuild-repository

This is my personal Gentoo overlay. Ebuilds I write and use myself, and I try to keep things reasonably current. It's not official and not affiliated with the Gentoo Foundation or any of the upstream projects packaged here.

Use at your own risk, and feel free to use whatever's useful here too.

I'm still pretty new to Gentoo and learning as I go, so if you spot something wrong or something that could be done better, please open a PR or an issue. All feedback's welcome.

## Packages

Please note that the versions below are as of time of writing and may have moved on since.

| Package                      | Version | Gentoo Tree Version | Notes |
|-------------------------------|---------|------------------------|-------|
| mail-mta/proton-mail-bridge   | 3.25.0  | 3.21.2                  | Wrote this because the official tree was several releases behind |

## Adding this repo

```bash
eselect repository add personal-ebuild-repository git https://github.com/Shagasresthaa/personal-ebuild-repository.git
emaint sync --repo personal-ebuild-repository
```
