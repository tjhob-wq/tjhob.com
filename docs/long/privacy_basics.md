# Privacy Basics (as of 2025-01)

Here are some privacy thoughts and recommendations, specifically for less tech-y people who just want to use tech and not be constantly stalked by every site, bro, cop, and advertiser on Earth. If you're not sold on why that should be important to you, [this](https://ideas.ted.com/why-online-privacy-matters-and-how-to-protect-yours/) may help. It's also worth remembering:

- Things that used to require a warrant for police to get at, they are legally allowed to purchase from large data clearing houses and use against you.

- What is legal / not a big deal for employers is very likely to change significantly in the near future. Your milquetoast take that climage change is bad, or that certain politicians suck, may become a fireable / jailable offence with little-to-no warning.

## Basic philosophy

- Think about who you're trying to keep your information private from. Big tech companies vs. individuals intent on harming you vs. hostile governments are very different things. This list is mostly for "general privacy for normal humans". If you have other challenges let me know and I'll try to point you in the right directions... but it does get complicated fast.

- Privacy and security is more important than convenience. Think about the amount of time, money, frustration you're willing to devote to the process. Are you willing to change email addresses? To switch phone OS? Switch to Linux on your computer? Both of these can be big wins for privacy, and full of frustrations and learning new technical things. It's better to have "good enough" privacy tools that you actually use than "better" privacy tools that you don't.

- I'm trying not to do details on configuration on this list, but configuration is important! Happy to answer questions or point people to better resources if anyone adopts any of this.

- Some things are worth paying for. Especially things that protect your privacy. When dealing with for-profit companies, stick to those that commit to providing value directly to customers in exchange for direct payment. Most terrible things that happen in privacy these days are driven by trying to monetize "free" services (though plenty of paid services also do this to "get a little on the side"). Stick with reputable companies recommended by groups like the EFF, ACLU, etc.

- There are diverse opinions on this stuff. Excellent lists (that I disagree with on some points, but are WAY more thorough) are available at [EFF](https://ssd.eff.org/) and [Privacy Guides](https://www.privacyguides.org/en/).

## Easy recommendations

- Search engine: [DuckDuckGo](https://duckduckgo.com/) has been my only search engine for years, it's vastly better than Google at this point, and has less intrusive ads, without all of the creepy tracking and surveillance. You can just change this in your browser settings and feel a little better about people being able to read your search history.

- Desktop browser for general use: [Librewolf](https://librewolf.net/) is a privacy focused Firefox fork, but behaves like a normal browser. I suggest using it with the Ublock Origin, Privacy Badger, and Facebook Container extensions. If you have a password manager, their extension as well. The Facebook Container extension uses a nice Firefox feature that allows you to segment your browsing data so that, say, your "Banking" tabs don't share cookies with your "Social Media" tabs without having to go to private browsing all of the time, further complicating tracking you. The fewer other extensions you add, the better. Configuring a browser for privacy should be covered below if I remember. [Vivaldi](https://vivaldi.com/) is also a good choice if you need compatibility with Chrome, but I'm not as familiar with it.

- Desktop & Mobile browser for sensitive browsing: [Tor Browser](https://torproject.org/) Tor is a complicated topic, but it's the best we've got right now for evading surveillance and censorship. It's not a top recommendation for a daily driver as it tends to be slow and a lot of sites block known Tor nodes. [This video](https://neat.tube/w/6HDQH1wnTACKFHh2u1CRQ5) explains pretty well the differences between Tor, VPN, and what each does (and doesn't) protect you from. [The Tor FAQ](https://support.torproject.org/faq/staying-anonymous/) has more details.

- Phone browser: [DuckDuckGo](https://duckduckgo.com/duckduckgo-help-pages/get-duckduckgo/browser/) or [Vivaldi](https://vivaldi.com/) (though again I'm not as familiar with this and it's best if you need something that is only supported in Chrome derivitave browsers). I recommend having the browser clear everything frequently. It takes some getting used to, but helps prevent a lot of random tabs collecting and data sharing between sites.

- Uninstall phone apps, as many as you can. When you use a web browser to access things there are a number of privacy and security restrictions in place. Phone apps can do a lot more, so if you _can_ do a thing in the privacy-centric browser that's a better option than using an app. The permissions an app asks for are usually shown in the store you're downloading from so it's good to get in the habit of seeing if those actually make sense. Selling personal data acquired from apps is a [huge business that puts people at risk](https://www.wired.com/story/gravy-location-data-app-leak-rtb/).

- Turn off biometrics (face unlock / fingerprint unlock) on your phone and only use unlock codes. There are [conflicting](https://reason.com/2024/04/19/appeals-court-rules-that-cops-can-physically-make-you-unlock-your-phone/) [opinions](https://www.pcmag.com/news/court-cops-cant-force-you-to-unlock-a-phone-with-biometrics) about whether police can force you to unlock with biometrics, but why risk it?

- VPN: Here's that [explainer video](https://neat.tube/w/6HDQH1wnTACKFHh2u1CRQ5) again. I go with [Proton](https://proton.me/), people whose opinions I respect use [NordVPN](https://nordvpn.com). There are a LOT of shitty VPNs out there that are worse than not using one at all, especially free ones. Yes their CEO has dubious, probably shitty, politics. This is one place where I deal with it because I want someone who will firmly stand up to censorship. After all, if it can be used against your enemies, it can and will be used against you eventually. Being located in Switzerland is a big plus. VPNs are a big topic, and can complicate things like accessing things on your home network, but good ones are also the number 1 easiest and best way to keep your internet provider from selling a list of every site you visit to literally anyone who asks. They can also filter an absolute ton of ads and trackers, increasing safety, usability, and speeding up browsing substantially. Be wary of "best VPN services" articles, the proliferation of affiliate programs in this space means that a lot of them hype services just to get paid.

- Password manager: [Proton](https://proton.me/) again. It comes free with your proton account, works as well as any other I've used (and I've used many), and can do things like automatically create a forwarding email address for each site you sign up for so you can tell who's selling your email / delete it so you stop getting mail from them.

## Social media recommendations

Moving social media is hard, but trying new services is easy so this gets its own section. I recommend trying to boost the new federated services and helping them grow instead of jumping to the latest venture capital supported monolith (Bluesky), which already seems doomed to repeat all of the same old mistakes. These are highly personal choices, ymmv.

It requires a little more effort to build your own community, and it certainly has fewer people, but the interactions tend to be higher quality and more authentic. There's no money to be made, no advertising, and basically no clout.

The hardest part can be finding the right "instance". Federated social media platforms are more like email providers, they can mostly all talk to each other, but your instance is like your local neighborhood and picking a good one can help find like-minded people... and keep the assholes and nazi instances off your feed. It is also possible, common, and fairly easy to move between instances.

There is a ton of work going on in this space, here are some of the larger and better supported options:

### Twitter-like instances (Mastodon and friends)

- Instance search: https://www.fediverse.to/
- Another instance search: https://joinfediverse.wiki/Instances

### TikTok-like / Instagram-like

These first two a projects are developed by someone who seens to be kind of an ass, but is definitely less of an ass than any big tech CEO you can imagine.

- [Loops](https://loops.video/) (I think this is the only server right now, it's very new)
- [Pixelfed](https://pixelfed.org/servers)
- Bonus, this site lets you watch TikToks without the ads, app, or tracking: https://www.sticktock.com/

### Youtube-like

- [Peertube](https://instances.joinpeertube.org/instances)

### Music and Podcases

- [Funkwhale](https://www.funkwhale.audio/join/)

### Facebook-like

- [Friendica](https://dir.friendica.social/servers)
- [Diaspora](https://diasporafoundation.org/)

## "Medium effort" recommendations

- Phone / Phone OS: This is a big topic, but my suggestion is any [Android phone](https://grapheneos.org/faq#device-support) that supports [GrapheneOS](https://grapheneos.org/). Stock Android is a [privacy nightmare](https://ssd.eff.org/module/how-to-get-to-know-android-privacy-and-security-settings) (and that doesn't even include the new AI / Gemini settings), but GrapheneOS makes it actually usable. Note that with US carriers there are confusing things to navigate to make sure you can actually unlock the phone and install Graphene on it. [This post](https://discuss.grapheneos.org/d/5880-where-to-buy-grapheneos-smartphones/3) covers most of it. You may need a technical friend to help with actually installing the OS, but it's not terrible.

- One reason I recommend Android these days is that on most Android devices you can use alternative stores to download apps that the offical stores don't / won't list. This is a mixed bag as most 3rd party stores don't have the same level of scanning for viruses or ensuring that the package is official and not some clone with even worse spyware / malware. However you may also be able to get software that's been banned in your country (TikTok?) or that has privacy features that the official store won't / can't support because it harms their business model.

- If you're on iOS, tighten up your settings. Here's [one article](https://www.33rdsquare.com/iphone-privacy-settings/), but again there are new settings to turn off Apple Intelligence that you may have to hunt down. I also personally advise against using iCloud, but ymmv.

- Email / Calendar / Cloud file backup: [Proton](https://proton.me/) again. A lot of these products are new, and show it, but are improving rapidly. End-to-end encryption can slow things down, especially the calendar... but again that thing about convenience. Same thing with having to move everything to a new email / calendar. There are tools to help smooth move from GMail etc, though.

- Chat / calling: [Signal](https://signal.org/) does an excellent job of providing features without compromising functionality, but is also a single service run by one group. If a government decides to shut it down, that's easier to do than a distributed service. I personally like [DeltaChat](https://delta.chat/en/) as a 2nd choice for secure messaging and am in the process of setting up a server.

## "High effort" recommendations

Switch to Linux on the desktop. :)

- [Linux Mint](https://www.linuxmint.com/) and [Fedora Workstation](https://fedoraproject.org/workstation) seem to be the easiest for people to adapt to, which does not mean that it's easy. A lot of tools you may be used to won't exist, or will have replacements that aren't as polished. On the upside they are highly unlikely to take all of your writing and pull it into AI training data without your consent.

- If you need "maximum easy security" check out [Tails](https://tails.net/), which can run off of a thumb drive on cheap hardware and automatically uses Tor / Tor browser to hide your network traffic. It tries very hard to not store any data during use, which makes it ideal for booting into, doing your very private work, and then rebooting into your usual operating system. On the downside, you need to take some extra steps to preserve any files created or altered between boots.
