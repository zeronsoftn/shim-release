# ZeronsoftN's shim releases

ZeronsoftN's Shim Binaries and Reviews

ZeronsoftN's Shim is used to sign the binaries below:
- grub2
- systemd-boot

## shim-15.8

- REVIEW: https://github.com/rhboot/shim-review/issues/408
- Vendor Certificate : `CN=ZeronsoftN Secure Boot Signing (2022),OU=Secure Boot,O=ZeronsoftN,C=KR`
- Hashes:

```
476f27d9a51166a30cb03cec053b8ef3001861552ac181667e589bc16a69f741  shimaa64.efi
27db830e66bba9162a6d5d1c7f9746a51ef686f3e922d5616b11e6292592df95  shimia32.efi
a6defac57dedac220249c66645f70e9d6682e058c5ea5da24c18ba8b1809044d  shimx64.efi
```

- SBAT:

```
sbat,1,SBAT Version,sbat,1,https://github.com/rhboot/shim/blob/main/SBAT.md
shim,4,UEFI shim,shim,1,https://github.com/rhboot/shim
shim.zeronsoftn,1,ZeronsoftN,shim,15.8-0zeron1,https://github.com/zeronsoftn/shim-release
```

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

