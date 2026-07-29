# HAAG Compute & Storage Usage Log — Questionnaire

**Purpose:** Log actual compute, storage, and technical resource usage per team/project, broken down by workload type — not adoption sentiment or pain points. This replaces the earlier advisor conversation questionnaire, which focused on barriers and guide fit rather than logged usage.

**Suggested unit of collection:** per *project*, not per advisor — a group running three distinct workload types should fill this out three times, once per project, since resource profiles differ by workload.

---

## 1. Team & Project Context

1. Team / group name
2. Project name (if a group runs multiple projects, one entry per project)
3. Primary research domain / project type — LLM, computer vision, classical ML / tabular, audio / signal processing, bioinformatics, simulation / numerical, distributed training, other (specify)
4. Number of researchers actively submitting jobs under this project

## 2. Compute Usage

5. Which GPU type(s) does this project request most often? — V100, A100, H100, H200, RTX 6000 Pro, CPU-only / no GPU, other (specify)
6. Typical number of GPUs per job
7. Typical CPU cores requested per job
8. Typical job wall-time (e.g. under 1 hr, 1–8 hrs, 8–24 hrs, 1–3 days, 3+ days)
9. Approximate number of jobs submitted per week
10. Does this project run distributed / multi-node jobs? If yes, typical number of nodes

## 3. Storage Usage

11. Approximate total current storage footprint for this project
12. Approximate size of raw datasets used
13. Approximate size of model checkpoints / outputs generated
14. Is storage usage growing over time? If yes, roughly how much per month
15. Does this project rely heavily on scratch/temporary storage? Approximate size if so

## 4. Technical / Workload Details

16. Framework(s) used — PyTorch, TensorFlow, JAX, scikit-learn, custom, other (specify)
17. Is the workload containerized (Docker / Apptainer)?
18. Any specialized software, libraries, or license-restricted tools required?
19. Is the data pipeline I/O-heavy (frequent reads/writes) or primarily compute-bound?
20. Any other technical constraints worth noting (e.g. specific CUDA/driver version requirements)?

---

## Notes on use

- This is designed to be filled out directly by each project/team, not run as a live interview — the questions ask for numbers and technical specifics rather than opinions, so a form or written response is a more natural fit than a conversation.
- Worth checking with Neelima Pandey before distributing this broadly — her Computational Resources Requirements Estimation Process initiative covers adjacent ground (semester-level team resource demand), and there may be room to combine efforts rather than run two separate surveys.
- Aggregated across teams, this becomes the same kind of pattern data the original questionnaire was after (which research domains use the most GPU-hours, which store the most data) — just grounded in actual numbers instead of self-reported sentiment.
