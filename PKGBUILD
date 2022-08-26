# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-color-schemes
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii color schemes for KDE Plasma'
groups=('kawaii')
url='https://github.com/LeonidPilyugin/kawaii-color-schemes'
arch=('x86_64')
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('c62f64320dbe1ab2bb491b977edc83d522cdcd919ef695943d09c29385687998')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/color-schemes
    install -dm755 $dir
    cp -r $srcdir/* $dir
}
