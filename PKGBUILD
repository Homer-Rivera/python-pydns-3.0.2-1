# Maintainer: Sebastien Leduc <sebastien@sleduc.fr> Contributor: Samed Beyribey <ras0ir AT eventualis DOT org>

pkgname=python-pydns 
_realname=py3dns 
pkgver=3.0.2 
pkgrel=1 
pkgdesc="A module for looking up DNS entries in Python applications" 
arch=('any') url="http://pydns.sourceforge.net" 
license=('Python') 
depends=('python') 
source=("http://downloads.sourceforge.net/pydns/$_realname-$pkgver.tar.gz") 
md5sums=('0d807cfbea9199c4acd8d0695106694e') 

package() {
  cd "$srcdir/$_realname-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
   
  patch DNS/Base.py < ../../Bas
}
