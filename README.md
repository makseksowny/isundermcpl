# Witaj użytkowniku! Oto github hostingu itemshopów, jakim jest: https://is.undermc.pl/

# INFORMACJE

**Z jakich korzystamy technologii?** \
python, cloudflare, java

**Jakich operatorów wspieramy?:** \
icehost, skillhost, nhost, chunkserve

**Jakie silniki wspieramy?:** \
spigot, bungeecord \
*(Przeróbki, które mają prawie identyczny kod też są wspierane)*

# Poradniki:

**1)** Jak podpiąć domene?

**1a)** (Wersja FREE) *Ta wersja wymaga cloudflare lub, aby każdy kto się łączy na sklep miał ipv6.*\
1 - Zaloguj się do panelu admina domeny\
2 - Kliknij zarządzanie rekordami DNS\
3 - Dodaj rekord DNS "AAAA"\
4 - Ustaw "Name" na nic lub na @ (Jak poprosi o wprowadzenie czegoś) *(jak chcesz, żeby adres root kierował na sklep)* lub ustaw na byle co np: "sklep", żeby subdomena kierowała\
5 - Ustaw "Content" na custom.undermc.pl i zapisz\
5a - Jeżeli używasz cloudflare, kliknij po prawej stronie obok "Content" taki przełącznik, aby świecił się na pomarańczowo (proxied == on)\
6 - Dodaj rekord DNS "TXT"\
7 - Ustaw "Name" na "itemshop.subdomena" *(subdomena to jest to co podano w "Name" w punkcie 4\
8 - Ustaw "Content" na "discord_id" *(discord_id to jest discordowe id konta, z którego zalogowano się na panel)* i kliknij "Zapisz"\
9 - W panelu itemshopu kliknij zakładke dodaj domene wpisz tam to co podano w "Name" w punkcie 4 i kliknij przycisk "Zastosuj"\
10 - Gratulacje twoja domena została pomyślnie skonfigurowana\
**1b)** (Wersja PREMIUM) *Ta wersja NIE wymaga cloudflare i, aby każdy kto się łączy na sklep miał ipv6 albo ipv4.*\
1 - Aby dostać tą wersje PREMIUM skontaktuj się z nami na discordzie: https://is.undermc.pl/discord

**2)** Jak wgrać plugin na serwer minecraft?

1 - Pobierz plugin z tego linku: https://github.com/makseksowny/isundermcpl/releases \
2 - Wgraj plugin na swój serwer minecraft \
3 - Skonfiguruj config.yml pluginu
