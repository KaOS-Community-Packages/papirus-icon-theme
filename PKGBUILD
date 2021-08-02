pkgname=papirus-icon-theme
pkgver=20210802
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('7ad00ef1132c2345cf5d6a36969c5c3f')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
