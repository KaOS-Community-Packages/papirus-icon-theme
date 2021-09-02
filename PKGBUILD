pkgname=papirus-icon-theme
pkgver=20210901
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('2a9e35d501c1ef01ff4c0598ccf2ef15')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
