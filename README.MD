
# MYiR MA35D1 manifest

## MA35D1 XML:
```
myir-ma35d1-5.10.140-1.0.0.xml
```

# MA35D1-5.4

## repo init and get myir-ma35d1-5.10.140-1.0.0.xml:
```
export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/'
repo init -u https://github.com/MYiR-Dev/myir-nuvoton-manifest.git --no-clone-bundle --depth=1 -m myir-ma35d1-5.10.140-1.0.0.xml -b MA35D1-5.10.140-dunfell
repo sync
```
