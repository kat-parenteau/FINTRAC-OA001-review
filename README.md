# Financial Crime Threat Intelligence: Romance Fraud Typology Analysis

## Project Overview
This repository contains a strategic analysis based on the **FINTRAC Operational Alert: Laundering of the Proceeds of Romance Fraud (FINTRAC-2019-OA001)**. 

The objective of this project is to deconstruct complex financial crime typologies and translate them into actionable corporate compliance controls. By analyzing the psychological manipulation tactics used by perpetrators, this project maps behavioral indicators to specific transactional data points, enhancing both rule-based transaction monitoring and front-line detection capabilities.

## Methodology
1. **Threat Deconstruction:** Analyzed government-issued operational alerts to identify the "grooming and extraction" lifecycle of romance fraud.
2. **Indicator Mapping:** Categorized risk indicators into two distinct streams: Behavioral (Front-Line) and Transactional (Data/Systemic).
3. **Control Design:** Developed actionable mitigation strategies, including automated system rules and operational escalation protocols, to support continuous Risk and Compliance Management (RCM).

---

## Executive Summary: The Threat Landscape
Romance fraud represents a critical vulnerability for financial institutions. Perpetrators systematically groom individuals—often targeting those at vulnerable life stages (e.g., seniors, recently widowed) to gain trust. Once established, perpetrators fabricate urgent financial scenarios to extract funds or manipulate victims into acting as unwitting "money mules" to layer illicit funds. 

Because this crime relies heavily on emotional manipulation, victims are often highly defensive and underreport the fraud, making proactive, data-driven detection critical.

---

## Key Risk Indicators (KRIs)

### 1. Behavioral Indicators (Client-Facing / Front-Line)
* **Coached Interactions:** The client appears to be directed by a third party (via phone, text, or earpiece) while conducting the transaction.
* **Defensive Explanations:** The client provides confusing, conflicting, or highly defensive rationales for unusual transactions when questioned by staff.
* **Digital-Only Relationships:** The client is sending funds to an individual they have never physically met and communicate with exclusively online.

### 2. Transactional Indicators (Data & Monitoring Systems)
* **Asset Depletion:** Sudden, uncharacteristic liquidation of core assets (e.g., breaking GICs, draining RRSPs) or taking out sudden credit advances to fund outgoing transfers.
* **Velocity & Volume:** An escalating frequency and dollar amount of outgoing Electronic Money Transfers (EMTs) or wire transfers.
* **High-Risk Corridors:** Transfers directed to jurisdictions heavily associated with this specific typology (e.g., Ivory Coast, Nigeria, Ghana, Malaysia, Turkey).
* **Money Mule Activity:** "In-and-out" account behavior characterized by multiple third-party transfers deposited into the account, followed immediately by cash withdrawals or outgoing wires.

---

## Recommended Mitigation Strategies & Controls

To effectively mitigate the risks associated with this typology and maintain regulatory compliance, the following controls are recommended for implementation:

1. **Rule-Based Transaction Monitoring (System Control):**
   * Implement automated logic alerts within the AML software to flag accounts exhibiting a combination of sudden asset depletion followed by outgoing international wires to identified high-risk jurisdictions within a 48-hour window.
2. **Enhanced Front-Line Training (Operational Control):**
   * Deploy targeted training for branch staff focusing on the psychological indicators of romance fraud, emphasizing de-escalation, empathetic questioning techniques, and the identification of "coached" behavior.
3. **Intervention Protocols (Governance Control):**
   * Establish a formalized escalation pathway allowing front-line staff to place temporary administrative holds on suspicious outgoing wires for vulnerable demographics pending an Enhanced Due Diligence (EDD) review.
4. **Victim Resource Distribution (Social Responsibility):**
   * Equip staff with standardized resource kits to tactfully provide contact information for the Canadian Anti-Fraud Centre and local law enforcement upon identifying a confirmed victim.

---

## Core Competencies Demonstrated
* **Regulatory Interpretation:** Analyzing FINTRAC guidelines and translating them into corporate policy.
* **Typology Research:** Understanding complex laundering methodologies and social engineering tactics.
* **GRC (Governance, Risk, and Compliance):** Designing internal controls to mitigate identified risks.
* **Technical Writing:** Producing structured, professional threat intelligence summaries for stakeholder review.
