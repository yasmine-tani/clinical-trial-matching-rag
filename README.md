# Clinical Trial Matching with RAG 🚧 (in progress)

Matches patients to recruiting clinical trials using semantic search
over ClinicalTrials.gov eligibility criteria.

## Progress
- [x] Pull recruiting trials from the ClinicalTrials.gov API (saved snapshot for reproducibility)
- [x] Chunk eligibility criteria with recursive splitting and a per-trial token budget
- [x] Embed chunks with all-MiniLM-L6-v2
- [ ] Semantic search grouped by trial
- [ ] Hard filters for age and sex
- [ ] LLM-generated explanations citing NCT IDs
- [ ] Evaluation on synthetic patient profiles