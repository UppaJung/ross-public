# Harsh Truths for Harsh Times
<!-- <author style="position: relative; font-size: 130%; top: -1rem; font-weight: bold; font-family: serif; margin-left: 15vw;">Stuart Schechter</author> -->

<div style="margin: 0vh 10vw 2vh; font-style: italic">To appear at <a href="https://www.cl.cam.ac.uk/events/rossfest/">RossFest</a>, a celebration of the life of Ross Anderson, who died March 28, 2024.</div>

Not everyone will miss Ross Anderson.

His ideas and arguments threatened the beliefs, status, power, ego, and bank balances of others — often those with power who professed to be faithfully working to serve the public. His writings and talks undermined proponents of hardware attestation, chip-and-pin authentication, and surveillance, to name just a few.

Ross was not afraid to speak truths that made people uncomfortable. 

Most of those of us celebrating Ross's life are members of the scientific and academic community that researches security within the context of computing, technology, and public policy. While we may not be policymakers or titans of industry, almost all of us are privileged to have knowledge and skills that give us far more power over our use of technology than the average citizen. Most of us believe that we we use this knowledge and our skills faithfully serve the public.

And so, the best way to honor Ross is to share truths that cause discomfort to *us*, by questioning our belief that we are using our power to make the world a better place.

We *should* be uncomfortable. I first met Ross in 2002, while I was a graduate student, at a time when the study of security was just starting to receive the attention it deserved. It was an exciting time, and many of us had high aspirations and ambitious goals. Yet, it is hard to imagine a metric of success for serving the public – real living people – for which our field can claim anything but harsh defeat.

Imagine the questions we would have to answer if our prior selves could hold a post-mortem of the past few decades given the goals and aspirations we started with in the early 2000s..

***Have we protected the privacy of people's government identifiers, financial data, or virtual and physical addresses and contact information?***

**No**. What have we achieved?
1. Nearly every member of the public now has enough free credit reporting to last until the heat death of the universe, and
2. we have numbed the public to seemingly-endless disclosures that their data has been compromised.

***Have we reduced losses to scams and cybercrime?***

**Nope**. On the other hand, if we had a conference on "harm-amplifying technologies" it could claim to be a smashing success.

We helped create the cryptocurrency technologies that have enabled ransomware, pump and dump schemes, romance scams, and human enslavement. We helped breathe new life into organized crime and authoritarian governments that harbor criminals. We helped fund a [\$197 million dollars of spending in the 2024 US election to support candidates willing to commit to ensure the spread of this cancerous *"industry"*](https://www.followthecrypto.org/)[^industry], eclipsing the lobbying of all other industries. We succeeded in making the lobbying of the fossil fuel industry seem like noise – [a mere $60 million!](https://www.statista.com/statistics/788056/us-oil-and-gas-lobbying-spend-by-party/) – by comparison. Perhaps our biggest achievement is making the fossil fuel industry look good: the *"industry"* we helped birth pollutes the earth and increases wealth inequality *without* producing any value for society.

[^industry]: Using the word "industry" generously to describe enterprises that produce no actual goods.

***Have we built a robust cybersecurity industry to at least attempt to protect the public?***

**Still No!** What we have built is an industry to protect business from the public. Walk the floors of our biggest industry conference, RSA, and you will see the extravagant display of the wealth of the [cybersecurity industry that brings in nearly $200 Billion dollars a year](https://www.statista.com/outlook/tmo/cybersecurity/worldwide). Yet, you'll be hard-pressed to find one of the roughly [600 vendors](https://www.rsaconference.com/library/press-release/rsa-conference-2024-opens) that is making products to protect actual people ("consumers", in industry-speak).[^exception] Economic theorists might tell us that the public should reap the benefits of a cybersecurity industry that protects businesses from losses that might otherwise be passed onto consumers but, in practice, much of what the industry sells are compliance products to protect businesses from negligence lawsuits. The net effect is that these expenditures protect business from members of the public who might seek recompense for the prices we pay for business's *endless* stream of security failures.

What's worse, this industry produces security products that require highly-privileged access to customers networks and data, yet its code is rarely written to the high standard one such security-critical code deserves. The result: security technologies have introduced new vectors through which attackers can compromise even the organizations that are in greatest need of protection and invest the most in it. Or, as in the case of [CrowdStrike](https://en.wikipedia.org/wiki/2024_CrowdStrike-related_IT_outages), security products introduce entirely new failure modes that require no adversarial behavior to disrupt lives and incur billions of dollars of losses.

[^exception]: The notable exceptions that proves the rule are password managers. Some were founded with the mission of serving consumers, but shifted focus to enterprises after being purchased by private equity ([LastPass](https://en.wikipedia.org/wiki/LastPass)) or receiving investments from Venture Capitalists (1Password).

***Have we secured citizens from authoritarian technology?***

**Mostly we have done the opposite.** We have given authoritarians greater control over their citizens' access to technology.

In 2002 most citizens had *technological autonomy*: their primary computing device was a personal computer onto which they could install or compile any software they wanted. Their government might ban certain software and make it hard to find, but if it wanted its citizens to have access to modern technology, it had to give them access to general-purpose computing devices capable of running *any* software.[^TPMs]

[^TPMs]: Back in 2002, trusted platform modules appeared to be the biggest threat to software autonomy.

Then, Apple and Google discovered they could make more money if they monopolized the means through which software was distributed on their platforms. Their mobile platforms, iOS and Android, took away users' autonomy to install the software of their choosing. Security technologists at Apple and Google told users that their loss of autonomy was in their best interest. Many of us in the security research community agreed that the only way to prevent malware was to prevent users from having the choice to do so. Our culture of blaming users for failures of software architecture[^malware] helped industry justify robbing users of their autonomy. And, once industry could restrict users' access to software, governments could force industry to impose their own restrictions. Today, governments can decide whether we are allowed to use applications that can perform encryption, and they have turned our computing devices are used to surveil us, reducing our privacy.

[^malware]: Malware was so prevalent on personal computers because their security model gave all software the power to corrupt other software by default. Mobile operating systems sandboxed applications from each other by default, and evolved fined-grained permissions systems so that users would not need to give the games they downloaded access to their camera, contact information, and stored passwords.


***Do we still even aspire to keep people safe and building systems they can trust?***

**Depressingly, No**. In an Orwellian twist, we have allowed industry to pervert the very meanings of such basic concepts as safety and trust. Back in January 2002, the year I met Ross, Bill Gates laid out a corporate vision for what "Trust" meant to tech's de-facto leader of the time:

> Users should be in control of how their data is used. Policies for information use should be clear to the user. Users should be in control of when and if they receive information to make best use of their time. It should be easy for users to specify appropriate use of their information including controlling the use of email they send.
>
> …
>
> There are many changes Microsoft needs to make as a company to ensure and keep our customers’ *trust* at every level – from the way *we* develop software, to *our* support efforts, to *our* operational and business practices.[^emphasis]

[^emphasis]: Emphasis in quote added to highlight that when *Microsoft's* founder and then-CEO used the word "trust", he used it to hold *Microsoft* accountable to its users. The original January 15, 2002 memo is reproduced available via a [10-year retrospective from Microsoft](https://news.microsoft.com/2012/01/11/memo-from-bill-gates/) and a Wired article from [January 17, 2002](https://www.wired.com/2002/01/bill-gates-trustworthy-computing/).

Regardless of what you think of Gates, Microsoft's history[^microsoft-disclosure], or the extent to which Gates and Microsoft were able to deliver on those principles, *Gates was willing to state without ambiguity that "trust" meant being accountable to customers about the quality and safety of its products.*

[^microsoft-disclosure]: Disclosure: I worked at Microsoft Research from 2007 until 2016.

Contrast that with today's doublespeak, where today's tech companies use "trust and safety" to mean protecting users from others, so that their company can control how their users' data is exploited, where their users' attention goes, and to obscure how this all happens so that users remain as oblivious as possible. The industry we created has gaslit the public by redefining *trust and safety* to mean moderating others' content and access, eliding even the slightest consideration that the service itself, be it a social network, [dating app](https://stuartschechter.org/posts/safety-tips-dating-apps-omit/), or other platform, might not adequately protect the public's data or might sell that data to advertisers, governments, political parties, and anyone else willing to pay.

This capture of our lexicon has been enabled by the students our academic institutions have produced and by our academic research institutions themselves, which hold conferences dominated by industry members and that embrace this language.

Industry thrives on the talent that our research institutions train and we thrive by consuming the funding they provide. Our research institutions welcome with open arms those who advanced their careers by enabling the industry's most abusive oligarchs. In addition to cozying up to companies and institutions that we know to be actively trying to subvert the public good, many of us not only accept research funding from them, but brag about that research funding when brandishing our credentials. And we don't question when our institutions do it.

Many of our most prestigious scientific research institutions have helped to promote technologies that harm the public. Cornell Tech advertises [its placement](https://admissions.tech.cornell.edu/admitted/we-are-one-of-the-best-universities-for-blockchain/) on [CoinDesk's Best Universities for BlockChain](https://www.coindesk.com/layer2/2022/09/26/best-universities-for-blockchain-2022/). [Stanford](https://fdc.stanford.edu/) and [Berkeley](https://haas.berkeley.edu/blockchain/research/) (funded by cryptocurrency company Ripple) are also actively promoting their links to the *"industry"*. They show no shame for doing so because too few of us have had the courage to shame them.
<!-- Perhaps too many of us are fearful of sharing our disappointment of becoming outcasts in a community that stridently rejects attempts to examine our own complicity, or perhaps we fear examination of our own complicity. The belief that only (s)he who is without sin may cast the first stone only acts to ensure we all will remain unarmed and defenseless. -->

***Have we improved the study of the science of security?***

**Not significantly.** Our scientific culture perpetuates systems that subvert the truth. Scientist's success and prestige is not judged by the meticulousness of our methods or our caution against overstating the implications of our findings, but on how significant we can make our findings appear, how many papers we can publish, and whether these appear in venues of the highest prestige.[^weis] We gather for exclusive meetings amongst our research-area elites, to decide how we will distribute prestige, and pat ourselves on the back for performing this "community service". We direct our time and effort is directed at explaining to a super-majority of researchers submitting results that their work does not meet "the bar" for the arbitrarily-chosen acceptance rate that we believe maintains our desired the aura of prestige. We put service to our employers, and industry organizations, and program committees over service to science.

[^weis]: Ross didn't seem to care much about venue prestige. He refused to reposition the Workshop on Economics of Information Security as a conference even if it would have made it appear more prestigious on authors' CVs.

We know these institutions pervert how we conduct and evaluate science to serve their interests, but we choose complicity rather than risk our degrees, jobs, promotions, and social status. Perpetuating this system may be the default choice, *but it is a choice*. It is a choice we make make unconsciously every time we dedicate a service hour to peer reviewing a work to determine if it's worthy of prestige, when we could instead be helping others conduct more meticulous research and communicate it to the public more clearly.

It's not that most of us don't want to make pro-social choices and better the world. And some members of our community have had huge positive social impact. Two worthy examples are efforts to democratize public key infrastructure ([Let's Encrypt]()) and secure messaging ([Signal]()), both through not-for-profits. These wins came from principled people who believed that it should be safer for *everyone* who wants to publish information on the web, and safer for *everyone* to communicate with others over telecommunications networks. There's a lot to learn from these *exceptional* wins, and I do not mean to diminish them, but we can't get the most out of them if we fail to understand that they are, indeed, *exceptions*. We need to do more.

### What can we do?

We cannot fix problems if we deny their existence. We cannot fix problems if we deny our role in them.

One problem is that many of us in public-facing security roles purport that protecting the public (*users*) is our paramount goal when, in fact, our first obligation is to protect our employers.

Deception about who security is meant to protect underlies many of our other problems: the cybersecurity industry that protects companies from the public's negligence lawsuits, the cryptocurrency industry that protects organized crime's payment infrastructure, and big tech platforms protecting their monopolies. This deception is all enabled by security technologists who purport that their work directly or indirectly serves the public.

Whereas doctors are bound by the ethical code of nonmaleficence (do no harm), there is no code that obligates those of us working in security protect and inform the public when the public interest is in conflict with that of our employer.[^breach] If killing our metaphorical patients would save our employer money, many of our employers would tell us we have a duty to their shareholders to do so. A code of ethics would give us grounds to fight back.

[^breach]: Breach-disclosure laws attempt to remedy a symptom of this problem, but not the underlying cause.

Not everyone in our community would want to adopt a code that obligates them to protect the public over their employers, but there would still be great value to having such a code that we adopt, whether we agree to abide by it for one job or for our entire careers. We would all be better off knowing who working in the field believed it was their obligation to protect the public interest even when it was costly to their employers, and which companies were (and were not) willing to hire those who felt so obligated. Without such a code, those of us working in industry will continue to be expected by our employers to give the public the impression that our job is to protect the public, then expect us to make choices that put their shareholders before the people who believe we are there to protect them.

In addition to codes of behavior, we need to build a culture where we expect more from each other and help each other anticipate and make hard choices. We need to ask hard questions of each other, and we need to expect our peers to ask hard questions of us.

  - "Are you confident that your are making the choice that makes people's lives better?"
  - "Are you actively looking for ways you may be causing harm or are you actively trying not to look?"
  - "Is your ability to gauge whether this choice furthers the public interest compromised by it furthering your own interest or that of your employer?"
  - "Are you confident you are the protagonist in this story?"
  
<!-- Imagine if we all graduated from school with a support group that we could call not when we wanted someone to tell us someone we wanted to hear, but with peers who left with the same idealism that we had and who had promised to ask us these tough questions when the time came. -->

We need to all be a little more willing to ask ourselves, colleagues, friends, and those with power over us questions that are certain to make us all uncomfortable and some of us even angry.

Those most likely to be angered off will be people in authority who fear having their power undermined. We have to be prepared for them to brush us off with indignant responses, such as "Who died and made you the asshole who thinks it's okay to ask that kind of question?"

Funny you should ask.

His name was Ross Anderson.

---
Stuart would like to thank:
  - Cormac Herley for comments, ideas, and edits;
  - Maritza Johnson for comments and edits;
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
