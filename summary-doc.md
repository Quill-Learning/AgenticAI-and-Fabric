---
title: 'Agentic AI & Microsoft Fabric Labs'
author: 'Luke Duffy'
date: '16 Dec 2025'
---

# Lab 1: Microsoft Fabric Data Engineering

## Lab 1 Overview

- Focus: Data engineering in Fabric
- Create workspace and Lakehouse
- Ingest, validate, and transform data
- Automate ingestion and apply governance

**Resources:**
- [Microsoft Fabric Overview](https://learn.microsoft.com/en-us/fabric/fundamentals/microsoft-fabric-overview)
- [Create and manage workspaces](https://learn.microsoft.com/en-us/fabric/admin/workspaces)

::: notes
Introduce Lab 1 objectives and why Fabric is central for modern data workflows.
:::

## Task 1: Create a Fabric Workspace

- Navigate to Microsoft Fabric portal
- Create a new workspace
- Configure workspace settings

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Explain why a dedicated workspace is essential for organizing resources.
:::

## Task 2: Create a Lakehouse

- Select Lakehouse option
- Name and configure storage
- Validate creation

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Discuss how Lakehouse enables unified data storage for analytics.
:::

## Task 3: Ingest Data via a Standard Pipeline

- Create a pipeline
- Connect to data source
- Run ingestion job

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Highlight best practices for reliable data ingestion.
:::

## Task 4: Validate the Ingested Data

- Open Lakehouse tables
- Check schema and row counts
- Verify data quality

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Stress importance of validation before transformation.
:::

## Task 5: Transform Data with a Fabric Notebook

- Launch Fabric notebook
- Write transformation code
- Execute and save results

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Explain why notebooks are powerful for iterative data prep.
:::

## Task 5.4 (Optional): Use Copilot to Generate More Advanced Calculations

- Enable Copilot in Fabric
- Request advanced transformations
- Review generated code

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Show how Copilot accelerates complex calculations.
:::

## Task 6: Automate Ingestion with Fabric Copilot

- Open Copilot automation panel
- Define ingestion schedule
- Activate automation

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Discuss benefits of automation for operational efficiency.
:::

## Task 7: Apply Basic Security and Governance Patterns

- Set permissions
- Enable data policies
- Audit access logs

**Resources:**
- [Microsoft Fabric documentation](https://learn.microsoft.com/en-us/fabric/)
- [Fabric Lakehouse guide](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-overview)

::: notes
Explain governance as a foundation for compliance and trust.
:::

## Lab 1 Key Takeaways

- Fabric simplifies data engineering
- Lakehouse unifies storage and analytics
- Automation and governance ensure scalability

**Resources:**
- [Fabric governance best practices](https://learn.microsoft.com/en-us/fabric/admin/security-governance)

::: notes
Summarize Lab 1 outcomes and readiness for Lab 2.
:::

# Lab 2: Agentic AI Integration with Fabric

## Lab 2 Overview

- Focus: Multi-agent orchestration
- Connect Fabric with Azure AI Foundry
- Implement MCP proxy and tools
- Enhance with chat and optional data agent

**Resources:**
- [Azure AI Foundry overview](https://learn.microsoft.com/en-us/azure/ai-foundry/)
- [Agent Framework documentation](https://learn.microsoft.com/en-us/agent-framework/)

::: notes
Introduce Lab 2 objectives and integration patterns for agentic AI.
:::

## Task 1: Confirm the Fabric Dataset and Publish a Query Endpoint

- Open dataset in Fabric
- Validate schema
- Publish endpoint for queries

**Resources:**
- [Agent2Agent protocol](https://www.microsoft.com/en-us/microsoft-cloud/blog/2025/05/07/empowering-multi-agent-apps-with-the-open-agent2agent-a2a-protocol/)
- [Connect agents via A2A](https://learn.microsoft.com/en-us/microsoft-copilot-studio/add-agent-agent-to-agent)

::: notes
Ensure dataset readiness for external consumption.
:::

## Task 2: (Instructor-Led) Create a Microsoft Foundry Agent Connected to Fabric

- Access Azure AI Foundry
- Create agent
- Connect agent to Fabric workspace

**Resources:**
- [Agent2Agent protocol](https://www.microsoft.com/en-us/microsoft-cloud/blog/2025/05/07/empowering-multi-agent-apps-with-the-open-agent2agent-a2a-protocol/)
- [Connect agents via A2A](https://learn.microsoft.com/en-us/microsoft-copilot-studio/add-agent-agent-to-agent)

::: notes
Explain integration between Foundry agents and Fabric.
:::

## Task 3: Implement a Minimal MCP-Style Proxy Service

- Develop proxy service
- Expose MCP-compatible API
- Test connectivity

**Resources:**
- [Agent2Agent protocol](https://www.microsoft.com/en-us/microsoft-cloud/blog/2025/05/07/empowering-multi-agent-apps-with-the-open-agent2agent-a2a-protocol/)
- [Connect agents via A2A](https://learn.microsoft.com/en-us/microsoft-copilot-studio/add-agent-agent-to-agent)

::: notes
Discuss why MCP proxy enables interoperability.
:::

## Task 4: Register the Proxy as an MCP Tool in Foundry and Test End-to-End

- Add proxy as tool in Foundry
- Configure agent to use tool
- Run end-to-end test

**Resources:**
- [Agent2Agent protocol](https://www.microsoft.com/en-us/microsoft-cloud/blog/2025/05/07/empowering-multi-agent-apps-with-the-open-agent2agent-a2a-protocol/)
- [Connect agents via A2A](https://learn.microsoft.com/en-us/microsoft-copilot-studio/add-agent-agent-to-agent)

::: notes
Highlight importance of tool registration for orchestration.
:::

## Task 5: (Optional) Add a Simple Web Chat Experience

- Create web UI
- Integrate with Foundry agent
- Test chat interactions

**Resources:**
- [Agent2Agent protocol](https://www.microsoft.com/en-us/microsoft-cloud/blog/2025/05/07/empowering-multi-agent-apps-with-the-open-agent2agent-a2a-protocol/)
- [Connect agents via A2A](https://learn.microsoft.com/en-us/microsoft-copilot-studio/add-agent-agent-to-agent)

::: notes
Show how chat enhances usability for end-users.
:::

## Optional Exercise: Try Fabric Data Agent

- Enable Fabric Data Agent
- Configure agent settings
- Run sample queries

**Resources:**
- [Agent2Agent protocol](https://www.microsoft.com/en-us/microsoft-cloud/blog/2025/05/07/empowering-multi-agent-apps-with-the-open-agent2agent-a2a-protocol/)
- [Connect agents via A2A](https://learn.microsoft.com/en-us/microsoft-copilot-studio/add-agent-agent-to-agent)

::: notes
Demonstrate advanced capabilities for data-driven workflows.
:::

## Lab 2 Key Takeaways

- Multi-agent systems enable advanced orchestration
- MCP proxy ensures interoperability
- Foundry agents integrate seamlessly with Fabric

**Resources:**
- [AI Agent Orchestration Patterns](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/ai-agent-design-patterns)

::: notes
Summarize Lab 2 outcomes and enterprise readiness.
:::
