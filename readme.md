# Byond Media Website - Powered by Hugo

Owner: **Billy Astika** 
Developer: **Rhys Abas**

Website is hosted on Cloudflare Pages. To make any adjustments to the deployment, you can edit the following scripts:
- `build.sh`
- `wrangler.jsonc`

Further configurations can be done within Cloudflare itself. 

## Prerequisites:
- Hugo v0.167.0 (or higher)  https://github.com/gohugoio/hugo/releases  

## Development instructions:
To start developing this site, please follow the instructions below:

1. Clone this repo to you terminal
```bash
git clone https://github.com/BillyByond/byondSite.git
```
2. Change directory into the `beyondSite` directory
3. Pull the Blowfish submodule. If you do not do this, the Hugo will not be able to build the site.
```bash
git submodule update --init --recursive
```
4. Next you will need to build the site in order to reconstruct the web elements.
```bash
hugo build
```
5. Test to see if the site loads. If the site loads content, then you have setup everything correctly.
```bash
hugo server -D
```
# References:
https://gohugo.io/documentation/ (Hugo Documentation)
https://blowfish.page/docs/ (Blowfish theme Documentation)
