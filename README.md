<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/facebook-wall-1.png" width="66%" />
</p>

# The Mastodon Science Collective

## The Basic Idea

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/facebook-wall-2.png" width="66%" />
</p>

Science Collective would be a fork of [the Mastodon project](https://joinmastodon.org/) which I hope to create and maintain to service the maverick science community.  The idea is that each maverick science thought leader would spin up their own [Twitter clone](https://mastodon.social/web/getting-started) dedicated to their particular project.  All of these instances can [federate with one another](https://github.com/tootsuite/documentation/blob/master/Using-Mastodon/User-guide.md#decentralization-and-federation) to form into meta-communities, and the fork would be designed to specifically support collaboration between these independent science communities.

| [![The Pre-Scientific Judgment of New Ideas](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-prescientific-judgment-of-new-ideas.jpg)](https://www.controversiesofscience.com/pre-scientific-judgment/worldview/card) | [![The Decline in Conceptual Revolutions](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-decline-in-conceptual-revolutions.jpg)](https://www.controversiesofscience.com/conceptual-revolutions/worldview/card) |
|:---:|:---:|
| There exists a cultural tendency today to judge complex scientific claims before enough details have been collected to justify those judgments | Is it possible that the rate of innovation in the sciences has been affected by cultural tendencies like this? |

The social network's primary purpose would be to set up a self-supporting ecosystem to support the vetting of challenges to entrenched scientific theories and the elaboration of groundbreaking science claims into predictive scientific hypotheses.  To get to that primary objective, science collective breaks the problem down into its constituent components:

1. Creating the infrastructure required to support the aggregation of information about controversial and groundbreaking science claims and questions.

2. Supplementing laypeoples' existing science education with details that are crucial for understanding controversial and groundbreaking science claims.

3. Establishing a process for the aggregation and binning of critique of scientific theories and science journalism, in order to transform from people who are **subject to** science claims, to people who can treat science claims **as objects** (basically helping them to think about science claims at a higher, more critical level). 

| [![The 5 Stages of the Mind](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-5-stages-of-the-mind.jpg)](https://www.controversiesofscience.com/the-5-stages-of-the-mind/worldview/card) | [![Why Critique Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-why-critique-science.jpg)](https://www.controversiesofscience.com/critique-science/worldview/card) |
|:---:|:---:|
| Science education and science journalism both encourage an approach to science which can stunt our cognitive development | One way to address the problem is to seek out the best critiques we can find |

## A Detailed Look at How this System Would Work

The fork's primary features would include:

*A Discourse Schema Which Brings Order to Process and the Against-the-Mainstream Science Space* - The site would introduce a structure for discussion which is intended to distinguish the different types of scientific discourse, because people who are seeking to elaborate existing models can oftentimes clash with people who are questioning assumptions and starting-point hypotheses for the purpose of constructing new models.

*Modeling Integration* - Support into the Mastodon instance for rendering [Jupyter notebooks](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) will enable the rendering of complex simulations in service of specific technical arguments.  Jupyter is sort of like an open-source, embeddable version of Mathematica.

> [The Jupyter Notebook App is a server-client application that allows editing and running notebook documents via a web browser. The Jupyter Notebook App can be executed on a local desktop requiring no internet access (as described in this document) or can be installed on a remote server and accessed through the internet.](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)

See [The Scientific Paper is Obsolete](https://www.theatlantic.com/science/archive/2018/04/the-scientific-paper-is-obsolete/556676/) for more information.

> I spoke to Theodore Gray, who has since left Wolfram Research to become a full-time writer. He said that his work on the notebook was in part motivated by the feeling, well formed already by the early 1990s, **“that obviously all scientific communication, all technical papers that involve any sort of data or mathematics or modeling or graphs or plots or anything like that, obviously don’t belong on paper. That was just completely obvious in, let’s say, 1990,” he said.**
>
> “It’s been a source of ongoing bafflement and consternation for the past 29 years, that with the exception of a few people who get it, the community at large hasn’t really adopted it,” he said. **“It’s incalculable, literally ... how much is lost, and how much time is wasted, and how many results are misinterpreted or are misrepresented.”**

| [![Why Outsider Mavericks Matter in Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-why-outsider-mavericks-matter-in-science.jpg)](https://www.controversiesofscience.com/outsider-mavericks/worldview/card) |
|:---:|
| Since certain groundbreaking scientific advances require that we reject some pre-existing theory, these problems are more likely to be resolved by maverick thinkers with little investment in the current ideas |

| [![The Stucture of Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-structure-of-science.jpg)](https://www.controversiesofscience.com/structure-of-science/worldview/card) |
|:---:|
| By bringing a newfound sense of organizational order to challenges to mainstream theory, it should be possible to enhance innovation in the sciences. The proposed schema would categorize interactions as clashes of worldview, model discussion, propositions and concepts. |

*Prediction Market Tracking, Integration and Standardization* - Integration of [the Auger blockchain](http://www.augur.net/) for registering and betting on scientific predictions; will probably require the creation of prediction standards to label those predictions which avoid common, predictable mistakes.

| [![The Science Futures Market](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-science-futures-market.jpg)](https://www.controversiesofscience.com/science-futures-market/worldview/card) |
|:---:|
| Although not all domains lend themselves well to the futures market approach, there are some specific areas where it can work quite well |

Some consideration needs to go into how Auger works, in order to get a better sense for what sort of integrations are possible with the site's token (e.g., does the Auger blockchain base upon its own token or coin?  Did they implement smart contracts?)

> [How Augur Works](http://www.augur.net/about/)
>
> Augur is a decentralized oracle and prediction market platform. Users feed real world information into Augur's contracts. Augur ensures the accuracy of this real world information by providing a financial incentive for REP token holders to correct markets they believe have been reported on incorrectly. There are several ways users can participate in Augur: you can trade shares in markets, create prediction markets, or participate in the reporting system to keep the Augur oracle honest.
>
> Markets & Trading
>
> On Augur, market creators set the event start and end times, a designated reporter, resolution source, and settlement fee. Traders can purchase shares in Augur markets immediately after market creation. The Augur contracts maintain an order book for every market created, and offer shares at the current best price. Settlement fees are paid by traders when positions are settled within a market. After the event has occurred, the outcome is determined by the designed reporter, or ultimately, Augur’s decentralized oracle, if necessary.
>
> Reporting
>
> REP (Reputation) token holders can participate in the Augur reporting system. REP token holders have the ability to dispute the tentative outcome of any Augur market within 7 days of resolution by staking a dispute bond. When doing so, the Augur market will go into a dispute round, where REP holders can stake REP tokens on one of the markets possible outcomes. If the tentative outcome is overturned, users who participated by staking on the new winning outcome will receive a 50% ROI. There is always a financial incentive to keep the Augur oracle reflecting reality.

*Integration with the Institute for Venture Science* - If there exists interest, my hope would be to work with Dr. Gerald Pollack of the University of Washington to fast-track the creation of controversy cards related to challenges being reviewed or funded by the [Institute for Venture Science](https://ivscience.org/).  The IVS has devised [a unique process for judging whether or not challenges to entrenched science research topics should be funded](https://www.controversiesofscience.com/ivs-process/worldview/card), and they are currently seeking out benefactors.  Much of the science collective idea was inspired by, and designed to work with, Dr. Pollack's IVS concept.

| [![The Institute for Venture Science Process](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-institute-for-venture-science-process.jpg)](https://www.controversiesofscience.com/ivs-process/worldview/card) |
|:---:|
| The IVS is a proposal for a special process which hopes to streamline the process of disruption in the sciences |

*Bounty-Based Moderation Reward Schema* - This would be [a karma-like system](https://en.wikipedia.org/wiki/Slashdot#Peer_moderation) where [ERC20 tokens](https://hackernoon.com/erc20-tokens-b3b50c95ad08) are used to reward the site's moderation and early adopters, similar in principle to how the [Steem-It social network](https://en.wikipedia.org/wiki/Steemit) operates.  Roles specifically suited for peer review are built into a checks-and-balances system ecology for reviewing content.  There would be rewards for identifying pertinent content (especially vindications); for proposing novel conjectures or analysis; for creating wikis and controversy cards which users end up actually using for annotations; for participating in the judgment of reviews; for exposing undesired behaviors on the site; for annotating content; etc.

([I do not assume that Ethereum will figure out how to scale](https://www.coindesk.com/information/will-ethereum-scale/), so it may make sense to hold off on implementation of the blockchain aspects of this proposal until a scalable blockchain exists.)

*A Federated System for Annotating Scientific Papers* - All federated sites can activate libraries of annotations according to Mastodon instance.  These are basically tags where keywords are assigned a ranked, context-filtered list of informational bits, for the purpose of automatically tagging textual content.  Over time, users and moderators would rate the utility of (and contextually bin) these annotations, with the hope that laypeople can eventually use this tool in the manner of an overlay, to understand complex scientific papers.  It's sort of like an annotation version of wikipedia, but specifically directed at helping people to read scientific papers that are difficult to understand.

| [![The Crowdsourcing of Scientific Controversies](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-crowdsourcing-of-scientific-controversies.jpg)](https://www.controversiesofscience.com/crowdsourcing/worldview/card) |
|:---:|
| Mastodon can provide the technology needed to crowdsource scientific controversies |

| [![The Annotation of Scientific Papers](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-annotation-of-scientific-papers.jpg)](https://www.controversiesofscience.com/annotations/worldview/card) |
|:---:|
| What if we were to design the system so that one output of this activity is a set of annotations which can subsequently be directed towards helping laypeople to understand complex scientific papers? |

*Controversy Card Annotations* - This is a library, partially constructed, of topics that are necessary to understand in the domain of scientific controversies.  They bin into six categories:

| category | description |
|:---:|:---|
| ongoing | Recent, ongoing controversies |
| historical | Controversies possibly still at play, but more historical in nature |
| person | Some people you should know about + character studies |
| reform | Relevant to academic reform and redesigning scientific discourse |
| critique | The best critical commentary ever published for modern science |
| thinking | How to think like a scientist about controversies |

The science collective fork of the Mastodon instance will be enhanced with an ability to annotate content with this controversy card content.  There are currently [182 controversy cards](https://plus.google.com/collection/Yhn4Y), but there are plans to expand this library to at least 500 cards.

Compared to wikis, the controversy card format is more story-based, more focused on the passing on of extraordinary critique, more graphical, and also more useful for sharing content to social media.  The site would moderate the creation of controversy cards, but wikis would be open to everybody.  And since the site's schema enables people to create conflicting wikis and controversy cards in different areas, turf battles between maverick against-the-mainstream thinkers and defenders of existing theory could be replaced with discussion of the actual debate.

*Federated Science Collective Search* - A component which can be placed onto a Mastodon instance which permits searching through all science collectives.

<p align="center">
    <a href="https://www.controversiesofscience.com">
        <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/controversies-of-science-homepage.png" width="50%" />
    </a>
</p>

*Social Media Article Snapshot Tool* - The point of this tool is to simplify the process of sharing quotes to social media platforms.

This would be a tool (possibly a chrome plugin?) for snapshotting science journalism quotes with the same color schema for font color and background, but with preferred font size, custom highlighting and framing options.  The tool would identify the original font, then reconstruct the quote (assuming that the font is accessible).  It would also present a variety of formats which would allow placement of either (or both) of an image and title from the article into the social media share.  I could incorporate this into the existing quotes database as metadata, and open the system to participation by others.

*A Process for Grooming Questions Into Testable Hypotheses* - This process is meant as a solution to the publish-or-perish problem, where researchers are subjected to a constant pressure to publish results even though original research can require decades to elaborate.

> [NO TIME TO THINK](http://www.nature.com/polopoly_fs/1.20872!/menu/main/topColumns/topLeftColumn/pdf/538446a.pdf)
>
> ... Two years into the position, Hermans was feeling overwhelmed. She was grappling with the responsibilities of managing her two graduate students and one postdoc, prepping for teaching courses, and what felt like endless ‘service’ requests to review papers for journals and colleagues. The spreadsheet work had in some ways run its course, and she wanted to pivot to a more stimulating research area. But the pressure to publish continuously and copiously dogged her. Her job is formally split between 40% teaching, 40% research and 20% academic service, but the message is that research should trump everything else. 'Four papers are better than three. And five are better than four,' she says.
> 
> Like Alberts, she says **the idea that research output is now synonymous with publication quashes all creativity. 'Papers are just one form of communicating ideas and experiments.' She yearns 'for an afternoon of looking out the window and thinking, ‘What will I do next?’'.**

<a href="https://www.controversiesofscience.com/pressure-to-publish/worldview/card">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-pressure-to-publish.jpg" width="100%" />
</a>

Each stage involves feedback.  The process begins with a proposition -- a question, claim or conjecture.  These propositions do not have to necessarily be original; they can simply be questions about existing hypotheses which a person wants to actively track.

If vindications can be found, they are then aggregated through a collaborative process known as tracking.  All of this tracking and discussion bins under the unique hashtag which is assigned to the original question.  As tracking progresses, any user can submit a request for review, which involves summarizing the claim, question or controversy as length-limited answers to a series of standard questions for a broader audience, who then weigh in on whether or not a controversy card should be created (the next step in this process).  Tracking does not stop once a controversy card is created, and at any point through the process, challenges can be lodged w/ their own hashtags, which then also become a focus for discussion.

[Mastodon's User Guide](https://github.com/tootsuite/documentation/blob/master/Using-Mastodon/User-guide.md)

> When you have a hashtag search open, it will automatically update with new toots. You can pin the column to keep the search open by clicking the settings symbol at the top right of the hashtag search column and clicking "pin".

*An Interface for Users to Track Numerous Controversial Claims* - This is simply a meta-tracking panel which shows metadata for each of the hashtags which a user is following.

| [![The Anti-Pattern of Settled Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-anti-pattern-of-settled-science.jpg)](https://www.controversiesofscience.com/settled-science/worldview/card) | [![Controversy-First Science Education](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-controversy-first-science-education.jpg)](https://www.controversiesofscience.com/controversy-first-science-education/worldview/card) |
|:---:|:---:|
| My thesis is that the tracking of scientific controversies over time is the secret missing sauce to evaluating what claims to focus upon | By flipping our approach, the maverick thinker is motivated to learn to think like a scientist through actual practice |

*A System for Assigning Expertise to Users* - As users track controversies, they are encouraged to establish their expertise through a set of activities: 

1.  They convert their learnings into force concept inventory questions for the purpose of helping others to gain fluency in their controversy.

2.  They present vindications in press releases which are then rated by others across a spectrum of criteria.  When other users agree that a vindication has occurred, they receive points to establish their expertise.

3. They create relevant concept maps, wikis or articles which other users agree add clarity to the controversy.

4. They annotate a crucial scientific paper which relates to their expertise in such a manner that laypeople are now able to understand it.

5. They propose experiments or observations which might vindicate the hypothesis.

(etc.)

The way that we will support these activities is to create the infrastructure required to reward particular activities like those listed above -- from providing the UI necessary to bin these activities, to providing the system necessary for other users to judge the contributions, to then providing the token rewards necessary to encourage the large-scale tracking of scientific controversies, to then also aiding in subsequent discovery by and education of other users.

*A System for Measuring a User's Generalization* - This would be a discovery-type tool which measures the breadth of a user's participation, and helps them to identify their own blindspots through exposure to new controversies outside of their preferred specialization.

I don't expect this feature to exist right away, because there needs to be enough social network history for there to be a need to condense the existing feeds into a more targeted service.

| [![The Generalist](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-generalist.jpg)](https://www.controversiesofscience.com/generalist/worldview/card) | 
|:---:|
| We need a platform which seeks to revive the generalist scientific tradition if we want groundbreaking breakthroughs to become a regular occurrence again |

| [![Innovation's Long Tail](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-innovations-long-tail.jpg)](https://www.controversiesofscience.com/long-tail/worldview/card) |
|:---:|
| Just as Amazon.com created a "long-tail" business by supporting millions of one-off sales, we can also facilitate collaboration by creating a platform which supports one-off informational exchanges |

*A System for Categorizing Contributions* - The following list is a schema which can act as the basis for categorizing, rewarding and discovering the informational content that is the backbone for tracking scientific controversies.  I don't expect that participants would always bin these properly, so there would need to be a process for correcting binning mistakes.

**THE CLASH OF WORLDVIEWS**

- *An Observational or Experimental Confirmation* - try to be concise if the link between the two is not immediately obvious; emphasis upon documenting the needed context for a typical layperson to understand it (you can assume they have read the controversy card, points deducted if there is some sort of misunderstanding of the controversy or science).

- *Links to the Best Related Critiques* - short-form journalism ("articles"); emphasis upon basic journalism and science standards; do not fall back upon overly-simplistic filters (like ignoring all publications by a particular source), take the time to actually evaluate the claims; emphasis upon the author's selection of details; upon applicability to the controversy; upon level of detail with the sourcing (please add corrections for broken links); emphasis upon empirical science over other forms (thought experiments, purely observational, excessive reliance upon constructs).

- *Press Releases or Scientific Papers that Relate to this Controversy* - not to be confused with PR's that more properly relate to the challenged theory; emphasis upon significance to the controversy; emphasis upon the logic of the claimed fit; points for filtering out unnecessary information or emphasizing the important bits (either bolding or highlighting); particular emphasis upon relevant points from scientific papers which have not shown up in mainstream science aggregators.

- *Noteworthy Online Discussions* - (please include URL to exchange and take high-resolution snapshots of the exchange by pressing command-plus a few times in your browser to embiggen the snapshotted text) emphasis upon identification of misconceptions or misguided "debunking"; upon proper addition of context (could people understand what the point of this was?); upon surprising claims; upon noting patterns discussed in controversy cards; upon character studies of the main players in online debates; upon any related online censorship; upon people who take the time to run claims and report back on their findings with snapshots; upon any discussions for how to deal with online challenges.  Points always deducted for evidence of any petty or trollish behaviors (or any other violation of the site's own principles when members interact with the larger science community since these behaviors can lead to stereotypes).

- *Observational / Experimental Suggestions* - pretend you are a graduate student who actually had access to facilities, equipment and funding, can you devise a test that might resolve the debate?  emphasis upon whether or not sufficient technical detail was provided to fully understand the idea; upon whether or not people think it might work; points for creative problem-solving.  Don't hold ideas back here if you lack all of the quantitative details, assume that somebody else at a later time may be able to help with that.

- *Crucial Resources* - where would somebody go to get a deeper background in this subject? if it's just a chapter of a larger book, please identify (or if helpful) describe the chapters; emphasis upon whether or not the material is accessible to laypeople, but technical materials are of course important here too; if the material is very technical, the reviewer can rank the material higher if they provide their own annotated version of the resource.  Opinions on how to properly approach the subject are encouraged.

**MODEL TALK**

- *The Best Explanations* - selected according to usage of visuals, clarity on assumptions, good presentation of historical context, thorough conceptual explanation of any presented mathematics, written at a level that a layperson non-scientist can understand.  These pieces should not be rated on the basis of age so long as there is no confusion generated from the introduction of that former context.

- *Modeling Practices & Assumptions* - explanation of some particular modeling practice or assumption (preferably focused on just one at a time), with an emphasis upon how the practice/assumption would be conveyed within scientific papers or press releases (such that the reader is now better equiped to identify this pattern in the future).  Points for emphasis upon hidden practices or assumptions whose exposure alters the interpretation of the results.  This would be a good spot to place discussions about statistics.

- *The History and Origin of the Idea* - emphasis upon unexpected context, little-known historical facts/interpretations or popular beliefs, famous or otherwise important quotes.

- *Tracking the Science Journalism and Public Perception* - emphasis upon tracking changes in the journalism; upon initial expressions of surprise or honest admissions which are subsequently rolled into the model (which can help us to identify hindsight biases); upon any omission of context or detail which undermines the offered conclusions; upon materials presented purely for their clickbait attributes; upon dubious logic.  Extra points for those who take the time to dig up some unexpected science journalism gem from the distant past which gives us some insight on how ideas have transformed over time.

- *Press Releases that Relate to the Challenged Theory* - not to be confused with PR's that are more directly relevant to the controversy, and realize there is a category already dedicated to inconsistences and anomalies; try to focus people on the specific part you want them to read, and help us understand why it should matter to us.

- *Things to Know About Wikipedia's Coverage on This* - think supplemental -- the point is not to replicate work already done on Wikipedia (this is analysis, not duplication); emphasis upon ideology posing as facts, questionable selection of evidence, information about wiki wars and activities of those known to abuse the platform.  If the entry (and its history) is unremarkable and uncontroversial, then this bin should be empty.

- *The Inconsistencies and Anomalies* - emphasis upon internal inconsistencies and any attempts to resolve them -- born of either observations or logic; slight emphasis upon those which are more empirically established, but it's okay if some of these turn out to be to incorrect (let's keep a broad dragnet).

**PROPOSITIONS**

- *Dumb Questions* - emphasis upon how common these questions pop up.

- *Poignant Questions* - do not judge these questions on your perception of whether or not they will prove true; the emphasis is upon asking good questions that can in some way be justified; emphasis upon creativity and synthesis (bringing together two ideas whose connection is not immediately obvious).

- *Creative Conjectures* - a general-purpose bin for conjectures; ranking might not be necessary.

- *Confident Claims*

- *Predictions* - emphasis upon the rationale (does this person know something we previously did not?); points after-the-fact if it proves correct.

**CONCEPTS**

- *Concept Maps* - emphasis upon use of concept maps as a pedagogical tool.

- *Explain the Math* - emphasis upon the conceptual explanation or critique of some mathematics.

- *Multiple Representations in Multiple Agents* - emphasis upon some mismatch in definitions, either according to worldview or domain.

**NARRATIVES**

- *Examples* - emphasis upon exposure of unsupported or faddish narratives; upon effective demonstrations, with evidence, that the narratives are off.

## Moderation and Comments Infrastructure

Science collectives need a system of comments and feedback which is appropriate for the objectives, and which bases upon a survey of similar existing systems.  We should not necessarily approach the existing Mastodon UI as a complete or appropriate solution to these problems.

For example, Slashdot's karma system empowers users to rate one anothers' content, but deprives them of this power once they participate in the conversation.

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/slashdot-moderation.png" width="100%" />
</p>

The Slashdot system for rating content can observably produce unusual results for science conversations.  [In this case](https://science.slashdot.org/comments.pl?sid=11892849&cid=56312159), an invitation to track scientific controversies is labeled as "Troll", [a term which was originally intended to describe insincere agitators](https://www.controversiesofscience.com/troll/worldview/card) ...

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/slashdot-troll.jpg" width="50%" />
</p>

So, are there any aspects of these mechanics worth copying?

Phys.org comments, by contrast, do not prevent users from judging contributions in the conversations they participate in.  When phys.org moderators decide that a user has violated their policy, they might choose to remove every single post the user has ever made, [with results which today look like this](https://phys.org/news/2018-01-black-hole-breakthrough-insight-mysterious.html):

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/physorg-comments.png" width="100%" />
</p>

You might wonder about the nature of this commentary that was removed.  Most of what was removed [looks like this](https://web.archive.org/web/20180111042502/https://phys.org/news/2018-01-black-hole-breakthrough-insight-mysterious.html):

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/physorg-censored-comments-1.png" width="100%" />
</p>

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/physorg-censored-comments-2.png" width="100%" />
</p>

Notice that comment scores oftentimes end up pegged to one of the two ends of the 5-point spectrum.

The phys.org policy [directs its users to read wikipedia's definition of pseudoscience](https://sciencex.com/help/comments/).

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/physorg-policies.png" width="100%" />
</p>

They equate "non-mainstream theories" with "pseudoscience".

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/physorg-pseudoscience.png" width="100%" />
</p>

One thing to notice about their guidelines is that this is not so much a purpose-driven, principled approach, but rather focused upon the minutia, the transactional details which would ideally be handled by the infrastructure and system for feedback.  What's interesting about phys.org's policy on non-mainstream theories is that it seems to leave the suggestion that the point of the comments is to support mainstream theory.  It can be argued that the guidelines say a lot about the point of comments on phys.org.

Another commenter, Captain_Stumpy, [is permitted to repeatedly and overtly violate phys.org's policy against "avoiding personal attacks and name calling"](https://phys.org/news/2017-11-closest-temperate-world-orbiting-quiet.html) -- one imagines because he is defending mainstream science:

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/captain-stumpy.png" width="100%" />
</p>

Phys.org comments are length-limited to 1000 characters, but users are allowed to post another comment within 3 minutes.  Mastodon does not implement the 3-minute delay, but it does apply a 500-character limit to each individual chunk.  Neither phys.org nor slashdot permit inline images, and for the user's protection, slashdot annotates links with the link's domain.  That's in part because slashdot permits the user to write their post in HTML, thus obscuring links behind anchor tags.

Chunking seems to have a positive effect upon encouraging the participant to keep their contributions concise -- on Twitter, Mastodon and phys.org.  Twitter seems to not count every letter inside of links towards these limits.

Slashdot and Twitter discussions are threaded, whereas sites like physorg and Mastodon seem to bin comments into flat feeds.

One observation is that chunking seems to rely heavily upon links to off-site content.  Users oftentimes ignore links when there is no excerpt which indicates the link's content.  Also, websites are ephemeral.  Content can completely disappear, and it may or may not be archived on Google's Wayback Machine.  One idea worth considering is that excerpts should not count towards the character limit.  The same effect, more-or-less, can be had by attaching screenshots to Twitter posts.

Reddit differs in that they order comments on the basis of votes.

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/reddit-ranking.png" width="100%" />
</p>

Notice that they also provide the option to sort comments by "Controversial".

[One commenter notes](https://www.reddit.com/r/AskReddit/comments/3xk6rl/how_exactly_do_reddit_pointsupvotes_work/) that

> Its supposed to be a way of acknowledging quality posts, but it's basically a like/disagree button.

This same pattern is observed on Slashdot, Phys.org and Reddit.

Another commenter notes:

> I have a theory that the voting system is what makes Reddit awesome.
>
> Compare it to the standard first-come, first-shown system. For some idiot with anti-social views, this is his one chance to get his views amplified. The pay-off here is high.
>
> Normally he can’t get anyone to listen. But if he quickly writes something inflammatory, he can spend a happy afternoon jousting with people he made angry.
>
> Intelligent people look at the animals head-butting each other in the comments section and can see no reason to get involved.
>
> On Reddit, it's not like that. The incentive system is powerful. Instead of bad comments floating round riling people up, they disappear. That disincentivises trolls. And good comments are rewarded. This creates a problem in the opposite direction, a la Unidan.

Reddit is also somewhat unique in that it also tracks downvotes, while also prioritizing more recent comment.  There is some interesting commentary on this online ...

> [Effects of downvotes](https://medium.com/hacking-and-gonzo/how-reddit-ranking-algorithms-work-ef111e33d0d9)
>
> Reddit is one of the few sites that has downvotes ...
>
> This has a big impact for stories that get a lot of upvotes and downvotes (e.g. controversial stories) as they will get a lower ranking than stories that just get upvotes. This could explain why kittens (and other non-controversial stories) rank so high :)
>
> Conclusion of Reddit’s story ranking
>
> - Submission time is a very important parameter, generally newer stories will rank higher than older
> - The first 10 upvotes count as high as the next 100. E.g. a story that has 10 upvotes and a story that has 50 upvotes will have a similar ranking
> - Controversial stories that get similar amounts of upvotes and downvotes will get a low ranking compared to stories that mainly get upvotes

The problem with Reddit (and other sites, such as phys.org), to my eye, is that the ranking occurs along a single ambiguous dimension.  Some architects I've spoken to about the subject claim that people are not capable of adapting to complex content rating systems.  That may make sense for generalized systems like Reddit, but I would argue that this makes less sense for systems like phys.org which are focused specifically on the subject of science.  What is the point of designing content rating systems to accommodate the lowest common denominator when the subject matters relate to complex scientific questions?

The risk of adding complexity to these rating systems is that users will not understand them, with the consequence that nobody would use them.

## First Steps

My first need is to get some firsthand experiences with the Mastodon codebase, its stability and its typical monthly costs.  Since my time is too constrained to explore new Cloud platforms; since I'd like to explore the possibility of porting the system from t2's to AWS Lambda functions; and since I'd like to merge my existing codebase into the Mastodon instance, I'm going to attempt to deploy Mastodon to [an AWS t2.medium instance](https://discourse.joinmastodon.org/t/q-costs-of-running-a-server/77/3).

> You will need either a t2.small with a swap partition (not sure this is possible or recommended) or a t2.medium, due to the amount of memory used by the app when it runs and when it is precompiling assets. I have seen the precompile process alone consume (just slightly) over 1G of memory at peak. Since these EC2 boxes only have EBS storage by default, they do not come with swap partitions and thus if you run out of memory everything will stop until the oomkiller comes out to play. I think you probably know this stuff, I’m partly writing it for other people who find this question and have different levels of background knowledge.
>
> You are in danger of running out of disk space though if you store uploaded media on the instance, so you might want to use S3 and/or CloudFront to store/distribute uploads/media. Right now I’m paying maybe $10 CAD a month for S3 and CloudFront (which is optional). There are things you can do to reduce the amount of storage you need, like deleting old uploads/media, or ones from other instances (remote media is cached).
> 
> So your basic fixed cost is just an EC2 t2.medium
>
> From there you can really go wild with the various AWS services if you feel like it, but it will increase your cost significantly and you probably won’t see much benefit from it unless you end up supporting more users than you anticipate. I use RDS for the DB, ElastiCache for redis, and an ALB instead of nginx to proxy the app servers (as well as do HTTPS and HTTP2 termination). None of it is necessary, I just do it for fun, and to see how it would work.

There are a few guides ([here](https://github.com/ummjackson/mastodon-guide/blob/master/up-and-running.md), [here](https://github.com/tootsuite/documentation/blob/master/Running-Mastodon/Production-guide.md) and [here](https://www.makeuseof.com/tag/social-network-set-mastodon-instance-linux/)) which guide the installation process.  Although there exists a couple of sites ([here](https://github.com/ceejbot/mastodon-ansible) and [here](https://medium.com/@aureliendemilly/deploy-a-mastodon-instance-aec81d17f18a)) which are specifically directed at getting Mastodon to work on AWS, there's not a lot of information dedicated to the subject.  The second AWS explanation appears to be the easiest and interests me the most because it involves use of an interesting tool named [Terraform](https://www.terraform.io/intro/index.html), which I might need to use later when it's time to package up new science collectives.

> Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing and popular service providers as well as custom in-house solutions.
>
> Configuration files describe to Terraform the components needed to run a single application or your entire datacenter. Terraform generates an execution plan describing what it will do to reach the desired state, and then executes it to build the described infrastructure. As the configuration changes, Terraform is able to determine what changed and create incremental execution plans which can be applied.
>
> The infrastructure Terraform can manage includes low-level components such as compute instances, storage, and networking, as well as high-level components such as DNS entries, SaaS features, etc.

I am able to estimate that the EC2 costs should be around $40 per month, based upon the $0.052 hourly charge, but there will also be S3 costs associated with the users' assets and a very small charge associated with the domain.  Ideally, the cost would be more in the neighborhood of $10/month, and I wonder if implementing the backend as lambdas might reduce the system's costs (?).  But, my most immediate interest is to simply learn how the Mastodon system works, for the purpose of creating Science Collective by merging the Controversies of Science site into Mastodon's codebase.

So ...

Step 1: Secure a route53 domain (domain: sciencecollective.org)

Step 2: Get an SSL certificate for the domain (done)

Step 3: Set up a VPC ready to host an EC2 machine (presumably generating subnet, security group and zone id)

Step 4: Set up a mail server (generating SMTP server, login, password and from address)

Step 4: Install Terraform (done)

Step 5: Fill out Terraform configuration file

Step 6: Run Terraform

## About Me

My name is Chris Reeve, and I have been tracking scientific controversies as a layperson for 12 years now.  I have a Bachelors in Electrical and Computer Engineering from Carnegie Mellon University.  My interest in scientific controversies began when I embedded myself into [an against-the-mainstream group of theorists who have struggled to have their arguments heard out](http://www.thunderbolts.info).

Since then, I have created the [Controversies of Science search portal prototype](https://www.controversiesofscience.com) to showcase my existing collection of [182 controversy cards](https://plus.google.com/collection/Yhn4Y).

I am now attempting to apply what I've learned from those experiences running claims against critics and the public, towards the creation of a scientific social network where maverick layperson thinkers work with science specialists and academic researchers to vet and aggregate information about challenges to entrenched scientific theories.

I became a full-stack engineer 3 years ago, in part to create this social network.  Today, I am a React developer building out an e-commerce site for a stealth startup in San Francisco, CA.  While the ideas presented here may sound lofty, it is my long-term mission in life to reform the way our culture interacts with controversial science claims.  I will continue to track scientific controversies for the remainder of my life, because I feel that tracking is the missing ingredient which modern science needs to avoid [innovation starvation](https://www.controversiesofscience.com/innovation-starvation/worldview/card).

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/chris-giving-talk.png" width="50%" />
</p>