# Author: Reda Lazri (0rAX0) <http://0rax0.deviantart.com/>
# Maintainer: Reda Lazri (0rAX0) <the.red.shortcut at gmail dot com>
 
pkgname=uniform-icon-theme
pkgver=0.1.6.1
pkgrel=1
pkgdesc="A non-uniform yet consistent icon theme."
url="http://0rax0.deviantart.com/art/Uniform-Icon-Theme-453054609"
license=('cc-by-nc-sa-3.0')
arch=('any')
depends=('gnome-icon-theme' 'gnome-icon-theme-extras' 'gnome-icon-theme-symbolic')
makedepends=('wget')
optdepends=('gnome-tweak-tool: A tool to customize advanced GNOME 3 options.')
source=("http://fc05.deviantart.net/fs70/f/2015/009/5/1/uniform_icon_theme_by_0rax0-d7hqj69.zip")
DLAGENTS=('http::/usr/bin/wget -c -t 3 --waitretry=3 -H -U Mozilla -O %o %u')
 
 
package() {
  mkdir -p "${pkgdir}/usr/share/icons/"
  cp -r "${srcdir}/Uniform" "${pkgdir}/usr/share/icons/"
}
 
md5sums=('f0ad8b9f55d2ebbf7b88ae9a6619b7f3')

