pkgname=nvidia-prime
pkgver=1.0
pkgrel=4
pkgdesc="NVIDIA Prime Render Offload configuration and utilities"
arch=('any')
url="https://www.archlinux.org/packages/extra/any/nvidia-prime/"
license=('GPL')
depends=('bash' 'nvidia-utils')
source=("prime-run")
md5sums=('3d377404ef87df6e18ea3b149ba1110b')
sha512sums=('d9158ddee6ec105796d86ac42b32c6c925cfa866d5e25c64d5a29be47fe393ace0efb4ef8a3e7cff699abc599d28ee46866dcbfdfd1920122e426ee262c562e6')

package() {
    install -Dm755 $srcdir/prime-run $pkgdir/usr/bin/prime-run
}
