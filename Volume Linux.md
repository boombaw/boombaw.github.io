# Untuk meresize logical volume

## Periksa ruang bebas di volume group
> $ sudo vgdisplay

## Perluas logical volume
> $ sudo lvextend -l +100%FREE /dev/ubuntu-vg/ubuntu-lv

## Perbarui filesystem
> $ sudo resize2fs /dev/ubuntu-vg/ubuntu-lv

## Verifikasi perubahan
> $ df -h
