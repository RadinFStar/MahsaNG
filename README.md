# MahsaNG
MahsaNG is not just a V2rayNG client, this beast of a VPN aims to provide free and uncensored internet access to the people who need it. It uses Rotating configs, integrated Psiphon and WARP, Fragmentation, MUX, FakeHost, and more to make internet censorship almost impossible.

<a href="https://play.google.com/store/apps/details?id=com.MahsaNet.MahsaNG&hl=en-US">
    <img src="playstorebadge_en.svg" width=239px height=71px alt="Get it on the play store"> <!--https://github.com/pioug/google-play-badges-->
</a> <br>

<a href="https://github.com/GFW-knocker/MahsaNG/releases/latest">
    <img src="https://img.shields.io/badge/Download_from-Github_releases-blue" alt="Download from github releases">
</a><a href="https://t.me/mahsa_net">
    <img src="https://telegram-badge.vercel.app/api/telegram-badge?channelId=@mahsa_net&style=social" alt="Telegram" />
</a>

<img src="https://github.com/GFW-knocker/MahsaNG/blob/master/Mahsa_logo.jpg?raw=true" width="480" ><br>


# What's the idea?

This is a client-side of the project [Segaro Dream](https://github.com/GFW-knocker/Segaro_Dream) 
.

Basically, people who have bought or made configs donate it to MahsaNG. Then, It's available to many MahsaNG users worldwide, but to decrease load on the servers and make the app more managable, MahsaNG allows no more than 25 configs per user.

Also, Donated configs are continuously monitored and redistributed to users based on client feedback.

This project is decenteralized and non-profit. It is a labor of love.


# Differences with V2rayNG
- VPN providers can use ADS service to make income instead of directly selling them.
- Everyone can share their unused vps bandwidth to help others connect.
- We prevent free configs from being stolen and reselled.
- Automatic feedback for refining config collection at central servers
- Option for DNS over HTTPS
- Powerful TLS Fragmentor
- HTTP & WS fake Host
- Rotating Configs
- Random Subdomain
- And much more
# Building from source

It is not possible to build a standalone APK directly from source.

### Why?

Some parts of the project like the part responsible for encrypting configs had to stay proprietary to prevent configs from being resold.

### What parts?

Only 2:

- Parts responsible for encrypting/decrypting configs
- Classes responsible for authentication with the [Mahsa Server](https://www.mahsaserver.com/) <br><br>
All other technology used to bypass filtering is willingly published in [Mahsa Xray-Core](https://github.com/GFW-knocker/Xray-core), including but not limited to Wireguard Noise, Youtube Direct , TLS & HTTPS & DoH fragmentor and FakeHost.

### NikaNG


<a href="https://github.com/mahsanet/NikaNG"><img src="https://img.shields.io/badge/NikaNG_on-Github-blue" alt="NikaNG on Github"></a>

NikaNG is a fork or V2rayNG with the Mahsa Xray-Core. It is entirely FOSS and can be built.

If you're intrested in Mahsa Core as a developer, looking for a more FOSS alternative to MahsaNG, or anything else, then NikaNG is for you.

>[!IMPORTANT]
>
>  You need to place [libv2ray.aar](https://github.com/GFW-knocker/AndroidLibXrayLite) in the `v2rayng/apps/libs` folder before compiling



