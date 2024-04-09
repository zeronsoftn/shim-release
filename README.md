# ZeronsoftN's shim releases

ZeronsoftN's Shim Binaries and Reviews

ZeronsoftN's Shim is used to sign the binaries below:
- grub2
- systemd-boot

---

## Template: shim-xx.x

- REVIEW: https://github.com/rhboot/shim-review/issues/xxxx
- Vendor Certificate: `CN=...`

## Template: grub2-2.xx

- Related SHIM REVIEW: https://github.com/rhboot/shim-review/issues/xxxx
- Signer Certificate: `CN=...`

SBAT:

```
sbat,1,SBAT Version,sbat,1,https://github.com/rhboot/shim/blob/main/SBAT.md
grub,4,Free Software Foundation,grub,2.06,https://www.gnu.org/software/grub/
...
```

## Template: systemd-boot 255-xx

- Related SHIM REVIEW: https://github.com/rhboot/shim-review/issues/xxxx
- Signer Certificate: `CN=...`

SBAT:
```
sbat,1,SBAT Version,sbat,1,https://github.com/rhboot/shim/blob/main/SBAT.md
systemd-boot,1,The systemd Developers,systemd,255,https://systemd.io/
...
```

