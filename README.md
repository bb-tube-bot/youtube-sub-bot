# 🚀 YouTube Subscriber Bot - [YouTube Booster](https://youtube-booster.space/)
YouTube Booster is a software that allows you organically increase your subscriber count, boost audience engagement, and accelerate your channel's growth. The program emulates real users: they subscribe to the channel, turn on notifications, likes, and watch videos. All of this creates a natural growth pattern for YouTube's algorithms.

Unlike simple boosting services, our software works through advanced browser profiles with unique fingerprints and proxies, making each subscriber unique and indistinguishable from a real person. The program is flexibly customized for any task: from smooth organic growth to large-scale subbotting. But initially, the software was created to boost young channels, to help them in the beginning.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8ff2c23b-d382-42b9-b22d-d6a3ff728336" />
</p>

# Table of Contents

- [💣 YouTube Sub Bot Features](#-youtube-sub-bot-features)
- [🎯 How the Follower Bot Works](#-how-the-follower-bot-works)
- [🧑‍💻 Installation and Setup](#-installation-and-setup)
  * [🔧 Step 1: Prepare Accounts and Profiles](#-step-1-prepare-accounts-and-profiles)
  * [🌐 Step 2: Connect Proxies](#-step-2-connect-proxies)
  * [🌱 Step 3: Warm Up Profiles](#-step-3-warm-up-profiles)
  * [🚀 Step 4: Launch YouTube SubBot](#-step-4-launch-youtube-subbot)
- [⚙️ System Requirements of the Subs Bot](#%EF%B8%8F-system-requirements-of-the-subs-bot)
- [❓ FAQ](#-faq)
- [🗒️ Notes](#%EF%B8%8F-notes)

# 💣 YouTube Sub Bot Features

- Subscribers increase.
- Warm-up of profile before subscribing (reduces drop rate and allows you to assign targeted interests for bots).
- Warm-up via YouTube search, search engines, and websites.
- Views increase.
- Likes increase.
- Enabling notifications after subscribing.
- Scheduler support: run on a timed schedule.
- Multithreading (up to 500 threads on a single instance).
- Proxy support (http/socks/IPv4/IPv6): static, residential, and mobile.
- Advanced browser fingerprints for each profile.
- Real user behavior emulation.
- Automatic captcha solving.
- Support for accounts with two-factor authentication (2FA).
- SMS verification via third-party services + QR challenge bypass.

# 🎯 How the Follower Bot Works?

Boosting followers is technically more difficult than boosting views: YouTube carefully checks accounts that subscribe to channels, analyzes their activity history and behavior. That's why YouTube Booster uses a multi-level approach that makes each subscription as natural as possible.

**Unique profiles.** Each subscriber is a separate browser profile with a unique fingerprint (browser and system characteristics). YouTube sees them as different users from different devices.

**Proxies and geolocation.** The profile works through a proxy, which provides a unique IP address and geographical diversity of subscribers. This makes the channel's growth organic in the eyes of YouTube's algorithms.

**Account warm-up.** Before subscribing to your channel, each profile goes through a mandatory warm-up stage: visiting websites, watching videos, and performing search queries. This builds up an activity history and increases YouTube's trust in the account. Warming up is a key factor that distinguishes subscribers who stay from those who drop out.

**Natural behavior after subscribing.** After subscribing, the bot can automatically turn on notifications, like a video, and watch another video on the channel, just like an interested viewer would.

**Scalability.** The number of auto subscribers is limited only by the number of accounts, proxies, and the power of your PC. On average, you can expect several hundred subscribers per day with a standard configuration. However, it is recommended that new channels do not overuse this feature.

# 🧑‍💻 Installation and Setup

> Before you start, make sure you have everything you need.
> Skipping any of the steps below is the most common cause of problems.

## 📋 What You'll Need

| Component | Required | Where to Get |
|---|---|---|
| Google accounts | ✅ | [Accounts Creator](https://youtube-booster.space/google-accounts-creator/) or purchase |
| Proxies (mobile or residential) | ✅ | See FAQ section |
| Captcha service API key | ✅ | [CaptchaGuru](https://captcha.guru/en/reg/?ref=109944) |
| SMS service API key | Recommended | smshub.org or similar |
| FingerprintSwitcher Premium key | Recommended | fingerprints.bablosoft.com |

---

## 🔧 Step 1: Prepare Accounts and Profiles

Boosting subscribers works **only via Google accounts** —

**Option A — Create accounts yourself:** Use [Google Accounts Creator](https://youtube-booster.space/google-accounts-creator/).
This is the preferred option: accounts will be linked to unique profiles and give the best results. After creating them, move the data from accounts.xlsx (Accounts Creator folder) to accounts.xlsx in the /YoutubeSubscribeBooster/settings/ folder.

**Option B — Buy ready-made accounts:** Accounts from [accsmarket.com](https://accsmarket.com/?ref=338617) or [accfarm.com](https://accfarm.com?ref=MTAwODQ2S3V6aWFDYXQ=) are suitable. Enter the data manually into the accounts.xlsx file.

<img width="1917" height="527" alt="1" src="https://github.com/user-attachments/assets/fc1ac25c-d9b3-4a87-a4d4-a96660122d45" />

After filling out the file, run YoutubeSubscribeBooster.exe, select the **"Profiles Generation"** mode, configure the necessary parameters, and wait for completion. The program will create browser profiles with a unique fingerprint for each account.

<img width="1051" height="310" alt="3" src="https://github.com/user-attachments/assets/9584954f-5d90-4d26-bc89-f67c3911f38b" />

⚠️ Do not interrupt the generation process. If you see the message "Query limit reached," this is a limitation on the part of FingerprintSwitcher; simply ignore it. To speed up the process, purchase a premium key and enable the "FingerprintSwitcher Premium" option in the settings.

---

## 🌐 Step 2: Connect Proxies

Open the accounts.xlsx file and fill in the appropriate columns for each profile:
'''
Column E → proxy: http(socks)://ip:port@login:password
Column F → IP rotation interval in minutes (if IP rotation is time-based)
Column G → API link for IP rotation (if rotation is on-demand)
'''

<img width="1917" height="527" alt="2" src="https://github.com/user-attachments/assets/eb59f0b4-b841-434d-bca6-4bf604029d6d" />

**Which proxy type to choose:**

🥇 **Mobile LTE** — best choice. Mobile IPs don't end up in spam lists. One proxy handles up to 1000 profiles.

🥈 **Residential** — also great option, but may cost more due to traffic-based billing.

🥉 **Static** — works for smaller volumes. 1 proxy per 1 profile, 1 thread. Subs may be dropped.

<img width="1051" height="263" alt="5" src="https://github.com/user-attachments/assets/b0ddddb7-55a0-4c28-b98b-9d18f27a8bc2" />

---

## 🌱 Step 3: Warm Up Profiles

This is the most important step for increasing subscribers. YouTube analyzes the account's activity history before counting a subscription. Without warming up, you will get a
high drop rate!

Select **"Warm Up"** mode and configure:

- Number of threads
- Path to the folder with profiles
- Warm-up duration per profile (min 4 minutes)
- YouTube/Sites ratio (80%/20% recommended)

<img width="1046" height="354" alt="4" src="https://github.com/user-attachments/assets/968b9022-c8db-4cd7-874e-640c45915a27" />

Additionally, fill in:

'''
- search queries (related to your channel's topic + general)
- sites to visit
- videos to watch during warm-up
'''
If you leave this blank, the program will choose random topics.

On the **Captcha** tab, select automatic captcha solving and enter the API key.

<img width="1051" height="154" alt="6" src="https://github.com/user-attachments/assets/b3fc1408-13af-4742-9e8c-f3d6cffc5982" />

On the **SMS** tab, configure the behavior when SMS verification request is received: use the SMS service (recommended), skip or delete such accounts.

<img width="1052" height="264" alt="7" src="https://github.com/user-attachments/assets/e39765d6-91c2-4d5a-bdea-34011437f88e" />

When everything is ready, you can start warming up.

**The minimum warm-up period for profiles is approximately 14 days, 10 minutes per day for each profile.** However, the longer - the better.

---

## 🚀 Step 4: Launch YouTube SubBot

Open the **promotion.xlsx** file and specify your channel promotion parameters.
You can add an unlimited number of channels simultaneously.

**Task parameters:**

| Parameter | Description | Example |
|---|---|---|
| Channel URL* | Link to the channel to promote | https://youtube.com/@Channel |
| Subscriber count* | How many subscriptions to perform | 1000 |
| Pause between runs* | Minutes between task repetitions | 10-50 |
| Pre-start warm-up* | Watch videos before subscribing (min) | 2-6 |
| Channels/videos for warm-up | What to watch before subscribing | link;query;random |
| Notification chance %* | Enable notifications after subscribing | 30 |
| Like chance %* | Like a video after subscribing | 20 |
| Watch chance %* | Watch a video after subscribing | 40 |
| Watch duration %* | How much of the video to watch | 40-70 |
| Traffic sources | How to navigate to the channel | (all available sources described below) |
| YouTube search queries | For the search source | youtube growth;nature channel |
| Google search queries | For the google source | best nature channel |

* - required parameters

**Traffic sources:**
- 'direct' — direct navigation
- 'search' — from YouTube search
- 'google' — from Google search
- 'main' — from YouTube homepage
- 'suggestions' — from recommendations
- 'channel' — from the channel page

Fill format: 'direct(40);search(30);main(20);google(10)'
The number in brackets = % of traffic from that source.
The sum of all values must equal 100.

After filling in, save and close the file. Launch YoutubeSubscribeBooster.exe, 
select **"Subscriber Boost"** mode and click OK.

<img width="1053" height="502" alt="8" src="https://github.com/user-attachments/assets/51e964e3-8df4-42bd-83b2-46308734fbdd" />


# ⚙️ System Requirements of the Subs Bot

The program supports Windows 8.1 / Windows Server 2016 and above.

**Minimum system requirements:**
- CPU: 2 threads
- RAM: 8 GB
- HDD/SSD: 200 GB minimum
- GPU: not required

Running on Linux or macOS is only possible via emulators like Wine or virtual machines.

**Additional software:** nothing needs to be installed manually — the program 
sets up all required tools and dependencies on first launch.

# ❓ FAQ

## — What consumables do I need?

- Proxies.

  **Mobile (recommended):**
  [https://iproyal.com](https://iproyal.com?r=youtube_booster)
  [https://mobileproxy.space](https://mobileproxy.space/en/?p=29804)

  **Residential:**
  [https://asocks.com](https://asocks.com/?c=BOOSTER2)
  [https://geonix.com/](https://geonix.com/?partner_link=Vvv3t2JxYY)

  You can also set up a mobile proxy on an old phone via 
  [IProxy.online](https://iproxy.online/invite/friend/mAAGVJKtEu).

- Google accounts (can be created with [Google Accounts Creator](https://youtube-booster.space/google-accounts-creator/)).
  Or purchased from:
  - [accsmarket.com](https://accsmarket.com/?ref=338617)
  - [accfarm.com](https://accfarm.com?ref=MTAwODQ2S3V6aWFDYXQ=)

## — Can I use the subscriber bot at the same time as the view bot?
Sure, both botter modules work in parallel.

## — How many sub bots can be boosted per day?
The program has almost no limits. It depends on the number of accounts, proxies, and the power of your PC. With a standard configuration, several hundred subscribers per day.

## — What is the percentage of subscriber drop?
With the correct settings and sufficient account warm-up, about 10-15%.

## — Why do subscribers drop and how can this be prevented?
- **Insufficient warm-up.** Increase the duration and intensity of the warm-up of profiles (minimum 14 days).
- **Low proxy quality.** Use mobile or residential proxies from recommended providers.
- **New accounts.** YouTube is skeptical of new accounts — give them more time to warm up.
- **Too high subscription rate.** Reduce the number of threads or increase the pause between executions in promotion.xlsx.

## — Can a channel be banned for inflating subscriber bots?
No. In the worst case, YouTube will simply not count the subscriptions or delete them later. Sanctions against the channel itself are extremely unlikely — otherwise, this scheme would be used to attack competitors.

## — What happens if a botting account is banned by YouTube?
Subscribers from blocked accounts are automatically removed from your channel's counter. That's why it is very important strictly follow the manual.

## — How do these subscribers look in channel analytics?
Subscribers look like regular users with a history of activity. The program emulates real behavior — views, likes, notifications, making them virtually indistinguishable from a live audience in YouTube analytics.

## — Which countries and languages does the script supports?
The program works with all geolocations and languages.

## — How often do I need to upgrade the tool?
Updates occur automatically, about several times for a month.

## — When authorizing accounts, Google requests QR confirmation via mobile. Can the bot bypass this?
Yes, we alredy developed a solution to this problem.

## — "Unable to connect proxy" error.
Make sure that the proxies are entered correctly and are working. It is also possible that connections are being blocked by your PC or server. In 99% of cases, the problem is on the client side or the proxy server.

## — The robot hangs for a long time on the "Waiting for IP change" action.
Most likely, there was an internal failure. Restart the script. If that doesn't help, check the proxy and API link for changing the IP.

# 🗒️ Notes
**Moving the subscribers generator to another server or PC/Server.** Close the program completely on the current machine, go to https://youtube-booster.space/binding-reset/, enter your login or email from the license, then you can run the program on the new device.

**Installing a second copy of the program.** You cannot simply copy the folder with the already installed program. You have to unrar the program from the archive, as you did when you first launched it. Folders with settings and system folders can be transferred from the old directory.

**Updating the program.** Simply restart the program, it will update automatically. There is no need to download the archive again.
