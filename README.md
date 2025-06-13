# Zapret (обход блокировки Discord'а и Youtube'а)

> [!NOTE]  
> Данный форк - собран из [репозитория](https://github.com/Flowseal/zapret-discord-youtube), дополнен темой из issues by [V3nilla](https://github.com/Flowseal/zapret-discord-youtube/issues/3265). 
>
> Этот форк помогает разблокировать множество сайтов и игры, которые используют cloudflare или amazon серверы.
>
> Здесь используются оригинальные бинарники, сравнить которые вы можете с помощью хэша.
> Так как zapret open-source, вы всегда можете сами собрать эти бинарники и не бояться вирусов.
> 
>
>**Поставьте [⭐ оригинальному репозиторию](https://github.com/Flowseal/zapret-discord-youtube/stargazers) (в правом верхнем углу) у репозитория 🙂**

## License

Я никак не претендую на права данной сборки, всё сделано силами коммьюнити для комфортной игры в любимые игры. Форк сделан мной для удобства и для друзей.

Этот проект распространяется на условиях лицензии MIT.  
Полный текст лицензии можно найти в файле [LICENSE.txt](./LICENSE.txt)

## Guides

Запустите **от имени администратора**:
- **`general (ALT6)+Cloudflare V2.bat`** - запустить обход дискорда, ютуба, cloudflare + amazon.

## Решение проблем

- Проверьте, запускаете ли вы файлы от **ИМЕНИ АДМИНИСТРАТОРА**
- Не запускаются bat файлы? Попробуйте найти ответ здесь: https://github.com/Flowseal/zapret-discord-youtube/issues/522
- <p style="text-align: left;">
    <img src="https://cdn-icons-png.flaticon.com/16/3670/3670147.png" alt="discord" style="vertical-align: middle;"/>
    Не работает <strong>Youtube</strong>? Попробуйте найти ответ здесь - 
    <a href="https://github.com/Flowseal/zapret-discord-youtube/discussions/251">Обсуждение YouTube</a>
  </p>
- <p style="text-align: left;">
    <img src="https://cdn-icons-png.flaticon.com/16/906/906361.png" alt="discord" style="vertical-align: middle;"/>
    Не работает <strong>Discord</strong>? Попробуйте найти ответ здесь - 
    <a href="https://github.com/Flowseal/zapret-discord-youtube/discussions/252">Обсуждение Discord</a>
  </p>
##
- Не работает вместе с **VPN**? Отключите функцию **TUN** (Tunneling) в настройках VPN.

### Остановка и удаление обхода
Для этого запустите **`service.bat`** и выберите Remove Services.
- Если WinDivert так и не удалился, узнайте его название с помощью команды `driverquery | find "Divert"` в cmd, а затем удалите данными командами (заместо WinDivert введите название, которые вы узнали):
```
sc stop WinDivert
sc delete WinDivert
```
#
* Many thanks to [bol-van](https://github.com/bol-van/), creator of original [zapret](https://github.com/bol-van/zapret/) repository.
#