# PasswordGenbyweb
A password generator only needs to be managed through offline web pages. (This means you can cross end, cross platform, without any risk of data leakage).

一个密码生成器只需要通过离线网页管理。（意味着你可以跨端，跨平台，同时不存在任何数据泄露的风险）。
使用方法是你只需要管理好一个主密钥即可，并输入你的ID和平台名字就可以生成不同的密码。

这样做的好处就是在于当一个平台出现了密码泄露，也不会危害其他平台的密码安全。

同时使用sha256作为密码增强，使得较为简单的密码也不会被字典攻击。

它的安全性取决于你的主密钥，我们推荐至少使用8位以上的字符串。你可以为每个平台再设置一个子密钥，这样可以进一步提高安全性。

访问通过：https://kexinoh.github.io/PasswordGenbyweb/
