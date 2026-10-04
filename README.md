# SE_LAB3
# Component Modelling & Architectural Pattern Selection

## SRN:PES2UG24AM108

## Scenario Overview
Software architecture design for a **Self-Service Coffee Kiosk System** in a café environment. The kiosk manages order configuration (coffee type, size), credit card payment handling, and receipt generation.

## Architectural Style
- **Selected Pattern:** Layered Architecture
- **Rationale:** Strict separation of concerns across Presentation (Touch Screen UI), Business Logic (Order Manager, Payment Service, Receipt Printer), and Data Storage (Menu & Pricing Database).

## Components Identified
1. **Touch Screen UI Component:** Presentation layer handling user touch input and item selection.
2. **Order Manager Component:** Central business logic coordinator orchestrating order flow.
3. **Payment Service Component:** Dedicated service communicating with credit card gateways.
4. **Receipt Printer Component:** Hardware driver interface for printing transaction receipts.
5. **Menu & Pricing DB Component:** Persistent data store for beverage catalog and pricing.

## Deliverables in this Repository
- `Lab3_Component_Diagram.drawio` – Source editable file (draw.io)
- `Lab3_Component_Diagram.drawio.png` – Exported high-resolution UML component diagram
- `Lab3_Architecture_Justification.docx` – Written justification report
- `Lab3_Architecture_Justification.pdf` – Exported justification document
