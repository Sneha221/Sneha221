Hi, I'm Sneha Banerjee 👋
Generative AI Lead · AI Security Practitioner · Technical AI Safety Researcher
I build and evaluate AI systems with a focus on reliability, security, and controlled behavior. I bring eight years of experience across cybersecurity, threat hunting, incident response, and cloud security to work on agent security, AI Control, and adversarial evaluation.
Portfolio · AI Safety portfolio · LinkedIn · Email
Current focus
- AI Control and agent security: authorization boundaries, tool permissions, and controls that operate outside the model.
- AI safety evaluations: reproducible tests of model behavior under adversarial instructions, including prompt injection.
- AI verification: monitoring, policy enforcement, and evidence that systems meet specified behavioral requirements.
- Efficient AI systems: model benchmarking, routing, prompt caching, and inference cost and latency optimization.
Selected AI safety work
PACT: Purpose-Bound Agent Control
Designed and implemented controls for tool-using agents, including purpose binding, tool authorization, instruction/data separation, deterministic enforcement, runtime monitoring, signed Agent Cards, and sandboxed MCP execution. Presented the research at ICICCS 2026.
- In the reported AgentDojo evaluation across 97 task domains, attack success decreased from 17.6% to 1.9%, with 90.6% task utility and a 2.5% false-positive rate.
- In a separate compound-attack setup, success decreased from 31.4% to 1.9%.
- These findings apply to the evaluated benchmarks and threat models; they are not a general guarantee of agent security.
Prompt-injection evaluation prototype
Built Inspect AI scenarios for direct, authority-based, urgency, roleplay, and indirect instructions embedded in untrusted incident reports, alongside a simulated sensitive-action tool, configurable authorization guard, and custom scorer. The initial guard blocks all simulated exports when enabled, so the preliminary comparison does not establish general prompt-injection resistance or preserved task usefulness.
AI Control evaluation tooling
Implemented Trusted Monitoring, Defer-to-Trusted, Trusted Editing, Defer-to-Resampling, and Hybrid protocols for coding-integrity tasks, with configurable thresholds, monitor variants, and trusted/untrusted model-pair sweeps. Added keyword and model-based monitors, ensemble scoring, escalation logic, and analysis for attack success, usefulness, precision/recall, F1, bootstrap confidence intervals, and paired tests where matched samples are available.
PyRIT prompt-injection and jailbreak experiments
Developed experiments covering direct and cross-prompt injection, multi-turn jailbreaks, encoding and multilingual obfuscation, attack orchestration, scoring pipelines, and multimodal inputs. The work surfaced evaluation-design lessons: attacks can enter through retrieved content and tool outputs; tests should vary attack strategies under a consistent threat model; and defenses should authorize tools outside the model. These experiments did not produce generalizable model-level attack-success results.
Cyber Guard Agent
Built a four-agent security-operations pipeline for triage, investigation, remediation, and reporting using Amazon Bedrock AgentCore and simulated MCP tools. On 100 synthetic alerts it achieved 94% accuracy, 12.4 seconds average latency, and $0.034 average cost per incident. In a matched-pair simulation, 0 of 50 prompt injections succeeded; this result is limited to that synthetic setup.
Frontier AI Security Training (FAST)
Selected 1 of 20 participants from 700+ applicants for the Singapore AI Safety Hub program. Work included AI Control and ControlArena, monitoring and verification, and open-weight security experiments: editing refusal directions in activations and weights, detecting trigger backdoors with activation probes, and comparing logit, text-only, and top-k distillation risks.
Professional experience
Senior Consultant – Generative AI Lead | Infosys
- Lead and coordinate 9+ AI R&D workstreams, including enterprise prompt caching, agent cost optimization, runtime benchmarking, model routing, and vectorless RAG.
- Turn research opportunities into reusable accelerators, implementation guides, benchmarking frameworks, governance assets, and adoption playbooks.
- Identified up to 86% caching-related savings opportunities and 50–75% optimization potential across evaluated workloads.
- Produced benchmarking evidence of 8.53× runtime efficiency gains and 74.98× scalability improvements in evaluated scenarios.
- Contribute to secure agent architecture and the Agent Certification Engine (ACE), focused on deterministic authorization, policy enforcement, prompt-injection defense, adversarial testing, and runtime monitoring.
Earlier security engineering
At Microsoft India R&D, led cloud and identity investigations, analyzed activity across 5,000+ Entra ID tenants, built Azure ML anomaly detection for password attacks, and automated response workflows. Earlier roles at Nike, Aujas Cybersecurity, and Hewlett Packard Enterprise covered threat detection, WAF deployment, penetration testing, cloud security, and identity systems.
Technical toolkit
- AI and evaluation: Python, Inspect AI, ControlArena, PyRIT, Ollama, LLM evaluation, RAG, model benchmarking, prompt caching, model routing
- AI security: prompt injection, adversarial testing, tool authorization, AI Control, runtime monitoring, threat modeling
- Cloud and engineering: Amazon Bedrock, AgentCore, SageMaker, Azure OpenAI, Azure AI Foundry, Docker, Kubernetes, Terraform, GitHub Actions
- Cybersecurity: Entra ID, OAuth 2.0, Conditional Access, incident response, forensics, threat hunting, penetration testing
Education and training
- M.Tech, Artificial Intelligence and Machine Learning (NLP) — BITS Pilani, 2024–2026
- B.Tech, Computer Science and Engineering — Vellore Institute of Technology, 2014–2018
- AGI Strategy — BlueDot Impact, currently pursuing
- AI/ML in Drone Technology — TiHAN, IIT Hyderabad, March 2026
Certifications and community
GIAC Certified Incident Handler (GCIH) · Certified Azure Red Team Professional (CARTP) · AWS Certified Solutions Architect – Associate · Certified Ethical Hacker (CEH v10)
Presented RAM forensics at Hackfest 2023 and PACT research at ICICCS 2026; spoke at Women Who Code Singapore, NASSCOM Global Inclusion Summit, and Winja Talks. Mentored students in digital literacy with Connecting Dreams Foundation.
Research interests
AI Control · AI verification · Agent security · Prompt-injection resistance · Adversarial evaluation · Evaluation reliability
I’m interested in turning practical security experience into rigorous experiments and deployable controls that help increasingly capable AI systems remain useful, measurable, and safe.
