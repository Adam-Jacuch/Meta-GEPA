# Meta-GEPA
Official repository for "Meta-GEPA: Trace-Grounded Bi-Level Co-Evolution of System and Diagnostic Prompts" (IEEE SSCI).

## Status: Coming Soon

The implementation code, prompt templates, and synthetic linguistic ambiguity benchmark generation scripts are currently being prepared for release and **will be made publicly available upon final publication/proceedings inclusion**.

## Overview

**Meta-GEPA** is a bi-level evolutionary prompt optimization framework that jointly evolves task-level system prompts alongside the meta-level diagnostic instructions used to critique and improve them. 

* **Inner Loop:** Performs trace-grounded reflective mutation over execution traces, maintaining behavioral diversity through strict minibatch admission and instance-level Pareto survival.
* **Outer Loop:** Assigns credit to diagnostic meta-prompts based on downstream full-suite score gains, analyzes both productive and failed mutation lineages, and periodically synthesizes new diagnostic strategies targeted at emerging error distributions.

## Authors

* **Adam Jacuch** (Stony Brook University)
* **Alex Doboli** (Cornell University / Stony Brook University)
* **Matthew Fernando** (Stony Brook University)
* **Gnaneswar Villuri** (Stony Brook University)
