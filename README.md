# CyberDNA

**AI-powered behavioural identity and cyber threat detection**

CyberDNA is a cybersecurity project that aims to build a behavioural
profile for users and detect suspicious activity by analysing patterns
and relationships between users, devices, and system interactions.

## Overview

Traditional security systems often rely on fixed rules or isolated
anomaly signals. CyberDNA explores a graph-based approach: it models
entities and their interactions, learns patterns of normal behaviour,
and flags significant deviations for further investigation.

## Key Features

-   **Behavioural profiling:** Build evolving digital behaviour profiles
    from activity data.
-   **Graph-based modelling:** Represent users, devices, applications,
    and activities as connected entities.
-   **Anomaly detection:** Identify deviations from learned behavioural
    patterns.
-   **Threat identification:** Help surface suspicious access, possible
    account compromise, and potential insider threats.
-   **Explainable investigation:** Present detected anomalies and the
    activity patterns that contributed to an alert.

## Proposed Technical Approach

1.  Collect and preprocess suitable cybersecurity activity data.
2.  Represent entities and interactions as a graph.
3.  Generate behavioural representations using Graph Neural Networks
    (GNNs).
4.  Learn baseline behaviour and detect unusual patterns.
5.  Present alerts and relevant evidence through an investigation
    interface.

## Proposed Technology Stack

-   **Language:** Python
-   **Deep learning:** PyTorch
-   **Graph learning:** PyTorch Geometric
-   **Models to explore:** GraphSAGE, Graph Attention Networks (GAT),
    and temporal graph learning
-   **Potential dataset:** CERT Insider Threat Dataset, subject to
    availability and suitability

> The architecture and tools above describe the proposed direction.
> Update this section to reflect the components actually implemented in
> the repository.

## Getting Started

The project setup instructions will be added once the implementation and
dependency list are finalized.

A typical setup may look like:

``` bash
git clone <repository-url>
cd CyberDNA
python -m venv .venv
```

Activate the virtual environment:

**Windows**

``` bash
.venv\Scripts\activate
```

**macOS / Linux**

``` bash
source .venv/bin/activate
```

Install dependencies after creating the project's `requirements.txt`:

``` bash
pip install -r requirements.txt
```

## Project Status

**Status:** In development / proposed architecture.

Implementation details, dataset preparation, model evaluation, and usage
instructions should be documented here as the project progresses.

## Responsible Use

CyberDNA is intended for defensive cybersecurity research and threat
detection. Use activity data only when you have appropriate
authorization, protect sensitive information, and validate alerts before
taking action.

## Future Scope

-   Temporal behavioural modelling
-   Improved anomaly explanations
-   Real-time event ingestion and alerting
-   Analyst dashboard and investigation workflows
-   Evaluation on suitable benchmark datasets

## Contributing

Contributions are welcome. Open an issue to discuss a proposed change
before submitting a pull request.

## License

No license has been specified yet. Add a license before distributing or
accepting external contributions.
