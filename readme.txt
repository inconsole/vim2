1:
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/

2:
BundleInstall






//
a:  
ycm_client_support.[so|pyd|dll] and ycm_core.[so|pyd|dll] not detected; you need to compile YCM before using it. Read the docs!

To:
cd ~/.vim/bundle/YouCompleteMe 
./install.sh --clang-completer


a:
Exuberant ctags not found

To:
apt-get install ctags



技巧
1：
如果想要统一文件中的不同格式的tab，请使用
:retab
这个命令对于解决"IndentationError: expected an indented block"非常管用

2:格式化dos成unix
:set ff=unix
