simple script to download latest x86_64 deb package and install
<br />
I made it for a personal use since Cloudflare doesnt provide a packman package repository for ARCH family
<br />
and the current AUR package is outdated more than 3 versions already.
<br />
Instruction 
<br />
`git clone https://github.com/alfrejimglez/cloudflare-warp-installer.git)`<br />
`cd cloudflare-warp-installer`<br />
`./installer.sh`<br />
`sudo systemctl enable --now warp-svc.service`<br />
done<br />
register new <br />
`warp-cli registration new`<br />
now you can start connection like<br />
`warp-cli connect`<br />
or<br />
`warp-cli disconnect`<br />

