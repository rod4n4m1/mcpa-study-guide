# MCP Associate Study Guide

# Model Context Protocol Associate (MCPA) Source Catalog
**MCPA Certification Source Index & Domain Guide**  
*Standardized Catalog of 90 Notebook Sources Categorized by Official MCPA Certification Domains*

- **Catalog Authors:** Rod Anami & Gemini
- **Certification Target:** Linux Foundation MCPA Blueprint
- **Total Ingested Sources:** 90

---

## Domain 1: MCP Fundamentals (16% Exam Weight)

**Domain Scope & Focus:** Covers the core value proposition of standardizing AI context exchange, collapsing integration complexity from $O(N \times M)$ to $O(N + M)$, open vendor-neutral governance under the Agentic AI Foundation (AAIF) / Linux Foundation, and foundational protocol concepts.

| # | Source Title & Target Link | Type | MCPA Certification Relevance & Key Concepts Summary |
|---|---|:---:|---|
| 1 | [A Complete Guide to the Model Context Protocol \| Bolder Apps Blog](https://www.bolderapps.com/blog-posts/model-context-protocol) | `URL` | Detailed overview of MCP architecture, solving the $N \times M$ integration problem, and core protocol primitives. |
| 2 | [What is the Model Context Protocol (MCP)? - Model Context Protocol](https://modelcontextprotocol.io/docs/2026-07-28/getting-started/intro) | `URL` | Official introductory specification guide framing MCP as the universal 'USB-C port for AI applications'. |
| 3 | [Overview - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/basic) | `URL` | Official high-level specification overview of the data layer, transport layer, and core participant roles. |
| 4 | [What is Model Context Protocol (MCP)? - IBM](https://www.ibm.com/think/topics/model-context-protocol) | `URL` | Enterprise-oriented explanation of MCP's role in streamlining tool integration for autonomous multi-agent workflows. |
| 5 | [What is Model Context Protocol (MCP)? A guide \| Google Cloud](https://cloud.google.com/discover/what-is-model-context-protocol) | `URL` | Practical technical overview of MCP vs RAG, open-source ecosystem benefits, and Google Cloud integrations. |
| 6 | [What is the Model Context Protocol (MCP)? - Databricks](https://www.databricks.com/blog/what-is-model-context-protocol) | `URL` | Architectural breakdown of runtime-discoverable tools/data resources and enterprise integration strategies. |
| 7 | [Introduction to Model Context Protocol (MCP): Why It Matters for Scalable AI Applications - GitHub](https://github.com/microsoft/mcp-for-beginners/blob/main/00-Introduction/README.md) | `URL` | Microsoft curriculum module establishing the core necessity for standardized model-to-tool communication. |
| 8 | [Model Context Protocol (MCP) in 2026: Standard for AI Tool Use - Future AGI](https://futureagi.com/blog/model-context-protocol-mcp-2025/) | `URL` | Industry retrospective on why MCP won the AI tool-use standard across Anthropic, OpenAI, and Google. |
| 9 | [Model Context Protocol (MCP) explained: A practical technical overview for developers and architects - CodiLime](https://codilime.com/blog/model-context-protocol-explained/) | `URL` | Comprehensive architectural walkthrough of the client-server model, primitive flows, and networking case studies. |
| 10 | [Model Context Protocol Associate (MCPA) - Linux Foundation - Education](https://training.linuxfoundation.org/certification/model-context-protocol-associate-mcpa/) | `URL` | Official Linux Foundation exam blueprint, domain breakdown, and certification competencies for MCPA. |
| 11 | [asinghcsu/model-context-protocol-survey: Model Context Protocol (MCP) - GitHub](https://github.com/asinghcsu/model-context-protocol-survey) | `URL` | Academic survey paper categorizing MCP core concepts, comparative API analysis, and agentic composability. |

---

## Domain 2: Architecture & Components (14% Exam Weight)

**Domain Scope & Focus:** Examines the three-role architecture (MCP Host, Client, and Server), JSON-RPC 2.0 wire framing, string-based date versioning (`YYYY-MM-DD`), capability negotiation, and configuration standards like `mcp.json`.

| # | Source Title & Target Link | Type | MCPA Certification Relevance & Key Concepts Summary |
|---|---|:---:|---|
| 1 | [Architecture overview - Model Context Protocol](https://modelcontextprotocol.io/docs/2026-07-28/learn/architecture) | `URL` | Detailed specification of participants (Host, Client, Server), protocol layers, and discovery exchanges. |
| 2 | [Understanding MCP clients - Model Context Protocol](https://modelcontextprotocol.io/docs/2026-07-28/learn/client-concepts) | `URL` | Guide to client-side responsibilities, connection management, protocol adapters, and user interaction boundaries. |
| 3 | [Understanding MCP servers - Model Context Protocol](https://modelcontextprotocol.io/docs/2026-07-28/learn/server-concepts) | `URL` | Detailed breakdown of MCP server design, exposing capability manifests, and tool/resource/prompt boundaries. |
| 4 | [Lesson 3 of 55: JSON-RPC 2.0, MCP Lifecycle, and Capability Negotiation - SudoAll](https://sudoall.com/mcp-json-rpc-lifecycle/) | `URL` | Deep dive into the JSON-RPC wire protocol, initialization handshakes, and client-server capability exchanges. |
| 5 | [JSON-RPC 2.0 Specification](https://www.jsonrpc.org/specification) | `URL` | The foundational transport-agnostic remote procedure call specification utilized by MCP for all wire messaging. |
| 6 | [Specification - Model Context Protocol](https://modelcontextprotocol.io/specification/2025-11-25) | `URL` | The 2025-11-25 baseline specification defining schema requirements, transport rules, and core protocol boundaries. |
| 7 | [Key Changes - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/changelog) | `URL` | Comprehensive spec changelog detailing major protocol shifts between the 2025-11-25 and 2026-07-28 releases. |
| 8 | [Versioning - Model Context Protocol](https://modelcontextprotocol.io/docs/2026-07-28/learn/versioning) | `URL` | Specification rules for string-based date versioning (`YYYY-MM-DD`), feature deprecations, and negotiation probes. |
| 9 | [Proposal: Universal MCP Configuration File Standard #2218 - GitHub](https://github.com/modelcontextprotocol/modelcontextprotocol/discussions/2218) | `URL` | Community proposal standardizing `mcp.json` schemas across IDEs and host environments. |
| 10 | [MCP Server Complete Guide for Developers (2026) - Cosmic JS](https://www.cosmicjs.com/blog/mcp-server-complete-guide) | `URL` | Practical developer guide covering `mcp.json` configurations, transport setups, and hosting patterns. |
| 11 | [Technical Evaluation of the Model Context Protocol: Architectural Foundations for ReAct, Tool-Use, and Sequential Cognitive Emulation](./technical-evaluation-mcp.md) | `Markdown` | Deep technical evaluation analyzing MCP's architectural support for ReAct execution loops and cognitive emulation. |
| 12 | [Architectural Portability and Integration Flexibility in the Model Context Protocol (MCP) Ecosystem](./architectural-portability-mcp.md) | `Markdown` | In-depth study on integration flexibility, mathematical complexity scaling, and cross-framework portability. |

---

## Domain 3: Interactions & Execution (26% Exam Weight)

**Domain Scope & Focus:** Covers technical execution and protocol primitives: Tools (model-controlled), Resources (application-controlled), Prompts (user-controlled), Transports (stdio & Streamable HTTP), Multi Round-Trip Requests (MRTR), Elicitation, and Tasks.

| # | Source Title & Target Link | Type | MCPA Certification Relevance & Key Concepts Summary |
|---|---|:---:|---|
| 1 | [Tools - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/server/tools) | `URL` | Authoritative spec for model-controlled executable functions, JSON Schema validation, and result content types. |
| 2 | [Resources - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/server/resources) | `URL` | Authoritative spec for application-driven context data, URI templates, resource links, and embedded blobs. |
| 3 | [Prompts - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/server/prompts) | `URL` | Authoritative spec for user-selected reusable instruction templates, arguments, and embedded resources. |
| 4 | [MCP resources vs tools vs prompts: when to use each - Stacktree](https://stacktr.ee/blog/mcp-resources-vs-tools-vs-prompts) | `URL` | Clear decision matrix classifying primitives by invocation control: model, application, or user. |
| 5 | [MCP Prompts and Resources: The Primitives You're Not Using - DEV Community](https://dev.to/aws-heroes/mcp-prompts-and-resources-the-primitives-youre-not-using-3oo1) | `URL` | Engineering guide on structuring deterministic multi-step prompt workflows with embedded resource context. |
| 6 | [Transports - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/basic/transports) | `URL` | Overview of transport boundaries, message framing, and communication channels in MCP. |
| 7 | [Streamable HTTP - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/basic/transports/streamable-http) | `URL` | Technical spec for stateless HTTP POST communication, single-endpoint paths, and scoped SSE streaming. |
| 8 | [MCP Message Types: Complete MCP JSON-RPC Reference Guide - Portkey](https://portkey.ai/blog/mcp-message-types-complete-json-rpc-reference-guide/) | `URL` | Complete reference guide mapping JSON-RPC requests, responses, and error codes across all MCP primitives. |
| 9 | [Elicitation - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/client/elicitation) | `URL` | Specification for server-initiated user input requests via Form Mode and out-of-band URL Mode. |
| 10 | [SEP-1036: URL Mode Elicitation for secure out-of-band interactions - Model Context Protocol](https://modelcontextprotocol.io/seps/1036-url-mode-elicitation-for-secure-out-of-band-intera) | `URL` | Specification Enhancement Proposal defining secure out-of-band browser interactions for sensitive data. |
| 11 | [Sampling - Model Context Protocol](https://modelcontextprotocol.io/specification/2026-07-28/client/sampling) | `URL` | Specification for server-nested LLM sampling, prompt context inclusion, and human-in-the-loop review. |
| 12 | [mcp-for-beginners/03-GettingStarted/14-sampling/README.md at main - GitHub](https://github.com/microsoft/mcp-for-beginners/blob/main/03-GettingStarted/14-sampling/README.md) | `URL` | Practical tutorial on implementing client-side sampling requests and understanding deprecation timelines. |
| 13 | [Memgraph MCP Experimental Server: Elicitation and Sampling Explained](https://memgraph.com/blog/memgraph-mcp-elicitation-and-sampling) | `URL` | Case study demonstrating real-world usage of elicitation forms and sampling loops in graph database servers. |
| 14 | [Tasks - Model Context Protocol (2026-07-28 Extension)](https://modelcontextprotocol.io/extensions/tasks/overview) | `URL` | Official extension spec for long-running asynchronous operations, polling, and progress tracking. |
| 15 | [Tasks - Model Context Protocol (2025-11-25 Utility)](https://modelcontextprotocol.io/specification/2025-11-25/basic/utilities/tasks) | `URL` | Legacy utility spec for task handles, status tracking, and result retrieval in stateful sessions. |
| 16 | [The 2026-07-28 Specification \| Model Context Protocol Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28/) | `URL` | Release announcement covering the shift to stateless HTTP, MRTR patterns, and header-based routing. |
| 17 | [MCP 2026-07-28: What's Changing and How to Migrate - Agentic AI Foundation (AAIF)](https://aaif.io/blog/mcp-2026-07-28-whats-changing-and-how-to-migrate) | `URL` | Migration guide detailing stateless core upgrades, header standardization (SEP-2243), and legacy cleanup. |
| 18 | [MCP Deprecation Policy: A Template for Tool Lifecycle - Agentic AI Foundation (AAIF)](https://aaif.io/blog/mcp-just-handed-you-a-deprecation-policy-steal-it) | `URL` | Overview of SEP-2596 establishing feature lifecycles (Active, Deprecated, Removed) and 12-month windows. |

---

## Domain 4: Security & Governance (24% Exam Weight)

**Domain Scope & Focus:** Focuses on trust boundaries, permissions/consent, OAuth 2.1 (PRM & CIMD), threat modeling (STRIDE/DREAD), Tool Poisoning, Prompt Injection, Confused Deputy defenses, Zero-Trust Gateways, and auditability.

| # | Source Title & Target Link | Type | MCPA Certification Relevance & Key Concepts Summary |
|---|---|:---:|---|
| 1 | [Authorization - Model Context Protocol (2025-11-25)](https://modelcontextprotocol.io/specification/2025-11-25/basic/authorization) | `URL` | Legacy authorization spec defining OAuth 2.0 integration and scope management. |
| 2 | [Authorization - Model Context Protocol (Draft)](https://modelcontextprotocol.io/specification/draft/basic/authorization) | `URL` | Draft specification outlining hardened OAuth 2.1 authorization flows, PKCE, and audience binding. |
| 3 | [Client Registration - Model Context Protocol](https://modelcontextprotocol.io/specification/draft/basic/authorization/client-registration) | `URL` | Specification for OAuth Dynamic Client Registration and Client ID Metadata Documents (CIMD). |
| 4 | [The Anatomy of MCP Authorization: How the Hardened Flow Actually Runs - AAIF](https://aaif.io/blog/the-anatomy-of-mcp-authorization-how-the-hardened-flow-actually-runs) | `URL` | Step-by-step walkthrough of the cold-start authorization flow (401/WWW-Authenticate), CIMD, and token binding. |
| 5 | [OAuth 2.1](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-v2-1-12) | `URL` | The core OAuth 2.1 authorization framework mandating PKCE, exact redirect URIs, and secure token handling. |
| 6 | [SEP-1024: MCP Client Security Requirements for Local Server Installation - MCP](https://modelcontextprotocol.io/seps/1024-mcp-client-security-requirements-for-local-server-) | `URL` | Security requirements enforcing explicit user consent and command transparency during local server installs. |
| 7 | [Security Best Practices - Model Context Protocol](https://modelcontextprotocol.io/specification/draft/basic/security_best_practices) | `URL` | Official guidelines for mitigating Confused Deputy, SSRF, state handle hijacking, and scope over-privileging. |
| 8 | [modelcontextprotocol/SECURITY.md at main - GitHub](https://github.com/modelcontextprotocol/modelcontextprotocol/blob/main/SECURITY.md) | `URL` | Official security policy, vulnerability reporting guidelines, and stdio transport trust boundaries. |
| 9 | [Verifiable Evidence at the MCP Boundary - Agentic AI Foundation (AAIF)](https://aaif.io/blog/verifiable-evidence-at-the-mcp-boundary) | `URL` | Technical article on Confidential MCP (cMCP), cryptographic audit trails, and zero-trust verification. |
| 10 | [Model Context Protocol (MCP): Security Design Considerations - Department of War](https://media.defense.gov/2026/Jun/02/2003943289/-1/-1/0/CSI_MCP_SECURITY.PDF) | `PDF` | Government security report on threat vectors, serialization risks, and defense-in-depth recommendations. |
| 11 | [Model Context Protocol Threat Modeling and Analysis of Vulnerabilities to Prompt Injection - MDPI](https://www.mdpi.com/2624-800X/6/3/84) | `URL` | Academic research applying STRIDE/DREAD threat modeling across 6 MCP components and testing 7 clients. |
| 12 | [Model Context Protocol Threat Modeling and Analyzing Vulnerabilities to Prompt Injection - arXiv](https://arxiv.org/html/2603.22489v1) | `URL` | Empirical study on client-side prompt injection, tool poisoning attack flows, and static validation defenses. |
| 13 | [Systematic Analysis of MCP Security - arXiv](https://arxiv.org/html/2508.12538v1) | `URL` | Paper introducing MCPLib and analyzing 31 distinct MCP attack types including file manipulation and RCE. |
| 14 | [MCP Security Notification: Tool Poisoning Attacks - Invariant Labs](https://invariantlabs.ai/blog/mcp-security-notification-tool-poisoning-attacks) | `URL` | Security advisory detailing Tool Shadowing, Rug Pulls, and prompt injection hidden in tool comments. |
| 15 | [Understanding MCP Tool Poisoning Attacks - Descope](https://www.descope.com/learn/post/mcp-tool-poisoning) | `URL` | Educational guide explaining how poisoned tool metadata influences LLM reasoning and exfiltrates data. |
| 16 | [Model Context Protocol (MCP) - Black Hills Information Security, Inc.](https://www.blackhillsinfosec.com/model-context-protocol/) | `URL` | Penetration testing perspective on MCP attack surfaces, proxy boundaries, and credential risks. |
| 17 | [mcpserver-audit: Helps you check if MCP servers are safe before using them... - GitHub](https://github.com/ModelContextProtocol-Security/mcpserver-audit) | `URL` | Open-source security auditing tool providing AIVSS scoring and static analysis for MCP server code. |

---

## Domain 5: Use Cases & Ecosystem (20% Exam Weight)

**Domain Scope & Focus:** Covers practical adoption across roles (SRE, Platform Engineering, AI Engineers), Code Mode execution, Dynamic ReAct / Active Tool Discovery, official language SDKs, framework adapters, and server registries.

| # | Source Title & Target Link | Type | MCPA Certification Relevance & Key Concepts Summary |
|---|---|:---:|---|
| 1 | [The official TypeScript SDK for Model Context Protocol servers and clients - GitHub](https://github.com/modelcontextprotocol/typescript-sdk) | `URL` | Official TypeScript monorepo providing `@modelcontextprotocol/server` and `@modelcontextprotocol/client` packages. |
| 2 | [The official Python SDK for Model Context Protocol servers and clients - GitHub](https://github.com/modelcontextprotocol/python-sdk) | `URL` | Official Python SDK implementing FastMCP, high-level server/client abstractions, and async transports. |
| 3 | [Announcing v2.0 of the official MCP C# SDK - .NET Blog](https://devblogs.microsoft.com/dotnet/announcing-v20-of-the-official-mcp-csharp-sdk/) | `URL` | Announcement of the official .NET MCP SDK v2.0 with native MRTR support and stateless HTTP bindings. |
| 4 | [GitHub - modelcontextprotocol/rust-sdk: The official Rust SDK for Model Context Protocol](https://github.com/modelcontextprotocol/rust-sdk) | `URL` | Official Rust SDK (`rmcp`) providing high-performance server/client handlers and macro-based routing. |
| 5 | [Go SDK: Design · modelcontextprotocol · Discussion #364 - GitHub](https://github.com/orgs/modelcontextprotocol/discussions/364) | `URL` | Official design discussion and implementation roadmap for the Go MCP SDK in collaboration with Google. |
| 6 | [GitHub - microsoft/mcp-for-beginners: Curriculum for Model Context Protocol](https://github.com/microsoft/mcp-for-beginners/) | `URL` | Comprehensive multi-language open-source curriculum covering MCP fundamentals to production deployment. |
| 7 | [model-context-protocol-resources/guides/mcp-server-development-guide.md at main](https://github.com/cyanheads/model-context-protocol-resources/blob/main/guides/mcp-server-development-guide.md) | `URL` | Extensive developer guide covering SDK choice, modular capabilities, and path traversal security. |
| 8 | [langchain_mcp_adapters - LangChain Reference](https://reference.langchain.com/python/langchain-mcp-adapters) | `URL` | Official LangChain adapter documentation for converting MCP tools and prompts into LangChain objects. |
| 9 | [Tutorial - Building an AI Agent Using LangChain with Couchbase MCP Server](https://developer.couchbase.com/tutorial-ai-agent-using-langchain-and-couchbase-mcp-server/) | `URL` | Hands-on tutorial building a ReAct agent using LangChain, LangGraph, and a Couchbase MCP database server. |
| 10 | [Model Context Protocol (MCP) \| Developer Documentation - LlamaParse](https://developers.llamaindex.ai/python/framework/module_guides/mcp/) | `URL` | LlamaIndex integration guide for serving LlamaIndex workflows as MCP servers or consuming external MCP tools. |
| 11 | [Model Context Protocol (MCP) :: Spring AI Reference](https://docs.spring.io/spring-ai/reference/api/mcp/mcp-overview.html) | `URL` | Spring AI reference manual for configuring Java-native MCP client and server Spring Boot starters. |
| 12 | [Model context protocol (MCP) - OpenAI Agents SDK - GitHub Pages](https://openai.github.io/openai-agents-python/mcp/) | `URL` | OpenAI Agents SDK documentation for integrating hosted, Streamable HTTP, and stdio MCP tools. |
| 13 | [Code Mode MCP server patterns · Cloudflare Agents docs](https://developers.cloudflare.com/agents/model-context-protocol/codemode/) | `URL` | Cloudflare documentation detailing Single Code Tool and Search and Execute patterns for Code Mode. |
| 14 | [Code Mode · Cloudflare Agents docs](https://developers.cloudflare.com/agents/tools/codemode/) | `URL` | Technical guide on creating durable Code Mode runtimes inside isolated V8 Worker containers. |
| 15 | [Code Mode: give agents an entire API in 1000 tokens - Cloudflare Blog](https://blog.cloudflare.com/code-mode-mcp/) | `URL` | Architectural blog post explaining how Code Mode exposes massive APIs in under 1,000 prompt tokens. |
| 16 | [Code execution with MCP: building more efficient AI agents - Anthropic](https://www.anthropic.com/engineering/code-execution-with-mcp) | `URL` | Anthropic engineering paper detailing token reduction (98%+) by presenting MCP tools as code APIs. |
| 17 | [Code execution with MCP: Building more efficient agents - Simon Willison's Weblog](https://simonwillison.net/2025/Nov/4/code-execution-with-mcp/) | `URL` | Technical analysis of Anthropic's code execution proposal for context-efficient tool chaining. |
| 18 | [Code Execution with MCP: A New Approach to AI Agent Efficiency - AIMultiple](https://aimultiple.com/code-execution-with-mcp) | `URL` | Empirical benchmark comparing regular MCP tool loops vs. Code Execution MCP across large tool catalogs. |
| 19 | [Dynamic ReAct: Scalable Tool Selection for Large-Scale MCP Environments - arXiv](https://arxiv.org/html/2509.20386v1) | `URL` | Research paper proposing Search and Load meta-tool architectures for dynamic tool binding in ReAct loops. |
| 20 | [SING: Synthetic Intention Graph for Scalable Active Tool Discovery - arXiv](https://arxiv.org/html/2606.16591v1) | `URL` | Research paper introducing intention-tool graphs for active tool discovery across 700+ MCP servers. |
| 21 | [What is a ReAct Agent? \| IBM](https://www.ibm.com/think/topics/react-agent) | `URL` | Conceptual guide on the Reasoning and Acting (ReAct) paradigm for LLM-driven decision loops. |
| 22 | [Comparing MCP vs LangChain/ReAct for Chatbots - Glama](https://glama.ai/blog/2025-09-02-comparing-mcp-vs-lang-chainre-act-for-chatbots) | `URL` | Comparative analysis contrasting rigid framework integrations with MCP's plug-and-play architecture. |
| 23 | [A framework for integrating AI into platform engineering](https://platformengineering.org/blog/platforms-are-sitting-on-buried-knowledge-for-agents) | `URL` | Article on embedding organizational knowledge and security standards into developer Golden Paths. |
| 24 | [Why MCP is critical for AI-driven SRE \| Thoughtworks Brazil](https://thoughtworks.com/mcp-sre-incident-response) | `URL` | Analysis of MCP's operational value in Site Reliability Engineering for context-aware incident response. |
| 25 | [Architectural Standardisation of Enterprise AI: Operational Use Cases, Technical Evolution, and Value Realization of the Model Context Protocol (MCP)](./architectural-standardisation-mcp.md) | `Markdown` | Enterprise whitepaper detailing MTTR reductions, ROI calculations, and zero-trust gateway deployments. |
| 26 | [Supercharge Your IDE: Custom .NET MCP Servers for Amazon Q Developer - AWS](https://aws.amazon.com/blogs/dotnet/supercharge-your-ide-custom-net-mcp-servers-for-amazon-q-developer/) | `URL` | AWS tutorial building custom C# MCP database servers to extend IDE AI coding assistants. |
| 27 | [MCP Server Architecture Patterns for LLM-Integrated Applications - arXiv](https://arxiv.org/html/2606.30317v1) | `URL` | Empirical study documenting 5 server patterns (Resource Gateway, Tool Orchestrator, etc.) and anti-patterns. |
| 28 | [A community driven registry service for Model Context Protocol (MCP) servers. - GitHub](https://github.com/modelcontextprotocol/registry) | `URL` | Official repository for the centralized MCP Server Registry, discovery APIs, and publication workflows. |
| 29 | [modelcontextprotocol/servers: Model Context Protocol Servers - GitHub](https://github.com/modelcontextprotocol/servers) | `URL` | Official repository housing reference MCP server implementations (Filesystem, Git, Postgres, Memory, etc.). |
| 30 | [MCP Apps - Model Context Protocol](https://modelcontextprotocol.io/extensions/apps/overview) | `URL` | Official overview of the MCP Apps extension, rendering inline interactive UI elements in conversational hosts. |
| 31 | [Extensions - Model Context Protocol](https://modelcontextprotocol.info/docs/extensions/) | `URL` | Documentation on the MCP extension framework, capability flags, and official extension repositories. |
| 32 | [Model Context Protocol - GitHub](https://github.com/modelcontextprotocol) | `URL` | Official GitHub organization housing core specifications, SDKs, reference servers, and governance docs. |

