pkgname=papirus-icon-theme
pkgver=20200405
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('f24997293cfa8370cb4ddae75c843b3e')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
