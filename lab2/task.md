|  | Ping | tracert / traceroute | web-доступ через браузер |
| --- | --- | --- | --- |
| 1 | ya.ru | elibrary.ru | gmail.com |
| 2 | mail.ru | rambler.ru | vk.com |
| 3 | elibrary.ru | gmail.com | spbstu.ru |
| 4 | rambler.ru | vk.com | scopus.com |
| 5 | gmail.com | spbstu.ru | ok.ru |
| 6 | vk.com | scopus.com | pingmylinks.com |
| 7 | spbstu.ru | ok.ru | bing.com |
| 8 | scopus.com | pingmylinks.com | almazovcentre.ru |
| 9 | ok.ru | bing.com | pingmyurls.com |
| 10 | pingmylinks.com | almazovcentre.ru | useme.org |
| 11 | bing.com | pingmyurls.com | smallseotools.com |
| 12 | almazovcentre.ru | useme.org | nimtools.com |
| 13 | pingmyurls.com | smallseotools.com | duplichecker.com |
| 14 | useme.org | nimtools.com | pingomatic.com |
| 15 | smallseotools.com | duplichecker.com | pingler.com |
| 16 | nimtools.com | pingomatic.com | feedshark.brainbliss.com |
| 17 | duplichecker.com | pingler.com | backlinkping.com |
| 18 | pingomatic.com | feedshark.brainbliss.com | masspinger.org |
| 19 | pingler.com | backlinkping.com | websitepulse.com |
| 20 | feedshark.brainbliss.com | masspinger.org | uptrends.com |
| 21 | backlinkping.com | websitepulse.com | check-host.net |
| 22 | masspinger.org | uptrends.com | pingwebsite.com |
| 23 | websitepulse.com | check-host.net | indexkings.com |
| 24 | uptrends.com | pingwebsite.com | blo.gs |
| 25 | check-host.net | indexkings.com | escuela.bitacoras.com |
| 26 | pingwebsite.com | blo.gs | pingerati.net |
| 27 | indexkings.com | escuela.bitacoras.com | blogsnow.com |
| 28 | blo.gs | pingerati.net | allpodcasts.com |
| 29 | escuela.bitacoras.com | blogsnow.com | blog.goo.ne.jp |
| 30 | pingerati.net | allpodcasts.com | myblog.jp |
| 31 | blogsnow.com | blog.goo.ne.jp | github.com |
| 32 | allpodcasts.com | myblog.jp | blogg.de |
| 33 | blog.goo.ne.jp | github.com | biobiochile.cl |
| 34 | myblog.jp | blogg.de | mega.cl |
| 35 | github.com | biobiochile.cl | newzealand.com |
| 36 | blogg.de | mega.cl | rnz.co.nz |
| 37 | biobiochile.cl | newzealand.com | immigration.govt.nz |
| 38 | mega.cl | rnz.co.nz | puaha.wgtn.ac.nz |
| 39 | newzealand.com | immigration.govt.nz | skykiwi.com |
| 40 | rnz.co.nz | puaha.wgtn.ac.nz | ts-encyclopedia.theosophy.world |
| 41 | immigration.govt.nz | skykiwi.com | elliberal.com.ar |
| 42 | puaha.wgtn.ac.nz | ts-encyclopedia.theosophy.world | eldia.com |
| 43 | skykiwi.com | elliberal.com.ar | elintransigente.com |
| 44 | ts-encyclopedia.theosophy.world | eldia.com | laws-lois.justice.gc.ca |
| 45 | elliberal.com.ar | elintransigente.com | vietnam.gov.vn |
| 46 | eldia.com | laws-lois.justice.gc.ca | en.baochinhphu.vn |
| 47 | elintransigente.com | vietnam.gov.vn | ya.ru |
| 48 | laws-lois.justice.gc.ca | en.baochinhphu.vn | mail.ru |
| 49 | vietnam.gov.vn | ya.ru | elibrary.ru |
| 50 | en.baochinhphu.vn | mail.ru | rambler.ru |

Оформление отчета:

Титульный лист 

Задание работы - включив режим захвата трафика в одной из программ WireShark, tcpdump, windump и т.п. (в настойках или флагами указать, что захватываются минимум первые 100-120 байт каждого пакета, можно больше), запустить в консоле вызов команд ping и traceroute/tracert, а также открыть браузер и выполнить вход на сайт. После остановить захват трафика и проанализировать результаты, выделив пакеты, порожденные Вашими действиями.

Запускать лучше впервые, или перед запуском почистить кэш DNS (ipconfig /flushdns для Windows, sudo resolvectl flush-caches для Linux)

Если какой-то из серверов не работает (заблокирован и т.п., берите из строки выше, повторять, пока не найдете рабочий ("выше" 1 строки - 50-я))

При сдаче быть готовым показать онлайн (на ноутбуке) весь снятый трафик и прокомментировать что там за пакеты и откуда, и как работают ping и traceroute/tracert
