# Overview

An example helmfile to show off an issue.

# Steps to reproduce
1. This works: `helmfile apply`
2. This does not work: `helmfile --state-values-set foo=3 apply`
