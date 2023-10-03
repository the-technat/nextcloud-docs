# nextcloud-docs

My solution to edit documents in my Nextcloud. Based on Collabora Online.

Hosted on [fly.io](https://fly.io).

## Setup

- Install flyctl: `curl -L https://fly.io/install.sh | sh`
- Auth flyctl: `flyctl auth login`
- Start first deployment: `fly deploy`
- Give some performance: `fly scale memory 1024` && `fly scale vm shared-cpu-1x`
- Disable HA: `fly scale count 1`

Subsequent changes to the app will be automatically deployed thanks to Github actions ;)