# Longevity Testnet Request sample

以下哈希是文件原始字节（包括末尾换行）的 Keccak-256。Create Request 时填写：

| 字段 | 值 |
| --- | --- |
| Policy hash | `0xf8f4027123a5ceb1b7902403e2de1fac62a1dd99fa5c818b5204b5167d8bca7d` |
| Policy locator | `https://raw.githubusercontent.com/Galxe/explorer-data/0785830f0d8ddd07e9e317cb5f420de61568713c/jugge/longevity-testnet-arithmetic/policy.json` |
| Content hash | `0xcf146f00ce4ebc0724e08e1f09431552df423968c4187535c3bab53a0427a6a3` |
| Content locator | `https://raw.githubusercontent.com/Galxe/explorer-data/0785830f0d8ddd07e9e317cb5f420de61568713c/jugge/longevity-testnet-arithmetic/content.txt` |

相同钱包在同一网络上可复用已发布的元数据，重复创建新的 Request。若修改文件字节，须重新计算哈希并使用新文件的固定提交地址。
