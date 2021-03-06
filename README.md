# CS642
mipt python 2016-2017

Course site:

[http://judge.mipt.ru/mipt_cs_on_python3/](http://judge.mipt.ru/mipt_cs_on_python3/)

## IDE:

### On Linux

#### VIM: [https://wiki.python.org/moin/Vim](https://wiki.python.org/moin/Vim)

Short cheat sheet:

    vim name_of_file_to_open # open file, enter Normal Mode(NM)
    <i>, <ins> # enter Insert Mode(IM) - edit text
    :(<;>+<shift>) – enter Command Mod
    <esk> – exit IM or CM to NM
    q, w, wq, q! - quit, write and force in CM (:x - same as :wq)

[movement in vim](https://bitbucket.org/tednaleid/vim-shortcut-wallpaper/raw/tip/vim-shortcuts2560x1600.png)

#### Pycharm

Скачиваем:

    wget -qO- https://download.jetbrains.com/python/pycharm-community-2016.2.3.tar.gz | tar xvz
    cd pycharm-community-*/bin
    bash pycharm.sh

Устанавливаем новый мастер пароль чтобы залогинится в свой аккаунт GitHub:

    File -> Close Project -> Check out from Version Control(Github)
    -> Reset... -> Choose the password -> Yes(All stored passwords will be removed!...)

Увеличить шрифт:

    File -> Settings -> Editor -> General -> Change font size (Zoom) with Ctrl+Mouse Wheel

#### Нужные пакеты

Fedora:

    sudo dnf install -y python3-numpy python3-matplotlib # lab2
    sudo dnf install -y python3-tkinter # lab3

### On windows

#### Standard python IDE: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)

## Proxy на паре:

Настраиваем прокси в браузер отсюда:

    firefox http://10.55.163.167/

Чтобы работал Git на паре, в том числе и в PyCharm:

    export http_proxy=http://10.55.163.167:34735/
    export https_proxy=http://10.55.163.167:34735/

## Other:

Чтобы разобраться в командной строке Linux и не только читаем(перевод) ["Основы Linux от основателя Gentoo"](linux-basics.md)

Selflearning:

[https://www.codecademy.com/](https://www.codecademy.com/)

[http://rosalind.info/problems/locations/](http://rosalind.info/problems/locations/)

[http://learngitbranching.js.org/](http://learngitbranching.js.org/)
