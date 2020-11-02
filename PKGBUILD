pkgname=papirus-icon-theme
pkgver=20201031
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('c879de9fbc29ee1f35597e9440ba7396')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
