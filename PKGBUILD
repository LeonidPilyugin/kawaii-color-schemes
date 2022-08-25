# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-color-schemes
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii color schemes for KDE Plasma'
arch=('x86_64')
license=('GPL3')
groups=('kawaii')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/LeonidPilyugin/kawaii-color-schemes/releases/download/v$pkgver/files.tar.gz")
sha256sums=('354ef10f60d9bdae8055db5f5501eced5824fdfbb5425183feeba0c6b7ddeccd')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/color-schemes
    install -dm755 $dir
    cp -r $srcdir/* $dir
}
