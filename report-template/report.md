<div align="center">

![Bellum Galaxy](./logo.png)

</div>

</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>

# Table of Contents

- [Table of Contents](#table-of-contents)
- [Protocol Summary](#protocol-summary)
- [Disclaimer](#disclaimer)
- [Risk Classification](#risk-classification)
- [Audit Details](#audit-details)
  - [Scope](#scope)
  - [Roles](#roles)
  - [Issues found](#issues-found)
  - [Methodology](#methodology)
  - [Audit Findings](#audit-findings)
    - [Critical Vulnerabilities](#critical-vulnerabilities)
    - [High Severity Vulnerabilities](#high-severity-vulnerabilities)
    - [Medium Severity Vulnerabilities](#medium-severity-vulnerabilities)
    - [Minor Observations](#minor-observations)
  - [Conclusion](#conclusion)
  - [Appendices](#appendices)

# Protocol Summary

# Disclaimer
The Bellum Galaxy team makes all effort to find as many vulnerabilities in the code in the given time period, but holds no responsibilities for the findings provided in this document. A security audit by the team is not an endorsement of the underlying business or product. The audit was time-boxed and the review of the code was solely on the security aspects of the Solidity implementation of the contracts.

# Risk Classification

|            |        | Impact |        |     |
| ---------- | ------ | ------ | ------ | --- |
|            |        | High   | Medium | Low |
|            | High   | H      | H/M    | M   |
| Likelihood | Medium | H/M    | M      | M/L |
|            | Low    | M      | M/L    | L   |

We use the [CodeHawks](https://docs.codehawks.com/hawks-auditors/how-to-evaluate-a-finding-severity) severity matrix to determine severity. See the documentation for more details.

# Audit Details

- **Project Name:**

- **Smart Contract Address:**

- **Audit Date:**

- **Audit Tools Used:**

- **Auditors:**
  - Barba

## Scope
- `PoolFactory.sol`
- `TSwapPool.sol`

## Roles

## Issues found

| Severtity | Number of issues found |
| --------- | ---------------------- |
| High      | 4                      |
| Medium    | 2                      |
| Low       | 2                      |
| Info      | 9                      |
| Total     | 17                     |

## Methodology

The strategy was to break protocol invariants using Stateless and Stateful testing, apply Slither, and Aderyn, and then dive into the code review.

## Audit Findings

### Critical Vulnerabilities

- **Vulnerability 1**
  - **Description:**
  - **Impact:**
  - **Proof of Concept:**
  - **Recommendation:**
  - **Status:**

### High Severity Vulnerabilities

- **Vulnerability 2**
  - **Description:**
  - **Recommendation:**
  - **Status:**

### Medium Severity Vulnerabilities

- **Vulnerability 3**
  - **Description:**
  - **Recommendation:**
  - **Status:**

### Minor Observations

- **Observation 1**
  - **Description:**
  - **Recommendation:**
  - **Status:**

## Conclusion

A general summary of the findings and an overall assessment of the smart contract's security.

## Appendices

Any code, images, or other attachments that are relevant to the report.

---
