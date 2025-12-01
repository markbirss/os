# os


```
# sha256sum
# 32a9f7e30ea47f678453f8a37e8a8e8cd2faa30d0e6d3af4c00f3f023a6adad4  os.tar.gz

git clone https://github.com/markbirss/os.git
cd os
rm -fr .git
7z x os.7z.001
sha256sum os.tar.gz
rm -f os.7z*

mv os.tar.gz ../
cd ../
mkdir ubuntu
mv os.tar.gz ubuntu/ubuntu_24.04.3.tar.gz
```
