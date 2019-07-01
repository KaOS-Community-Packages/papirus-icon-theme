pkgname=papirus-icon-theme
pkgver=20190701
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('efabb51ca8da7899497abe6f201220fc')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
