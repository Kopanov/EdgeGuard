## EdgeGuard - Graph-Augmented xAI for Threat Intelligence on Edge Infrastructure

### Overview

EdgeGuard addresses the critical need for transparent, auditable threat intelligence for organizations with limited cybersecurity resources. Led by IICT-BAS in collaboration with our partner Ratio1, we are deploying a hybrid architecture that combines symbolic knowledge graphs with fine-tuned language models directly on edge infrastructure. This system transforms raw security alerts into clear, actionable recommendations that enable analysts to trace incident chains and respond effectively without relying on opaque cloud platforms.

Our motivation for participating in the ResilMesh Open Call is to validate these novel algorithms in a robust, decentralized environment. By leveraging Ratio1’s specialized edge cloud capabilities and commercial expertise, we aim to bridge the gap between advanced research and practical application, ensuring our solution effectively democratizes cyber defense while meeting the rigorous demands of critical infrastructure.

### Status

Stage 3 (Validation & Release, July–October 2026) is in progress: the full stack runs on Ratio1 edge
nodes and is rebuilt from a 730-day window of open threat data. Stages 1 (knowledge graph) and 2
(fine-tuned text-to-Cypher model and integrations) are complete.

### Partners

- **IICT-BAS**: Institute of Information and Communication Technologies, Bulgarian Academy of Sciences (Lead)
- **Ratio1**: Specialized edge cloud capabilities and commercial expertise

### Team

- **Prof. Dr. Tatiana Atanasova** – Project Lead, IICT-BAS  
- **Kalin Kopanov** – IICT-BAS  
- **Assoc. Prof. Dr. Andrei Damian** – Ratio1.ai  
- **Cristian Bleotiu** – Ratio1.ai  
- **Petrica Butusina** – Ratio1.ai

### Page structure

`index.html` is a single self-contained page (inline CSS, JS and SVG; no external requests). It has
four tabs selected from the left sidebar and addressed by hash: `#stage-3` (default), `#overview`,
`#stage-2` and `#stage-1`. Without JavaScript all tabs render one after another; printing does the same.

To update figures, edit the numbers in the matching `<section data-tab="...">` and keep the date next
to them current. Keep the `R1EN_HOST_ID` placeholder in the footer: the Ratio1 node fills it in.

