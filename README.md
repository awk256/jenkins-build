# jenkins-build

## AzureCLI2.0 non-interactive mode intall

AzureCLI2.0のinstall.pyをnon-interactiveモードに書き換えた。
標準ではnon-interactiveモードのインストールが対応できてないためにコード化できない。

```
wget https://github.com/awk256/jenkins-build/archive/master.zip
unzip master.zip
python  jenkins-build-master/azure-build/azure-cli20/install.py
```
