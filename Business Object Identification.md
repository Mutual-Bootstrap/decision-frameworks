# Business Object Identification

## Purpose

To identify business objects consistently from capabilities, operating models and organisational descriptions.

The objective is to create a stable business object catalogue that can support:

- Information architecture
- Data governance
- Digital Spine design
- Application architecture
- Integration architecture

## Principle

A business object is a durable thing of business significance about which the organisation needs to know something.

A business object:

- Has meaning independent of a system.
- Exists independently of a process.
- Has a lifecycle.
- Can be created, updated and retired.
- Is referenced by multiple stakeholders.
- Supports one or more business decisions.

## Identification Process

### Step 1: Identify the Capability

Example:

```text
Requirements Management
Technical Assurance
Design Management
Supply Chain Management
```

### Step 2: Ask Four Questions

For the capability:

1. What does it create?
2. What does it change?
3. What does it approve?
4. What does it govern?

Candidate business objects will typically emerge from the answers.

### Example

Capability:

```text
Technical Assurance
```

Questions:

```text
What does it create?
    Assessment
    Assurance Decision

What does it change?
    Compliance Status

What does it approve?
    Design Submission

What does it govern?
    Technical Standard
```

Candidate business objects:

```text
Assessment
Assurance Decision
Design Submission
Technical Standard
```

## Validation Tests

A candidate object should satisfy most of the following criteria.

### Test 1: Durability

Does it exist for longer than a single activity?

✅ Requirement

✅ Design Submission

❌ Design Review Meeting

### Test 2: Business Significance

Would the organisation care if it disappeared?

✅ Contract

✅ Asset

✅ Requirement

❌ Dashboard

❌ Workflow

### Test 3: Independent Identity

Can it be uniquely identified?

✅ Project

✅ Supplier

✅ Risk

❌ Governance

❌ Assurance

### Test 4: Lifecycle

Can it be created, modified and retired?

✅ Requirement

✅ Standard

✅ Derogation

❌ Technical Assurance

❌ Procurement

### Test 5: Decision Relevance

Is it used to support a business decision?

✅ Risk

✅ Design

✅ Cost Forecast

❌ Folder Structure

❌ SharePoint Site

## Common Misclassifications

| Often Mistaken For Object | Actual Type |
|--------------------------|-------------|
| Technical Assurance | Capability |
| Design Review | Process |
| Governance | Capability |
| Procurement | Capability |
| Risk Management | Capability |
| Compliance Assessment | Business Object |
| Requirement | Business Object |
| Supplier | Business Object |
| Technical Standard | Business Object |

## Output

The result should be a catalogue containing:

- Business Object
- Description
- Capability Source
- Lifecycle Owner
- Decision Supported

The catalogue becomes the foundation for subsequent information architecture work.
