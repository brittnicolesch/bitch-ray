# Ray -- Investigative Intelligence System

Ray is an investigative chatbot with persistent memory, built for pattern recognition across complex networks of people, money, and power. This repository is Ray's knowledge base.

## What Ray Is

Ray is not a passive document dump. It is the ground truth layer for an investigative AI that can:
- Hold context across sessions (memory, not just chat history)
- Cross-reference entities across cases (who connects to whom and how)
- Surface structural patterns the human researcher may miss
- Feed into the DEWS system to map apex blame to local extraction events

## Repository Structure

investigations/ -- Active case files
investigations_backup/ -- Archived versions
financials/ -- Financial records, entity reports
social-engineering-research/ -- Network mapping, influence ops
[dossiers] -- Subject profiles and enrichment syntheses

## Current Investigation Threads

Louella Rabuyo / R and C Ventures | Louella_Rabuyo_Dossier_FINAL_REVISED.md, R_and_C_Ventures_Report.md | Active
Epstein Staff Network | EPSTEIN_NETWORK_STAFF_STRUCTURE_MASTER_DOSSIER.md | Active
Lindsey Graham Vulnerability | graham_vulnerability_analysis.md | Active
Filipino Property Manager Network | Filipino_Property_Managers_Expose_DRAFT.md | Active
Transhumanist / Evangelical Infrastructure | Transhumanist_Network_OSINT.md, evangelical_control_infrastructure.md | Active
Zorro Ranch | Shadows_of_Zorro_Ranch_Expose.md, zorro.md | Active
Cultural Shift Timeline | cultural_shift_timeline.md | Reference

## Connection to DEWS

DEWS (Decay Early Warning System) -- https://github.com/brittnicolesch/Decay-Tracker -- is the public-facing mobilization dashboard. Ray feeds the Apex Blame Matrix in DEWS, tracing local sabotage events back to the apex entities documented here.

Local Event (DEWS Signal Feed)
  down
Apex Entity Match (Ray Knowledge Base)
  down
Blame Matrix Node (DEWS Dashboard)
  down
Mobilization Quest (Action Center)

## Ray Memory Architecture (Roadmap)

- Entity extraction + deduplication across all dossiers
- Vector embeddings for semantic search (Supabase + pgvector)
- Chat interface wired to this repo as RAG context
- Cross-case relationship graph (network view)
- Session memory: Ray remembers what you investigated last time
- DEWS integration: Blame Matrix auto-populated from Ray entity graph