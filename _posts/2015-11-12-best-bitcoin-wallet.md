---
layout: post
title: "The Best Bitcoin Wallets"
description: "Where to store your bitcoin: choose the best bitcoin wallet - web, downloaded, hardware wallets."
category: "bitcoin wallets"
permalink: best-bitcoin-wallet/
image:
- "/images/bestbitcoinexchange_mycelium.png"
- "http://i464.photobucket.com/albums/rr6/bitcoinexchange/bitcoin-wallets/Best-Bitcoin-Wallet_Electrum_zpsbhnnfnuw.png"
- "http://i464.photobucket.com/albums/rr6/bitcoinexchange/Best-Bitcoin-Wallet_Armory_zpsxgy9cltu.png"
image_alt:
- "Mycelium Android Bitcoin Wallet - bestbitcoinexchange.co"
- "Electrum wallet installation"
- "Armory Bitcoin cold storage"
feature: "/images/bestbitcoinexchange_mycelium.png"
---

* [Online Bitcoin wallets](#online) with access from web browser
  * [Coinbase](#coinbase)
  * [Blockchain.info](#blockchaininfo)
  * [BitGo](#bitgo)

* Online wallets with advanced privacy (separate article)
  * [Samourai (beta)](/samourai-wallet/)
  * [Xapo](/samourai-wallet/)

* [Bitcoin wallet as a mobile app](#mobile)
  * [Mycelium for Android](#mycelium-android-bitcoin-wallet)
  * [Samourai for Android (beta)](/samourai-wallet/) (separate article)
  * [Breadwallet for iPhone](#breadwallet)

* [Bitcoin wallet as a software](#download) - generally better
  * [Electrum](#electrum) - Now updated with better privacy
  * [MultiBit HD](#multibit-hd)
  * [Armory Online](#armory)

* [Bitcoin cold storage](#cold)
  * [What does it mean, cold storage?](#what-is-bitcoin-cold-storage)

* [Hardware Bitcoin wallets](#hardware)
  * [Trezor vs. Ledger Wallet](#ledger-wallet-vs-trezor-wallet)


{{ site.ads.aads }}

<h2 id="online"  class="exa">Online Bitcoin Wallets (Web Wallets)</h2>

Web wallets are convenient. Probably too convenient. You manage them in a web browser - if you need to reinstall your OS you don't have to worry about recovering of your Bitcoin, your coins are on someone else's servers, the user interface is nice and so on.

The disadvantage of many web-based wallets is that only some will let you
own your recovery seed. If you forget your passphrase all your Bitcoins are
gone. If you make up a weak passphrase {% aff someone's bot will steal your coins http://www.palkeo.com/code/stealing-bitcoin.html %}.

## Web Wallets and Privacy

Another aspect is that your activity. Your IP address and whatnot will be monitored and possibly disclosed to authorities without any notice. It is like using Gmail (Google discloses everything to everyone who says you _might_ be doing something illegal), only that the pool of users is smaller, so be careful.

So much for privacy. Just don't forget that online web-based Bitcoin wallets are a trust machine. You are
trusting someone enough to let your coins live on their servers.

Don't use a web Bitcoin wallet to store a lot of them. You don't think that any web wallet is good for [cold storage](#cold), do you? There are now places where you can have a web wallet for Bitcoin cold storage but you have to register and go through AML/KYC. If that is for you, head over to {% aff CryptoFacilities https://www.cryptofacilities.com/derivatives/380f92bf-2de7-45e5-bc0a-28faf5f217fc %}. They do it the same way as you would with any other Bitcoin cold storage - Bitcoins are on offline servers, safely separated from the Internets. The only drawback is you are giving out your Bitcoin to some organization.

[Up](#)


## Most popular Bitcoin web wallets

The two biggest and most popular web wallets are {% aff Coinbase https://www.coinbase.com/join/fany %} and {% aff blockchain.info https://blockchain.info %}. These
also have direct integration with certain exchanges or services so as to make
your transfers easier. Coinbase even has their own Bitcoin exchange with plenty traders. However, it is only convenient for people from the US.

<h6 class="exa">If you sign up with this {% aff Coinbase referral link https://www.coinbase.com/join/fany %} you will be rewarded $10 in BTC the moment you buy Bitcoin worth more than $100.</h6>

As for **security**, the most powerful wallet right now was said to be
_BitGo_. BitGo is the provider of hot wallets for exchanges like BitStamp, **BitGo also was the security solution provider for Bitfinex while it was hacked though**.

Still, even with stealth security, **privacy** cannot be compared to
<a href="#download">software</a> or <a href="#hardware">hardware</a> wallets
for any of these web apps.

Not only is your activity logged by third party and your account can be frozen for no reason any time. There is a much bigger issue regarding privacy and that is the number of addresses in each wallet.

Generally, <a href="#download">software wallets</a> generate a pool of
addresses that are all linked to your wallet. You can use a different address
for different types of incoming payments and you will still receive money to
the same wallet.

Online web-based wallets typically don't do this. You only get one bitcoin address and that's it.

This is great for privacy because of tools like [Wallet Explorer](https://www.walletexplorer.com/). Wallet Explorer knows addresses of hot wallets on major exchanges and of darknet marketplaces. If you have a blockchain.info wallet and you shared your address on your forum account or blog, anyone will see where the coins went. And remember, it is all on the blockchain: Even if Wallet Explorer doesn't know the Bitcoin address of a new darknet market today, it will know it in a few weeks time, while your transaction will still be on the blockchain - forever.

Hopefully, address pooling will be accessible from a browser app soon too. There is Samourai wallet being developed and there is Xapo. However Xapo will need your verified identity first. ([Read more about wallets with address poling and coinjoin](/samourai-wallet/))

[Up](#)


## Coinbase

{% aff Coinbase https://www.coinbase.com/join/fany %} is something like the bank institute of Bitcoin. You don't even get your recovery seed. Everything is taken care of.

* If you are just starting out it might be ideal for you.
* If you are not starting out, this might be too limiting for you.


Another thing good to know is that {% aff Coinbase https://www.coinbase.com/join/fany %} will let you buy Bitcoin with your bank account (unless you are from a wrong country). There is a busy and popular exchange connected to {% aff Coinbase https://www.coinbase.com/join/fany %} wallet.

As for security and privacy, {% aff Coinbase https://www.coinbase.com/join/fany %} logs your activity. A sign-in attempt from an unknown user agent and IP needs to be validated via email.

<h6>Getting a Coinbase account? If you sign up with this {% aff Coinbase referral link https://www.coinbase.com/join/fany %} you will be rewarded $10 in BTC the moment you buy Bitcoin worth more than $100.</h6>

[Up](#)


## Blockchain.info

{% aff Blockchain.info https://blockchain.info/wallet/ %} is another plain and simple wallet.

You have much more freedom though (and you also get your wallet's seeds). If you are willing
to play around with settings you can achieve a pretty good privacy.

* Sign-ins from new locations must be always validated via email. Users can even set up an IP whitelist and limit access only to these addresses.

* There is an option to have backup of your wallet sent to your mailbox. That is something to be
careful about because you need to be sure your mailbox is secured, too.

* There is no Bitcoin exchange on {% aff Blockchain.info https://blockchain.info/wallet/ %}. It has many partners
instead of that: itBit exchange, Gyft or Purse for shopping and BTCJam to borrow Bitcoin. (Also see: [Lending Bitcoin](/btc-lending/))

> _â€œPurse is a marketplace that connects shoppers with unused gift cards.
Shoppers pay with Bitcoins at a huge discount, and Earners liquidate gift
cards.â€_

**Something else also worth mentioning here:**

## Learned the hard way with blockchain.info:

Don't use a fake email to sign-up.

Your wallet comes with a unique, complicated User ID that you won't remember. The ID will be shown to you and it will also come to your mailbox.

Once you're logged in the wallet you have the option to go to _settings_ and set your alias that can be used instead of that ID. But **if you choose a simple alias** the system will ask you to use the original
ID on a future attempt to login from a different browser.

Now, you don't remember the ID. There is an option to have the ID sent to your email but that is indeed not possible if the email address was fake.

Still don't want use a real email address? Even if setting up one with {% aff openmailbox.org https://openmailbox.org %} takes like 20 seconds?

* Bookmark the login screen with original ID.

* Save the ID in a bit.ly.

[Up](#)


## BitGo


{% aff BitGo https://www.bitgo.com/ %} is trusted by major bitcoin trade exchanges so if you are looking for a very safe and very monitored online storage, {% aff BitGo https://www.bitgo.com/ %} might be a way to go.

There is a web client and a browser extension.

> The browser extension is in this case safer because it isn't loading your wallet from distant server where a developer could abuse your session while you are online.

On sign up with Bitgo you are asked to set up a two-factor auth, which
mitigates about 99% of hacking attempts. Each sign in is logged and the account
owner gets an email immediately.

Within a single account you can then set up multiple wallets and even add
new people to them. Each wallet can have a specific password, you don't have to
use the default account's pass. You can even add other users to manage certain wallets.

So, you can probably see why Bitgo is the
choice for businesses. All the functionalities are very useful if you really
have to manage those funds.

The web interface is a bit cranky though, especially if you use a VPN. VPNs
are sometimes slow in downloading media and scripts so the result can be your
wallets not showing up at all. It is just a glitch in the interface.

There is also one unusual thing regarding the private keys. Bitgo gives you no
seed as it uses {% aff keytern.al https://keytern.al/index.html %} to manage the recovery. You are given a PDF document with QR codes, you need to print this one.

[Up](#)

{{ site.lbc }}

<h4 id="mobile">Bitcoin Wallet as a Mobile App</h4>

Having a Bitcoin wallet on your mobile is quite popular. It is convenient,
whenever you want to tip someone scan the bar code â€“ done. But that's also the
only purpose a mobile wallet should have. Better not to store there all your
wealth... But that is better not to be stored on a single place either way.

## Bitcoin Wallets for Android

* The most popular of the â€œbrandsâ€, should we say, {% aff Mycelium https://play.google.com/store/apps/details?id=com.mycelium.wallet %}. With Mycelium you have 100% control over your private keys. The Android app is _top_, it is not a marketing thing or anything like that behind the Mycelium's popularity.

* Further brief look at Google Play and you will see a {% aff Bitcoin Wallet by Andreas Schildbach https://play.google.com/store/apps/details?id=de.schildbach.wallet&hl=de %}.

  * There are other Android Bitcoin wallets that are based on the Bitcoin
Wallet app: {% aff Blockchain.info for Android https://play.google.com/store/apps/details?id=piuk.blockchain.android %} for instance.

* The â€œbank of Bitcoinâ€ {% aff Coinbase has an Android app too https://play.google.com/store/apps/details?id=com.coinbase.android %}.

<div id="breadwallet"></div>

## Bitcoin Wallets for iPhone

* Interesting app seems to be {% aff Breadwallet http://breadwallet.com/ %}.

* While there is a {% aff Mycelium app for iOS https://itunes.apple.com/us/app/mycelium-bitcoin-wallet/id943912290?mt=8 %}, it is notable worse than the Android version. There also was a {% aff bug https://www.reddit.com/r/Bitcoin/comments/317tys/psa_warning_mycelium_for_ios_read %}. The iOS version is not even listed on Mycelium's homepage yet, but the code is on {% aff GitHub https://github.com/mycelium-com/wallet-ios %}. You see it is still actively developed.

## Mycelium Android Bitcoin Wallet

Rightly the most popular of mobile Bitcoin wallets. The Android app is _top_, it is not a marketing thing or anything like that behind the Mycelium's popularity.

Just a note to {% aff Mycelium for Android https://play.google.com/store/apps/details?id=com.mycelium.wallet %}.

* The app creates your wallet instantly.

* It will give you no recovery seed though, you have to generate the seed by using the â€Create Backupâ€ function.

* Mycelium will show you 12 words one by one. You will be then asked to type them back in to confirm you know the seed.

_See the image below, it is the top link in th menu._

{% amptall page.image[0] page.image_alt[0] %}

**As of late 2016 current Mycelium versions also include the Mycelium Local Trader which is equivalentof LocalBitcoins right inside your mobile wallet.**

{% aff Read here how to use Mycelium Local Trader https://mycelium.com/lt/help.html %}


[Up](#)

<h2 id="download"  class="exa">Bitcoin Wallet Installed on your Computer</h2>


{{ site.ads.aads }}


## The best Bitcoin wallets as a software

Bitcoin software wallets are free, open source and generally considered
better option. With software wallet you have the full control over your money.

* There is no website to go offline when you need to send money
* No third party can seize your funds (yes it still happens, ChangeTip does it if you are from a country with Bitcoin restrictions!).

With software wallets the only way someone can take your Bitcoin is through your own mistakes: Getting a malware or virus on your computer or having a very weak password.

## Electrum

{% amp page.image[1] page.image_alt[1] %}

Easiest to use: {% aff Electrum https://electrum.org/#download %}

Electrum is pretty lightweight, easy to install and intuitive to use. It is also actively maintained, there was a new version [released in February 2016](https://www.reddit.com/r/btc/comments/47p3e3/electrum_26/).

**Some of the new Electrum 2.6 Features**

* First official release of the Kivy GUI, with android APK
* New command: 'notify <address> <url>'
* **Alternative coin selection policy, designed to help preserve user privacy. Enable it by setting the Coin Selection preference to Privacy**.
* The install wizard has been rewritten and improved
* Much improved support for {% aff Trezor https://buytrezor.com?a=fany@tutanota.com %} devices...Device wipe, multiple device support etc.

**Installing Electrum Bitcoin wallet**

{% aff Get Electrum here https://electrum.org/#download %}. There are versions for all major OS.

As you open it for the first time the set up will walk you through the wallet creation.

* You can change the wallet's name, if you don't, Electrum will use *default_wallet*.

* The wallet already comes with a set (pool) of Bitcoin addresses, it's not just a single address. You will receive coins sent to any of your "receive" addresses.

* If you want to manage separate wallets you can always create another one in File &gt; New/Restore.

<h5 id="electrum-privacy">Electrum is not the greatest Bitcoin wallet for stealth security</h5>

While Electrum is fine for everyday use, it uses centralized servers and by the way it operates it is possible to tell Bitcoin addresses of the same wallet.

It is also possible to associate an IP address with the transactions.

With the amount of Bitcoin transactions it would be hell of a job to find you, but still - relying on this is security by obscurity.

If that is not good enough for you but you still want to use Electrum, generate separate wallets (File &gt; New/Restore) and use VPN when doing transactions.

## MultiBit HD

Still very easy to use: {% aff MultiBit HD https://multibit.org/ %}

The older version of Multibit used to be popular until {% aff rumors http://www.coindesk.com/multibit-user-loss-high-need-bitcoin-wallets/ %} about its security flaws started to spread. That was the Classic version though and the problem was the way the wallet's keys were
generated.

Back then the keys were a chunk of code that one needed to export and import somewhere else to restore the wallet. With MultiBit HD ([hierarchical
deterministic](https://en.bitcoin.it/wiki/Deterministic_wallet)) you get seed words that can be written on a paper. Problems recovering the wallet shouldn't come across anymore.


## Armory

More comples but more powerful: {% aff Armory https://bitcoinarmory.com/ %}

Armory is a great Bitcoin wallet for cold storage. The set up is a bit more complicated but both security and privacy is better. Unlike Electrum and MultiBit HD, Armory doesn't disclose your IP address when you make transactions.

<div style="text-align:center"><iframe frameborder="0" height="60" marginheight="0" marginwidth="0" scrolling="no" src="https://localbitcoins.com/affiliate-embed/half-banner?ref=4nq3" width="234"></iframe></div>

**Installing Armory Online**

There always is a setup process to take you through the wallet creation, so
no need to worry even if you are not a geek.

This is how to install it in online mode (NOT for cold storage).

* Armory is available for every major OS. {% aff Armory https://bitcoinarmory.com/ %}.

* Download it and select _online wallet_ to install.

* You'll first get your seed. A set of words that you want to write down on a paper. Your seed will let you recover your wallet if your computer should crash or get stolen.
  * Seed will also recover your wallet for anyone else who gets it. That means it shouldn't really see the electrons again if you want to keep it safe so don't store it in your Dropbox.

* Next important thing the installation process will come up with is password. You will use this one to make transactions. Come up with something strong and memorable, you can try diceware passwords. And again: Paper!

* Once you generate the wallet you will get a number of "receive" Bitcoin addresses. You may use either of them, the transaction will always end up in your wallet.

<h4 id="cold" class="exa">Bitcoin Wallet for Cold Storage?</h4>

{% amp page.image[2] page.image_alt[2] %}

If you want to have a kind of savings account on a laptop you don't use anymore, go ahead and get {% aff Armory https://bitcoinarmory.com/ %} on it. Armory on an offline computer is the only equivalent to a hardware wallet.

It's just that a hardware wallet is easier to use and lighter to carry around, of
course.

## What is Bitcoin cold storage

* The cold storage means that your wallet with Bitcoins lives on an offline computer.

* Then you create a _watching copy_ on a computer that is online.

* If you want to send money from your Armory wallet you'll have to sign the transaction in the offline wallet and broadcast it from the watching copy.

* With hardware wallets this process might get easier. They are carried around
more easily as well. Check out {% aff Trezor https://buytrezor.com?a=fany@tutanota.com %}, the display and buttons are there precisely because of this process.

[Up](#)

<h4 id="hardware" class="exa">Hardware wallets: Why not just a pen drive?</h4>

<iframe data-aa='114136' src='https://ad.a-ads.com/114136?size=468x60' scrolling='no' style='width:468px; height:60px; border:0px; padding:0;overflow:hidden' allowtransparency='true' frameborder='0'></iframe>

Hardware wallets are small devices that host your
Bitcoin wallet. They are meant to make it easy to have a safe _cold storage_ but being able to send transactions out of the hardware wallet, too.

* You initiate transaction on a computer
* Confirmation takes place on the secure hardware wallet device


## Why not just pen drive?

You could use a pen drive too. That will only get you a storage though, no added
security. Hardware wallets are stealth because all the sensitive processes happen inside of the wallet's hardware which is tamper-proof. You can use them on a computer infected
with virus and malware while your Bitcoin wallet will remain safe. You should even be able to restore your wallet on an infected computer, your data still should not be compromised.

If you are serious about Bitcoin, consider one. Hardware Bitcoin wallets are
the safest place to store your coins at all.

## Ledger Wallet vs. Trezor Wallet

There are currently two major players:

* {% aff Trezor Wallet https://buytrezor.com?a=fany@tutanota.com %} with plenty integrations & altcoin support.
* {% aff Ledger Wallet https://www.ledgerwallet.com/r/e274 %} with plenty shapes and flavors, even a contactless one.


## Trezor Hardware Wallet

Trezor is a bit more expensive but it comes with a display which makes it
easier to use for transactions. There is a Trezor API integrated into {% aff many platforms (merchants,
wallets and exchanges) https://doc.satoshilabs.com/trezor-apps/ %} to let you sign up directly with {% aff Trezor https://buytrezor.com?a=fany@tutanota.com %}.

* Electrum, Mycelium and MultiBit HD wallets are all compatible.

* There is also a Chrome
extension and an Android app that sniffs any transaction activity on your
{% aff Trezor https://buytrezor.com?a=fany@tutanota.com %} device.

* {% aff Trezor https://buytrezor.com?a=fany@tutanota.com %} also supports altcoins, you can even keep multiple currencies on a single device.

## Ledger Hardware Wallet

* {% aff Ledger Nano https://www.ledgerwallet.com/r/e274?path=/products/1-ledger-nano %} looks much like a naked pendrive (it comes with a package for it).

* {% aff Ledger Unplugged https://www.ledgerwallet.com/r/e274?path=/products/6-ledger-unplugged %} is contactless and looks like a credit card. The
contactless version needs last generation Android phone or contactless USB
reader to make transactions but it is much easier to carry around then another
"device" or stick.

* Any flavor of {% aff Ledger Wallet https://www.ledgerwallet.com/r/e274 %} can be integrated with Electrum,
Mycelium and others, even though it by default runs its own interface.

* There is no altcoin support nor ever will be, according to {% aff Ledger Wallet https://www.ledgerwallet.com/r/e274 %} homepage.

As for security, the basic principle is the same for Trezor and {% aff Ledger Wallet https://www.ledgerwallet.com/r/e274 %}. The only thing you have to care about is your password and recovery seed. That said, the user is indeed owner of the keys and there is no third party involved here. The wallet then takes care of all the security, meaning you can use the hardware wallet even on a computer with malware or viruses.


Out of these two bitcoin hardware wallets,
{% aff Trezor https://buytrezor.com?a=fany@tutanota.com %} has wider range of functionalities and integrations.

{% aff Ledger Wallet https://www.ledgerwallet.com/r/e274 %} on the other hand has three different types, one of them contactless in the shape of a credit card.

Now the choice depends on your preferences - whether you need the integrations or the easy-to-carry edge.

[Up](#)

{{ site.ads.ledger }}
