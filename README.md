# cloudreve-turnstile-build

使用 GitHub Actions 编译，添加了 Cloudflare Turnstile 验证码支持的 Cloudreve 主程序。

参见原 repo 的 [#1593](https://github.com/cloudreve/Cloudreve/issues/1593)、[#1945](https://github.com/cloudreve/Cloudreve/discussions/1945)。

使用方法：从 Actions 下载并替换原版主程序，在管理面板的验证码选项中选择 reCAPTCHA，直接输入你添加的 Turnstile 站点的 Site Key 和 Secret Key，并**加上 `turnstile:` 的前缀**。

使用效果：

![](https://github.com/cloudreve/Cloudreve/assets/47057319/fe469d8a-ea1e-4e3d-ab01-fd94be3944e0)
