# how to read web article on kindle

移动互联网时代，我们的大量阅读是在手机上完成的，但是我发现，对于长文章来说，最好的阅读体验还是在kindle电子墨水屏幕上，没有各种超链接和即时通讯app的诱惑，经常有不知不觉看了半个小时的情况。

亚马逊提供了将 html 文件发送到Kindle 上的功能，但正常的页面带了额外信息，并不适合直接在 Kindle 上阅读，需要进行格式处理才可以。

这个 GitHub 项目就是用来整理将互联网文章发送到 Kindle 上阅读的各种方案。

## 已知方案
* kindle中国公众号：可以将微信公众号文章转发到绑定的kindle设备上。
* p2k(pocket to kindle)：定期将 pocket 中的文章发送到 Kindle 上，最高级的付费版本支持一旦pocket收到新文章，就发送到 Kindle 上。
* push 2 kindle：支持将任意页面发送到 Kindle 上，有 Firefox 插件。
* instapaper：待阅服务，观法支持发送到 Kindle 的功能，不需要借助第三方，隐私性更好。
* send to kindle：亚马逊官方推出的Chrome 插件，可以将任意文章推送到kindle上。（但是暂时没有 Firefox 版本）
* mercury reader：Chrome 插件，支持将文章发送到 Kindle 上（但是暂时没有 Firefox 版本）。

综上，有付费墙的内容服务（比如华尔街日报，端传媒），待阅服务无法支持，浏览器插件仍然有不可替代的空间，如果找不到合适Firefox空间的方案，我打算自己实现一个。

p2k在GitHub上开源了他们的实现方案，可以在家里的路由器上搭一个，实现 pocket 文章的实时转发。
