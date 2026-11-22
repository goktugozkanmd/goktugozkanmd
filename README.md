# Göktuğ Özkan, MD

**Biosecurity & Frontier AI×Bio Evaluation Researcher · Physician-Engineer (MD)**  
Nucleic-acid synthesis screening · Pathogen genomic surveillance · Deterministic AI safety verifiers · Benchmark integrity auditing

[Email](mailto:drozkan2@gmail.com) · [ORCID: 0000-0002-5022-9124](https://orcid.org/0000-0002-5022-9124) · [PubMed: PMID 42874665](https://pubmed.ncbi.nlm.nih.gov/42874665/) · [Hugging Face](https://huggingface.co/goktugozkanmd) · [LinkedIn](https://www.linkedin.com/in/goktugozkanmd/)

---

### Focus Areas
- **Defensive Biosecurity & Sequence Screening:** Nucleic-acid synthesis triage architectures, streaming screening pipelines, and zero-pathogen defensive verifiers.
- **Frontier AI×Bio Benchmark Integrity:** Forensic auditing of biological & safety benchmarks for data corruption, primer/sequence errors, and question-blind shortcuts.
- **Deterministic Biomedical Safety Harnesses:** Reproducible, clinician-designed evaluation suites and RLVR safety verifiers compatible with UK AISI **Inspect AI**.

---

### Flagship Open-Source Projects
- **[bioeval-guard (v1.0.0)](https://github.com/goktugozkanmd/bioeval-guard)** — Deterministic integrity auditor for frontier AI×Bio evaluations (`N=3,428` cross-benchmark audit across `WMDP`, `LAB-Bench`, and `BixBench`), capsule cluster-variance (`ICC`/`DEFF`), sequence/protein/phylodynamic screening invariants, and MCQ/judge scorer checks (`38/38` tests passing, zero API cost).
- **[open-viral-pgx-safety](https://github.com/goktugozkanmd/open-viral-pgx-safety)** — Defensive viral sequence-architecture screening (CpG host-mimicry index, dinucleotide entropy, synthetic ORF triage) & CPIC Level A pharmacogenomic AI safety verifier with an **Inspect AI** adapter. *(Defensive screening only; zero pathogen blueprints.)*
- **[medical-ai-failure-atlas (MedFailBench)](https://github.com/goktugozkanmd/medical-ai-failure-atlas)** — Reproducible open-source evaluation harness and clinician-graded severity rubrics exposing high-stakes safety failures masked by aggregate LLM scores.
- **[open-ehr-organ-toxicity](https://github.com/goktugozkanmd/open-ehr-organ-toxicity)** — Deterministic biomedical organ-toxicity evaluators (FDA eDISH/Hy's Law, KDIGO, Fridericia QTcF/CTCAE v5.0, ASTCT CRS) packaged as a Clinical AI RLVR safety verifier with schema-only MIMIC-IV/eICU-CRD BigQuery SQL.
- **[medfailscan](https://github.com/goktugozkanmd/medfailscan)** — Zero-dependency, offline deterministic red-flag scanner across 12 clinical/safety failure classes.
- **[Awesome-Agent-Harness-for-Healthcare](https://github.com/goktugozkanmd/Awesome-Agent-Harness-for-Healthcare)** — Curated biomedical & AI agent evaluation harnesses covering outcome scoring, tool-call process verification, and safety governance.

---

### Frontier Biosecurity, Genomics & AI Safety Contributions

#### Merged Upstream Contributions (21)
- **MIT Laboratory for Computational Physiology / PhysioNet (`MIT-LCP/wfdb-python`):** Authored `wfdb_to_mat` encoding, channel slicing, and header metadata fixes incorporated into `main` via [#650](https://github.com/MIT-LCP/wfdb-python/pull/650) *(from [#633](https://github.com/MIT-LCP/wfdb-python/pull/633))*.
- **UK AI Security Institute (`UKGovernmentBEIS/inspect_evals`):** Audited and migrated solver setup across `assistant_bench` and `gdm_self_reasoning` ([#1892](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1892), [#1893](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1893), [#1897](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1897)).
- **Biosafety & AI Safety Benchmarks:** Merged biosafety triage regression tests in [`AIEpisteme/BioSafeBench#1`](https://github.com/AIEpisteme/BioSafeBench/pull/1); evaluation card templates & LangFair card in **The AI Alliance** [`trust-safety-evals`](https://github.com/The-AI-Alliance/trust-safety-evals) ([#61](https://github.com/The-AI-Alliance/trust-safety-evals/pull/61), [#62](https://github.com/The-AI-Alliance/trust-safety-evals/pull/62)); healthcare safety eval fixtures in [`OpenGuardrailsBench#17`](https://github.com/openguardrails/OpenGuardrailsBench/pull/17) and [`AgentEval#273`](https://github.com/AgentEvalHQ/AgentEval/pull/273).

#### Benchmark Integrity Audits (Live Forensic Disclosures)
- **FutureHouse `LAB-Bench` ([Issue #20](https://github.com/Future-House/LAB-Bench/issues/20)) & UK AISI `inspect_evals` ([Issue #2953](https://github.com/UKGovernmentBEIS/inspect_evals/issues/2953)):** Identified `40/40` `PCR-seq-enzprimers` sense-strand reverse primers, `8/40` isoschizomer collisions, and duplicate `ded3f6ac` in pinned HF revision `5c77cec6`, `100.0%` (`80/80`) centroid exploitability on `DbQA/variant_multi_sequence_task`, `5/199` literal `"null"` ideals in `LitQA2`, and `46.1%` longest-option bias on `WMDP-Bio` (`p_adj=1.16e-58`).

#### Active Open Upstream PRs (11 Under Maintainer Review)
- **IBBIS (`ibbis-bio/common-mechanism`):** [#167](https://github.com/ibbis-bio/common-mechanism/pull/167) — Streaming `ScreenResult` JSON serialization (`-97.5%` peak RAM) for DNA synthesis screening.
- **SecureBio (`securebio/basecall-workflow` & `securebio/nao-read-sizer`):** [#28](https://github.com/securebio/basecall-workflow/pull/28) — Fail-fast barcode & demux read-count QC; [#28](https://github.com/securebio/nao-read-sizer/pull/28) — Pre-submission & Batch FASTQ input verification.
- **Nextstrain (`nextstrain/augur` & `neherlab/treetime`):** [`augur#2075`](https://github.com/nextstrain/augur/pull/2075) — Sequence-index mismatch warnings on partial overlap; [`treetime#968`](https://github.com/neherlab/treetime/pull/968) — Mismatched length & empty/missing alignment diagnostics (`augur#1919`).
- **FutureHouse (`Future-House/aviary` & `Future-House/BixBench`):** [`aviary#395`](https://github.com/Future-House/aviary/pull/395) — Typed `BaseModel` tool-argument deserialization; [`BixBench#51`](https://github.com/Future-House/BixBench/pull/51) — Safe XML `<tag>...</tag>` parsing without negative-slice corruption.
- **Chai Discovery (`chaidiscovery/chai-lab`):** [#439](https://github.com/chaidiscovery/chai-lab/pull/439) — Reject mismatched modified-FASTA brackets and empty FASTA labels.
- **UK AI Security Institute (`AI-Safety-Institute/transect`):** [#128](https://github.com/AI-Safety-Institute/transect/pull/128) — Line-terminator normalization in `digest_line`.
- **Arc Institute (`ArcInstitute/cellstream`):** [#4](https://github.com/ArcInstitute/cellstream/pull/4) — Lock sidecar cleanup and NFS staging resilience.
- **MIT-LCP / PhysioNet (`MIT-LCP/wfdb-python`):** [#653](https://github.com/MIT-LCP/wfdb-python/pull/653) — Vectorized `_checksums` consolidation across converters (`18/18` CI passing).

---

### Selected Peer-Reviewed Research
- **Özkan G.** *Do Large Language Models Link to Incorrect Citations? A PubMed and DOI Benchmark.* **Applied Clinical Informatics** (SCIE Q2). 2026;17(4):950–954. [doi:10.1055/a-2972-4974](https://doi.org/10.1055/a-2972-4974) · **PMID: 42874665** *(Sole Author)*.
- **Özkan G.** *Multicenter ICU Sepsis Aminoglycoside Nephrotoxicity Safety Benchmark (MIMIC-IV & eICU-CRD).* **Infectious Diseases and Clinical Microbiology (IDCM)** (ESCI, Accepted 2026, #1211).

---

<sub>All biosecurity and biomedical repositories are strictly defensive, deterministic, and research-only; no pathogen blueprints, no patient-identifiable data, and not for clinical use.</sub>
