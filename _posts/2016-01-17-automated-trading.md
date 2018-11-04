---
layout: post
title: "Bitcoin Trading Bots: Good idea? Bad idea?"
description: "Is it a good idea to get a Bitcoin trading bot?"
categories:
 - "trading"
permalink: trading-bots/
tag: "popular"
feature: "https://c1.staticflickr.com/1/532/31900942843_2b09b93b46_o.png"
image:
 - "https://c1.staticflickr.com/1/429/32591228351_bbd06a260b_o.jpg"
 - "https://c1.staticflickr.com/1/565/32673577276_00f74fbf00_o.png"
 - "https://c1.staticflickr.com/1/717/32591229411_9defe52a87_o.png"
 - "https://c1.staticflickr.com/1/510/32591227721_0935541c98_o.png"
 - "https://c1.staticflickr.com/1/532/31900942843_2b09b93b46_o.png"
updated: 2016-06-18
---


* [Your own bot for autotrading](#automated-trading-your-own-bitcoin-bot)

* [Buying bots and trading strategies](#bots-from-strategy-markets)
  * [Strategy market](#market)

* [A free Bitcoin trading bot Gekko](#gekko) written in node.

* [Arbitrage bots](#arbitrage-bots)

* [Opportunity sniffers](#opportunity-sniffers)

* [Summary & Tools](#summary) - Explain like I didn't read.


{{ site.aads }}

You cannot help but notice how many people are searching for _Bitcoin trading bots_ nowadays.

Let me get one thing clear right from the start: Bitcoin bot is not an automagical tool that will just be making money for you. Bitcoin trading bot, as any other trading bot, is a piece of code executing commands.

* Bad commands mean bad results.

* If you write your bot well you will earn money.


## Automated Trading: Your Own Bitcoin Bot

Ideally you code the bot yourself so that you know what exactly it does.

* You invent a Bitcoin trade strategy and make it a piece of code. For instance, buy and sell based on [MACD indicator](/best-exchange-bitcoin-trading.html#technical-analysis).

* You make this strategy a code. There is an API for Python developers over at [Tradewave](https://tradewave.net/help/api/). It is free for backtesting but you will have to pay for [real money trade](https://tradewave.net/pricing).

* You now test this code on dummy data and make sure it **always** does what you want it to do.

* In order to make the bot able to trade your money you give it API keys to a Bitcoin exchange you are using.

* You get a server/computer/service that will have your bot up and running all the time, sniffing opportunities and executing them.

A lot of work. **You see automated Bitcoin trading is not quite passive income.**

## Bots from Strategy Markets

Another option.

You may use someone else's strategy so as to avoid the coding. That's possible indeed. But remember that people usually don't sell perfect strategies. When a strategy works, having everyone use it will make it stop working.

The opportunity for trade gets exhausted when everyone starts using it.

Another point is you shouldn't run a bot without having the understanding of what it does on the inside.


<div id="market"></div>

If you still want to test it, there is a strategies marketplace at {% aff Cryptotrader https://cryptotrader.org/?r=419 %}. These are strategies that can be run at  {% aff Cryptotrader https://cryptotrader.org/?r=419 %} itself for a monthly fee of $8 - $80, based on your trade volume. You will see the paid strategies on  {% aff Cryptotrader https://cryptotrader.org/?r=419 %} are quite sophisticated, but - _that does not mean these bots cannot make mistakes_.

In the long run it is a bad idea to run someone else's strategy without check when you don't understand what exactly it does. Long term, you will lose money doing so.

{% amp post {{page.image[0]}} {{page.image_alt[0]}} %}

<a target="_blank" href="/images/bestbitcoinexchange_cryptotrader.jpg"><small>Click for larger image</small></a>

**Here's why:** The caveat is that Bitcoin price doesn't behave in the same way through all times. All trading bots need to be optimized for a specific kind of behavior. That's what the **backtest** section of all automated trading platforms does (see image above).

The thing is each bot can do very well if you use it in the right kind of situation.

**Trading bots cannot do the figuring for you:** You need to know when it is the right time to use which bot.

* That said, no bot is profitable if you run it with no adjustment over a long time. Bots perform well in certain kind of trend for which they are optimized. It might go on for a week or a few months, but not forever. You need to take care of the bot, so again: _Automated trading is not absolutely passive income_.

**Trading bot** is a **good idea** for you if you ...

* need to operate many accounts on many exchanges

* do insane amounts of operations at high speed

* either know how to code or are willing to spend hours optimizing your bot

**Simply put, in most cases it will be better to simply keep up to date with the price and use limit orders. Sorry folks, there ain't no free lunches. Bitcoin bots are not here to make you money while you spend a few years sipping capirinha on the beach unaware of the rest of the world.**

<div id="haas"></div>

## HaasBot of HaasOnline

If you've never heard of the Dutch company HaasOnline and their trading bot you are not alone, not by a long shot. There is a good reason for that though.

{% aff HaasOnline https://www.haasonline.com/?ref=49 %} bot targets serious traders who are _willing to put in the hours_ and learn how to configure and use the software. There is a version 2.0 currently online but version 3.0 shall be released soon.

The possibilities are many, you can indeed configure bots for Bitcoin long, short, arbitrage or any altcoin trading schemes.

Even the interface itself can save a lot of headaches. Take a look at price levels across exchanges to do arbitrage trading:


{% amp post {{page.image[1]}} {{page.image_alt[1]}} %}

<a target="_blank" href="/images/best-bitcoin-exchange_haasbot-3_1.png"><small>Click for larger image</small></a>

Such a thing makes it easy even to execute trades manually (with some HaasBot plans, the number of bots to run is limited anyway).


{% amp post {{page.image[2]}} {{page.image_alt[2]}} %}

<a target="_blank" href="/images/best-bitcoin-exchange_haasbot-3_2.png">
<small>Click for larger image</small></a>

When it comes to a basic trading bot setup **without testing**, that can be done quite fast. See the video below.

It shows how to set up a very basic bot ({% aff HaasOnline https://www.haasonline.com/?ref=49 %}) to do margin trading on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}. It uses the [DoubleMargin](https://wiki.haasonline.com/Leveraged_Trading_Bitfinex#Single_Margin_Trading_Module) setup which means the bot will do both long and short trades as the opportunities come. (So, if you want to hodl Bitcoin and are not interested in fiat profit, you should opt for the [SingleMargin](https://wiki.haasonline.com/Leveraged_Trading_Bitfinex#Single_Margin_Trading_Module) and only allow shorting.)

* When a buy signal comes, bot will close short position (if there is one) and open a long one. You can only have one position a time on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %} anyway.

* When a sell signal comes, bot will close the long position and open a short one.


All knowledge you need to set up this bot _untested_ is basic working knowledge of technical analysis as you have to choose your indicator.

<iframe src="https://www.youtube.com/embed/oQa6qmsQ_hc" frameborder="0" allowfullscreen style="width:100%;height:auto;min-height:250px"></iframe>

Be careful though, a correct set up might require a combination of indicators that depend on if you want to go long or short. Remember, pump and dumps occur every now and then - the market is manipulated. Some indicators react on this too late and so will a bot relying on them.

You can also set a few other things that are not compulsory. Quite a popular feature of {% aff HaasBot https://www.haasonline.com/?ref=49 %}  is what they call "insurance", for instance "Only execute trade if the profit pays the fee".


{% aff HaasBot https://www.haasonline.com/?ref=49 %} is available as a web app or on desktop for Windows, in beta for Linux and OS. The license runs out every three months, as for the cheapest one costs 0.22 BTC... For anyone who trades at least a little such an amount is generated quite easily.

<h6 class="exa">
<a style="color:white" href="https://www.haasonline.com/?ref=49" rel="nofollow">Get HaasBot License Here</a>
</h6>

## Where to run a Bitcoin trading bot

The {% aff HaasBot https://www.haasonline.com/?ref=49 %} runs primarily on Windows.

The minimum requirements to run {% aff HaasBot https://www.haasonline.com/?ref=49 %} are quite high, running the bot on a VM on your laptop will consume a lot of resources.

It is generally better to get a Windows VPS and run the bot from there. Windows VPS are more expensive than Linux equivalents since you need to pay for a proper license too. You will be able to get some good deals with annual billing. This way, expect to pay about $8 monthly for your VPS.

By the way, running Windows or Wine on cheaper Linux servers tends to be forbidden.

**Windows hosting companies to check out (they accept Bitcoin):**

* {% aff HostUs https://my.hostus.us/aff.php?aff=1064 %} has good plans but only for servers in USA. What are the legal implications of that we can only guess. Their TOS don't forbid trading servers though.

* {% aff RockHoster https://cloud.rockhoster.com/billing/aff.php?aff=42 %} is company registered in India and has cheap Windows VPS too. They have multiple offshore locations.

**Requirements to run the Windows {% aff HaasBot https://www.haasonline.com/?ref=49 %}:**

* Dual-core processor (1,6GHz and up)
* 2 GB random access memory
* Stable internet connection (minimum 1mbit download)

If you are looking to get a VPS get more than the minimal requirements to avoid future issues. Not all companies will return your payment if they cancel your account due to too-high usage (see TOS of {% aff RockHoster https://cloud.rockhoster.com/billing/aff.php?aff=42 %}).

{{ site.ledger}}

<div id="gekko"></div>

## Gekko, the free Bitcoin trading bot

Gekko has been around for a very long time and is still in active development/improvements. Yet you won't hear about it very much in trading communities, perhaps apart from occasional mention on Reddit.

If you are looking for a bot that is **not** a full-feature trading platform with fancy charts and the like, Gekko will be the right thing for you. It is just a command line node.js application.

As with every good algo trading software you cannot simply download Gekko and run it. To use Gekko as a true Bitcoin trading bot you first need to configure it.

> The basic configuration is simply declaring which exchanges you want to trade on.Gekko currently supports Bitstamp, Kraken, Bitfinex, Btc-e, Poloniex and BTCC (formerly called BTCChina).

> Configuring an exchange will only watch your selected market. What you need to trade with Gekko is enabling plugins, or writing your own. All the trading functionality depends on Gekko plugins.

Both to run Gekko as an advisor or as a trading script needs a plugin - [here is the list of them](https://github.com/askmike/gekko/blob/stable/docs/Plugins.md). One of the Gekko plugins, paper trader, is for live strategy testing - it reports profits and losses it would make if it wasn't a dry run.

**Here is the Github link to Gekko and to the docs:**

* [Download Gekko from GitHub](https://github.com/askmike/gekko)
* [Gekko manual: Installing Gekko on Windows](https://github.com/askmike/gekko/blob/stable/docs/installing_gekko_on_windows.md)
* [Gekko manual: Configuring Gekko](https://github.com/askmike/gekko/tree/stable/docs/Configuring_gekko.md)


## Arbitrage bots

Using [Bitcoin arbitrage bots](/bitcoin-arbitrage.html#bots) is generally a simpler strategy. In the link you will find two free arbitrage bots. One is an Android and iPhone app. The other is a piece of Python code. You can use it as a sniffer for reference or it can actually do the trade for you.


**Your own Bitcoin arbitrage bot**

If you are thinking about writing your own bot, you probably can figure out that arbitrage bots are both _easier to code_ and to use since the only thing they evaluate is price difference across exchanges. The need to adapt the bot for a trend is not the most important bit here.

That also makes automated Bitcoin trading with them somewhat safer, even long term.

You can be sure though they are getting used more and more since the arbitrage opportunities are getting poorer over time: _It won't work as soon as everyone starts doing it_.

Still: It might seem old-fashioned but if you are not quite seasoned executing trades manually is less risky if you are not a programmer willing to be immersed in code all day long.

* Traders often start with manual trading and start using bots a bit later on, no reason for rush.

* Even if you run a bot, keep some money aside for manual trades.

* Never give a bot money you cannot afford to lose.

### It is important to realize no profit comes without effort. Either keep taking care of the code/bot or keep taking care of the opportunities as they happen.

You can configure the mighty {% aff HaasOnline https://www.haasonline.com/?ref=49 %} trading bot for altcoin arbitrage too.

## Opportunity sniffers

Using an arbitrage or opportunity sniffer is risk-free. Sniffers will inform you but will not execute trades for you.

They are simply an app that will detect a possible opportunity.

* Arbitrage apps will compare selected exchanges against each other to let you know the price difference.  

* Opportunity sniffers are simply Bitcoin price tickers with alarm functionality.

You then decide yourself whether you want to trade or not.

The most convenient way is to set up basic text (SMS) or email notification.

* You can have a price notification on Bitstamp for free but it only works as a one-time text for quite a distant price level.

* Dedicated platforms have more advanced notification (see ”Plans” on {% aff CryptoTrader https://cryptotrader.org/?r=419 %}).

* **There are free apps that support notifications as long as you are online.**

  * [Bitcoin Paranoid (Android)](https://play.google.com/store/apps/details?id=br.eti.fml.satoshi) is probably the best. You choose the exchanges, it keeps flushing their BTC price into the top bar. In the alarm set up you can choose the price difference the app should notice. It will make some sound.

  * [Bitcoin ticker widget (Android)](https://play.google.com/store/apps/details?id=st.brothas.mtgoxwidget) - similar alternative, not so funny language.

<div style="width:50%;margin:0 auto">
{% amptall post {{page.image[3]}} {{page.image_alt[3]}} %}
</div>

Once you get the notification, go check out the situation in some good mobile trader app.

We have already recommended [TabTrader](/bitcoin-trading-basics.html#mobile) in the _Bitcoin Trading Basics post_. You can feed the TabTrader app your API keys too to trade real money from your mobile. There are more apps like this, for example zTrader with {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}-ish interface. ([Bitcoin Trading Basics / Mobile Trading](/bitcoin-trading-basics.html#mobile))

TabTrader is so good because its charts are quite fine. It lets you see all common indicators so that with a bit of practice you will not need to double check on a laptop screen.

On the image below see the default TabTrader screen with data from a few Bitcoin exchanges. You get the chart by clicking one of the tabs in the default screen. You can then choose your favorite indicators, you see the typical MACD here.

{% ampdouble post {{page.image[4]}} {{page.image_alt[4]}} %}

<h4 class="exa" id="summary">TL;DR - Bitcoin trading bots</h4>

Bitcoin trading bots need maintenance.

Additionally, you need to either buy or build one and you might need to rent server space for it to run.

_If you though of it as of long-lasting income with no investment and effort, you should forget it._

## If you decide to do the work yourself.

* Get accounts on several Bitcoin exchanges that are fit for trading

  * [Bitcoin Exchanges Good for Trading](/best-exchange-bitcoin-trading.html#exchanges)

* Get an app to trade on mobile

  * [Bitcoin Trading Basics / Mobile Trading](/bitcoin-trading-basics.html#mobile)

* Get a mobile bitcoin wallet to manage your funds

  * [Bitcoin Wallets / Mobile Apps](/best-bitcoin-wallet.html#mobile)

* Get an app to notify you on price swings

  * [Bitcoin Checker (Android)](https://play.google.com/store/apps/details?id=com.mobnetic.coinguardian&hl=en) supports 80 different exchanges for which you can set an alarm. Bitcoin Paranoid is a bit more intrusive option.

  * [Bitcoin Paranoid (Android)](https://play.google.com/store/apps/details?id=br.eti.fml.satoshi) is probably the best. You choose the exchanges, it keeps flushing their BTC price into the top bar. In the alarm set up you can choose the price difference the app should notice. It will make some sound.

  * [Bitcoin ticker widget (Android)](https://play.google.com/store/apps/details?id=st.brothas.mtgoxwidget) - similar alternative, not so funny language.

* Make the decision on whether to trade or not yourself

## If you are experienced in technical analysis and want to run bitcoin trading bots.

There is no doubt bots can execute tasks much faster than a human would ever be able to. But it is also true that bots need to be configured, tested and adjusted from time to time. If you are a good trader chances are trading bot will help you, if you really learn how to use it.

* Get a legit trading bot. A good one was designed by a Dutch company {% aff HaasOnline https://www.haasonline.com/?ref=49 %} and can be bought by 3 months subscription cycles. It is an actively maintained project available on all OS (Windows primarily, Mac OS and Linux if you ask for access). Version 3.0 was released in January '16 and is being tested now.

* The cheapest beginner license on {% aff HaasOnline https://www.haasonline.com/?ref=49 %} costs 0.22 BTC. If you want to learn using a bot and don't want to code one yourself, {% aff HaasOnline https://www.haasonline.com/?ref=49 %} is about as most legit solution you can get.

* {% aff HaasOnline https://www.haasonline.com/?ref=49 %} people state themselves in their FAQ that {% aff HaasBot https://www.haasonline.com/?ref=49 %} is not a one-click money making machine so keep that in mind.

* You will also need some solid hardware to run the HaasBot ([See this section for advice](#where-to-run-a-bitcoin-trading-bot)). You will need either a good Windows computer that you don't use or a VPS.
  * Dual-core processor (1,6GHz and up)
  * 2 GB random access memory
  * Stable internet connection (minimum 1mbit download)


<hr>
