# NeoSV-test
## 直接在python>3.6的环境中安装程序，即可调用
### 安装
pip install neosv
***
### 调用
neosv -sf test.sv.vcf\    # vcf变异文件
      -hf test.hla.txt\   # 需要识别的hla分型的文件
      -np /path/to/netmhcpan \ # NetMHCpan的绝对地址
      -o test \ # 输出目录
      -p test \ # 前缀，可以是sample ID
      -r 75    # 要使用的 Ensembl 版本。hg19/GRCh37 和 hg38/GRCh38 的 Ensembl 版本分别为 75 和 96。
### 详细使用说明请参见https://github.com/ysbioinfo/NeoSV
