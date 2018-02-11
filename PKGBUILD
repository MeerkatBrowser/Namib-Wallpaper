pkgname=namib-wallpapers
pkgver=17.12
pkgrel=1
pkgdesc='Wallpapers for Namib GNU/Linux'
arch=(any)
license=(GPL)
url="https://github.com/MeerkatBrowser/Namib-Wallpapers"
conflicts=('mate-backgrounds')
source=("git+$url.git")
sha256sums=('SKIP')

package() {
    install -d ${pkgdir}/usr/share/backgrounds/namib
    install -m644 Namib-Wallpapers/backgrounds/namib/* "${pkgdir}/usr/share/backgrounds/namib"
}
