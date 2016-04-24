# ptags.path

## Pythonのタグファイルを生成するスクリプトのパッチファイル

オリジナルはRaspbianの場合，下記のパス

```zsh
/usr/share/doc/python2.7/examples/Tools/scripts/ptags.py
```

適当なディレクトリにコピーして，パッチを当てる

```zsh
git clone https://github.com/TNaky/tools.git
cd tools/ptags_patch
cp /usr/share/doc/python2.7/examples/Tools/scripts/ptags.py ./ptags.py
patch -u ./ptags.py < ./ptags.patch
```
