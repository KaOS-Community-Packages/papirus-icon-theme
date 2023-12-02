pkgname=papirus-icon-theme
pkgver=20231201
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('5498bc168d422f274cf6232f0131d48f')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
