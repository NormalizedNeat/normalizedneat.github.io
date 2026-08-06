<span class="anchor" id="papers"></span>

# Papers

<div class="paper-topic-list" aria-label="Paper topics">
  <span class="paper-topic">LLM Agents</span>
  <span class="paper-topic">Wireless Communications</span>
</div>

## LLM Agents

<article class="paper-box">
  <div class="paper-box-image">
    <a class="paper-visual" href="/assets/papers/strat-bench-overview.png" aria-label="Open the full STRAT-Bench method overview">
      <img src="/assets/papers/strat-bench-overview.png" alt="STRAT-Bench and SPADE pipeline from offline evidence construction to online strategic interaction">
    </a>
  </div>
  <div class="paper-box-text">
    <h3>STRAT-Bench: Evaluating Conversational Agents with Strategic Users</h3>
    <p>Minhao Qi<sup>*</sup>, <strong>Yinuo Meng<sup>*</sup></strong>, Youjia Liu<sup>*</sup>, Rong Liu, Guohua Cheng, Jianling Liu, Chang Men, Zhengdan Zhu</p>
    <p class="paper-note"><sup>*</sup> Equal contribution.</p>
    <p class="paper-venue">Submitted to the KDD D&amp;B Track</p>
    <p class="paper-links"><a href="https://github.com/Archie-qi/STRAT-Bench">code</a></p>
    <details class="paper-abstract">
      <summary>Abstract</summary>
      <p>Existing conversational-agent benchmarks largely rely on cooperative users or fixed personas. Real users, however, may withhold information, challenge decisions, or change their strategy and emotion in response to the agent, making their behavioral evolution difficult to capture with a predefined transition model. We introduce STRAT-Bench, a benchmark of 300 executable tasks grounded in 500 anonymized real-world service conversations. We also propose SPADE, a training-free user simulator that grounds behavioral adaptation in real conversations through a recall-rerank-sampling pipeline. Against 200 held-out conversations, SPADE improves behavioral Likeness by 0.147 and 0.104 with Qwen and DeepSeek user backbones, respectively, and increases dialogue-level human judgments from 56.0% to 72.0%. When interacting with these strategic users, all three evaluated assistants exhibit 10.0-10.8 percentage-point decreases in Task Completion relative to task-only users, underscoring the importance of modeling strategic users when evaluating real-world conversational agents.</p>
    </details>
  </div>
</article>

## Wireless Communications

<article class="paper-box">
  <div class="paper-box-image">
    <a class="paper-visual" href="/assets/papers/uav-passive-6dma-system.png" aria-label="Open the full UAV-enabled passive 6DMA system model">
      <img src="/assets/papers/uav-passive-6dma-system.png" alt="System model of a UAV-enabled passive 6DMA-assisted multicast system">
    </a>
  </div>
  <div class="paper-box-text">
    <h3>UAV-Enabled Passive 6D Movable Antennas: Joint Deployment and Beamforming Optimization</h3>
    <p>Changhao Liu, Weidong Mei, Peilan Wang, <strong>Yinuo Meng</strong>, Boyu Ning, Zhi Chen</p>
    <p class="paper-venue">IEEE Transactions on Wireless Communications (TWC), 2026</p>
    <p class="paper-links"><a href="https://doi.org/10.1109/TWC.2025.3643647">webpage</a> <span aria-hidden="true">|</span> <a href="https://arxiv.org/pdf/2412.11150">pdf</a> <span aria-hidden="true">|</span> <a href="/assets/bib/uav-passive-6dma.bib">bibtex</a> <span aria-hidden="true">|</span> <a href="https://arxiv.org/abs/2412.11150">arXiv</a></p>
    <details class="paper-abstract">
      <summary>Abstract</summary>
      <p>This paper introduces a UAV-enabled passive 6D movable antenna by mounting an intelligent reflecting surface on a UAV. For a multicast downlink, it jointly optimizes the UAV/IRS location, three-dimensional orientation, and passive beamforming under an angle-dependent reflection model to maximize the minimum user SNR. The single-user analysis shows that one-dimensional orientation is sufficient and admits a closed-form optimum for a fixed location. For multiple users, the proposed method combines alternating optimization, successive convex approximation, coarse-to-fine search, and Gibbs sampling to improve exploration and avoid poor local solutions.</p>
    </details>
  </div>
</article>

<article class="paper-box">
  <div class="paper-box-image">
    <a class="paper-visual" href="/assets/papers/uav-secure-6dma-space-nulling.png" aria-label="Open the full passive-6DMA space-nulling system model">
      <img src="/assets/papers/uav-secure-6dma-space-nulling.png" alt="Passive-6DMA-enabled space nulling for secure communications">
    </a>
  </div>
  <div class="paper-box-text">
    <h3>UAV-Enabled Passive 6DMA for Secure Communications: A Space-Nulling Approach</h3>
    <p><strong>Yinuo Meng</strong>, Changhao Liu, Peilan Wang, Zhi Chen</p>
    <p class="paper-venue">IEEE Globecom Workshops (GC Wkshps), 2025</p>
    <p class="paper-links"><a href="https://ieeexplore.ieee.org/document/11591115">webpage</a> <span aria-hidden="true">|</span> <a href="/assets/papers/uav-secure-6dma-space-nulling.pdf">pdf</a> <span aria-hidden="true">|</span> <a href="/assets/bib/uav-secure-6dma.bib">bibtex</a></p>
    <details class="paper-abstract">
      <summary>Abstract</summary>
      <p>This paper studies physical-layer security with a UAV-mounted passive 6DMA. Beyond conventional signal nulling, it introduces space nulling: the UAV's position and three-dimensional rotation, together with the IRS's half-space reflection, are used to place an eavesdropper outside the reflection region. The design maximizes the legitimate user's achievable rate under the space-nulling constraint. For each UAV/IRS position, the optimal rotation is reduced to a lower-dimensional problem and derived in closed form; the position is then selected by exhaustive search. Analysis and simulations identify conditions under which the method approaches the secrecy-rate optimum.</p>
    </details>
  </div>
</article>
