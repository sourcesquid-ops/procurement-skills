# Procurement Skills 🧠

The world's first open‑source **Claude Skills** library for sourcing, procurement, logistics & supply chain professionals – built with Claude, for Claude.

## What is this?

This repo contains production‑ready Claude projects packaged as skills for real procurement and SCM work.  
Each `.zip` file is an export of a working Claude project (skills, tools, instructions), so you can import it straight into Claude and start using it.

Current skills include things like:

- Sourcing project context setup  
- RFQ drafting and comparison  
- Vendor qualification and scorecards  
- Incoterms & trade‑compliance advisor  
- Freight cost calculator and cost‑modelling helper  
- Supplier outreach and email drafting  
- Tariff / HS code lookup  
- Contract redlining assistance  
- Spend‑analysis helpers  
- DFM / manufacturability bridge  
- Resilience radar / risk mapping  
- Negotiation strategies support  
- Purchase‑performance scorecards  
- ESG / compliance checks  
- Customs documentation helpers  
- New‑product introduction workflows  

All skills were designed and iterated with Claude itself, then exported from Claude as `.zip` projects.

## How the skills are structured

Each skill is:

- A **Claude project export** (`skill-XX-*.zip`) that you can import directly into Claude.  
- Focused on a **specific procurement / SCM task** (e.g. RFQ drafting, HS lookup, freight costing).  
- Built around real‑world workflows used by practitioners.

Inside each project, you’ll typically find:

- System instructions tuned for that task  
- One or more tools / workflows wired together  
- Example prompts or starter templates  
- Guardrails for safety, compliance, and data handling

This means you’re not just copying a prompt – you’re loading a complete Claude configuration that already “knows” how to behave in that scenario.

## Who is it for?

- Procurement managers and buyers  
- Sourcing / category managers  
- Supply‑chain & logistics professionals  
- Founders and operators doing their own procurement  
- AI / operations teams building **Claude‑based agents** for SCM

If you live in RFQs, POs, supplier lists, price breakdowns, HS codes, and shipments, this repo is for you.

## Using these skills in Claude

1. **Pick a skill**

   Browse the `skill-XX-*.zip` files and choose the one closest to your workflow (e.g. `skill-02-rfq-drafting.zip`, `skill-08-tariff-hs-lookup.zip`).

2. **Import into Claude**

   - In Claude, create a new Project or Workflow.  
   - Use the import/upload option and select the `.zip` file.  
   - Claude will recreate the project: instructions, tools, and any included examples.

3. **Adapt to your environment**

   - Update any company‑specific settings (regions, categories, approval rules, preferred Incoterms).  
   - Plug in your own data: supplier lists, RFQs, SKUs, contracts, shipment data (respecting your company’s data policies).

4. **Run and iterate**

   - Test on safe or anonymised data first.  
   - Fine‑tune wording, thresholds, and outputs.  
   - Save your customised version in your own Claude workspace.

## Extending and composing skills

Because these are Claude projects, you can:

- Combine several skills into a larger **multi‑step workflow** (e.g. supplier discovery → RFQ → cost model → contract review).  
- Add your own tools (APIs, spreadsheets, internal systems) around the imported skill.  
- Fork a skill and specialise it for a specific category, region, or business unit.

If you build something robust and reusable, consider contributing it back.

## Contributing

Contributions are very welcome:

- New Claude skills (as `.zip` exports) for specific procurement / SCM use‑cases  
- Improvements to existing skills (better guardrails, clearer outputs, more robust logic)  
- Documentation: usage guides, screenshots, example workflows

See `CONTRIBUTING.md` for guidelines on:

- How to name and structure new skills  
- How to document inputs/outputs and limitations  
- How we review and merge pull requests

## License

This project is licensed under the MIT License – see `LICENSE` for details.
