pkgname=papirus-icon-theme
pkgver=20221101
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('de0159a00002ffc9703a8e86e950de9e')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
