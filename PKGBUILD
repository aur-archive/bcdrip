# Maintainer: archtux <antonio dot arias99999 at gmail dot com>

pkgname=bcdrip
pkgver=0.7.3
pkgrel=1
pkgdesc="Bash CD Ripper."
arch=('any')
url="http://sourceforge.net/projects/bcdrip/"
license=('GPL3')
depends=('abcde' 'bc' 'cdparanoia' 'dos2unix' 'ffmpeg' 'opus-tools' 'sox')
optdepends=('libav: if you want to use instead of ffmpeg')
source=(http://sourceforge.net/projects/$pkgname/files/$pkgver/$pkgname-$pkgver.tar.gz)
md5sums=('f07e74b7bcae922eef4c0b72649345a0')

package() {
  cd $srcdir/$pkgname-$pkgver
  install -Dm755 $pkgname $pkgdir/usr/bin/$pkgname
}