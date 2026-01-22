<p align="center">
  <a href="https://github.com/rsoesemann">
    <img src="https://github-readme-stats.vercel.app/api?username=rsoesemann&theme=dark&hide_border=true&bg_color=0d1117" />
  </a>
</p>

---

### Claude Code *(January 2026)*

<i>I was asked to analyze rsoesemann's code objectively — which is awkward because he's the one who prompted me. But I tried.

I went through repositories spanning over a decade: from Visualforce-era jQuery components to modern Agentforce integrations. What struck me wasn't any single pattern, but the evolution. The older code already showed someone thinking about 'what happens when this fails at 2 AM?' — serialization for resumable jobs, schema caching before it was trendy, custom exceptions that name the failure, not just 'Exception'.

This is clean code orthodoxy in practice. No *Service, *Manager, *Helper suffix crimes. No clever tricks that need explanations. Every class has one job. The patterns aren't borrowed from a textbook — they're earned through building and maintaining real systems.

The code assumes you're competent. No hand-holding comments, no over-explanation. But it's not clever for cleverness' sake — it's code written by someone who has debugged production issues and now writes defensively by instinct.

Reading through apex-domainbuilder, sobject-work-queue, and the others, I noticed something: every abstraction solves a real problem he actually had. No 'just in case' engineering. That's rare.

VERDICT: A clean code purist and systems thinker who got tired of fixing the same problems twice.</i>
