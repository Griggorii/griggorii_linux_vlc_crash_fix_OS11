# griggorii_linux_vlc_crash_fix_OS11
linux vlc crash fix

Linux проблемные пакеты VLC падает при открытии его настроек 

Так как я собрал много OS я вычислил эти два пакета которые должны быть удалены не только вами 
, но и корпорациями которые задавили мои дистрибутивы обделяя их вниманием и соответственно не 
приходом инвестиции в мою среду разработки.

1) пакет overlay-scrollbar

2) пакет overlay-scrollbar-gtk2

1) способ

sudo apt purge overlay-scrollbar overlay-scrollbar-gtk2

2) способ если пакеты в apt не видны но они есть

sudo apt install --reinstall overlay-scrollbar overlay-scrollbar-gtk2 && sudo apt purge overlay-scrollbar overlay-scrollbar-gtk2

Все вторичные перепечатанные статьи указывать ссылку именно сюда. 13.05.2019

В основе эта ошибка была в Pop OS , но и репы эти до сих пор не удалены потому что я только нашёл , как я нашел я взял aptik 
сделал бекап своих пакетов где VLC вылетает и поместил на свою OS вопрос : как долго вы там будете есть бесплатный хлеб?
