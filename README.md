# MahsaNG
MahsaNG is not just a V2rayNG client, this beast of a VPN aims to provide free and uncensored internet access to the people who need it. It uses Rotating configs, integrated Psiphon and WARP, Fragmentation, MUX, FakeHost, and more to make internet censorship almost impossible.

<a href="https://play.google.com/store/apps/details?id=com.MahsaNet.MahsaNG&hl=en-US">
    <img src="playstorebadge_en.svg" width=239px height=71px alt="Get it on the play store"> <!--https://github.com/pioug/google-play-badges-->
</a>

<a href="https://github.com/GFW-knocker/MahsaNG/releases/latest">
    <img src="https://img.shields.io/badge/Download_from-Github_releases-blue" alt="Download from github releases">
</a> <br>

<a href="t.me/mahsa_net">
    <img src="https://telegram-badge.vercel.app/api/telegram-badge?channelId=@mahsa_net&style=social" alt="Telegram" />
</a>

<img src="https://github.com/GFW-knocker/MahsaNG/blob/master/Mahsa_logo.jpg?raw=true" width="480" ><br>


# What is the idea
- MahsaNG is client-side of project [Segaro_Dream](https://github.com/GFW-knocker/Segaro_Dream)
- MahsaNG is a decentralized non-profit vpn platform in which everyone can share their configs to help others
- Donated configs continuously monitored and redistributed to users based on clients feedback in each subnet-ip
- Our goal is to make a superior vpn platform which is free,stable,scalable,distributed & filter-resistant

# Difference to v2rayNG
- vpn providers can use ADS service to make income instead of direct sell
- everyone can share their unused vps bandwidth to help others
- prevent free configs to be stolen and reselled
- Automatic report for refining config collection at central servers
- DNS over HTTPS
- TLS Fragmentor
- HTTP & WS fake Host
- Rotating Configs
- Random Subdomain
- & much more ...

# build from source
- the code can NOT build standalone apk directly from source
- some parts of source used for encrypting config is closed to prevent leakage & thus reselling of donated configs
- classes responsible for authentication with [mahsa server](https://www.mahsaserver.com/) is also closed to prevent abusing of mahsa server
- all other technology used to bypass filtering is willingly published in [Mahsa Xray-Core](https://github.com/GFW-knocker/Xray-core) including but not limited to Wireguard Noise, Youtube Direct , TLS & HTTPS & DoH fragmentor & fake Host

# build NikaNG from source
- [NikaNG](https://github.com/mahsanet/NikaNG) is a fork of v2rayNG with [Mahsa Xray-core](https://github.com/GFW-knocker/Xray-core)
- its fully open souce and it can build by github action or locally
- if you are interested in Mahsa-core as a developer , NikaNG is for you.
- you need to place [libv2ray.aar](https://github.com/GFW-knocker/AndroidLibXrayLite) in v2rayng/apps/libs folder before compile

