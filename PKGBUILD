pkgname=papirus-icon-theme
pkgver=20200702
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('45dd067697fcaadec64c7dcdb0c416fb')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
