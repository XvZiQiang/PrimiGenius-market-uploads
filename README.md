<!-- primigenius-market-submissions -->
# PrimiGenius 插件提交记录 / Plugin submissions

此处保存作者上传的插件及完整配置；审核和当前上架状态以平台市场记录为准。
Uploaded packages and full configurations are archived here. Review and listing status are maintained by the marketplace.

### SRA 高速下载（自动单双端） / SRA High-Speed Download \(Auto Layout\) · 2\.0\.0

- 插件 ID / Plugin ID: community\_242235968\_sra\_data\_download\_high\_speed\_auto
- 作者 / Owner: XvZiQiang
- 提交者 / Submitted by: XvZiQiang
- 类型 / Type: cli
- 提交时间 / Submitted: 2026-11-15T09:36:55Z
- 安装包大小 / Size: 48796431 bytes
- SHA256: `19339eecabfa3ec11f3b85090db7f1ff7bee2981ec18a4d5b00f06bea7d16041`

从 NCBI 官方 AWS 公共桶分片高速下载完整质量 SRA，逐个 accession 自动识别单端或双端，再用 fasterq-dump 与 pigz 生成并校验 FASTQ。插件自带离线运行环境，首次运行本地构建镜像，不依赖公共镜像站。 / Downloads full-quality SRA objects from the official NCBI AWS public bucket with resumable ranges, automatically detects SINGLE or PAIRED layout per accession, and creates verified FASTQ files with fasterq-dump and pigz\. The bundled offline runtime builds locally on first use without a public container registry\.

更新说明 / Changes: 从 NCBI 官方 AWS 公共桶分片高速下载完整质量 SRA，逐个 accession 自动识别单端或双端，再用 fasterq-dump 与 pigz 生成并校验 FASTQ。插件自带离线运行环境，首次运行本地构建镜像，不依赖公共镜像站。

[完整配置与提交信息 / Full record](https://github.com/XvZiQiang/PrimiGenius-market-uploads/blob/HEAD/submissions/submission-2e29553e750b61e0dcc8c4adfce990e8.json) · [安装包 / Package](https://github.com/XvZiQiang/PrimiGenius-market-uploads/releases/tag/submission-2e29553e750b61e0dcc8c4adfce990e8) · [审核记录 / Review](https://github.com/jianbai-design/PrimiGenius-community-plugins/issues/16)


