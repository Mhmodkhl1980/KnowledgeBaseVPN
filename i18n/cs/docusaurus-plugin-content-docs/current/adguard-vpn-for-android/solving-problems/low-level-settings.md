---
title: Průvodce nízkoúrovňových nastavení
sidebar_position: 6
---

## Jak dosáhnout nízkoúrovňových nastavení

:::caution

Změna _Nízkoúrovňových nastavení_ může způsobit problémy s výkonem AdGuard VPN, může přerušit internetové připojení nebo ohrozit vaši bezpečnost a soukromí. Tuto sekci byste měli otevřít pouze v případě, že víte, co děláte, nebo vás o to požádal náš tým podpory.

:::

Chcete-li přejít na _Nízkoúrovňová nastavení_, otevřete aplikaci AdGuard VPN a klepněte na ikonu ozubeného kola v pravém dolním rohu obrazovky. Poté zvolte _Obecné_ → _Pokročilé_ → _Nízkoůrovňová nastavení_.

## Nízkoúrovňová nastavení

Níže uvádíme všechna nízkoúrovňová nastavení dostupná v AdGuard VPN pro Android a vysvětlujeme, k čemu slouží. Ještě jednou vás vyzýváme, abyste si s těmito nastaveními nezahrávali naslepo, i když jste si přečetli tuto příručku. Považujte ji za tahák pro případy, kdy víte, co děláte, ale chcete si doplnit konkrétní informace.

### AdGuard VPN protokol

By default, AdGuard VPN protocol uses dynamic VPN protocol selection (_Auto-select_ option). That means that AdGuard VPN automatically figures out which protocol — HTTP2/TLS or HTTP3/QUIC — will give you the best performance and switches to it instantly. This improves VPN speed and stability, which is particularly helpful in regions where VPN usage is restricted or unreliable.

If you know what you are doing, you can switch AdGuard VPN to use only HTTP2/TLS or HTTP3/QUIC protocol instead of _Auto-select_. [QUIC](https://adguard-vpn.com/kb/general/why-adguard-vpn/#6-quic-support) je relativně nový protokol a proto může být méně stabilní. Pokud je však vaše internetové připojení nestabilní (např. při připojení k veřejné Wi-Fi), poskytuje lepší zabezpečení a zvyšuje rychlost připojení díky technologii [Head-Of-Line Blocking](https://adguard-dns.io/en/blog/dns-over-quic.html#headoflineblocking).

Also, here’s a dedicated article about the protocol: [How AdGuard VPN protocol works](/general/adguard-vpn-protocol.md).

### Include Wi-Fi gateway in VPN routes

If this setting is enabled, the gateway IP addresses will be added to VPN routes when on Wi-Fi.
If you disable it, then the route configuration (IP ranges that are filtered) will be changed. The Wi-Fi gateway of the network to which the user is connected will be excluded, and therefore, it will not be subject to filtering.

This setting is enabled by default.

### Packet capture (PCAP)

If this setting is enabled, AdGuard VPN will create a `.pcap` file with a timestamp for its name (for instance, `1682599851461.pcap`) in the app cache directory. This file lists all network packets transferred through the VPN and can be analyzed with the [Wireshark program](https://www.wireshark.org/).

### Watchdog

Watchdog monitors the VPN process state to check if there are any problems with it. When enabled, AdGuard VPN will protect itself against aggressive battery saver apps that could otherwise kill it.

### Preferred IP version

Here you can set up the endpoint addresses. There are three options: IPv4, IPv6 or IPv4 and IPv6 (if your device supports both).

### IPv4 ranges excluded from VPN

VPN tunneling for the IPv4 ranges listed in this section will be disabled.

### IPv6 interface

After enabling this option you will have an IPv6 address while routing traffic through the VPN connection. You can set up the exclusions in the _IPv6 ranges excluded from VPN_.

### IPv6 ranges excluded from VPN

VPN tunneling for the IPv6 ranges listed in this section will be disabled.

:::note

You need to enable _IPv6 interface_ setting in _Low-level settings_ first, otherwise this setting will not be applied.

:::

### MTU (maximum transmission unit)

Here you can set the maximum size (in bytes) of the data packet used in local VPN. The recommended range is 1500-9000 bytes.

### Excluded apps

You can list here UIDs (unique identifiers) or package names of the apps that you want to exclude from VPN routing.
Unlike with apps added to regular _Exclusions_, the traffic of apps added to _Excluded apps_ doesn’t go to the local VPN service on your device at all. Instead, it goes directly to the destination.

### Proxy server port

Here you can set up the internal SOCKS5 proxy server port. The default option is 1080.
