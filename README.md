# Hi, I'm Joshua 👋

I'm a student at the Texas Academy of Mathematics and Science (TAMS), an early-college program at the University of North Texas, planning to major in computer science. I work where computing meets the physical sciences, and I build things that hold up when someone else runs them.

### Interests

- 🔭 Astronomy and machine learning, especially classifying sources in large sky surveys
- 🧬 Computational biology and structure-based drug discovery
- 🌍 Remote sensing and deep learning on satellite imagery
- 💻 Web development and front-end design
- 📊 Data science on large, real-world datasets

### Research

My research repositories stay private while the write-ups are in progress. What I've been working on:

**Calibration of photometric classifiers (IEEE URTC, in submission).** I measured whether star/galaxy/quasar classifiers on ~500K SDSS DR17 sources produce probabilities you can trust, and whether that holds as sources get fainter. Random forests, gradient boosting, and MLPs stay well calibrated across the full magnitude range (ECE 0.003 to 0.005); logistic regression does not (ECE 0.077). The useful negative result: recalibration fit on bright sources transfers poorly to faint ones, and Platt scaling degrades worst. Temperature scaling is the safer choice.

**Deforestation detection under domain shift.** A ResNet50 fine-tuned on EuroSAT Sentinel-2 imagery reaches 98% benchmark accuracy, then falls apart out of biome: F1 of 0.001 in the Congo Basin, on a composite my diagnostics show to be clean. A label-free AdaBN pass recovers it to 0.397. Benchmark accuracy does not transfer for free, and across biomes robustness beats peak in-biome F1.

**Anti-virulence drug discovery.** Structure-based docking against a bacterial virulence target. The screen returned a null result, so I'm reframing the work as a benchmark study of the docking pipeline itself.

### Featured projects

- **[localflow](https://github.com/Joshua-Anojulu/localflow)**: local-first, system-wide dictation for Windows 11. Hold Left Ctrl, transcribe with faster-whisper large-v3-turbo on your own GPU, paste into whatever app has focus. No cloud, no quota, no audio leaving the machine.
- **[plan-hardening](https://github.com/Joshua-Anojulu/plan-hardening)**: an adversarial plan-review harness. One model drafts an implementation plan, a second model attacks it in a read-only sandbox and returns a verdict, and the loop repeats until the plan survives or hits a round cap. Ships with reviewer adapters for several backends.
- **[EnsureCollege](https://ensurecollege.com/)**: a live full-stack app that matches U.S. students to national scholarships and selective summer programs using a transparent scoring algorithm, with source-linked requirements, saved application plans, deadline tracking, and AI-assisted essay guidance. FastAPI backend, vanilla HTML/CSS/JS front end.
- **[Personal-Website](https://joshua-anojulu.github.io/Personal-Website/)** ([source](https://github.com/Joshua-Anojulu/Personal-Website)): my portfolio, pulling the research and web projects together.

### Tools

Python · PyTorch · scikit-learn · pandas · NumPy · matplotlib · pytest · FastAPI · TypeScript · Next.js · JavaScript · HTML · CSS · Git · Linux

📫 **Reach me:** joshanojulu@gmail.com
