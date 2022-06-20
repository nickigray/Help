---
title: "SSH | General information"
description: "General information about the MRC WIMM CCB high-performance computing (HPC) cluster."
lead: "General information about the MRC WIMM CCB high-performance computing (HPC) cluster."
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "ssh"
weight: 300
toc: true
---

## Login nodes

The CCB cluster has three login nodes that users can log into:

- `cbrglogin1.molbiol.ox.ac.uk`
- `cbrglogin2.molbiol.ox.ac.uk`
- `cbrglogin3.molbiol.ox.ac.uk`

## Compute nodes

The CCB cluster includes a number of compute nodes where the majority of
computations are run.

Compute nodes cannot be logged into directly.
Users are expected to interact with compute nodes through the
[Slurm workload manager]({{< relref "/docs/slurm/general-information" >}}).

{{< alert icon="👉" text="Users may log into compute nodes from any login node for debugging purposes." />}}

<!-- Link definitions -->