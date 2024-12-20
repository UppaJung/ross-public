# Harsh Truths for Harsh Times
<author style="position: relative; font-size: 130%; top: -1rem; font-weight: bold; font-family: serif; margin-left: 15vw;">Stuart Schechter</author>

This is an essay written in memory of the late Ross Anderson.[^cfp] Not everyone will miss Ross. His ideas and arguments made people uncomfortable. They were were often threatening to the beliefs, status, power, ego, and bank balances of others — often those with power who professed to be working to serve the public faithfully. Ross undermined proponents of hardware attestation, chip-and-pin authentication, and surveillance, to name just a few. And so, the best way to honor Ross is to share truths that cause discomfort to us – the scientific community that researches security within the context of computing and technology – and our need to believe that we faithfully serve the public.

[^cfp]: The wording of the [request](https://www.cl.cam.ac.uk/events/rossfest/) for contributions was to "make it a scientific contribution rather than just an opinion piece" and submit it in LNCS format, but adding an academic veneer and styling where it doesn't belong would have been an offense to Ross. We appreciate the organizing committee's understanding of our dedication to the spirit of the request.

We *should* be uncomfortable. I first met Ross in 2002, and it is hard to imagine a metric of success for serving the public – real living people – for which we can claim anything but harsh defeat.

A post-mortem of the past few decades is in order.

**Have we protected the privacy of the public's government identifiers, means of contact, or financial data?**\
*No*, though the public has received enough free credit reporting to last until the heat death of the universe, numbing them to seemingly-endless disclosures that their data has been compromised.

**Have we reduced losses to scams and cybercrime?**\
*No*, but if we had a conference on "crime-enhancing technologies" it could claim to be a smashing success. We created the cryptocurrency technologies that have enabled ransomware, pump and dump schemes, romance scams, and human enslavement. We helped breathe new life into organized crime and authoritarian governments that harbor criminals. We helped fund a [\$197 million dollars of spending in the 2024 US election to support candidates willing to commit to ensure the spread of this cancerous industry](https://www.followthecrypto.org/), eclipsing the lobbying of all other industries. We succeeded in making the lobbying of the fossil fuel industry seem like noise – [a mere $60 million!](https://www.statista.com/statistics/788056/us-oil-and-gas-lobbying-spend-by-party/) – by comparison. We did all this while helping to birth an industry[^industry] that pollutes the earth and increases wealth inequality while producing no value to society.

[^industry]: Using the word "industry" generously to describe enterprises that produce no actual goods.

**Have we built a robust cybersecurity industry to at least attempt to protect the public?**\
*No*. We have built an industry to protect business. Walk the floors of RSA and you will see the extravagant display of the wealth of the [cybersecurity industry that brings in nearly $200 Billion dollars a year](https://www.statista.com/outlook/tmo/cybersecurity/worldwide), and you'll be hard-pressed to find one of the roughly [600 vendors](https://www.rsaconference.com/library/press-release/rsa-conference-2024-opens) that is making products to protect actual people ("consumers", in industry-speak).[^exception] Economic theorists might tell us that the public should reap the benefits of a cybersecurity industry that protects businesses from losses that might be passed onto consumers but, in practice, much of what the industry sells are compliance products to protect businesses from negligience lawsuits. The net effect is that these expenditures protect business from members of the public who might seek recompense for facing the consequences of the business's security failures.

What's worse, these security products often require highly-privileged access to customers networks and data, yet their code is rarely written to the high standard one would expect given the privileged access it runs with. The result: security technologies have introduced new vectors through which attackers can compromise even the organizations that are in greatest need of protection and invest the most in it. Or, as in the case of [CrowdStrike](https://en.wikipedia.org/wiki/2024_CrowdStrike-related_IT_outages), security products introduce entirely new failure modes that require no adversarial behavior to disrupt lives and incur billions of dollars of losses.

[^exception]: The notable exceptions that proves the rule are password managers. Some started focused on serving consumers, but shifted focus to enterprises after being purchased by private equity ([LastPass](https://en.wikipedia.org/wiki/LastPass)) or receiving investments from Venture Capitalists (1Password).

**But, but at least we aspire to do better at keeping people safe?**\
*No*. Instead, in an Orwellian twist, we have allowed industry to pervert the very meanings of such basic concepts as safety and trust. Back in January 2002, the year I met Ross, Bill Gates laid out a corporate vision for what "Trust" meant to tech's de-facto leader of the time:

> Users should be in control of how their data is used. Policies for information use should be clear to the user. Users should be in control of when and if they receive information to make best use of their time. It should be easy for users to specify appropriate use of their information including controlling the use of email they send.
>
> …
>
> There are many changes Microsoft needs to make as a company to ensure and keep our customers’ *trust* at every level – from the *way* we develop software, to *our* support efforts, to *our* operational and business practices.[^emphasis]

[^emphasis]: Emphasis in quote added to highlight that when *Microsoft* used the word "trust", it applied to how *Microsoft* should behave. It was used to keep the company accountable to its users. The original January 15, 2002 memo is reproduced available via a [10-year retrospective from Microsoft](https://news.microsoft.com/2012/01/11/memo-from-bill-gates/) and a Wired article from [January 17, 2002](https://www.wired.com/2002/01/bill-gates-trustworthy-computing/).

Regardless of what you think of Gates, Microsoft's history[^microsoft-disclosure], or the extent to which Gates and Microsoft were able to deliver on those principles, Gates was willing to state without ambiguity that "trust" meant being accountable to customers about the quality and safety of its products.

[^microsoft-disclosure]: Disclosure: I worked at Microsoft Research from 2007 until 2016.

Contrast that with today's doublespeak, where today's tech companies use "trust and safety" to mean protecting customers from others, so that their company can control how their data is used, where their attention goes, and to obscure how this all happens so that users remain as oblivious as possible. They have redefined trust to mean moderating others' content and access, eliding even the slightest consideration that their social network, [dating app](https://stuartschechter.org/posts/safety-tips-dating-apps-omit/), or other service might not adequately protect your data or might sell access to it to advertisers, governments, political parties, and others.

This capture of our lexicon has been enabled by academic research institutions that hold conferences dominated by industry members and that embrace this doublespeak.

And this is just one way that scientific researchers and its institutions have become complicit in the direction of industry and its march toward [enshittification](https://en.wikipedia.org/wiki/Enshittification).


Industry thrives on the talent that we train and we thrive by consuming the funding they provide. We welcome with open arms those who advanced their careers by enabling the industry's most abusive oligarchs. In addition to cozying up to companies and institutions that we know to be actively trying to subvert the public good, many of us not only accept research funding from them, but brag about that research funding when brandishing our credentials. And we don't question when our institutions do it.

Many of our most prestigious scientific research institutions have helped to promote technologies that harm the public. Cornell Tech advertises [its placement](https://admissions.tech.cornell.edu/admitted/we-are-one-of-the-best-universities-for-blockchain/) on [CoinDesk's Best Universities for BlockChain](https://www.coindesk.com/layer2/2022/09/26/best-universities-for-blockchain-2022/). [Stanford](https://fdc.stanford.edu/) and [Berkeley](https://haas.berkeley.edu/blockchain/research/) (funded by cryptocurrency company Ripple) are also actively promoting their links to the industry. They show no shame for doing so because too few of us have had the courage to shame them. Perhaps too many of us are fearful of sharing our disappointment of becoming outcasts in a community that stridently rejects attempts to examine our own complicity, or perhaps we fear examination of our own complicity. The belief that only (s)he who is without sin may cast the first stone only acts to ensure we all will remain unarmed and defenseless.

Perversion of the truth has become endemic in scientific culture. Our success is judged by how meticulous our methods are or our caution against overstating the implications of our findings, but on how significant we can make our findings appear, how many papers we can publish, and whether these appear in venues of the highest prestige.[^weis] We gather for exclusive meetings amongst our research-area elites, to decide how we will distribute prestige, and congratulate ourselves for "service". We direct our time and effort is directed at explaining to a super-majority of submitters that their work does not meet "the bar" for the arbitrarily-chosen acceptance rate that we believe maintains our desired the aura of prestige. We serve our employers, and industry organizations, and program committees. These institutions pervert how we conduct and evaluate science to serve their interests, and we are far to eager to assist as we seek our degrees, jobs, promotions, and social status. Perpetuating this system may be the default choice, *but it is a choice*. It's a choice we make every time we dedicate a service hour to peer reviewing a work to determine if it's worthy of prestige, when we could instead be helping others conduct more meticulous research and communicate it to the public more clearly.

[^weis]: Being informed that the Workshop on Economics of Information Security would be a more prestigious venue for Computer Scientists to publish if it were renamed a "conference", he kept it a workshop.

It's not that most of us don't want to make pro-social choices and better the world. And some members of our community have had huge positive social impact, such as those responsible for democratizing public key infrastructure ([Let's Encrypt]()) and secure messaging ([Signal]()), both through not-for-profits. These wins came from principled people who believed that it should be safer for *everyone* who wants to publish information on the web, and safer for *everyone* to communicate with others over telecommunications networks. There's a lot to learn from these *exceptional* wins, and I do not mean to diminish them, but we can't get the most out of them if we fail to understand that they are, indeed, *exceptions*. We need to do more.

### What can we do?

First, we need to distinguish between jobs where our first priority is to protect people and our first priority is to protect our employers. We need be honest about which side of the line we are on. When our peers claim to work to put people's safety first, but protect institutions or others instead, we need to hold them to account for this deception. We need to ask which side of a line we will stand on when considering jobs. We need to declare which side of the line we stand on when we accept those jobs. We need to learn to ask which side of the line our peers are on, can we hold to account those in our community who pretend to serve the public while serving others, or allow their employers to misrepresent which side of the line they are on.

We need to learn how to identify other hard choices we are likely to have to make in our careers *before* we have to make them, commit to a our positions, and to maintain long-term relationships with peers who expect us to stick to those commitments or disclose when we have abandoned them. We should expect them to ask us hard questions, and they should welcome hard questions from us.

  - "Are you confident that your are making the choice that makes people's lives better?"
  - "Would you know if you weren't?"
  - "Are you sure your further the public's interest and not your own?"
  - "Are you confident you are the protagonist in this story?"
  
<!-- Imagine if we all graduated from school with a support group that we could call not when we wanted someone to tell us someone we wanted to hear, but with peers who left with the same idealism that we had and who had promised to ask us these tough questions when the time came. -->

We need to all be a little more willing to ask ourselves and others questions that are certain to make us uncomfortable.

We have to be willing to piss people off.

We have to be prepared for people in authority to try to brush us off with such indignant responses as "Who died and gave you the power to be such an asshole as to ask me that question?"

Funny you should ask.

His name was Ross Anderson.

---
Stuart would like to thank:
  - Cormac Herley for comments, ideas, and edits
  - Bruce Schneier for encouragement and feedback.
<!-- 
Trust and Safety.

society would be better served if they were a little less comfortable.  These were usually people who should be less comfortable with what they thought or had done.  Yet, no good comes from avoiding hard truths, especially those that we may deny because they are inconvenient to our bank balances, status, or power.

The crypto wars.

We failed. We fucked up. We fail to protect PEOPLE.

Instead of creating organizations to hand out status and give out awards, we need organizations that do honest post-mortems, and that create social commitment mechanisms that bind us to a goal of actually serving the public.

Industry should exist to serve people, but in our upside-down world people exist to support industry and industry has co-opted security as a concept and a trade.

Pro-business

Security has been co-opted
  - We train people to enter the compliance industry (everyone at RSA).
    It's all about protecting companies.
	  Step foot onto the RSA floor. The only consumer-focused companies are a password-manager or two, and
		after a few rounds of venture capital and they don't care about consumers.

	- We build technologies that are hurt consumers by locking them into products and ecosystems

	- We celebrate those who win research funds from monopolists and crooks

	- Enabled ponzi schemes, extortion, and scams (romance and otherwise) (and let the industry fund professorships)

  - Our graduates (and Stanford) have enabled industry to co-opt such basic terms as "Trust and Safety"
	  (Like a pimp, we protect people only insomuch as it allows us to take advantage of them ourselves.)

  - We pretend fashion shows are contributions to science.

How do we fix this?

What we got right:
   Let's Encrypt
	 Signal
	 Proton?
	 Tor?

All are non-profits.

Civic security (we need to live by a code)
  - Protecting people first and foremost (we protect enterprises because business to provide services and jobs to people, but we have come to serve business at the expense of citizens)
  - "How does this making people's lives better?"
  - "Am I the protagonist in this story?"

Introductory classes should have an exercise where groups codify their expectations of what they will and won't do in 
the future when they go into industry. They should be invited back to every two years to report back on how they feel they have lived up to them. Peer pressure.

Civic science
  - How can I dedicate my service time to maximally HELP other researchers do better research and help build public faith in science?
  - Is what I'm doing furthering science, or perpetuating a broken system

Civic organizations
  - Civic patents (may not be used for lock-in, can be revoked by vote of a majority of users/customers)

Our biggest victories are not-for-profits. Why not co-ops?
 -->
