# rmm-sites
Rainbow Monkey Meat Static Sites

Hugo driven, hosted on Cloudflare pages

## Code Snippets - Modules

WARNING: Does not work, as this theme is not bundled as a go module (I think...)

```sh
sudo apt install hugo
sudo apt install golang
hugo new site rmm-future
cd rmm-future
# Make sure theme and modules/import/path set correctly in config.yml
hugo mod init github.com/rainbowmonkeymeat/rmm-sites/rmm-future
hugo mod get -u
```
