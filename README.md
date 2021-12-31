# Pro Bono Security Spot Checks

> **Pro bono publico** (English: "for the public good"; usually shortened to _**pro bono**_) is a Latin phrase for professional work undertaken voluntarily and without payment.

**Tl;Dr:** I choose projects that I find interesting or that are important to the Ethereum ecosystem, and perform pro bono security spot checks on them. I am NOT doing free security spot checks for every project who reaches out and asks.

## The problem
Smart contract security professionals have been in extremely high demand for years. Projects that are not well-funded have a difficult time getting experienced security professionals' eyes on their code. Even well-funded projects often have to wait several months before they can have their code reviewed because top security firms are usually booked out for months. These projects often launch before they have any professional security review at all, sometimes with [dire consequences for their user's and investors](https://rekt.news/).

Additionally, incentives in the security industry are not always aligned with what is best for Ethereum users or the Ethereum community. Auditors are almost always paid by the project's owners, which means the project owners end up defining the scope of the security reviews. It is not uncommon for important aspects of systems to be "out of scope" for auditors, most often due to (totally valid) budget concerns. Very often during paid audits the governance contracts, price oracles, system parameters, and off-chain tools and UI's are left out-of-scope, even though all of these are part of the IRL attack surface.

The incentive problems don't stop there. Consider scam projects whose sole purpose is to collect user funds and then rug everybody. These types of projects aren't going to pay a professional security firm to audit them. So the users don't have anyone looking out for them to alert them of security issues. When they get rugged, it decreases user trust in Ethereum and increases skepticism by no-coiners and regulatory bodies.

## An experiment
In an attempt to address some of these problems, I'm starting a short-term experiment where I go out and find projects that interest me, or that I consider to be "important to the Ethereum ecosystem" in some way, and then do pro bono security spot checks of them. I will convey any findings or recommendations privately to the project devs and/or publicly to the users of the project, whichever I feel is more appropriate.

Since there is nobody to pull the purse strings, I can direct my attention to whatever projects I think are important, not just the ones that have the money to buy my attention. And I can also define the scope to be "whatever I think is important for the users", and not leave that choice up to someone else with differing incentives or budget limitations.

Users, organizations, and DAOs that care about the health of the Ethereum ecosystem, as well as anyone who benefits from my spot checks after the fact, are welcome to send donations as a "thank you" for my work.

In short, the experiment is to see whether entirely self-directed, _pro bono_ security work can add any novel value to the Ethereum ecosystem, and/or to my daily work as a security researcher.

**Please note:** The opportunity cost of this experiment is very high for me, so I can't do these _pro bono_ spot checks full time. I'm just doing them part-time, as funding allows.

## What is a security spot check?
A security spot check is an extremely time-limited engagement during which a project is reviewed for potential security issues and/or potential design improvements. The results of spot checks can vary wildly depending on who is doing them, how long they last, and what the researcher decides to prioritize.

**A spot check is absolutely NOT a replacement for a security _audit_**, which is a longer process that involves a _much_ more thorough and formal approach to reviewing the code and architecture of a project. Spot checks will almost certainly miss _many_ issues (even very important ones) because the engagements aren't long enough to be thorough.

For the purposes of this _pro bono_ spot checking experiment, I will be focusing on a narrow class of high-value vulnerabilities, prioritizing loss-of-funds issues. I plan to spend much less time on other classes of vulnerabilities (e.g., correctness of implementation, etc).

In short, I will give myself a small window of time and ask, "how would a blackhat attack this system, or how would the owners rug the users?", and then start digging into code.

## What these spot checks AREN'T
It is important to note that my spot checks for this experiment are NOT a service or product that I'm offering anyone. While I _am_ trying to protect a project's users from loss of funds -- and I hope to work together with the project's devs towards that goal -- the project devs are NOT my clients and should not have any expectation of directing my work, choosing the scope, limiting what I say to their users in public forums, etc.

In some cases, such as a ruggable scam project, my relationship with the project devs may even be adversarial, as I'll warn their users of potential rug pulls.

I also have no intention of pumping your bags. E.g., I won't write you a security report that you can use in marketing material, and I won't shill-tweet stuff like "I spot checked ProjectX and didn't find any issues". Etc.

Unless I need some clarification about how the project works, I typically will not engage with the devs or the community unless I find something of value to report.

## What makes a project interesting or important?
There are a number of things about a project that I may find interesting or important enough for me to prioritize spot checking it. Any one of these may be enough to grab my attention. In no particular order:

- The project has received a large amount of money from many users, but has not yet been audited by a top security firm. This makes the project "important" in the immediate sense, because when a lot of users lose money due to a security issue it is bad for the Ethereum ecosystem. I don't find "holds lots of money" to be particularly _interesting_, but I do think it makes a project _important_ if the money belongs to many users.
- The project provides a tool to help increase freedom in the world. Especially (but not only) if the tool is practical and relevant for people living under autocracy, high-inflation, or general instability. This can include people living in unstable living situations _within_ an otherwise stable country.
- The project emphasizes trustlessness, censorship-resistance, and (where appropriate) governance minimization.
- The project provides tools to help users enjoy privacy.
- The project has novel incentive mechanisms or provides interesting game-theoretical assurances.
- The project creates an inordinate amount of MEV (whether intentionally or not), or it intentionally tries to minimize MEV.
- The project uses randomness.
- The project has a novel approach to the oracle problem.

## Where to send funds if you want to support my work
I expect nothing in return for the work done via this experiment, but I will happily accept and appreciate any funds people want to give. For any users, DAOs, companies, philanthropists, etc that want to send me money as a "thank you", below are my preferred was of receiving funds.

**Please note:** Sending me money _does not_ entitle you anything at all. It does not mean that I will spot check or audit a project of your choosing. It does not mean that I will continue this experiment longer than I want to. I'll treat all funds sent to me as non-refundable and with no strings attached, and I'll interpret them as a "thank you for the work you do".

**ZEC (preferred):** zs1pe7jd0vjq5n9kjdvkdau7lxfsna26ew9h0u40su3vjqeq29242d7s3h0d04aqqe42z99jc5qgcq

**ETH:** [0x51E0ECBAF73DD28394eFEc5Fc8e7E7071f7c8dBA](https://etherscan.io/address/0x51E0ECBAF73DD28394eFEc5Fc8e7E7071f7c8dBA)

**Private ETH address:** Feel free to reach out and ask for a private ETH address if you'd rather send ETH-based funds to me privately.
