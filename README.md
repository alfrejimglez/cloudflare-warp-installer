# Instalador de Cloudflare Warp para x86_64 (Debian)

Este es un script simple para descargar e instalar automáticamente el último paquete `.deb` de Cloudflare Warp en sistemas `x86_64`.  

Lo creé para uso personal, ya que Cloudflare no proporciona un repositorio de paquetes para la familia ARCH, y el paquete actual en AUR tiene un retraso de más de tres versiones.  

## Instrucciones de instalación

```sh
git clone https://github.com/alfrejimglez/cloudflare-warp-installer.git
cd cloudflare-warp-installer
./installer.sh
sudo systemctl enable --now warp-svc.service
