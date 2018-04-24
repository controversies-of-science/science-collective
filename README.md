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

### Is Science Collective like Slashdot.org?

For example, Slashdot's karma system empowers users to rate one anothers' content, but deprives them of this power once they participate in the conversation.

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/slashdot-moderation.png" width="100%" />
</p>

The Slashdot system for rating content can observably produce unusual results for science conversations.  [In this case](https://science.slashdot.org/comments.pl?sid=11892849&cid=56312159), an invitation to track scientific controversies is labeled as "Troll", [a term which was originally intended to describe insincere agitators](https://www.controversiesofscience.com/troll/worldview/card) ...

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/slashdot-troll.jpg" width="50%" />
</p>

I've spent [a few months posting critiques of modern science theories to Slashdot](https://slashdot.org/~paradigmsareconstruc).  I received a karma boost from an accepted submission, but I found that just going through the process of responding to people led me to lose a significant amount of my karma.  This would seem to cause a problem for the types of comments which are posted there: When people are taking the time to post information and arguments which are intended to be persuasive, this person is spending their own personal time to increase the quality of content on the social network.  They should not burn through their karma for the sin of bringing value to this network.  Such a rewards structure disincentivizes its user base from any sort of claim which might diverge from the mainstream view.

### Is Science Collective like Phys.org?

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

Notice that comment scores oftentimes end up pegged to one of the two ends of the 5-point spectrum on phys.org.

The phys.org policy [directs its users to read wikipedia's definitions for pseudoscience and internet trolls](https://sciencex.com/help/comments/).

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/physorg-policies.png" width="100%" />
</p>

They loosely equate "non-mainstream theories" with "pseudoscience".

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/physorg-pseudoscience.png" width="100%" />
</p>

One thing to notice about their guidelines is that this is not so much a purpose-driven, principled approach, but rather focused upon the minutia, the transactional details.  One guideline about avoiding pointless verbiage is borderline pedantic.  What's interesting about phys.org's policy on non-mainstream theories is that it seems to leave the suggestion that the point of the comments is to support mainstream theory.  It can be argued that the guidelines say a lot about the point of comments on phys.org.

Another commenter, Captain_Stumpy, [is permitted to repeatedly and overtly violate phys.org's policy against "avoiding personal attacks and name calling"](https://phys.org/news/2017-11-closest-temperate-world-orbiting-quiet.html) -- one imagines because he is defending mainstream science:

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/captain-stumpy.png" width="100%" />
</p>

Phys.org comments are length-limited to 1000 characters, but users are allowed to post another comment within 3 minutes.  Mastodon does not implement the 3-minute delay, but it does apply a 500-character limit to each individual chunk.  Neither phys.org nor slashdot permit inline images, and for the user's protection, slashdot annotates links with the link's domain.  That's in part because slashdot permits the user to write their post in HTML, thus obscuring links behind anchor tags.

Chunking seems to have a positive effect upon encouraging the participant to keep their contributions concise -- on Twitter, Mastodon and phys.org.  Twitter seems to not count every letter inside of links towards these limits.

Slashdot discussions are threaded, whereas sites like physorg, Twitter and Mastodon seem to bin comments into more of a flat structure.

One observation is that chunking seems to rely heavily upon links to off-site content.  Users oftentimes ignore links when there is no excerpt which indicates the link's content.  Also, websites are ephemeral.  Content can completely disappear, and it may or may not be archived on Google's Wayback Machine.  One idea worth considering is that excerpts should not count towards the character limit.  The same effect, more-or-less, can be had by attaching screenshots to Twitter posts.

### Is Science Collective like Reddit?

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

Reddit's system for ranking comments has undergone an important change in recent years that is described [here](https://medium.com/hacking-and-gonzo/how-reddit-ranking-algorithms-work-ef111e33d0d9), [here](https://redditblog.com/2009/10/15/reddits-new-comment-sorting-system/) and [here](http://www.evanmiller.org/how-not-to-sort-by-average-rating.html).

Since rapid access to the best information is part of the mission for Controversies of Science, it seems likely that both versions of the feed are needed -- the usual chronological version that comes with Mastodon, but also this alternative sorted version.

[Here's an explanation of how this system works:](https://redditblog.com/2009/10/15/reddits-new-comment-sorting-system/)

> reddit is heavily biased toward comments posted early. When a mediocre joke gets posted in the first hour a story is up, it will become the top comment if it’s even slightly funny. (I know this particularly well because I have dozens of reddit fake identities and with them have posted hundreds of mediocre jokes.) The reason for this bias is that once a comment gets a few early upvotes, it’s moved to the top. The higher something is listed, the more likely it is to be read (and voted on), and the more votes the comment gets. It’s a feedback loop that cements the comment’s position, and a comment posted an hour later has little chance of overtaking it — even if people reading it are upvoting it at a much higher rate.
>
> There are periodically big threads with subjects like “what’s your favorite joke/best advice/worst secret/weirdest habit?” A few weeks ago, I took one of these stories when it was 8 hours old and did a count of the top (root) comments. Of the top 10 comments, ALL were posted either “7 hours ago” or “8 hours ago” — that is, in the first hour or two the story had been up. The “top” list was simply a list of the best jokes from within the first hour. Not a single joke from the last six hours (when most of the comments had been posted) made it near the top. And they never got a chance to; the story fell off the frontpage and they all stopped accumulating votes. They may have been getting upvotes from everyone who saw them, but that didn’t let them catch up to the older comments at the top. One effect of this bias, which you may have seen, is posts saying “sorry to hijack your top comment, but I need to post some important information that refutes the main article.” They know that no matter how good their comment is, it won’t make it to the top.
>
> ... There’s a solution, and it’s the new ‘Best’ ranking. When a few people have voted on a comment, you get a rough idea of its quality. The more people who vote on it, the better an idea you get of where it ‘should’ ultimately end up. With this algorithm, you quantify exactly how much you can tell about a comment from a limited number of votes.
>
> If everyone got a chance to see a comment and vote on it, it would get some proportion of upvotes to downvotes. This algorithm treats the vote count as a statistical sampling of a hypothetical full vote by everyone, much as in an opinion poll. It uses this to calculate the 95% confidence score for the comment. That is, it gives the comment a provisional ranking that it is 95% sure it will get to. The more votes, the closer the 95% confidence score gets to the actual score.
>
> If a comment has one upvote and zero downvotes, it has a 100% upvote rate, but since there’s not very much data, the system will keep it near the bottom. But if it has 10 upvotes and only 1 downvote, the system might have enough confidence to place it above something with 40 upvotes and 20 downvotes — figuring that by the time it’s also gotten 40 upvotes, it’s almost certain it will have fewer than 20 downvotes. And the best part is that if it’s wrong (which it is 5% of the time), it will quickly get more data, since the comment with less data is near the top — and when it gets that data, it will quickly correct the comment’s position. The bottom line is that this system means good comments will jump quickly to the top and stay there, and bad comments will hover near the bottom. (Picky readers might observe that some comments probably get a higher rate of votes, up or down, than others, which this system doesn’t explicitly model. However, any bias which that introduces is tiny in comparison to the time bias which the system removes, and comments which get fewer overall votes will stay a bit lower anyway due to lower confidence.)

A problem with Reddit (and other sites, such as phys.org), to my eye, is that the ranking occurs along a single ambiguous dimension.  Some architects I've spoken to about the subject claim that people are not capable of adapting to complex content rating systems.  That may make sense for generalized systems like Reddit, but I would argue that this makes less sense for systems like phys.org which are focused specifically on the subject of science.  What is the point of designing content rating systems to accommodate the lowest common denominator when the subject matters relate to complex scientific questions?

The risk of adding complexity to these rating systems is that users will not understand them, with the consequence that nobody would use them.  But, the upside of such a system -- if it can be made to work -- is that since contributions to the Science Collective social network would be binned by a schema which differentiates the contributors' various motives, ratings can be applied in a manner which bubble to the top those contributions which service the actual processes of the scientific method.

For example, one type of content which should be rewarded is listed above as:

> *An Observational or Experimental Confirmation* - try to be concise if the link between the two is not immediately obvious; emphasis upon documenting the needed context for a typical layperson to understand it (you can assume they have read the controversy card, points deducted if there is some sort of misunderstanding of the controversy or science).

So, it's as simple as this: When a contributor posts his contribution, he will be given the opportunity to classify it as an observational or experimental confirmation.  Then, when the contribution is presented to the other site users, those users are asked to then judge the contribution according to the standards associated with that specific activity:

- Did the contributor clarify the link between the vindication and the original claim?

- Was the necessary context pointed out?

Providing these specific questions as opportunities for specific feedback would allow us to set up these different bins where contributions can be ranked according to these specific, targeted criteria.  Users are not forced to adhere to these processes, but when they do, the contributions can rank better.

### Is Science Collective like Stack Overflow?

There's a recent retrospective article on Stack Overflow [here](https://www.joelonsoftware.com/2018/04/06/the-stack-overflow-age).  Stack Overflow is of course a way for developers to quickly navigate to answers to common questions.

> We wanted the whole thing to be a fun game, with incentives to answer questions, so we had a reputation system. The more you answer, the more reputation you earn. The reputation idea had been seen before on sites like Slashdot and Reddit.
>
> As you earn reputation, you also earn moderation privileges on the site. So the site actually moderates itself, which is pretty cool.
>
> Instead of putting all the Java programmers in one little forum and all the C++ programmers in another, we dumped everyone together and just let them tag their questions. This idea was stolen from flickr (remember flickr?) who, I think, stole it from del.icio.us (now gone)—who knows, anyway, the point is, tags were the new hotness and made Stack Overflow work great.
>
> Most importantly, we realized that each question is asked by one person but the answers are seen by thousands of people who found it through a search. So we decided to optimize everything to be useful for the thousands, not the individual. We literally have 1000 visitors for every person who asks a question. That’s why we sort the answers by votes. It’s also why we optimize for questions and answers that will be helpful to other people, later.

Stack Overflow's rewards system is explained in [a second extremely important article which I need to excerpt at length](https://www.joelonsoftware.com/2018/04/13/gamification/):

> Stack Overflow reputation started as a very simple score. The original idea was just that you would get 10 points when your answers were upvoted. Upvotes do two things. They get the most useful answers to the top, signaling that other developers who saw this answer thought it was good. They also send the person who wrote the answer a real signal that their efforts helped someone. This can be incredibly motivating.
>
> You would lose points if your questions were downvoted, but you actually only lose 2 points. We didn’t want to punish you so much as we wanted to show other people that your answer was wrong. And to avoid abuse, we actually make you pay one reputation point to downvote somebody, so you better really mean it. That was pretty much the whole system.
>
> Now, this wasn’t an original idea. It was originally inspired by Reddit Karma, which started out as an integer that appeared in parentheses after your handle. If you posted something that got upvoted, your karma went up as a “reward.” That was it. Karma didn’t do a single thing but still served as a system for reward and punishment.
>
> What reputation and karma do is send a message that this is a community with norms, it’s not just a place to type words onto the internet. (That would be 4chan.) We don’t really exist for the purpose of letting you exercise your freedom of speech. You can get your freedom of speech somewhere else. Our goal is to get the best answers to questions. All the voting makes it clear that we have standards, that some posts are better than others, and that the community itself has some norms about what’s good and bad that they express through the vote.
>
> It’s not a perfect system (more on the problems in a minute), but it’s a reasonable first approximation.
>
> By the way, Alexis Ohanian and Steve Huffman, the creators of Reddit, were themselves inspired by a more primitive karma system, on Slashdot. This system had real-world implications. You didn’t get karma so that other people could see your karma; you got karma so that the system knew you weren’t a spammer. If a lot of your posts had been flagged for abuse, your karma would go down and you might lose posting or moderation privileges. But you weren’t really supposed to show off your high karma. “Don’t worry too much about it; it’s just an integer in a database,” Slashdot told us.
>
> To be honest, it was initially surprising to me that you could just print a number after people’s handles and they would feel rewarded. Look at me! Look at my four digit number! But it does drive a tremendous amount of good behavior. Even people who aren’t participating in the system (by working to earn reputation) buy into it (e.g., by respecting high-reputation users for their demonstrated knowledge and helpfulness).
>
> But there’s still something of a mystery here, which is why earning “magic internet points” is appealing to anyone.
>
> I think the answer is that it’s nice to know that you’ve made a difference. You toil away in the hot kitchen all day and when you serve dinner it’s nice to hear a compliment or two. If somebody compliments you on the extra effort you put into making radish roses, you’re going to be very happy.
>
> This is a part of a greater human need: to make an impact on the world, and to know that you’re contributing and being appreciated for it. Stack Overflow’s reputation system serves to recognize that you’re a human being and we are super thankful for your contribution.
>
> ... That said, there is a dark side to gamification. It’s not 100% awesome.
>
> The first problem we noticed is that it’s very nice to get an upvote, but getting a downvote feels like a slap in the face. Especially if you don’t understand why you got the downvote, or if you don’t agree. Stack Overflow’s voting has made many people unhappy over the years, and there are probably loads of people who felt unwelcome and who don’t participate in Stack Overflow as a result. (Here’s an old blog post explaining why we didn’t just eliminate downvotes).
>
> ... Gamification can shape behavior. It can guide you to do certain things in certain ways, and it can encourage certain behaviors. But it’s a very weak force. You can’t do that much with gamification. You certainly can’t get people to do something that they’re not interested in doing, anyway. I’ve heard a lot of crazy business plans that are pinning rather too high hopes on gamification as a way of getting people to go along with some crazy scheme that the people won’t want to go along with. Nobody’s going to learn French just to get the Duolingo points. But if you are learning French, and you are using Duolingo, you might make an effort to open the app every day just to keep your streak going.

### Is Science Collective like Hacker News?

http://www.paulgraham.com/hackernews.html

> Internet conversation generally is only a few decades old. So we've probably only discovered a fraction of what we eventually will.
>
> That's why I'm so optimistic about HN. When a technology is this young, the existing solutions are usually terrible; which means it must be possible to do much better; which means many problems that seem insoluble aren't. Including, I hope, the problem that has afflicted so many previous communities: being ruined by growth.

Here's their site policy:

> [Welcome to Hacker News](https://news.ycombinator.com/newswelcome.html) 
>
> Hacker News is a bit different from other community sites, and we'd appreciate it if you'd take a minute to read the following as well as the official guidelines.
>
> HN is an experiment. As a rule, a community site that becomes popular will decline in quality. Our hypothesis is that this is not inevitable—that by making a conscious effort to resist decline, we can keep it from happening.
>
> Essentially there are two rules here: don't post or upvote crap links, and don't be rude or dumb in comment threads.
>
> A crap link is one that's only superficially interesting. Stories on HN don't have to be about hacking, because good hackers aren't only interested in hacking, but they do have to be deeply interesting.
>
> What does "deeply interesting" mean? It means stuff that teaches you about the world. A story about a robbery, for example, would probably not be deeply interesting. But if this robbery was a sign of some bigger, underlying trend, perhaps it could be.
>
> The worst thing to post or upvote is something that's intensely but shallowly interesting: gossip about famous people, funny or cute pictures or videos, partisan political articles, etc. If you let that sort of thing onto a news site, it will push aside the deeply interesting stuff, which tends to be quieter.
>
> The most important principle on HN, though, is to make thoughtful comments. Thoughtful in both senses: civil and substantial.
>
> The test for substance is a lot like it is for links. Does your comment teach us anything? There are two ways to do that: by pointing out some consideration that hadn't previously been mentioned, and by giving more information about the topic, perhaps from personal experience. Whereas comments like "LOL!" or worse still, "That's retarded!" teach us nothing.
>
> Empty comments can be ok if they're positive. There's nothing wrong with submitting a comment saying just "Thanks." What we especially discourage are comments that are empty and negative—comments that are mere name-calling.
>
> Which brings us to the most important principle on HN: civility. Since long before the web, the anonymity of online conversation has lured people into being much ruder than they'd be in person. So the principle here is: don't say anything you wouldn't say face to face. This doesn't mean you can't disagree. But disagree without calling names. If you're right, your argument will be more convincing without them. 

[This commentary by Paul Graham on broken windows](http://www.paulgraham.com/hackernews.html) is especially thought-provoking ...

> It's pretty clear now that the broken windows theory applies to community sites as well. The theory is that minor forms of bad behavior encourage worse ones: that a neighborhood with lots of graffiti and broken windows becomes one where robberies occur. I was living in New York when Giuliani introduced the reforms that made the broken windows theory famous, and the transformation was miraculous. And I was a Reddit user when the opposite happened there, and the transformation was equally dramatic.
>
> I'm not criticizing Steve and Alexis. What happened to Reddit didn't happen out of neglect. From the start they had a policy of censoring nothing except spam. Plus Reddit had different goals from Hacker News. Reddit was a startup, not a side project; its goal was to grow as fast as possible. Combine rapid growth and zero censorship, and the result is a free for all. But I don't think they'd do much differently if they were doing it again. Measured by traffic, Reddit is much more successful than Hacker News.
>
> But what happened to Reddit won't inevitably happen to HN. There are several local maxima. There can be places that are free for alls and places that are more thoughtful, just as there are in the real world; and people will behave differently depending on which they're in, just as they do in the real world.
>
> I've observed this in the wild. I've seen people cross-posting on Reddit and Hacker News who actually took the trouble to write two versions, a flame for Reddit and a more subdued version for HN.

[This commentary on the Fluff Principle](http://www.paulgraham.com/hackernews.html) is also compelling, but may relate more to the creation of controversy cards than moderation of comments ...

> The most dangerous thing for the frontpage is stuff that's too easy to upvote. If someone proves a new theorem, it takes some work by the reader to decide whether or not to upvote it. An amusing cartoon takes less. A rant with a rallying cry as the title takes zero, because people vote it up without even reading it.
>
> Hence what I call the Fluff Principle: on a user-voted news site, the links that are easiest to judge will take over unless you take specific measures to prevent it.
>
> Hacker News has two kinds of protections against fluff. The most common types of fluff links are banned as off-topic. Pictures of kittens, political diatribes, and so on are explicitly banned. This keeps out most fluff, but not all of it. Some links are both fluff, in the sense of being very short, and also on topic.
>
> There's no single solution to that. If a link is just an empty rant, editors will sometimes kill it even if it's on topic in the sense of being about hacking, because it's not on topic by the real standard, which is to engage one's intellectual curiosity. If the posts on a site are characteristically of this type I sometimes ban it, which means new stuff at that url is auto-killed. If a post has a linkbait title, editors sometimes rephrase it to be more matter-of-fact. This is especially necessary with links whose titles are rallying cries, because otherwise they become implicit "vote up if you believe such-and-such" posts, which are the most extreme form of fluff.
>
> The techniques for dealing with links have to evolve, because the links do. The existence of aggregators has already affected what they aggregate. Writers now deliberately write things to draw traffic from aggregators—sometimes even specific ones. (No, the irony of this statement is not lost on me.) Then there are the more sinister mutations, like linkjacking—posting a paraphrase of someone else's article and submitting that instead of the original. These can get a lot of upvotes, because a lot of what's good in an article often survives; indeed, the closer the paraphrase is to plagiarism, the more survives. [3]
>
> I think it's important that a site that kills submissions provide a way for users to see what got killed if they want to. That keeps editors honest, and just as importantly, makes users confident they'd know if the editors stopped being honest. HN users can do this by flipping a switch called showdead in their profile. [4]

This commentary on comments is fascinating because these problems are actually observable in Slashdot comments today.  The pithy commenters have completely overtaken Slashdot, and it appears that HN has attempted to fix this problem ...

> [Comments](http://www.paulgraham.com/hackernews.html)
>
> Bad comments seem to be a harder problem than bad submissions. While the quality of links on the frontpage of HN hasn't changed much, the quality of the median comment may have decreased somewhat.
>
> There are two main kinds of badness in comments: meanness and stupidity. There is a lot of overlap between the two—mean comments are disproportionately likely also to be dumb—but the strategies for dealing with them are different. Meanness is easier to control. You can have rules saying one shouldn't be mean, and if you enforce them it seems possible to keep a lid on meanness.
>
> Keeping a lid on stupidity is harder, perhaps because stupidity is not so easily distinguishable. Mean people are more likely to know they're being mean than stupid people are to know they're being stupid.
>
> The most dangerous form of stupid comment is not the long but mistaken argument, but the dumb joke. Long but mistaken arguments are actually quite rare. There is a strong correlation between comment quality and length; if you wanted to compare the quality of comments on community sites, average length would be a good predictor. Probably the cause is human nature rather than anything specific to comment threads. Probably it's simply that stupidity more often takes the form of having few ideas than wrong ones.
>
> Whatever the cause, stupid comments tend to be short. And since it's hard to write a short comment that's distinguished for the amount of information it conveys, people try to distinguish them instead by being funny. The most tempting format for stupid comments is the supposedly witty put-down, probably because put-downs are the easiest form of humor. [5] So one advantage of forbidding meanness is that it also cuts down on these.
>
> Bad comments are like kudzu: they take over rapidly. Comments have much more effect on new comments than submissions have on new submissions. If someone submits a lame article, the other submissions don't all become lame. But if someone posts a stupid comment on a thread, that sets the tone for the region around it. People reply to dumb jokes with dumb jokes.
>
> Maybe the solution is to add a delay before people can respond to a comment, and make the length of the delay inversely proportional to some prediction of its quality. Then dumb threads would grow slower. [6]

On attracting the right people ...

> the most important thing a community site can do is attract the kind of people it wants. A site trying to be as big as possible wants to attract everyone. But a site aiming at a particular subset of users has to attract just those—and just as importantly, repel everyone else.

[On the need for downvotes:](https://stackoverflow.blog/2009/03/09/the-value-of-downvoting-or-how-hacker-news-gets-it-wrong/)

> Perhaps the most notable difference between Hacker News and Reddit is that it’s impossible to downvote anything on Hacker News. There exists one, and only one, form of vote: the upvote. So you can either upvote something, or do nothing at all. It’s an interesting design decision, but ultimately a bad one, in my opinion ...
> 
> On Hacker News, every post effectively starts at zero (technically, one implied upvote, which is your own, but we’ll call that zero), and can be upvoted indefinitely ...
> 
> The advantage of this system is that nobody gets downvoted, but at a steep cost: we’ve lost half the potential information. If a post has zero upvotes, does that mean it’s bad? incorrect? uninteresting? mediocre? There’s no way to tell, because zero has multiple meanings ...
> 
> If you add back in the negatives, suddenly the range is doubled. An evil or incorrect post is now different than a mediocre or uninteresting post, because it will have downvotes and a negative score.
>
> But getting downvoted isn’t anyone’s idea of a good time. It’s tempting to disallow it entirely, to avoid this inevitable discussion:

[On why downvoting should be discouraged](https://stackoverflow.uservoice.com/forums/1722-general/suggestions/133310-discourage-downvoting):

> Please do something else to discourage downvoting. Maybe increase the cost to the downvoter (there’s already a “declined” on force user to comment on downvoting).
>
> This isn’t about points. It’s about participation. Downvoting should be reserved for nasty/offensive/stupid/poorly-thought-out/totally-off-base comments. If someone spends the time to make an honest effort to answer a question, but it’s not that great an answer, just don’t upvote them… Downvoting sends a message, “We disapprove. You spent your valuable time, but we don’t care.” It makes me think, why should I bother spending the time to write up answers for this forum?
>
> I stopped posting on several usenet newsgroups because the major participants were just nasty and sarcastic. Don’t let this happen to Stack Overflow.

[On the importance of downvotes](https://stackoverflow.blog/2009/03/09/the-value-of-downvoting-or-how-hacker-news-gets-it-wrong/) ...

> Downvotes give you the critically important ability to distinguish between the good, the bad, and the ugly. Without downvotes, how can you possibly tell the difference between a post that is harmless but uninteresting, and one that is actually wrong or harmful? Sure, it stings a bit to get downvoted. I’ve been downvoted myself on Stack Overflow. And each time, it makes me pause. But that’s good! That’s necessary! You have to believe there are potential consequences for every post you make — both good and bad. This is how things work on real playgrounds; why would we expect our web playgrounds to be any different?
>
> The idea of a world where nobody can be downvoted strikes me as more than a little utopian. Is it realistic for users to expect to post in an environment where there are no penalties at all, no way for their peers to express disapproval or disagreement with their post? When you can’t leave a quiet, anonymous downvote, you’re more likely to post a snarky reply to express your displeasure. That’s why disallowing downvotes is actively harmful to community.
>
> The problem isn’t downvotes, per se, but encouraging responsible downvoting. That’s why on Stack Overflow, we do it this way:
>
> - Upvotes add 10 reputation to the post author
>
> - Downvotes remove 2 reputation from the post author, and 1 from your reputation
>
> The trick here is that downvotes are mostly informational. The cost of a downvote to the users’ reputation (or karma in Slashdot/Reddit parlance) is quite low. It would take a whopping 5 downvotes to equal the effect of a single upvote. And, on top of that, downvotes cost you a tiny bit of reputation. The net effect is that you have to feel very strongly about something to downvote it. Downvotes are serious business, and not to be cast lightly. We designed our system around that maxim.
>
> Does it work? I think the data itself tells the story. Here are the total number of votes cast on Stack Overflow through 3/7/2009:
>
> upvotes - 1,251,020
> 
> downvotes - 122,141
>
> On average, there are 10x as many upvotes cast as downvotes.

[On the need for interaction limits](https://stackoverflow.blog/2009/03/09/the-value-of-downvoting-or-how-hacker-news-gets-it-wrong/) ...

> we also do a few other things that help keep downvoting in check:
>
> - We limit total votes per day to 30 per user.
>
> - You do not have the right to cast downvotes at all until you earn the equivalent of 10 upvotes, or 100 reputation.
>
> The endless inflation of a system with no voting limits is something we learned early on. Instituting vote limits has many advantages besides reducing the inherent inflation. Even if you want to maliciously downvote someone out of revenge, you can only do -60 damage to that user’s reputation per day — while simultaneously reducing your own reputation by -30. And you’ll have to wait 24 hours to do it again, which is a nice de-facto timeout to potentially let cooler heads prevail.

This collection of articles on these four sites -- Slashdot, Reddit, Stack Overflow and Hacker News -- reveal an important history to aggregator sites, where the more recent site designers are attempting to start with the lessons from the former sites, which they view in some manner as flawed.  There are some very practical suggestions here.  In a sense, Phys.org comments are to science discourse what Usenet was to Internet information aggregation more broadly, 30 years ago: It's a sort of gestative state for complex conversations, and a platform where the bad behaviors can be traced directly back to the site's design decisions.

In the midst of compiling these articles, [a former Reddit product head argued](http://nymag.com/selectall/2018/04/dan-mccomas-reddit-product-svp-and-imzy-founder-interview.html) that they permitted cultural norms rooted in harassment, abuse or bad behavior to dominate the platform to such an extent that there is no way to undo the damage which has been done.

> I think, ultimately, the problem that Reddit has is the same as Twitter and Discord. **By focusing on growth and growth only and ignoring the problems, they amassed a large set of cultural norms on their platforms. Their cultural norms are different for every community, but they tend to stem from harassment or abuse or bad behavior, and they have worked themselves into a position where they're completely defensive ... I really don't believe it's possible for either of them to catch up on the problem. I think the best that they can do is figure out how to hide this behavior from an average user.**
>
> I don't see any way that it's going to improve. I have no hope for either of those platforms. I just think that the problems are too ingrained, in not only the site and the site's communities and users but in the general understanding and expectations of the public ... I don't think that they're going to be able to turn these things around ... 
>
> I fundamentally believe that my time at Reddit made the world a worse place. And that sucks, and it sucks to have to say that about myself ... **I've got a lot of advice for start-ups, and it's not very fucking complicated. It's just: Think about the impact that you want to have on your users and on the people consuming your content and do the right thing ... Don't be idiots about it. You're people, you see what's going on, you see trends that are forming, just fucking do something. It's not that hard.**
>
> ... I don’t think the existing platforms are going to change. **I do believe that new platforms could be started up, could operate better, could be more mindful, and could create better infrastructure and platforms for the large public. But in order to do that, I think that one of two things needs to happen. I think that the venture capitalists need to kind of reframe their thinking on how these companies look as they start up and grow.** I know firsthand that at least the investors that I worked with at Imzy are not ready to undertake that path. Imzy shut down, we still had $8 million in the bank, and we had raised $11 million. I know firsthand the palate of these investors, and from my experience, the majority of Silicon Valley investors are all the same archetype. I think that somebody needs to come along and change their thinking on that. I don’t think that that’s going to happen.
>
> **The other way is for a group of people to get together and create a modern platform using in some way their own resources, or finding the resources in interesting ways to do so. Unfortunately, it’s a really expensive process to build a platform like this. It takes a lot of engineering, it takes a lot of human power, it takes a lot of marketing and PR power, and it’s just an expensive process and it takes a long time. It’s really hard to get a network effect going. It would take years. It’s just a really hard process that somebody needs to be in for that ride.** I just don’t believe that right now we have found the right mix of the right founders and team to build the infrastructure, and the right funding mechanism to make that happen. I tried, and it just totally didn’t work. It failed. I don’t know. I would love to take a crack at it, but it’s fucking hard to put these resources together.
> 
> ... I think a start-up needs to think about the monetization and how it can work with the users instead of against the users. I think they need to figure out the right funding mechanisms and incentive structures that also work toward the users. I think they need to have the right product team in place to focus on users. You’ll start to see a pattern emerge here. I think that they need to have a community or a service team from day one that focuses on users’ well-being. I think they need to have the right intentions. I think you need to get all those kinds of things in place; you need to understand the investment that you’re in for, as far as time. Most start-ups these days have a 12-to-18-month horizon that they look at, and that’s just not enough. That’s not enough to build one of these platforms.

### Is Science Collective like CosmoQuest (Formerly Bad Astronomy and Universe Today)?

[Some basic details](https://rationalwiki.org/wiki/Cosmoquest_Forum) ...

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/bautforum-basics.png" width="100%" />
</p>

This part in particular ...

> The "Against the Mainstream" section serves as a dumping ground for the crank threads that inevitably appear on such forums. It operates on special rules that require proponents to support their claims and answer direct questions.

... sends a clear message that the point is to defend mainstream science theories.

[A change in policy](https://forum.cosmoquest.org/showthread.php?54741-New-Policies-Regarding-Against-the-Mainstream-section) ...

> New Policies Regarding Against the Mainstream section
>
> Okay folks, we're implementing a new policy for the Against the Mainstream (ATM) section of BAUT.
>
> New ATM theories will remain open for 30 days, and then they'll be closed by the moderation staff. In other words, if you've got an interesting new theory about the Universe, you've got 30 days to deal with objections, and then we'll seal it up - preserved for all eternity. Any new topics started up by the ATM theorist will be shut down immediately, and/or deleted.
>
> Okay, so why did we make this decision?
>
> There are two kinds of people who post threads in the ATM section:
>
> 1. People who have an interesting idea to explain some aspect of the Universe. They post their idea, community members generously donate their time to help think it through and provide ways to test the theory. It happens quickly and we all move on.
>
> 2. People who are looking to use BAUT as a marketing platform for their alternative theories. Tell us your idea, that's fine. But we're not going to allow the forum to turn into a marketing vehicle for them. 30 days should be plenty of time to present your concept, deal with objections, answer anything else.
>
> The problem is that the people in group 2 were stretching the patience of the community and using up moderator resources. So we've decided to take this direction.
>
> We'll start this new policy a week from today - March 6, 2007. We'll close up every ATM thread older than 30-days, no exceptions. They'll all still be accessible by the search engine, and if you want to put in a hard link.

This policy may at first glance seem harmless, but it's quite the opposite: Challenges to textbook theory can only gain validity over time through a process of tracking.  There is little reason to believe that taking a snapshot of the vindications for some controversial claim at some arbitrary point in time will, in terms of process, reveal the best challenges to existing theory.  It really seems that the point of CosmoQuest is to defend textbook theory.  A site where the point is to identify the best challengers would not be designed this way.

[Advice for Against-the-Mainstream Idea Advocates](https://forum.cosmoquest.org/showthread.php?107271-Advice-for-ATM-Idea-Advocates-Read-before-posting-in-ATM) ...

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/bautforum-advice-1.png" width="100%" />
</p>

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/bautforum-advice-2.png" width="100%" />
</p>

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/bautforum-advice-3.png" width="100%" />
</p>

[Rules for Posting to the Against-the-Mainstream Board](https://forum.cosmoquest.org/showthread.php?32864-**-Rules-For-Posting-To-This-Board-**)

> The purpose of the Against The Mainstream forum is to allow you to defend a non-mainstream scientific idea, hypothesis or theory. Once. For 30 days only. A number of behavior rules follow from that. The forum is not for developing an idea. Either you have something to defend, or you don't. Not "hey guys, what if X? Do the math for me please!". It's not for complaining about mainstream science. It's not for spamming an idea and never posting again.
>
> 30 days are short, therefore we crack down hard on things that distract from the forum's primary purpose of defending your idea. Like other "helpers" or collaborators chiming in. Like arguing about moderator actions. Like side discussions on the merit of the ATM forum. Like attacking the person, not the idea. Like other off-topic stuff. 
>
> People will vigorously challenge your arguments; that's what science and scientists do. If you cannot handle a frank and critical examination of your theory, then maybe you need to rethink your theory. Remember: you came here. It's our job to question new theories. Those that are strong will survive, and may become part of mainstream science. All such discussions must be kept polite and respectful, by all parties.
>
> Your ATM thread will be closed after 30 days. Extensions may be granted by Moderators/Admins, if circumstances warrant. Once an ATM idea has been presented, it may not be presented again unless you have information not available the first time.
>
> You may have only one thread active at a time in ATM. If you ask to have a thread closed before the 30 days limit so that you may open a new thread, the old thread will not be reopened later.
>
> If you post an ATM idea elsewhere, it will be split off to an ATM thread. That new split thread will be locked on creation, if there's a current one open, to be unlocked when the current one times-out at 30 days. The 30 day count for the new one, however, starts on creation, not unlocking. (See preceding paragraphs.)
>
> You must defend your arguments and directly answer pertinent questions in a timely manner. Honestly answering "I don't know" is acceptable. Evasiveness will not be tolerated.
>
> If it appears that you are using circular reasoning, depending on long-debunked arguments, or breaking any of these other rules, you will receive one warning, and if that warning goes unheeded, you will receive infractions, which can lead to suspension or banishment.
>
> The ATM forum is not the place for speculative discussion. Whether you are presenting your own ideas or those of another, you are responsible for defending them according to the provisions above. If you have a question about an ATM idea, you may pose it in Q&A, but you may not advocate it there.

It's interesting that there is no place for speculations on CosmoQuest.  Speculations serve an important purpose in the scientific method, and some speculations are far better than others.

[The actions which moderators can take are extraordinary](https://forum.cosmoquest.org/showthread.php?32864-**-Rules-For-Posting-To-This-Board-**):

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/bautforum-moderator-powers.png" width="100%" />
</p>

I think it's safe to say that Science Collective will very much be the antithesis of CosmoQuest.

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