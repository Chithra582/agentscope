---
name: model-router-middleware
description: Routes inference requests dynamically based on cost and latency.
---

# Model Router Middleware

## Overview
Provides intelligent routing between frontier reasoning models and cost-effective lightweight models based on user tier, prompt complexity, and live provider uptime metrics.

## Key Capabilities
- Latency and token quota monitoring per provider.
- Automatic fallback on 429 rate limit or 5xx server errors.
- Cost budget enforcement per session or workspace.
