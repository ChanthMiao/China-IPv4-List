# China-IPv4-List

中国大陆IPv4地址库

## 说明

本项目为[gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip)的个人重构，和原项目有以下不同：

- 移除了具体的运营商分类，仅保留了中国大陆IPv4地址
- 构建流程完全迁移至Github Action，北京时间每日6:00自动构建

此外，因和 CC-BY-NC-SA 4.0 协议存在[兼容问题](https://creativecommons.org/share-your-work/licensing-considerations/compatible-licenses)，本项目未合并[ipip免费提供的数据](https://github.com/17mon/china_ip_list)。

## 下载地址

> 2023.01.24 更新: 因 [jsdelivr 大陆服务节点关闭](https://luotianyi.vc/6295.html)，移除相应 CDN 链接。

- cn.txt:
  - <https://raw.githubusercontent.com/ChanthMiao/China-IPv4-List/release/cn.txt>
- cn.txt.sha256sum:
  - <https://raw.githubusercontent.com/ChanthMiao/China-IPv4-List/release/cn.txt.sha256sum>

## 致谢

- 感谢[gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip)项目提供的具体实现方法
- 感谢[Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)项目提供的 Github Action 编写参考
- 感谢[actions/checkout](https://github.com/actions/checkout/discussions/479)提供的 github-actions bot 正确用法

## License

The code in this repository is licensed under the [MIT License](https://github.com/ChanthMiao/China-IPv4-List/blob/main/LICENSE).
