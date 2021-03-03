pkgname=papirus-icon-theme
pkgver=20210302
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('b20f6768c98e8f12cbf38b9ff445c775')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
