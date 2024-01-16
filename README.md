# transfer_everything_ok
从交易所向链上转账，以ok平台为例

查询转账后的余额，可参考：https://github.com/gm365/BalanceChecker

参考教程：https://github.com/gm365/Web3Scripts/tree/main

https://twitter.com/0x3lang/status/1681610436612083712?t=C-0t7Gjj7-haOuw1jQaZDQ&s=19

https://gist.github.com/3lang3/a4da6078853150db3031f0d8d51bde9e

1、ok网页端，按F12已经出不来调试信息了，可以手动解除(方法自搜)

解除后直接将代码贴上去，自动操作了，请将默认批次输入1，一次添加20个白名单
![image](https://github.com/xyyz12/transfer_everything_ok/assets/91812763/59ba915d-121e-42d2-acdc-ff26be2f6fd4)

将代码导入

![image](https://github.com/xyyz12/transfer_everything_ok/assets/91812763/6b76a2a7-6bf7-4dbe-9385-20a0767e99a4)

![af1e0339c8d474e74cfee0f257ccddf](https://github.com/xyyz12/transfer_everything_ok/assets/91812763/832973ea-be2c-4138-9c41-a76d17ae28bc)

输入地址和指令
![51a5b4c1ab3dfd3464e0ad75fc112c3](https://github.com/xyyz12/transfer_everything_ok/assets/91812763/5a4ddba5-b7c7-4f76-b800-b7fb51601a20)

得到结果

![8ab521cfc8212223b30882336f008a8](https://github.com/xyyz12/transfer_everything_ok/assets/91812763/64e3d819-00a8-4e7d-9701-85570fe62441)

问题所在

会有查询限制，每次最多查询300次，限制api，需要自己做更改

![image](https://github.com/xyyz12/transfer_everything_ok/assets/91812763/6afe5082-ff23-4867-abcb-510a0cfaec26)






