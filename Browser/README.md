# 浏览器相关的奇淫技巧

# 为躲避浏览器安全性拦截如何做

- 退出当前的浏览器（Chrome、Safari）

- 打开命令行启动 相关浏览器

  - Chrome

  ```
    open -a "Google Chrome" --args --disable-web-security  --user-data-dir
  ```
  - Safari

  ```
    open -a '/Applications/Safari.app' --args --disable-web-security --user-data-dir
  ```