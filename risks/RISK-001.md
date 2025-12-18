---
id: "RISK-001"
title: "Browser Compatibility"
category: "technical"
probability: "high"
impact: "medium"
status: "mitigating"
owner: "Product Manager"
revision: "01"
dateCreated: 1766070033735
lastModified: 1766070057451
linkedArtifacts: []
isDeleted: false
customAttributes: []
---

# Browser Compatibility

## Description
Risk of the File System Access API not being supported in all browsers.

## Mitigation Strategy
Implement a fallback to virtual filesystem (indexedDB) or cloud sync.

## Contingency Plan
Allow users to manually export data as JSON if the filesystem is unavailable.