---
title: Přehled funkcí
sidebar_position: 1
---

## Co dělá AdGuard VPN pro Windows

- Chrání před zachycením síťového provozu (spoofing). AdGuard VPN vytvoří šifrovaný tunel mezi vaším zařízením a vzdáleným serverem. Veškerý internetový provoz prochází tímto tunelem, takže vaše data jsou po cestě chráněna. A díky [jedinečnému AdGuard protokolu](/general/adguard-vpn-protocol) máte zaručeno rychlé a bezpečné připojení.

- Maskuje IP adresu. Vaše skutečná IP adresa je pro kyberzločince klíčem k vašim osobním údajům. Vaše jméno, e-mailová adresa, telefonní číslo a údaje o kreditní kartě se mohou dostat do rukou podvodníků, pokud neskryjete svou IP adresu. S AdGuard VPN prochází veškerý váš datový provoz šifrovaným tunelem a přichází na server VPN. Webový server registruje IP adresu koncového bodu tunelu, tj. serveru VPN, a nikoli skutečnou IP adresu zařízení.

- Skrývá vaši skutečnou polohu. Co tím získáte? Například možnost rezervovat si hotel za ceny pro místní obyvatele nebo se skrýt před geograficky cílenou reklamou.

AdGuard VPN pro Windows má mnoho výhod, proto jsme tomu věnovali [samostatný článek](/general/why-adguard-vpn). Zde se však chceme zaměřit spíše na samotnou aplikaci a její fungování.

## Jak začít používat AdGuard VPN pro Windows

Chcete-li začít používat AdGuard VPN pro Windows, stáhněte si aplikaci z [našich webových stránek](https://adguard-vpn.com/welcome.html). Instalace netrvá déle než minutu — zobrazí se dialogové okno, ve kterém je třeba zaškrtnout alespoň jedno políčko s podmínkami uživatelské smlouvy a zásady ochrany osobních údajů. Je na vás, zda chcete, aby AdGuard shromažďoval anonymizovaná data o používání aplikací. Nakonec vás program požádá o přihlášení, a to buď prostřednictvím účtu [AdGuard](https://auth.adguardaccount.com/login.html), nebo prostřednictvím sociálních sítí (Apple, Google, Facebook). To je vše, nyní můžete používat AdGuard VPN pro Windows.

## Domovská obrazovka

![Home screen](https://cdn.adguardvpn.com/content/kb/vpn/windows/saved_locations.png)

Nejvýraznější položkou na **Domovské obrazovce** je tlačítko AdGuard VPN *Připojit/Odpojit*, pod nímž je zobrazen vybraný server. Na pravé straně obrazovky se zobrazí seznam dostupných umístění. Nejrychlejší umístění, tj. umístění s nejmenší odezvou ping se zobrazí na začátku seznamu. K dispozici je také tlačítko pro obnovení, na které můžete kliknout, pokud jsou některá místa offline.

Můžete si také uložit oblíbená umístění, abyste k nim měli rychlý přístup. Stačí najet na umístění, kliknout na ikonu záložky, která se zobrazí, a umístění se uloží. Označená umístění se pak zobrazí na kartě *Uložené*.

V horní části obrazovky je navigační panel s pěti kartami: **Domů**, **Výjimky**, **Statistiky**, **Podpora** a **Nastavení**.

## Výjimky

Ve výchozím nastavení funguje AdGuard VPN pro Windows všude. Do seznamu výjimek můžete přidat webové stránky a aplikace, které chcete z tunelu VPN vyloučit. Nebo můžete nastavit, aby AdGuard VPN fungoval pouze na webových stránkách a aplikacích uvedených v seznamu výjimek. Upozorňujeme, že tyto dva seznamy jsou na sobě nezávislé.

![Exclusions *border](https://cdn.adguardvpn.com/content/kb/VPN/windows/new_exclusions_screen.png)

Webové stránky můžete do výjimek přidat **ručně** zadáním názvů jejich domén. Aplikace také nabízí možnost vybrat si oblíbené weby **ze seznamu**.

![Add Exclusions from list *border](https://cdn.adguardvpn.com/content/kb/VPN/windows/new_exclusions_from_list_en.png)

:::note

Při ručním přidávání domén byste měli vzít v úvahu určité podrobnosti. Pokud například ručně vyloučíte doménu `google.com`, budou do výjimek přidány také všechny subdomény `*.google.com`. Doménové názvy s ostatními doménami nejvyšší úrovně, jako je `google.es` nebo `google.it`, však vyloučeny nebudou. Nebo můžete do výjimek přidat `youtube.com`, ale doména stejné služby `youtu.be` se do seznamu nedostane.

:::

Doporučujeme použít možnost **Ze seznamu**. Weby jsou rozděleny do osmi kategorií: sociální sítě, messengery, služby pro streamování videa a hudby, hry, nakupování, vyhledávače a nástroje pro pracovní komunikaci. Umístili jsme tam nejoblíbenější služby, včetně všech názvů domén a subdomén souvisejících s každou platformou.

:::info Prohlížeče přidané do výjimek

Od verze 2.4 jsou všechny prohlížeče automaticky přidány do seznamu výjimek, pokud je VPN aktivní pouze pro vybrané aplikace a webové stránky. Tato změna přináší větší pohodlí uživatelům, kteří byli často zmateni a nevěděli, zda mají své prohlížeče považovat za aplikace, nebo ne. Platí za následujících podmínek:

- Uživatel nainstaloval AdGuard VPN poprvé
- Uživatel nezměnil nastavení výjimek před verzí 2.4

:::

### Import/export seznamů výjimek

Chcete-li exportovat seznam výjimek z AdGuard VPN pro Windows do počítače, klikněte na **Exportovat výjimky**, vyberte složku, do které bude seznam uložen, a klikněte na **Uložit**. Stáhne se archiv `exclusions.zip` se dvěma soubory `.txt`, jeden pro každý ze seznamů. Můžete je upravit přidáním nových výjimek nebo odstraněním starých.

V cílovém zařízení otevřete AdGuard VPN, klikněte na *Výjimky* a vyberte *Webové stránky* nebo *Aplikace*. Klikněte na *Importovat výjimky* a vyberte přijatý archiv.

## Statistiky

![Statistics screen *border](https://cdn.adguardvpn.com/content/kb/vpn/windows/statistics_en.png)

Obrazovka Statistiky zobrazuje podrobné informace o využití dat rozdělené do kategorií podle umístění a aplikací. Zvýrazňuje nejčastěji používaná umístění a aplikace. Můžete získat přístup ke statistikám za různá časová období: denní, měsíční nebo za celou dobu používání AdGuard VPN pro Windows.

Důležité je, že všechny tyto informace jsou uloženy výhradně ve vašem zařízení, takže je můžete zobrazit pouze vy. Přístup k funkci statistik mají pouze předplatitelé AdGuard VPN.

## Nastavení

![Settings *border](https://cdn.adguardvpn.com/content/kb/vpn/windows/settings_en.png)

Pátá karta obsahuje části, které vám pomohou přizpůsobit aplikaci.

### Nastavení aplikace

![App settings *border](https://cdn.adguardvpn.com/content/kb/vpn/windows/app_settings_en.png)

V sekci **Nastavení aplikace** můžete nastavit jazyk aplikace a také povolit funkci **Kill Switch**, která zablokuje přístup k internetu, pokud připojení VPN selže. Tím se zabrání vetřelcům v přístupu k vašim datům, pokud se ocitnete bez ochrany VPN a jste připojeni k veřejné síti Wi-Fi nebo mobilní síti.

Jedním kliknutím můžete také aktivovat následující funkce: **automatické aktualizace**, **spuštění AdGuard VPN při spuštění systému Windows**, **automatické připojení při spuštění aplikace**, a také umožnit společnosti AdGuard shromažďovat anonymizovaná data o používání aplikace. Zde můžete také změnit motiv na **Světlý**, **Systémový**, nebo **Tmavý**.

Ve spodní části stránky jsou dvě sekce: **DNS servery** a **Pokročilá nastavení**.

#### DNS servery

Karta **DNS servery** umožňuje přidat vlastní DNS server — ručně nebo ze seznamu. DNS server můžete nastavit u libovolného poskytovatele. Doporučujeme přidat server [AdGuard DNS](https://adguard-dns.io/kb/general/dns-providers/#adguard-dns), který kromě standardních funkcí dokáže chránit před reklamami, sledováním a krádeží identity.

#### Pokročilá nastavení

Je zcela možné používat AdGuard VPN pro Windows, aniž byste se dotkli pokročilých nastavení, ale mohou být užitečná, pokud jste ochotni věnovat čas tomu, abyste se naučili, k čemu slouží.

##### Pracovní režim

Přestože existují dva provozní režimy — VPN a SOCKS5 — doporučujeme používat pouze ten, který je zvolen jako výchozí (VPN). Když je povolen režim **VPN**, veškerý datový provoz vašeho zařízení bude přesměrován přes AdGuard VPN, zatímco v režimu **SOCKS5** AdGuard VPN používá místní proxy server, který mohou používat jiné aplikace k přesměrování svého datového provozu.

##### Úroveň záznamu

Na výběr jsou dvě úrovně záznamu: **Výchozí záznam** a **Záznam všeho**. První možnost je ve výchozím nastavení povolena. Možnost **Zaznamenat vše** by měla být zapnuta pouze v případě, že vás o to požádá náš tým podpory. Při delším používání aplikace v tomto režimu dochází ke zvýšené spotřebě baterie.

Všechny záznamy jsou uloženy lokálně v zařízení a v případě potřeby je můžete odeslat na naši podporu.

##### Postkvantová kryptografie

![Post-quantum cryptography *border](https://cdn.adtidy.org/blog/new/qe7fgimage_3.png)

Tato funkce šifruje provoz tak, aby je nemohly zachytit ani kvantové počítače.

##### AdGuard VPN protocol

![Select VPN protocol *border](https://cdn.adtidy.org/content/release_notes/vpn/windows/v2.7/auto_en.png)

By default, AdGuard VPN protocol uses dynamic VPN protocol selection (*Auto-select* option). That means that AdGuard VPN automatically figures out which protocol — HTTP2/TLS or HTTP3/QUIC — will give you the best performance and switches to it instantly. This improves VPN speed and stability, which is particularly helpful in regions where VPN usage is restricted or unreliable.

If you wish, you can switch AdGuard VPN to use only HTTP2/TLS or HTTP3/QUIC protocol instead of *Auto-select*. Each protocol has its strengths, but the best choice can vary depending on your location, network conditions, and even the server you connect to.

##### Použít WinTun

WinTun is a traffic routing driver commonly used for VPN implementations on Windows that improves the quality of VPN connections by creating a virtual network adapter. By default AdGuard VPN uses the regular WFP driver (and TDI driver for Windows 7).

#### Výjimky podsítě

This feature allows you to add subnets to exclude traffic from specific devices connected to your network. For example, your robot vacuum cleaner.

## Další karty

### O programu

The **About** tab provides information about the current version of AdGuard VPN for Windows, an update button, and links to the AdGuard VPN website, EULA, and Privacy policy.

### Účet

Here you can find information about your license status, as well as a link to your personal AdGuard account, where you can manage your current subscriptions and purchase new ones.

## Podpora

This tab is aimed to solve users’ questions: there you can find a link to the FAQ page, report a bug or leave feedback, and export logs if the support team asks you to.
