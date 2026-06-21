---
title: "Research Overview"
summary: "Decoding the microbiome using deep learning and metagenomics."
date: 2026-06-21T00:00:00Z
---

<div class="relative rounded-3xl overflow-hidden bg-gradient-to-br from-indigo-950 via-slate-900 to-emerald-950 p-8 md:p-12 mb-12 border border-slate-800 shadow-2xl backdrop-blur-md">
  <!-- Glowing gradient background orbs -->
  <div class="absolute -top-24 -right-24 w-96 h-96 bg-indigo-500/20 rounded-full filter blur-3xl opacity-30"></div>
  <div class="absolute -bottom-24 -left-24 w-96 h-96 bg-emerald-500/10 rounded-full filter blur-3xl opacity-20"></div>

  <div class="relative z-10 max-w-3xl">
    <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-semibold bg-emerald-500/10 text-emerald-400 border border-emerald-500/20 mb-4">
      🧬 Research Vision
    </span>
    <h1 class="text-3xl md:text-5xl font-extrabold tracking-tight mb-4 leading-tight text-white">
      Decoding Microbial Life with <span class="bg-gradient-to-r from-indigo-400 via-sky-400 to-emerald-400 bg-clip-text text-transparent">AI & Metagenomics</span>
    </h1>
    <p class="text-base md:text-lg text-slate-300 leading-relaxed font-light mb-6">
      My research lies at the intersection of <strong class="text-white font-semibold">computational biology, machine learning, and microbiology</strong>. I develop and apply deep learning models to explore massive metagenomic datasets, with the goals of describing planetary viral diversity and elucidating functions of novel genes.
    </p>
    <div class="flex flex-wrap gap-2.5">
      <span class="inline-flex items-center px-3 py-1.5 rounded-full text-xs font-semibold bg-rose-500/20 text-white border border-rose-500/30">
        🦠 Virology
      </span>
      <span class="inline-flex items-center px-3 py-1.5 rounded-full text-xs font-semibold bg-indigo-500/20 text-white border border-indigo-500/30">
        🏷️ Functional Annotation
      </span>
      <span class="inline-flex items-center px-3 py-1.5 rounded-full text-xs font-semibold bg-emerald-500/20 text-white border border-emerald-500/30">
        🧬 Microbiome
      </span>
    </div>
  </div>
</div>

<h2 class="text-2xl md:text-3xl font-bold text-slate-800 dark:text-slate-100 mb-8 flex items-center gap-2">
  <span class="text-indigo-500">■</span> Core Research Directions
</h2>

<div class="grid grid-cols-1 lg:grid-cols-3 gap-8 mb-12">
  <!-- Panel 1: Biological Sequence Analysis -->
  <div class="flex flex-col justify-between p-6 rounded-2xl bg-slate-50 dark:bg-slate-900/60 border border-slate-200 dark:border-slate-800/80 hover:border-indigo-500/50 dark:hover:border-indigo-400/50 transition-all duration-300 hover:shadow-xl group">
    <div>
      <div class="w-10 h-10 rounded-xl bg-indigo-500/10 text-indigo-500 dark:text-indigo-400 flex items-center justify-center mb-4 group-hover:scale-110 transition-transform duration-300">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"/></svg>
      </div>
      <h3 class="text-lg font-bold text-slate-800 dark:text-slate-100 mb-3">Biological Sequence Analysis</h3>
      <ul class="space-y-3 text-sm text-slate-600 dark:text-slate-400 leading-relaxed mb-6">
        <li>
          <strong class="text-slate-800 dark:text-slate-200">CRISPR-PAM:</strong> Metagenomic mapping of PAM preferences across millions of Cas9 proteins to expand targeting options.
        </li>
        <li>
          <strong class="text-slate-800 dark:text-slate-200">DeepFRI:</strong> GNN-based function prediction directly from sequence-derived contact maps at database scale.
        </li>
        <li>
          <strong class="text-slate-800 dark:text-slate-200">scikit-bio:</strong> Contributions to Python's core bioinformatic library for sequence analysis and diversity metrics.
        </li>
      </ul>
    </div>
    <div class="flex flex-wrap gap-2 text-xs">
      <a href="/publications/cas9-pam-diversity-2026/" class="font-semibold text-indigo-500 hover:text-indigo-600 dark:hover:text-indigo-400">CRISPR-PAM ↗</a>
      <span class="text-slate-300 dark:text-slate-700">|</span>
      <a href="https://github.com/scikit-bio/scikit-bio" target="_blank" rel="noopener" class="font-semibold text-indigo-500 hover:text-indigo-600 dark:hover:text-indigo-400">scikit-bio ↗</a>
    </div>
  </div>

  <!-- Panel 2: Microbiome - Host Relationship -->
  <div class="flex flex-col justify-between p-6 rounded-2xl bg-slate-50 dark:bg-slate-900/60 border border-slate-200 dark:border-slate-800/80 hover:border-emerald-500/50 dark:hover:border-emerald-400/50 transition-all duration-300 hover:shadow-xl group">
    <div>
      <div class="w-10 h-10 rounded-xl bg-emerald-500/10 text-emerald-500 dark:text-emerald-400 flex items-center justify-center mb-4 group-hover:scale-110 transition-transform duration-300">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"/></svg>
      </div>
      <h3 class="text-lg font-bold text-slate-800 dark:text-slate-100 mb-3">Microbiome - Host Relationship</h3>
      <ul class="space-y-3 text-sm text-slate-600 dark:text-slate-400 leading-relaxed mb-6">
        <li>
          <strong class="text-slate-800 dark:text-slate-200">Probiotics:</strong> Clinical trial mapping multi-species probiotics response on gut microbiota functions in obese postmenopausal women.
        </li>
        <li>
          <strong class="text-slate-800 dark:text-slate-200">Rhinosinusitis:</strong> Investigating spatial variability in chronic rhinosinusitis sinus microbiome, highlighting patient-specific differences.
        </li>
      </ul>
    </div>
    <div class="flex flex-wrap gap-2 text-xs">
      <a href="/publications/probiotics-2022/" class="font-semibold text-emerald-500 hover:text-emerald-600 dark:hover:text-emerald-400">Probiotics ↗</a>
      <span class="text-slate-300 dark:text-slate-700">|</span>
      <a href="/publications/determinants-microbiome-rhinosinusitis-2024/" class="font-semibold text-emerald-500 hover:text-emerald-600 dark:hover:text-emerald-400">Rhinosinusitis ↗</a>
    </div>
  </div>

  <!-- Panel 3: Machine Learning -->
  <div class="flex flex-col justify-between p-6 rounded-2xl bg-slate-50 dark:bg-slate-900/60 border border-slate-200 dark:border-slate-800/80 hover:border-sky-500/50 dark:hover:border-sky-400/50 transition-all duration-300 hover:shadow-xl group">
    <div>
      <div class="w-10 h-10 rounded-xl bg-sky-500/10 text-sky-500 dark:text-sky-400 flex items-center justify-center mb-4 group-hover:scale-110 transition-transform duration-300">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
      </div>
      <h3 class="text-lg font-bold text-slate-800 dark:text-slate-100 mb-3">Machine Learning</h3>
      <ul class="space-y-3 text-sm text-slate-600 dark:text-slate-400 leading-relaxed mb-6">
        <li>
          <strong class="text-slate-800 dark:text-slate-200">Metagenomic DeepFRI:</strong> Integrating deep-learning GNNs into bioinformatics pipelines to annotate novel gut microbial genes.
        </li>
        <li>
          <strong class="text-slate-800 dark:text-slate-200">TM-Vec2:</strong> Lightweight sequence embedder trained via knowledge distillation to predict protein structure similarity (TM-scores) at scale.
        </li>
      </ul>
    </div>
    <div class="flex flex-wrap gap-2 text-xs">
      <a href="https://github.com/bioinf-mcb/Metagenomic-DeepFRI" target="_blank" rel="noopener" class="font-semibold text-sky-500 hover:text-sky-600 dark:hover:text-sky-400">DeepFRI ↗</a>
    </div>
  </div>
</div>

