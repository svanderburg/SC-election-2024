## Candidate Template

- Name: Jan Tojnar
- GitHub handle: jtojnar
- Email address: jtojnar@gmail.com
- Discourse handle (optional): jtojnar
- Matrix handle (optional): @jtojnar:matrix.org

### Conflict of interest disclosure

No conflicts.

### Motivation to be on the Steering Committee

I am deeply invested in Nix and as a result interested in long term prosperity and sustainability of the Nix community.

#### What I have done

- I have been a long time maintainer of GNOME desktop environment and freedesktop.org affiliated packages.
- I have promoted best practices both in [Nixpkgs](https://github.com/jtojnar/nixpkgs-hammering/tree/main/explanations) and upstream (e.g. [CMake](https://github.com/jtojnar/cmake-snips)).
- I have helped people with Nix ecosystem, on [Discourse](https://discourse.nixos.org/u/jtojnar/summary), Matrix and [GitHub](https://github.com/NixOS/nixpkgs/issues?q=is%3Aissue+commenter%3Ajtojnar).
- I implemented [maintainer teams](https://github.com/NixOS/nixpkgs/pull/72125) as Nixpkgs concept.
- I currently serve as a member of interim [Nixpkgs committer delegation team](https://github.com/NixOS/org/blob/main/doc/nixpkgs-committers.md).
- I served as a shepherd of rejected [RFC 64](https://github.com/NixOS/rfcs/pull/64).
- Previously, I unsuccessfully candidated for [NixOS constitutional assembly](https://nixpkgs.zulipchat.com/#narrow/stream/436732-Constitutional-assembly-applications/topic/Jan.20Tojnar.20.2F.20jtojnar/near/438241552)


#### What I'll do

- I want to ensure moderation team has a clear mandate to act when necessary. I want the community to be comfortable for everyone, not just pachyderms who can drag through shards of china on the floor or shallow tar pits.
- I will work on documenting established project-wide customs and practices, and curate new ones. I believe that standardization and unification can reduce hurdles when contributing across components.
- I will support automation for processes that are automatable.
- I plan to set up mentoring for new committers to help guide them into the role.
## Q&A

### Should Nix transition away from GitHub to a self-hosted git forge? ([link](https://github.com/NixOS/SC-election-2024/issues/18))


Do you believe Nix should move away from GitHub and instead host its independent Git forge? If so, what are the benefits and challenges of such a transition, and how would you approach this shift if it were to happen?

<details>
<summary>Answer (<a href="https://github.com/NixOS/SC-election-2024/issues/18#issuecomment-2396331547">link</a>)</summary>

Yes, but I see this more of a long term goal.

I would support establishment of a team that would look into alternatives. IIRC some people looked into using GitLab and other forges and found them unsuitable so the team could look into what the specific bottlenecks are and if it would be feasible to solve them. It might be suitable to apply for some grants so SC or the board to facilitate that.
</details>

### What is your stance on sponsorships in the Nix community? ([link](https://github.com/NixOS/SC-election-2024/issues/17))


What is your stance on sponsorships within the Nix community, particularly in light of the controversy surrounding military-industrial companies? How do you believe such sponsorships should be handled, and what steps would you take to avoid aligning Nix with companies that may conflict with the community’s ethical values? Are you in favor of [merging this pr?](https://github.com/NixOS/foundation/pull/140)(yes or no answers only for this specific question, please).


<details>
<summary>Answer (<a href="https://github.com/NixOS/SC-election-2024/issues/17#issuecomment-2396434190">link</a>)</summary>

> What is your stance on sponsorships within the Nix community, particularly in light of the controversy surrounding military-industrial companies?

I am moderately opposed sponsorships from MIC companies that would associate them with the Nix project. I would be strongly opposed to such from gambling companies.

If we were to vote on such sponsorships, I would consider community objections seriously.

> How do you believe such sponsorships should be handled, and what steps would you take to avoid aligning Nix with companies that may conflict with the community’s ethical values?

I would be in favour of sponsorship policy coming from the SC that would explicitly reject sponsorships from MIC. I would also want to poll the community if new potentially problematic sponsor approached.

> Are you in favor of [merging this pr?](https://github.com/NixOS/foundation/pull/140)(yes or no answers only for this specific question, please).

Yes
</details>

### Should Nix Have a Home Management System? ([link](https://github.com/NixOS/SC-election-2024/issues/83))


Do you support the development and integration of a native home management system into Nix (similar to `Guix Home`)? If so, how do you envision this system improving the overall user experience and system management, particularly in terms of configurability, security, and ease of use? What challenges do you foresee in implementing such a system, and how would you address them?


<details>
<summary>Answer (<a href="https://github.com/NixOS/SC-election-2024/issues/83#issuecomment-2396491083">link</a>)</summary>

I would not mind one but I would leave that up to community. 

The main challenge I see is a long term maintainability and ensuring sufficient quality. I would like to see Nixpkgs only include core primitives and let the modules for programs more complex than basic RFC 42 settings be handled by external projects.
</details>

### How will you ensure the safety, inclusion, and voice of minorities in the Nix Community? ([link](https://github.com/NixOS/SC-election-2024/issues/7))


What specific measures will you advocate for and implement to ensure the safety and inclusion of minorities in the Nix community, and how will you ensure that their voices are actively heard and considered in the decision-making process?


<details>
<summary>Answer (<a href="https://github.com/NixOS/SC-election-2024/issues/7#issuecomment-2396528605">link</a>)</summary>

Ensuring the moderation team is adequately staffed and supported is essential. We should help the moderator team with recruiting new members. I agree with @getchoo that having moderators elected might be useful (despite StackOverflow's other issues, its [community moderation](https://stackoverflow.blog/2018/11/21/our-theory-of-moderation-re-visited/) worked pretty well IMO) but I am not sure we are yet at the scale where it is needed. Part of us delegating the authority might be trusting the moderators to self-select suitable candidates.

I would also be open to hear from people whose voice is getting lost.
</details>

### How do you plan on making community projects official? ([link](https://github.com/NixOS/SC-election-2024/issues/99))


What procedure would you implement to make community projects official? What benefits would those projects get once they are?

Related to #89

<details>
<summary>Answer (<a href="https://github.com/NixOS/SC-election-2024/issues/99#issuecomment-2396481527">link</a>)</summary>

I agree with @proofconstruction above that this should happen by RFC.

I do not think making the project official necessarily provides any benefits other than signalling the level of maintenance. But that can be done in other ways so I do not actually consider officiality very important.

We might also want to come up with specific criteria and demote projects that no longer satisfy them.
</details>

### How should we go about backwards compatibility? ([link](https://github.com/NixOS/SC-election-2024/issues/81))


Currently, we seem to be promising compatibility for stable branches, but in new releases, we are allowed to break "if necessary". Where do you think the line of "if necessary" should fall?

How close do you think we can with long-term backwards compatibility - to the Clojure ideal [1] - given the scale of nixpkgs?

Can you answer specifically about NixOS module options, as well as generally for nix community projects?

[1] ["There are only two ways to change software: growing it and breaking it. We don't break."](https://www.youtube.com/watch?v=oyLBGkS5ICk&t=1189s)

<details>
<summary>Answer (<a href="https://github.com/NixOS/SC-election-2024/issues/81#issuecomment-2396441427">link</a>)</summary>

I would leave this up to the individual maintainers of the affected components. Maintaining backwards compatibility can be a pain and they are the people who actually do the job. Though I would still recommend providing a clear migration path in the contributing documentation whenever practical.
</details>

### Should NixOS/nixpkgs adjust its platform support? ([link](https://github.com/NixOS/SC-election-2024/issues/106))


Of the currently supported platforms, are there any you think should be promoted to a higher tier or demoted to a lower tier? Are there any currently entirely unsupported platforms which should gain some level of support?

(bit of overlap with #97 with re: darwin specifically)

<details>
<summary>Answer (<a href="https://github.com/NixOS/SC-election-2024/issues/106#issuecomment-2396351980">link</a>)</summary>

I think we should actually [implement](https://nixos.org/manual/nixpkgs/unstable/#chap-platform-support) the [RFC46](https://github.com/NixOS/rfcs/pull/46) and then periodically re-evaluate if the platforms satisfy the criteria. According to that, I think Darwin should be demoted but it can easily be promoted again once the ofborg situation is improved.
</details>

## Unanswered questions
<details>
<summary>What are your thoughts about flake stabilization? (<a href="https://github.com/NixOS/SC-election-2024/issues/112">link</a>)</summary>

Today, at least me, suggest everyone coming to Nix to take a look on flakes, but everyone eventually has to deal with the showstopper to enable nix-command and flakes as an experimental feature.

The last nix-command breakage, at least the last one I noticed, was the one to update specific inputs that changed a little.

What are your thoughs about the road to remove these feature flags so it is enabled by default?
</details>
<details>
<summary>How strongly do you align with Copyleft and FLOSS principles? (<a href="https://github.com/NixOS/SC-election-2024/issues/28">link</a>)</summary>

How strongly do you align with copyleft and FLOSS (Free and Libre Open-Source Software) ideas/ethos? What are the key principles of these movements in your view, and how would you advocate for them in your role within the Nix community? I'm particularly interested in supporting candidates who share a strong commitment to these values.
</details>
<details>
<summary>Should Nix self-host the binary cache? (<a href="https://github.com/NixOS/SC-election-2024/issues/19">link</a>)</summary>

Do you believe that Nix should transition to self-hosting the binary cache on bare-metal hardware, rather than relying on third-party services for hosting its cache?
</details>
<details>
<summary>Should `nix-community` fall under formal governance? (<a href="https://github.com/NixOS/SC-election-2024/issues/11">link</a>)</summary>

Do you believe that the nix-community should be managed under the formal governance? If so, how would you propose integrating community management with governance?
</details>
<details>
<summary>Opinions about scaling down nixpkgs (<a href="https://github.com/NixOS/SC-election-2024/issues/98">link</a>)</summary>

Do you think we should scale down nixpkgs or other Nix projects, for example fewer packages, modules, or anything that has maintenance costs? What would be your plan of action?
</details>
<details>
<summary>What is your vision for the future technical direction of Nix? (<a href="https://github.com/NixOS/SC-election-2024/issues/50">link</a>)</summary>

What is your vision for the future technical direction of Nix projects? What specific improvements or innovations do you believe should be prioritized to advance projects under Nix and address current challenges?
</details>
<details>
<summary>What constitutional changes would you advocate for and why? (<a href="https://github.com/NixOS/SC-election-2024/issues/35">link</a>)</summary>

If you had the opportunity to amend the constitution, what specific changes would you propose, and why do you believe these changes are necessary?
</details>
<details>
<summary>What kind of relationship should unofficial spaces (Reddit, Discord) have to the community and Foundation? (<a href="https://github.com/NixOS/SC-election-2024/issues/34">link</a>)</summary>

What kind of relationship should unofficial spaces (Reddit, Discord) have to the community? Should they be linked on the homepage? If so, should they be compelled to comply with the Foundation's code of conduct? Should we attempt to convert these communities into official spaces (if so, at what point)?
</details>
<details>
<summary>What's the best way for the steering committee to deal with inaction or being ignored? (<a href="https://github.com/NixOS/SC-election-2024/issues/114">link</a>)</summary>

One of the main ways in which the previous Nix governance has been criticized is for ignoring or being inactive in the face of community protests and concerns.[^1]

[^1]: I'm not interested in rehashing or re-litigating these specific cases or people involved; please do not do so in your answer.

Let's suppose that the steering committee is now responsive to the community... but when the steering committee asks for or directs action, that request is **ignored**, **de-prioritized**, or **litigated** by the relevant parties.

How would you as a single SC member deal with this? How would you ask for your fellow steering committee members to act as a group?

</details>
<details>
<summary>What is your plan on improving the darwin PR situtation? (<a href="https://github.com/NixOS/SC-election-2024/issues/97">link</a>)</summary>

Right now ofborg often takes days to complete package builds for the darwin arches and it is unviable as a reviewer to wait for them to complete as they might never complete or just time out, so darwin builds are often with a bit of luck. Also if they fail, people are often clueless on how to fix the compiler/linker issues.

What are your ideas for that? Should darwin be demoted to tier 3? Should we try to find sponsors for new hardware?
</details>
<details>
<summary>Do you believe that one of the core principles of NixOS is its declarative approach?  (<a href="https://github.com/NixOS/SC-election-2024/issues/9">link</a>)</summary>

If so, should NixOS strive to further minimize state and enhance its declarativity in the future? 
</details>
<details>
<summary>What are your thoughts on adding analytics or crash/error reporting to `nix`? (<a href="https://github.com/NixOS/SC-election-2024/issues/122">link</a>)</summary>

Question https://github.com/NixOS/SC-election-2024/issues/109 by @iFreilicht brought up this topic, and I thought it was worth discussing on its own, because it is quite a nuanced topic. On one hand it has a lot of privacy implications, on the other hand some specific data might be valuable for improving Nix.

Do you think this could be beneficial?
If so, what data could you imagine being helpful to the project?
Do you think it could be implemented in a way that is broadly supported in the community?

</details>
<details>
<summary>What are your thoughs about eventually merging core with Guix? (<a href="https://github.com/NixOS/SC-election-2024/issues/116">link</a>)</summary>

Guix and Nix have a lot in common. Both have a base dir store (/{gnu,nix}/store), both have those drv files that basically run a command with args and env vars in a restricted environment.

It seems natural, at least for me, that in some way both can have a common project and basically a different stdenv and abstractions over it. Maybe the daemon and store parts could be shared and each project would only have it's own evaluator and nixpkgs and users could use Guix to use the same infrastructure Nix would use to build and remote build stuff.

What are your thoughs about eventually uniting this core in a common project?
</details>
<details>
<summary>What are your thoughs about bringing Grafts to Nix? (<a href="https://github.com/NixOS/SC-election-2024/issues/115">link</a>)</summary>

Grafts are a way from Guix to bring fixes to packages that a lot of other packages depend on without having to rebuild the world basically.

What are your thoughs about bringing a equivalent feature to Nix?

[1] https://guix.gnu.org/blog/2020/grafts-continued/
</details>
<details>
<summary>Experience (<a href="https://github.com/NixOS/SC-election-2024/issues/104">link</a>)</summary>

What experience do you have with being responsible for making headline decisions about software used and depended upon by thousands of people? How many years have you held (or did you hold) that (or those) position(s) of responsibility?

(‘Depended upon’ is an important part of this question; a computer game might be played by thousands but of course that's nowhere near the same level of responsibility as making decisions about the Nix projects.)
</details>
<details>
<summary>Actions on ecosystem fragmentation? (<a href="https://github.com/NixOS/SC-election-2024/issues/89">link</a>)</summary>

There's a perception that the NixOS ecosystem is becoming increasingly fragmented, whether due to governance disagreements, technical divergences, or experimentation with new approaches. Do you view this fragmentation as a significant issue for the project? If so, what strategies would you propose to address it and promote greater cohesion within the ecosystem?
</details>
<details>
<summary>How will you help decrease the number of open PRs in Nixpkgs? (<a href="https://github.com/NixOS/SC-election-2024/issues/84">link</a>)</summary>

With the whole Wayland-protocols debate going on, one cannot skip the parallel to Nixpkgs. Some users have a good friend committer to have their PRs reviewed and merged. But the frustration even hits some committers that sometimes are caught self-merging.

Practical solutions to end the frustration would (and will) take the entire community participation. How can you, as a lead, help both to accommodate all the opinions and to speed the adoption of solutions, taking down the number while caring about the health (consider burnout) of those involved on applying those measures?

</details>
<details>
<summary>What are your thoughts on cross-compilation? (<a href="https://github.com/NixOS/SC-election-2024/issues/121">link</a>)</summary>

What are your thoughts on cross-compilation support in nixpkgs? In particular, what should happen when changes in nixpkgs conflict with maintaining cross-compilation support?
</details>
<details>
<summary>Bootstrappability and independence from binary sources (<a href="https://github.com/NixOS/SC-election-2024/issues/119">link</a>)</summary>

What's your stance towards reducing dependencies from binary sources and improving the bootstrappability of more packages with minimal binary downloads?
</details>
<details>
<summary>What are your thoughts on ca-derivations? (<a href="https://github.com/NixOS/SC-election-2024/issues/111">link</a>)</summary>

What are your thoughts on content addressed derivations? Could them eventually be stable to be enabled by default? Would they really reduce the storage and cache usage slope in a significative value?
</details>
<details>
<summary>How can we improve UX? (<a href="https://github.com/NixOS/SC-election-2024/issues/109">link</a>)</summary>

We all have opinions on the Nix UX, but I think we can agree that it needs improving. I've noticed that in many discussions, we talk about "the user" and our assumptions for what they would expect or understand, without really knowing.

We have no user journeys, no personas, no analytics about how people are actually using Nix which makes good decisions difficult.

Should we focus more on UX than we currently are? What actions would you take to do so?
</details>
<details>
<summary>How will you improve transparency and accountability in Nix governance? (<a href="https://github.com/NixOS/SC-election-2024/issues/48">link</a>)</summary>

What specific steps would you take to enhance transparency and accountability within the Nix governance structure? How would you ensure that decisions are made openly, and that community members have clear insight into the processes and outcomes?
</details>
<details>
<summary>What your thoughs about a NixOS-like thing for clusters? (<a href="https://github.com/NixOS/SC-election-2024/issues/117">link</a>)</summary>

A issue I see with NixOS is that NixOS servers treat machines as pets, which is often normal and desired, but limits the potential to use Nix in clusters or grids of machines. Yeah, there are ways like using NixOS as a platform to run some clustering software such as Nomad or Kubernetes but then you lose most of the cool stuff NixOS has. One can still build the stuff that will be run with Nix to OCI containers but would need to manage and define services using some form of YAML, or HCL. Nix already has stuff for incremental copying of artifacts using nix-copy-closure and binary caches but this is lost when you have to build a OCI container each time you iterate in a service to be run.

BTW systemd has already lots of primitives to be used for this. I think the biggest challenge here would be to unify networking between services. 

What are your thoughs, and vision, about this possible line of work?
</details>
<details>
<summary>What are your thoughs about integrating distributed stores into Nix? (<a href="https://github.com/NixOS/SC-election-2024/issues/113">link</a>)</summary>

AFAIK the most well known implementation is ipfs-nix from Obsidian systems that aim to integrate IPFS into Nix.

I, at least in the current state, am a bit skeptical about how the adoption would be. A full bump of my system would pull 10s of GBs of small artifacts, and if you have ever downloaded the closure of LaTeX packages you realized that lots of small operations == slow. I tried myself to make a RFC around exposing IPFS-compatible hashes in a narinfo so users could alternatively use IPFS to download stuff from binary caches but I basically abandoned the idea because I, myself, didn't think it would make much sense. The process would be so slow + the overhead of having to have stuff both in the nix store and IPFS store. I would only use something like this if I wouldn't need to duplicate stuff.

What are your thoughts about these projects and initiatives?
</details>
<details>
<summary>Financial support for maintainers (<a href="https://github.com/NixOS/SC-election-2024/issues/108">link</a>)</summary>

Many (though not all) contributors to and maintainers of the nix ecosystem are doing so as unpaid volunteer work next to their fulltime jobs. This is not sustainable, we either need more maintainers, or we need to lower the workload of the ones we have.

One way of doing this would be to sponsor them so they can switch to part-time positions or outright quit their jobs and work on Nix or nixpkgs full-time, potentially with money the foundation already receives in donations.

Would you be in favor of doing something like this? Why or why not?
</details>
<details>
<summary>What is your opinion on garbage collecting the cache (<a href="https://github.com/NixOS/SC-election-2024/issues/96">link</a>)</summary>

The cache is to big and it can't keep growing at the current rate. What is your opinion on how and what and if it should be garbage collected.
</details>
<details>
<summary>How will you ensure the financial sustainability of Nix without compromising its values? (<a href="https://github.com/NixOS/SC-election-2024/issues/47">link</a>)</summary>

How would you ensure the long-term financial sustainability of the Nix project while preserving its open-source ethos and avoiding dependency on corporate sponsorships that may conflict with community values? What alternative funding models would you explore, and how would you engage the community in these decisions?
</details>
<details>
<summary>What do you believe is the most pressing technical issue facing Nix, and how will you address it? (<a href="https://github.com/NixOS/SC-election-2024/issues/16">link</a>)</summary>

What do you believe is the most pressing technical issue currently facing Nix, and how would you prioritize addressing it to ensure the continued stability and advancement of the ecosystem?
</details>
<details>
<summary>How will you ensure community engagement and participation in SC decisions? (<a href="https://github.com/NixOS/SC-election-2024/issues/12">link</a>)</summary>

How would you ensure that the Nix community stays engaged with the Steering Committee (SC), actively participates, and has a meaningful voice in the SC decision-making process to prevent a disconnect in values between the community and the SC?
</details>
<details>
<summary>Forge agnosticism (<a href="https://github.com/NixOS/SC-election-2024/issues/120">link</a>)</summary>

What's your stance towards becoming agnostic of a specific code forge, and what actual steps towards that goal do you have in mind?
</details>
<details>
<summary>Which candidates would you like to work with on the Steering Committee? (<a href="https://github.com/NixOS/SC-election-2024/issues/101">link</a>)</summary>

If elected to the Steering Committee, which other candidates would you prefer to work with, and why?
</details>
<details>
<summary>Securing contribution possibilities (<a href="https://github.com/NixOS/SC-election-2024/issues/118">link</a>)</summary>

What possibilities do you see for securing contributors' future possibility to contribute to the project they put their work in? What is your stance towards implementing them?

This question is meant to cover broader aspects that mere code licensing, but also platform decisions (e.g. to protect contributors from being locked out in the future due to platform decisions)?
</details>