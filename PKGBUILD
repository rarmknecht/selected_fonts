# Maintainer: rarmknecht <rarmknecht at gmail dot com>

pkgname=otf-rma-fonts
pkgver=0.1
pkgrel=1
epoch=1
pkgdesc='A selected grouping of fonts'
arch=('any')
url="http://github.com/rarmknecht/selected_fonts"
depends=('fontconfig' 'xorg-fonts-encodings' 'xorg-font-utils')
makedepends=('unzip')
install=otf-rma-fonts.install
source=("http://github.com/rarmknecht/selected_fonts/blob/master/otf-rma-fonts-$pkgver.tar.gz")

build() {
  mkdir -p $pkgdir/usr/share/fonts/OTF
  cp $srcdir/fonts/*.otf $pkgdir/usr/share/fonts/OTF
}

md5sums=('4904d05e85a7e58b1f1d116741d10ecc')
