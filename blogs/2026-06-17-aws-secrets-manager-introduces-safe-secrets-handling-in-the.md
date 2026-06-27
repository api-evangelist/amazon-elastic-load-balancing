---
title: "AWS Secrets Manager introduces safe secrets handling in the Agent Toolkit for AWS"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/safe-secrets-handling-in-agent-toolkit-for-aws/"
date: "2026-06-17"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Secrets Manager now offers a secret safety skill in the aws-core plugin of the Agent Toolkit for AWS, letting AI coding agents use secrets without exposing values to the model or session logs. It steers the agent to construct commands that use the secret rather than retrieve it, while a child process resolves secret references to actual values only at execution time. Available for harnesses including Claude Code, Codex, and Cursor in all Regions where Secrets Manager runs.
