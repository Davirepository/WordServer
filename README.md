# WordServer

Чтобы запустить сервер пройдите следующие шаги:
1. Убедитесь, что у вас установлен HomeBrew или установите  используя в терминале команду: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. Установите vapor(если он не установлен) используя следующие команды в терминале: 
<br/>`brew tap vapor/homebrew-tap`
<br/>`brew update`
<br/>`brew install vapor`
3. Клонируйте проект с гитхаба, разъархивируйте. 
<br/>Перейдите в папку, которая содержит папку `wordsServer`. 
<br/>Откройте терминал и используте следующую команду:
`cd перетащите папку wordsServer из finder` или пропишите вручную путь до папки `wordsServer` после команды `cd`. 
<br/>У вас получится что-то вроде такого `cd /Users/user/Downloads/WordServer-master/wordsServer`.
<br/> Дальше следует ввести комнду `vapor build` чтобы установить все связи.
<br/> После завершения выполнения команды `vapor build` запустите сервер как обычный проект swift через `get-word.xcodeproj`
<br/> Убедитесь перед запуском, что схема запуска `Run` и устройство `My Mac`