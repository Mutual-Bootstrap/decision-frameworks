# Decision Framework: Information Accountability

## Purpose

To determine who should be accountable for an information asset, irrespective of which team creates, consumes or stores the information.

The objective is to assign accountability based on organisational purpose and business outcomes rather than organisational convenience or technology ownership.

## Principle

Information accountability follows business accountability.

Ownership must not be assigned because an individual:

- Owns a system.
- Manages a database.
- Commissions a project.
- Funds a service.

Instead, accountability belongs to the role responsible for the business outcome that depends upon the information.

## Framework

See https://github.com/HeliosAnavatis/EA-Thoughts/blob/main/sectors/DA/TOM/Information%20Accountability.md for a full worked example

### Step 1: Identify the Capability

Determine which business capability the information primarily enables.

Examples:

| Information | Capability |
|------------|------------|
| Asset Register | Asset Management |
| Requirements Specification | Requirements Management |
| Technical Standards | Technical Assurance |
| Contractor Competency Records | Supply Chain Management |
| Parliamentary Estate Survey Data | Estate Intelligence |

If multiple capabilities use the information, identify the capability responsible for maintaining its truth.

### Step 2: Identify the Decision

Determine the significant organisational decisions that rely on the information.

Examples:

| Information | Decision Supported |
|------------|-------------------|
| Cost Forecast | Investment Decisions |
| Design Assurance Record | Design Approval |
| Risk Register | Risk Acceptance |
| Asset Condition Data | Maintenance Prioritisation |

The person accountable for making or assuring the decision is usually a strong candidate for accountability.

### Step 3: Identify the Authoritative Source

Determine where the information is created and validated.

Questions:

- Who confirms accuracy?
- Who approves changes?
- Who determines quality rules?
- Who can reject incorrect information?

The authoritative source is often a process rather than a system.

### Step 4: Identify the Business Object

Determine the business object represented by the information.

Examples:

- Requirement
- Asset
- Standard
- Contract
- Risk
- Design
- Project
- Supplier
- Derogation

Ownership should normally exist at business object level.

### Step 5: Identify the Accountable Role

Assign accountability to the role accountable for:

- Definition
- Quality
- Integrity
- Lifecycle
- Appropriate use

Examples:

| Business Object | Accountable Role |
|----------------|------------------|
| Requirement | Head of Requirements |
| Technical Standard | Chief Engineer |
| Asset | Asset Owner |
| Contract | Commercial Lead |
| Design Assurance Record | Head of Technical Assurance |

Prefer roles over named individuals.

## Decision Rules

### Rule 1: Capability Before System

The owner of Microsoft 365, SAP, Oracle or any other platform is not automatically the owner of information stored within the platform.

### Rule 2: One Authoritative Owner

Every information asset must have one accountable owner.

Many stakeholders may contribute, approve or consume.

Only one role is accountable.

### Rule 3: Ownership Exists Above Projects

Projects may create information.

Projects do not normally own information.

Ownership should persist beyond project closure.

### Rule 4: Accountability Follows Lifecycle Control

The accountable role must be able to:

- Define standards.
- Set quality rules.
- Mandate remediation.
- Approve disposal.

Without these responsibilities, accountability is ineffective.

### Rule 5: Stewardship May Be Delegated

Accountability and stewardship are different.

Example:

| Responsibility | Role |
|---------------|------|
| Accountable | Chief Engineer |
| Steward | Technical Assurance Team |
| Custodian | Technology Provider |

Only accountability remains with the accountable role.

## Example

| Consideration | Description |
| --------------|-------------|
| Business Object | Technical Standard |
| Capability | Technical Assurance |
| Business Decision | Is a design compliant with organisational standards? |
| Accountable Role | Chief Engineer |
| Steward | Technical Assurance Team |
| Custodian | Document Management Platform |
| Conclusion | The accountable owner is the Chief Engineer, not the owner of the document repository and not the project producing the design. |

## Architecture Implication

Information ownership models should be derived from:

Capability Model
→ Business Object Model
→ Information Asset Catalogue
→ Accountability Model

Ownership should never be derived from:

Application Landscape
→ Database
→ Data Owner

This produces unstable and technology-dependent governance arrangements.

## Success Test

A proposed owner is valid if the role can answer:

1. What does this information mean?
2. What quality is required?
3. Who may change it?
4. Who may consume it?
5. When should it be retained or disposed of?
6. What organisational decision depends upon it?

If the proposed owner cannot answer these questions, accountability has been assigned incorrectly.
