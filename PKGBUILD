pkgname=papirus-icon-theme
pkgver=20220808
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('10e97de782df2cb63af86ef6980ee08d')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
