# cf-warp

> A simple cli to get [Warp+](https://blog.cloudflare.com/announcing-warp-plus/) as [WireGuard](https://www.wireguard.com/) configuration

## Usage

By using this, you agree the [Privacy Policy](https://www.cloudflare.com/application/privacypolicy/) and [Terms of Service](https://www.cloudflare.com/application/terms/) of Cloudflare 1.1.1.1

### Step 1

Follow [Installation Guide](https://www.wireguard.com/install/) on WireGuard official webiste to install WireGuard on your system.

You have to make sure `wg` binary exists in your `PATH`.

### Step 2

Install `cf-warp` globally through yarn or npm.

```bash
yarn global add cf-warp # npm i -g cf-warp
```

### Step 3

Initialize your Warp+ account by running `cf-warp` command.

Example:

```bash
$ cf-warp
Your Warp credentials are located at "C:\Users\maple3142\.cf-warp\data.json", and WireGuard connection file is "C:\Users\maple3142\.cf-warp\wireguard.conf".
You currently have 1GB Warp+ quora.
To get your current Warp+ quora, simply run "cf-warp".
To increase your Warp+ quora by 10 GB, simply run "cf-warp 10".
```

### Step 4

Obtain `wireguard.conf` from `~/.cf-warp/wireguard.conf` and use it normally.

## Thanks

https://github.com/yyuueexxiinngg/some-scripts/tree/master/cloudflare