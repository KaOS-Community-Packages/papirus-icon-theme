pkgname=papirus-icon-theme
pkgver=20210701
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('bf102e4a759b85680452d950f6338941')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
