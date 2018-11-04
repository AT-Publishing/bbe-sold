---
layout: post
title: "All About Bitcoin Lending"
description: "All you need to know to lend Bitcoin and earn interest: Margin swaps on Bitfinex, lending bots, Poloniex lending, BTCJam."
categories:
- "bitcoin lending"
permalink: btc-lending/
tag: "popular"
image:
- "/images/btc-loans/bitfinex/btc-lending1.jpg"
- "/images/btc-loans/bitfinex/btc-lending2.jpg"
- "/images/btc-loans/bitfinex/bitfinex-lending-reports1.jpg"
- "/images/btc-loans/bitfinex/bitfinex-lending-reports2.jpg"
- "/images/btc-loans/poloniex/poloniex-lending.jpg"
- "/images/btc-loans/poloniex/poloniex-lending1.jpg"
- "/images/btc-loans/poloniex/poloniex-lending-report.jpg"
- "/images/btc-loans/poloniex/poloniex-lending-bot.png"
- "/images/btc-loans/poloniex/active-bot.jpg"

image_alt:
 - "Bitcoin interest - Bitfinex Lending"
 - "Bitcoin interest - Bitfinex Lending"
 - "Bitcoin interest - Bitfinex Lending report"
 - "Bitcoin interest - Bitfinex Lending report"
 - "Bitcoin interest - Poloniex Lending"
 - "Bitcoin interest - Poloniex Lending"
 - "Bitcoin interest - Poloniex Lending"
 - "Poloniex lending bot"
 - "Poloniex lending bot"
chart:
- "/images/btc-loans/charts/poloniex-lending-ideal.png"
- "/images/btc-loans/charts/real-poloniex-lending.png"
- "/images/btc-loans/charts/approx-poloniex-lending.png"
- "/images/altcoins/ether.png"
feature: "/images/btc-loans/bitfinex/btc-lending2.jpg"
updated: 2016-04-03
---

<iframe data-aa='114136' src='https://ad.a-ads.com/114136?size=468x60' scrolling='no' style='width:468px; height:60px; border:0px; padding:0;overflow:hidden' allowtransparency='true' frameborder='0'></iframe>


* [Is Bitcoin lending risky?](#risk-involved)

* [Bitfinex Margin Funding](#bitfinex-lending) - How to lend money on Bitfinex. Be careful about the interests.
  * [How to start lending on Bitfinex](#how-to-lend-money-on-bitfinex)
  * [How much will you earn?](#bitfinex-margin-lending-interests)
    * [Bitfinex lending bots](#bitfinex-lending-bots) - Free bots for loans management
  * [Always check your payouts](#check-your-payouts)
  * [Dummy numbers](#bitfinex-dummy-numbers)

* [Poloniex Lending](#poloniex-lending) - Lending Bitcoin and other cryptocurrencies on Poloniex.
  * [How to start lending on Poloniex](#how-to-lend-money-on-poloniex)
  * [Interest rates on Poloniex](#interest-rates-on-poloniex)
  * [High interest rates won't always earn you more](#charts)
    * [Poloniex lending bot](#poloniex-lending-bots) - Free lending bot for Poloniex
  * [Always check your payouts](#check-your-payouts)
  * [Dummy numbers](#poloniex-dummy-numbers)

* [Bitcoin P2P Lending](#bitcoin-p2p) - Lending Bitcoin outside of exchanges.


<iframe data-aa='114136' src='https://ad.a-ads.com/114136?size=468x60' scrolling='no' style='width:468px; height:60px; border:0px; padding:0;overflow:hidden' allowtransparency='true' frameborder='0'></iframe>

## Risk involved

If you lend money in any way: Yes it is risky.

### Margin Trading

If you lend {% aff Bitcoin on trade exchanges https://www.bitfinex.com/?refcode=5egV78YtlC %}, your money goes on margin trading.

**Risk of lending to margin traders**

If a trader borrowed to trade but the market moves against them, at some point the position will be force-closed by the system.

But it can happen that the market will move too fast for the system to close the position in time. In that (unlikely) case the trader would get a negative balance. The borrowed funds would not be repaid which means the lender loses too.

_BTCUSD market is typically not so volatile. Altcoin trading can pump and dump tragically though._

**Preventing this risk?**

There is no way to prevent this risk. On top of that, on trade exchanges all lending is processed by lending bots. You cannot choose whom you lend the money:

* A trader places margin trade order with a maximum interest rate above which they don't want to go.

* The system funds this order from available margin loan offers. It chooses the cheapest way to fund the trade.

* The position is either closed by the trader with profit/loss or force-closed by the system. If nothing goes wrong in the system the position is closed at the point where available funds still cover the trade expenses.

The only way to minimize the risk is to _split your money and lend different currencies on different places_.

### Peer-to-peer Bitcoin Loans

Even low risk plans count on defaults: There will always be someone who doesn't pay back.

That's why autoinvest bots split your deposit into very small chunks and lends these.

You need to do a very high amount of contracts to get the statistical effect and reach the expected value.

<div id="#bitfinex-lending"></div>

## Bitfinex Margin Funding

If you open a trading account on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %} you automatically have access to _exchange trading, margin trading and margin funding_.

The latter are indeed Bitcoin loans to other traders.

{% amp post {{page.image[0]}} {{page.image_alt[0]}} %}

On {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %} you can lend out USD, BTC or LTC. You can choose the section on the Margin Lending tab, see picture above.

It makes sense, people borrow to go long (USD) or short (BTC) and there are a few altcoin traders too.
(Though on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}, if you are used to the BTCUSD market, you should know the altcoin volumes are lower.)

###  How to lend money on Bitfinex

By default you get three different types of wallets on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}:

_exchange, trading, deposit:_

 {% amp post {{page.image[1]}} {{page.image_alt[1]}} %}


* To lend money you need to move the currency you want to lend to your **deposit wallet**. Transfer between your own wallets is free and instant.

* Then go to _Margin Funding > [currency]_. Check out the common interest in the order books in lower section of the page and set your rate to something reasonable. You want your money to actually get borrowed.

* The listed rates are already in percentage per day.
  * The percentage changes, sometimes it's too peaceful around and people want to borrow cheap. Sometimes Bitcoin is rallying and people are willing to pay more to get a loan, expecting a thick profit anyway.

You can either choose to lend your money at once and get them back once the contract is over, or you can choose to _autorenew_. This way your money will be offered for loans again as soon it is available.

Your interest will be auto-offered too. That means your profit should grow since you will be offering more and more money over time.

_Autorenew on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}:_

{% amp post {{page.image[0]}} {{page.image_alt[0]}} %}

* The autorenew option doesn't guarantee your money will be in a loan at all times though. Sometimes interest rates drop and your pre-set rate will get too high for the market situation.

### Funds in loans are blocked

**During the time your funds are borrowed they are blocked. You will not be able to stop the loan if you get to need the money.**

**The funds will be still shown in your total balance in deposit wallet but not as available balance.**

* If you want to lend out some money without caring about it too much you can set fixed rate (something average) and autorenew.

* When you decide it's good time to stop doing that, turn that autorenew off and wait for remaining contracts to finish.

### What are hidden offers

If you have a lot of money that you want to chuck in {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %} lending you can opt for hidden offer.

* Hidden offers are still regarded by the system but are not listed in the order book. That prevents other people from setting a rate a tad lower than yours and picking offers before you.

* The fee on hidden offers is higher (18% instead of standard 15% fee in interest earnings that is charget by {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}.)

###  Bitfinex margin lending interests

By and large on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %} you are quite well off if you lend out USD. To lend out BTC or LTC, you will find the interest rate is typically very low.

<pre>
Interest rates for lending out USD are fairly high.
You can expect somewhere between 0.1% and 0.5% per day.
The rates for lending out BTC and LTC are,
on the other hand, usually very low.
Around 0.005% per day is "normal".
</pre>

([Bitfinex Wiki](http://bfxwiki.everdot.org/Lending_%28Contracts_for_difference%29))

### Bitfinex Lending Bots

There is a PHP bot for lending management making sure your money is out at the high possible rate. Since the script is in PHP you can easily run it from a web server if it's secure enough. [Download from GitHub](https://github.com/HFenter/MarginBot).

If you don't like PHP, there is another lending bot written in Go. [Download here](https://github.com/eAndrius/BitfinexLendingBot).


###  Check your payouts

There have been rumors on Reddit that {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %} underpays margin funding earnings. It occurred repeatedly, [the most recent post is from January 2016](https://www.reddit.com/r/BitcoinMarkets/comments/401dne/is_bitfinex_underpaying_margin_funding_again/?ref=readnext_7).

_As you know, what is on Reddit is always true /s._

Nonetheless it is a good idea to check your earnings in any case.

Since there are records of all your transactions you don't need to check your interest earnings very often like every week. There will always be an opportunity to contact the support.

<div style="text-align:center;">
    <a rel="nofollow" target="_blank" href="https://www.ledgerwallet.com/r/e274">
    <img alt="Ledger Wallet protects your bitcoins" src="https://www.ledgerwallet.com/images/promo/ledger-468x90-01.jpg">
    </a>
</div>

**How to check Bitcoin interest earnings on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}**

{% amp post {{page.image[2]}} {{page.image_alt[2]}} %}

* Click on your username. In the dropdown menu, choose _History and Reports_.

* It will get you to a site with links to the web versions of reports. There are all your exchange trades, margin trading, used margin funding and offered margin funding. To check interest earnings you want offered margin funding reports.

* Your offered funding is divided into used and unused loans. You are supposed to be earning interest on all money that has ever been borrowed by a user. If the user actually traded the money makes no difference.

{% amp post {{page.image[3]}} {{page.image_alt[3]}} %}

* On the right hand side of each report is an icon that will export your data into CSV so that you can manually recalculate the rates.

* Remember that the rate is already a percentage per day. {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %} takes a fee of 15% on your interest earning (or 18% if the loan offer was hidden). If you signed up with a referral code this fee will be lower by 10%.

* If you calculated your expected return beforehand with correct interest rate and all fees but your expected return is still lower, check if your money was used all the time through. Chances are there were days your money was just sitting there not getting borrowed.

### Bitfinex: Dummy numbers

**Started with: $5000**  

Offer funding for 2-30 days max, autorenew, fixed rate 0.1% daily.  

* Part of your funding gets borrowed by someone who requested $4000 for 30 days. The money sits somewhere reserved for 30 days, earning your interest.

* Rest goes into smaller loans and is not borrowed at all times.

Your interest is `4000*(0.001*30-0.001*30*0.15)=$102` after fees. Plus some change from the $1000 on smaller loans.

_Earned: ~2% monthly profit_ (Not bad.)


**Started with: 5BTC**  

Offer funding for 2-30 days max, autorenew, fixed rate 0.005% daily.  

* Your bitcoin gets into smaller contracts, borrowed for 20 days in total.

Your interest is `5*(0.00005*20-0.00005*20*0.15)=0.00425 BTC` after fees.

_Earned: ~0.09% monthly profit_ (Not much.)

<div id="#poloniex-lending"></div>

<iframe data-aa='114136' src='https://ad.a-ads.com/114136?size=468x60' scrolling='no' style='width:468px; height:60px; border:0px; padding:0;overflow:hidden' allowtransparency='true' frameborder='0'></iframe>


## Poloniex lending

You might have several reasons to want to lend out Bitcoin and not USD.

* In some countries, Bitcoin earnings are non-taxable

* You are a long term Bitcoin holder

* You don't want to pay out via bank from an exchange. By converting coin into fiat you are taking a position (hoping you will be able to buy Bitcoin back as cheap as originally one day in the future)

For those of you who want to work with cryptocurrencies only {% aff Poloniex https://poloniex.com %} will be the best choice.

Poloniex is an estabilished exchange for altcoin trading.

Many markets over there, and a lot of money to be made or also lost.


<div style="text-align: center;float: center;">
    <iframe frameborder="0" height="60" marginheight=
    "0" marginwidth="0" scrolling="no" src=
    "https://localbitcoins.com/affiliate-embed/half-banner?ref=4nq3"
    width="234"></iframe>
</div>


**Altcoins might be riskier since altcoin markets are at time very volatile.**

* [Remember lending on a volatile market is not risk free.](#risk-involved)

* On the other hand, higher risk also means the chance of higher profit.

* Interest rates on Bitcoin loans Poloniex are much higher than on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}

### How to start lending on Poloniex

Your Poloniex account comes with three sets of wallets for all currently listed coins:

_exchange, margin trading and lending_

* To start lending, transfer some Bitcoin into your _lending_ wallet.

* Transfers between your own wallets are executed immediately (no waiting for confirmations) and have no fee.

{% amp post {{page.image[4]}} {{page.image_alt[4]}} %}

Switch to the _lending_ tab, you should already see your balance there.

{% amp post {{page.image[5]}} {{page.image_alt[5]}} %}

If you check out the interest rates, you see they are not bad.

* Either lend all at once or segment the amount into blocks of different interests rates.

* The latter might help your offers get filled as rates fluctuate.

* Choose if the loan offer should autorenew or not.

That's it. The loan system is automatic, you cannot choose whom you lend.

* A trader places margin trade order with a maximum interest rate above which they don't want to go.

* The system funds this order from available margin loan offers. It chooses the cheapest way to fund the trade.

* The position is either closed by the trader with profit/loss or force-closed by the system. If nothing goes wrong in the system the position is closed at the point where available funds still cover the trade expenses.

### Interest rates on Poloniex

To lend out Bitcoin you will be OK with a rate of 0.1% - 0.6%. See

Yes, that's what you get for lending fiat on {% aff Bitfinex https://www.bitfinex.com/?refcode=5egV78YtlC %}.

Remember that on Poloniex, Bitcoin is _the fiat_. Poloniex only handles cryptocurrencies and Bitcoin is the base currency of majority of the trades.

<div id="charts"></div>

### Why high interests won't always earn you more

So you might get lucky and get a loan offer filled that has a daily rate of 0.88% and contracts for 60 days. Good on you, but to count on this is not very wise.

Usually the daily interest rates will oscillate, depends how lively the altcoin trading is. It has been more lively recently but the rates still oscillate. Also, most traders are after quick profit. They will borrow for 2 days, after that the lending system looks for a new trader that would borrow your funds.

In an ideal world your earnings would simply grew with the interest rate you offer. Your loan offers would get filled every day, your money would never stop earning, you could dictate the interest rate and there would always be a borrower.

{% chart post {{page.chart[0]}} %}

_Chart 1: Ideal lending earnings._

In the real world though your money will never be earning at all times. If you set your interest rate low, like 0.12%, you have a fair chance you will hit full 30 days activity. The inactivity is higher if your suggested interest rate is higher.

{% chart post {{page.chart[1]}} %}

_Chart 2: Lending earnings that are a bit closer to reality. You see that doubling the rate will not earn you twice as much because the offer will be unfilled for more days than a cheaper offer._

So, in any situation there will be an interest rate that will give you best returns over the timeframe, and it will not be the highest possible interest rate. You can imagine it similar to _Chart 3_, but note that this is just an example. The curve shows what your monthly earnings would be if the number of days where your loans are active depends on the interest rate by a simple linear relationship. With the dummy numbers used here, your maximum earnings would be with an interest rate of 0.5% daily.

{% chart post {{page.chart[2]}} %}

_Chart 3: Dummy numbers in action._

In some situation it might be better to stick with an average interest rate and just keep it open with autofill, but you might as well differentiate and always keep some money to lend at high rates. In case of a spike these offers will get filled but for the most part the money will sit there doing nothing.

<div id="no-bot"></div>

**Dummy numbers once again - What kind of returns are to see?**

These are real returns after one month of lending without any lending bot. The account was simply checked once in the morning and once in the evening. All money went into lending, none was traded.

<pre>
Initial balance: 5 BTC
Final balance: 5.1271266 BTC
Monthly earning: 2.54%
Average daily interest: 0.08%
</pre>

You see that this could possibly be the worst lending result ever - the daily interest was on average far below where the coins were lent. That means most of the time the money was sitting there, not provided in a loan. Good news is that since interest rates on Poloniex rarely drop below 0.1% you will see results better than this with help of a lending bot.

### Poloniex lending bots

<iframe data-aa='114136' src='https://ad.a-ads.com/114136?size=468x60' scrolling='no' style='width:468px; height:60px; border:0px; padding:0;overflow:hidden' allowtransparency='true' frameborder='0'></iframe>


As ideal as it gets.

While it is not feasible to check the current interest rates all the time you can have a bot that will do that for you. It is a python code that will try to spread your money in your lending wallet across the lending book offers. It doesn't guarantee you will always get the highest possible rate but it will help to spread your money so that you will pick up the spikes.

The bot was posted on [Reddit](https://www.reddit.com/r/BitcoinMarkets/comments/3a595w/i_wrote_a_lending_bot_for_poloniex/), code is available for free on [GitHub](https://github.com/Mikadily/poloniexlendingbot).

**The Poloniex lending bot in action:**

On the first run it will ask you to edit a config file, filling in your API key and secret.

You can also change the default minimum and maximum acceptable interest rate and the amount of single offers to split your lending equity into. _Do change the minimum_, at the very least, the defult value is some 0.06% which with the boom of altcoin trading now is far too cheap.

{% amp page.image[7] page.image_alt[7] %}

The bot keeps waiting and calling the exchange every 60 seconds. If there is some money returned to your lending wallet it will attempt to lend them. As it makes a lot of offers that are to high to be immediately filled you have to wait a few minutes.

The lending book updates every minute, to be honest the bot gives you better chance to hit the spikes. Placing a high offer first when _you_ see it in the web book is often already too late.

This is the result  - all offers taken, rates are fine (1.498%, right?!). The default 2 day length of loan was changed by the bot to 60 days.

{% amp page.image[8] page.image_alt[8] %}

You can kill the bot once your money is borrowed, it only _places_ the orders and it is not necessary to keep the bot running to have the orders active. But with the bot off you might miss returned money that could be lent again right away. It is certainly better to keep the bot running.

_This is one of the ways that is as close to Bitcoin passive income as it gets. Do the math though, if you (realistically) earn 5% netto per month, you still only earn 0.5 BTC on each 10 BTC you lend._



### Check your payouts

There have been **no** rumors about Poloniex on Reddit. Still, it is a good practice to check if you are getting paid what you earned.

On Poloniex you can indeed view your full trading history. Your lending reports are part of it:

* Click on _Orders_ in the upper right corner and choose to see _Trading History_.

* Be default your exchange trading history will show up. Use the dropdown to select _Loan Earnings_.

* Export it into CSV (_Export complete trade history_)

{% amp post {{page.image[6]}} {{page.image_alt[6]}} %}


### Poloniex: Dummy numbers

**Started with: 5BTC**  

Offer funding for 2-30 days max, autorenew, fixed rate 0.13% daily.  

* Your bitcoin is borrowed at all times. (In the real world it might not be.)

Your interest is `5*(0.0013*30-0.0013*30*0.15)= 0.16575 BTC` after fees.

_Earned: ~3% monthly profit_ (Fine, isn't it?)


<div style="text-align:center;">
    <a rel="nofollow" target="_blank" href="https://www.ledgerwallet.com/r/e274">
    <img alt="Ledger Wallet protects your bitcoins" src="https://www.ledgerwallet.com/images/promo/ledger-468x90-01.jpg">
    </a>
</div>

<div id="bitcoin-p2p"></div>

## Bitcoin P2P Lending

Ok, there are some people out there who don't like the fact that Poloniex needs no verification and that Bitfinex is a Hong Kong company with servers in Milan, Italy. To some people, these things are just _dodgy_.

It is true that apart from borrower defaulting on payback you are also exposed to the risk that the exchange will exit scam, get hacked, go titsup and so on.

(BTW. The danger of your account getting hacked is low enough if you use 2FA. Either way, people wouldn't be able to steal anything that is tied in a loan from your account.)

So, there are a few reasons to keep some of your money in other institutions as well.

If you want to diversify and offer loans outside of trade exchanges and make sure some of your money will not be used for speculations, you can try places like [BTCJam](https://btcjam.com/).

**To invest Bitcoin you don't need to get verified.**

* You can either choose your borrowers one by one or opt for _autoinvest_.
  * Autolending will split your deposit into **100-150 chunks** and lend one by one.
  * You get to choose the plan based on the risk involved - people are grouped A-D based on their risk level.
  * Some people will always default so you don't really want to put all your money on one person.
  * Even with autoinvest plans you can still choose preferred length of loans. Shorter loans might get you to cycle your capital more. It is a time-domain layer of diversification.

* Most people go for the moderate risk plan that should get you about 10% return.
  * Have you checked the risk levels? Basically people get labeled less risky if they sent in some ID. That's why even low risk plan calculates with quite a high number of people who will never pay back.

* Your money will not be earning at all times.
  * On BTCJam you don't set your own interest rate, you are autoinvesting tiny amounts of money into everything that sent in an ID (That is, with moderate risk plan. With high risk plan you give some money to everything that asks).
  * But each loan request has a time window where it either gets enough funding or not.
  * Since people usually invest small amount of money into each person, many loan requests will not be filled.
  * Unfilled requests are canceled.
  * Your money is just sitting there, not earning an interest.

________________


<div id="eth-update"></div>

### Update 3 April '16

{% chart post page.chart[3] %}

Historical data of [coinmarketcap](https://coinmarketcap.com/). Ethereum collapsed as everybody stopped believeing in the bubble, now it is only doing small movements. Much like MaidSafeCoin or Factom, for that matter.

| Snapshot           | mil. USD | price USD |
|--------------------|----------|-----------|
| February 28, 2016  | 495      | 6.4       |
| March 06, 2016     | 880      | 11.4      |
| March 13, 2016     | 1104     | 14.2      |
| March 20, 2016     | 821      | 10.5      |
| March 27, 2016     | 858      | 10.9      |
| April 03, 2016     | 915      | 11.6      |

 So what more does it say than that the market cap and price are correlated?

 Well, that no one is trading!

 All altcoin volumes dropped and Bitcoin has been boring lately anyway. Where do you think all the coins went? Not to Bitcoin markets indeed.

 Large part went to lending, where else. Interest rates on Poloniex dropped roughly one decimal place.

 **People, I know it's a drag but someone will have to do the hard work of actually trading.**

[Have some inspiration about value of altcoins.](https://www.altcointrading.net/value/)

_________________
