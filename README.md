# jenkins-build

## AzureCLI2.0 non-interactive mode intall

AzureCLI2.0のinstall.pyをnon-interactiveモードに書き換えました。
標準では、non-interactiveモードの対応ができてないようです(2017-07-06現在)。

```
yum install -y gcc libffi-devel python-devel openssl-devel
wget https://github.com/awk256/jenkins-build/archive/master.zip
unzip master.zip
python jenkins-build-master/azure-build/azure-cli20/install.py
```
