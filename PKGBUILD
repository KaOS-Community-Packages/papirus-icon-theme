pkgname=papirus-icon-theme
pkgver=20200602
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('26a07a82fa33805ae33d99e3ba3ab109')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
