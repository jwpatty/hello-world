# Entry 1 — Gossip markets: when junk becomes informative

*2026-11-18*

## The noodle (in your words, lightly cleaned)

> Think about a model of gossip — a gossip network or a gossip market. The simple version: if I want somebody to pay me for information, I want that information to be highly reliable, from good sources and so forth. Once a gossip outlet develops a reputation for high standards — holding the bar high for the base rate of accuracy, integrating it all out — people are willing to pay for it.
>
> Suppose keeping accuracy high incurs additional costs. Eventually, if reputation isn't too responsive, I'm going to pull the accuracy back. That's a traditional unraveling-esque story.
>
> Now imagine you've become so unreliable that you're junk bonds times a million. Here's the thing: suppose people infer something crazy or exotic about a person who would be willing to put out rumors through an essentially tabloid-times-a-million outlet. Then potential readers say: "I like celebrity gossip, but what I really love is the celebrity gossip in the tabloids." Everybody asks why — that stuff's not very true. And you say: yes, but it says something true about the person that I must know gave that story to the tabloid.

## Notes and pushback

**The core move.** At high accuracy the outlet sells *facts*, meaning claims about the subject. At near-zero accuracy the content stops being informative about the claim and becomes informative about the *channel*: who chose to bring a story here, and why. The outlet's product goes from a market for facts to a market for motives. "There is a feud" can be true even when "she threw a lamp at him" is invented.

**Pushback / open problems**

1. **Sorting is required.** The signal exists only if sources select into the junk outlet by type (grudge-holders, people who've lost access to respectable channels, people who *want* deniability). If the staff fabricate, there's no sorting and no signal. The key distinction is *junk because motivated sources* vs. *junk because invented*.
2. **A U-shape prediction.** Reliable outlets are valuable for facts, and extreme junk can be valuable for motives. The middle may be the worst place: not credible enough to believe, not extreme enough that choosing it reveals much. Respectability is a trap if you can't afford to sustain it.
3. **Deniability as product.** Some senders choose the junk outlet *because* it's junk, so they can send a message while keeping the option to call it nonsense. Related to strategic ambiguity, threats, and diplomatic signaling.

**Why it belongs in the book.** Experienced members of organizations read the channel, not the content. When the anonymous complaint, the press leak, or the department rumor arrives, the first question is "who wanted this out, and why now?" Formal models of information mostly treat messages as being about the state of the world, not about the sender's position in a network.

**Possible connections:** Akerlof (lemons/unraveling); reputation and career-concerns models (Holmström); cheap talk (Crawford–Sobel); signaling (Spence); media economics (Gentzkow–Shapiro); Dunbar on gossip; Scott's hidden transcripts.

## Open questions

- Where did this come from? A moment when someone learned more from *where* a rumor surfaced than from what it said?
- Is the tabloid end a stable equilibrium, or a phase on the way to death?
- Track for this entry: *(tbd)*

## Noodling

*(continued below as we talk)*

### Two audiences; the subject's response (round 1)

- The junk outlet needs naive readers (who supply reach) *and* sophisticated readers (who decode motive). One text, read two ways, which fits Scott's public and hidden transcripts. If everyone became sophisticated, reach would disappear and the market might collapse.
- Kremlinology: *Pravda* was read for placement, not truth. This moves the idea from celebrity gossip to political economy.
- The subject's response (deny, ignore, attack) is a second signal, aimed at the network rather than the public.

### Kremlinology thread: "Why do tabloids flourish everywhere, regardless of press freedom?" (round 2)

**Your prompt:** tabloids flourish in all nations regardless of the independence of the press. There are a few models in here.

**Unifying frame: you learn about whatever the gatekeeper screens on.**

| Gatekeeper | Screens on | A published story tells you… |
|---|---|---|
| Serious newspaper | Truth | Something about the world |
| Censor / state editor | Political approval | Someone powerful allowed or wanted this |
| Tabloid | Nothing about truth, but sources sort by motive | Someone with a stake wanted this out |

Fact-checkers and censors are the same kind of object, screens that differ in what they select on. Kremlinology = reading the screen instead of the claim.

**Answer to the question:** press freedom shapes the *fact* market. The *motive* market rests on universal demand (tracking alliances and status, per Dunbar) and universal supply (factions needing deniable channels). Hypothesis: **the motive market doesn't depend on the regime; the senders do.**

**Models**

1. **Censorship turns all media into tabloids.** Under a censor, every publication signals approval, so information shifts from being about the world to being about elite preferences. Lit: King, Pan & Roberts (2013); Lorentzen (2014) on strategic censorship; Guriev & Treisman on spin dictators.
2. **The state needs a junk outlet.** Official channels commit and disreputable ones don't. Regimes demand tabloids and kompromat outlets for deniable signaling to elites.
3. **Liberalization causes a tabloid explosion.** Factions lose coded channels but persist, and fact reputations build slowly, so the motive end fills first. Candidate case: 1990s Russia.

**Open pushes**

- One mechanism or a family resemblance? Celebrity tabloid = entertainment plus a thin motive layer; Kremlinology = nearly pure signal.
- Libel law as a natural variable: strict defamation regimes (UK vs. US) may push free-press tabloids toward coded insinuation, making them more Kremlinological.
- Equilibrium share of naive readers needed to sustain the market.
- A human figure for the chapter: someone known for reading the screen.

### Corrections and refinements (round 3)

*Provenance convention from here on: **[you]** = your move, **[me]** = Claude's suggestion. Retroactive note: the term "Kremlinology" was introduced by [me] in round 1, not by you.*

**[you] The table elides positive vs. negative agenda control.** "Allowed or wanted" mixes two distinct powers:

- **Negative control (veto):** publication shows only *not blocked*, a weak signal. Absence is informative under this regime.
- **Positive control (placement):** publication shows *someone pushed it*, a strong signal. Absence is mostly uninformative.
- [me] So the reader's first task is to infer which face of power is operating, since that decides whether to read presence or absence. Connects to Cox & McCubbins (agenda control) and Bachrach & Baratz (non-decisions). Revised frame: each gatekeeper is described by *what it screens on* and *which direction it screens*.

**[you] In a liberal press there is still a censor: the subject.**

- [me] Censorship is spread out rather than central. Subjects hold both faces partially: negative (killing stories, catch-and-kill, legal threats, access) and positive (publicists, placements).
- [me] Inference: since censoring capacity grows with power, an unflattering story getting through is evidence of a *lapsed veto*, a signal about the subject's power and not only their conduct. "They're finished" is a reading of the screen's failure.
- [me] Sharpens the cross-national answer: every regime has censors; the difference is one vs. many.

### Model 2 as a real paper: "the dictator's tabloid" (round 4)

**[you] The setup (lightly cleaned):**

> The government has a binary, costly preventive action. The only reason to take it is a 1-in-20-year flood (~5%). Think about oversight of the preventive-action agency: there's a small latent probability p that the agency isn't responsive. We need to work out the Markovian variable the agency conditions on each period. If I watch it for 400 periods and never see it pull the trigger, I conclude it's not using the 5% rule.
>
> If you're a Kremlinologist, you don't want completely accurate coverage of the agency's actual performance (it won't be optimal, because of corruption or whatever), but you want coverage that's informative about what people are seeing on the ground. Global-games-esque, but without the weirdness.
>
> N voters (finite, for measure-theoretic reasons) each observe the same signal (the truth) but have different thresholds for protest vs. not. The government wants to know: is over 5% of the population protesting? It worries about tails. The small set of states where the government didn't want the truth ex ante but was glad ex post to have it ("thank goodness I knew, my best response would have been terrible without it") is enough support that there are worlds where the autocracy really needs the tabloids. And willingness to accommodate tabloids (a risk) will accentuate the autocrat's willingness to further suppress the top-end outlets.

**[me] Tightening**

1. **Information asymmetry:** the autocrat sees actions a_t, not floods. Citizens see both. With p = 0.01 and a never-acting bad agency, the center needs about 90 quiet periods to reach 50% belief that the agency is bad (400 periods gives near-certainty: 0.95^400 ≈ 1e-9). Citizens learn in one flood. The tail risk lives in that gap, so the tabloid's value is *early warning*.
   - Harder case: a bad agency that **mimics the base rate** (acts randomly ~5%) makes action frequency uninformative. Only the action–flood correlation reveals type, and only ground observers see it.
2. **The designer is also a receiver.** Unlike standard Bayesian persuasion, the autocrat doesn't know the state, and any outlet informs both it and the public. The tabloid breaks this through **differential decoding**: citizens discount it (no threshold shift, no common knowledge), while the center reads its selection, Kremlinologically. Links to round 1: the autocrat is the ultimate sophisticated reader.
3. **[you] Complementarity, [me] mechanism:** value of the quality outlet to the autocrat ≈ information value − coordination cost. The tabloid substitutes for the information part (especially tail states) and leaves the coordination cost unchanged, so the suppression region expands. *Tolerating junk and repressing quality press are complements.* Policy implication: backing "any independent media" may lower the cost of cracking down on quality outlets.
   - Corollary: **the autocrat wants the tabloid to stay junk** and may salt it with fabrications to keep citizens discounting it. This is the entry's unraveling story run in reverse, on purpose.
4. **Global games:** without strategic complementarity in protest, the protest share is a deterministic F(θ), so the tail event is {θ : F(θ) > 5%} with a unique outcome. Start there. Adding complementarity brings back multiplicity, so treat it as an extension.

**Referee pushes to pre-empt**

- Why not informants or secret police? (They're a private tabloid inside the same corrupt chain, or costlier; the tabloid's sources self-select from the ground.)
- Why tolerate a corrupt agency? (A patronage good for the coalition, which is also why accurate coverage is costly ex ante.)
- Protest is observable, so why does the center need media? (By the time it's visible you're past 5%. The "glad ex post" set is the states just short of tipping.)

**Minimal model sketch**

- Periods t = 1…T; flood ω_t ∈ {0,1}, Pr = q = 0.05.
- Agency good w.p. 1−p (acts iff ω_t = 1); bad never acts (extension: mimics at rate q).
- Autocrat observes a_t; citizens observe (ω_t, a_t).
- Citizen i protests if accumulated failures g_t ≥ t_i; protest share s_t, N finite.
- Quality outlet Q: accurate, credible, common knowledge, lowers thresholds by Δ. Tabloid J: noisy ground reports, discounted by citizens, decoded by the autocrat.
- Autocrat each period: intervene at cost k; loss L if s_t > 0.05.
- Target results: (i) suppress-Q condition without J; (ii) J expands the suppression region; (iii) the autocrat's optimal J credibility is low (deliberate degradation).

**Literature to position against (verify):** Egorov, Guriev & Sonin (2009); Lorentzen (2014); Gehlbach & Sonin (2014); Shadmehr & Bernhardt (2015); Edmond (2013); Wintrobe (dictator's dilemma); Kuran (preference falsification). Claimed novelty: the differentially decoded outlet and the complementarity with quality-press suppression.
