# xiaomi-lavender-victor
esse projeto é um Port para o redmi note 7

Este repositório contém os arquivos necessários para portar o sistema Phipset baseado em Debian/Ubuntu para o dispositivo Xiaomi Redmi Note 7 (lavender).

## Componentes

- Kernel Linux compatível
- Rootfs Debian com overlay Phipset
- Scripts para flash via ADB ou Fastboot
- Arquivos de configuração (init.rc, udev, fstab)

## Instruções rápidas

```bash
git clone https://github.com/Phipset/xiaomi-lavender-victor.git
cd xiaomi-lavender-victor
./rootfs/create-rootfs.sh
./kernel/build-kernel.sh
./install/flash.sh
```
