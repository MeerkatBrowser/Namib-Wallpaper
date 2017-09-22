pkgname=namib-wallpapers
pkgver=17.09
pkgrel=1
pkgdesc='Wallpapers for Namib GNU/Linux'
arch=(any)
license=(GPL)
url="https://github.com/MeerkatBrowser/Namib-Wallpapers"
conflicts=('mate-backgrounds')
source=("git+$url.git")
sha256sums=('SKIP')
install=$pkgname.install

package() {
    install -d ${pkgdir}/usr/share/backgrounds/namib
    install -m644 Namib-Wallpapers/backgrounds/namib/* "${pkgdir}/usr/share/backgrounds/namib"

    install -d ${pkgdir}/usr/share/backgrounds/namib/config
    install -m644 Namib-Wallpapers/mate-backgrounds.xml "${pkgdir}/usr/share/backgrounds/namib/config"
}
