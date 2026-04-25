---
layout: post
title: OPSEC for using a pseudonym to speak out
date: 2026-04-22 12:00:00 -0700
categories: politics science
permalink: /blog/OPSEC-for-pseudonyms
---

![a 3-panel comic](/assets/images/260420.png)

# OPSEC for Political Speech

I feel compelled to speak out against the abuses of the Republican administration, but it is clear that this carries risks. Security by obscurity is a bad idea. Probably this little blog project won't be noticed much, but it is a mistake to rely on low readership to prevent blowback (whether through spurious legal actions, unofficial blacklisting, or just disruptive trolling).

This post is also available as a [youtube video here](https://youtu.be/AllopHwkhmo) [https://youtu.be/AllopHwkhmo](https://youtu.be/AllopHwkhmo)

The government is not supposed to target political opponents for law enforcement. The government is not supposed to withhold contracts and grants based on political speech. But there are many lawsuits alleging that the government is doing exactly that. It is antithetical to democracy... but the government seems to be doing it anyway. 

[Reuters: Trump’s campaign of retribution: At least 470 targets and counting](https://www.reuters.com/investigates/special-report/usa-trump-retribution-tracker/)

[Reuters: Minority contractors say Trump DEI rollback poses threat to their livelihoods](https://www.reuters.com/legal/litigation/minority-contractors-say-trump-dei-rollback-poses-threat-their-livelihoods-2026-03-17/)

[ACLU: Trump on Surveillance, Protest, and Free Speech](https://www.aclu.org/trump-on-surveillance-protest-and-free-speech)

[TPM:  Social Security Admin Canceled Maine Contracts As Political Revenge For Trump ](https://talkingpointsmemo.com/where-things-stand/social-security-admin-canceled-maine-contracts-as-political-revenge-for-trump)

In light of that, how can working professionals (especially people like scientists who rely on government support) more safely speak out against affronts to American principles? Depending on the threat model you are considering, it may be worth building a pseudonym. I'm not an operational security (OPSEC) expert. I've pulled this list from lurking in reddit.com/r/opsec/, various blogs, and LLMs. These steps can reduce risk, but risks still exist. For errata and corrections, check the bottom of the page.

## Threat models:

The first thing to consider before building a pseudonym (or any other political speech project) is the threat model. Who might want to threaten you, and how could they do it?

### Official actions:

If you are in a high profile position, leaking information to the media, or taking actions that could attract legal scrutiny, the security considerations need to include law enforcement and subpoena power. This means that a cell phone or email address attached to your real identity is vulnerable to a warrant.

Someone exercising protected speech, including expressing anti-administration sentiments, should be protected from such actions by the justice system. But that's a big "should" and it is worth considering the higher level of security that is required to avoid identification.

This is very difficult, and no level of operational security is completely safe. This article won't cover threats at this level. Consult experts (such as [EFF's Surveillance Self-Defense guide](https://ssd.eff.org/), or the [Freedom of the Press Foundation](https://freedom.press/digisec/guides/)) if you need to maintain anonymity from official government threats.

Activists and whistleblowers who are very serious about protecting their identity only use public internet connections with dedicated hardware. They buy hardware with cash, and never power it up at home, connect to the internet at cafes (cash only) or public libraries, and use TOR or a VPN (paid with cash or cryptocurrency) to prevent localizing their identity. 

But even all that won't protect from close scrutiny. Organizations with serious resources can use: text pattern analysis, social network analysis, correlated entry and exit node timing (a known attack against TOR), and networked cameras such as Ring and Flock (not to mention search warrants and subpoena power). These can de-anonymize almost anyone. 

This post will focus on lower level threat models. The goal here is modest: to prevent jerks from using unofficial channels to try to ruin your day and maybe your career for speaking out against government abuses of power.

### Unofficial actions and trolls:

Politically motivated individuals, trolls, and agents of the state acting on an unofficial basis do not have subpoena power or warrants. They probably cannot compel a large company to give up your real identity. But they can ask for it. Be careful what companies you trust.

It is easier to use public data and data purchased from data brokers. Data brokers buy and sell personal data you agreed to share when you joined various online services. Law enforcement and motivated individuals can buy that data. If that data links your political speech to your real identity, you are vulnerable to tactics like unofficial blacklisting. You are always vulnerable to doxxing and harassment. A reasonably well-maintained pseudonym identity online can protect from these threats. 
## Pseudonyms

Using a pseudonym for personal/political activity offers some security online. I know using a pseudonym limits my credibility, but this is the compromise that I can live with. I am not an OPSEC expert or a lawyer, but I've done my best to find some good practices.

The general principle is to consider what a pseudonym exists to accomplish and work backwards to likely security issues. What do I use the pseudonym identity for:
- Shitpost and argue online
- Publish political cartoons
- Publish a blog, op-eds, and think-pieces

Any of those activities might bring pseudonym and real identities into contact, and that is the quickest way for a pseudonym to be unmasked. Every person needs to game that out for themselves and try to avoid it. Here are some basic steps. 

- Create a new digital identity for your pseudonym (i.e., [proton.me](https://mail.proton.me) [tuta.com](https://tuta.com) or similar email address, new social media accounts). 
- Use a new login/account on your PC, or (even better) an alternative PC entirely dedicated to the pseudonym (ideally, running Linux)
- Use a password manager with a separate vault for the pseudonym identity (proton also includes a password manager, but bitwarden and lastpass are also reasonable options)
- Use 2-factor authentication (2FA) with a hardware key or authenticator app
- Be alert to phishing attacks that can compromise your pseudonym 
- Your browser fingerprint leads straight to you, so keep strict browser separation between identities (never use your main PC's browser to log into a pseudonym account)
- Never use the pseudonym identity at work or with work equipment
- Never use your credit card for *anything* associated with your pseudonym
- Never use your real phone for your pseudonym. If your pseudonym needs a phone (e.g., for account creation), buy a burner phone or temporary number with cash or gift card. Even this is a risky path that can connect you to your pseudonym
- If you must have a domain name for a pseudonymous project, do not trust an ISP's "private domain" service. Do not give any service your real name or credit card information
- If needed, use privacy-focused web services like njalla or 1984hosting and pay with Bitcoin purchased with cash. Such services have mixed reviews and this is not an endorsement. Check trusted sources for recommendations for privacy oriented internet services
- Avoid photos or videos that show any locations that you physically visit. Clip metadata from any photos or videos. Ideally, use only public domain material for visuals, and still strip metadata
- If you use AI, make sure it was generated in a private mode (e.g., not free MidJourney which posts all images publicly by default) or, ideally, use a local model (even better, don't use AI)
- If you use a messenger app, make sure it is end-to-end encrypted. Signal is a common choice. SMS text messaging is not encrypted at all
- Never cross post between accounts. Don't follow your pseudonym account or vice-versa. Don't let friends and family follow your pseudonym account. Avoid engaging with the same public accounts on your main and pseudonym account
- Abandon all hope of using your pseudonym to advance your career or make money at any point in the future


Look for places where your personas might overlap and give away the game. These kinds of similarities and overlaps are the points of contact to assess, mitigate, or eliminate.: 
- Did you see and reply to a thread with both personas?
- Did you comment on your pseudonym's blog?
- Did you buy supplies or software for your pseudonym with your credit card?
- Do you always post at a time that would imply your location?
- Do you write with the same style (word choice, tone) and domain of expertise? [Stylometry can be used to de-anonymize your pseudonym](https://www.wired.com/story/machine-learning-identify-anonymous-code/) 
- Do you stream or videoconference and leave your pseudonym's screen open?


Pseudonym anonymity is limited. Google, Apple, social media companies, your ISP, and even a VPN service will be able to infer your pseudonym's probable real identity. Law enforcement can ask for that information and probably get it. So be aware of the limitations and plan appropriately. Sign up for a data broker remover service for your real identity such as deleteme, or incogni

### Backup plan

How will you protect your main identity if you get outed? Make an "I’ve been doxxed" plan:
- Identify a lawyer you can call for help
- Identify journalists you can contact
- Identify trusted friends and family
- Decide which accounts to lock or temporarily deactivate 
- Build a backup email address for your main identity that you can use to access critical accounts
- Have a spreadsheet template handy to record incidents 
- Read though [EFF's anti doxxing tips](https://www.eff.org/deeplinks/2020/12/doxxing-tips-protect-yourself-online-how-minimize-harm)
- Read up on the anti-doxxing policies for your online accounts and how you can report violations

## Further reading

[ACLU tips](https://www.aclu.org/news/free-speech/some-steps-to-defend-against-online-doxxing-and-harassment)

[Gender Tech Pseudonym Manual](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual)

[Journalist's Guide to Risk Assessment](https://freedom.press/digisec/blog/a-journalists-guide-to-digital-security-risk-assessment/)

[EFF - A Case for Pseudonyms](https://www.eff.org/deeplinks/2011/07/case-pseudonyms)

## Why I'm using a pseudonym 

Many scientists are federal employees or federal grant recipients (or hope to be). The Hatch Act restricts federal employees including scientists from lobbying. Grant-funded scientists must refrain from using funding for lobbying, including grassroots lobbying (for example, encouraging people to call their senators about specific issues). Does this include their after-hours personal time and resources? Probably not, but nobody wants to be investigated. 

Lobbying rules are legally complicated. It *should* be protected speech to communicate about the consequences of policy decisions on your personal time. Even so, I would not be surprised if scientists found themselves getting investigated for lobbying rules violations (even when they were scrupulous about only using personal resources).  I am concerned that vocal scientists will have their funding quietly withheld through unofficial channels.

Even considering this risk, I think it's important. See [Degenerate Art by Andrea Pitzer: Why Speaking Out Matters](https://www.youtube.com/watch?v=eEjjgjm--1A)

I believe that scientists and academics need to promote a wider understanding of the value of science. I think scientists need to publicize the successes of public science funding.  Government failures and unforced errors need to be documented and publicized.

This is about advocating for science, reason, and accountability in public policy. It's about the things that used to be normal free speech: making a compelling argument for doing things to make peoples' lives better. It's about encouraging people to get involved locally in their own communities. It's about informing your elected officials and holding them accountable. 

If you feel the same, I suggest building a pseudonym. I've decided that I need to speak out, and this is what I can do to be safer. 

Of course, a pseudonym is only useful if you can reach people with it. I am  adopting a [POSSE strategy](https://indieweb.org/POSSE): "Post to Own Site, Syndicate Everywhere." I first heard about this from [Cory Doctorow.](https://pluralistic.net/2022/02/19/now-we-are-two/) The point is to leverage the social media discoverability algorithms, but maintain a connection to readers even if you get shadow-banned or throttled. 

An email list is an effective way to communicate with readers even if the algorithm doesn't want you to. Keep a copy of any email list you generate somewhere encrypted like [proton drive](https://drive.proton.me/). When managing multiple accounts like this, strict physical separation of my personas into separate computers is very useful. 

Do you have tips? Places to go for more information on securing your identity? Please send me an email at jbb774 at the domain tutamail dot com. I'll make an update if there's good advice I can pass along. For errata and corrections, check the bottom of the page.


