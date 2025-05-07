<!--
# SPDX-FileCopyrightText: Copyright 2024 SAP SE or an SAP affiliate company and cobaltcore-dev contributors
#
# SPDX-License-Identifier: Apache-2.0
-->

# KVM-Operations

This Helm chart packages resources and configuration for KVM operations.

# Content

The content is structured as follows:

```
 kvm-operations
    │
    ├── alerts                      Prometheus alerts for KVM.
    │
    ├── playbooks                   Playbooks outlining resoluting steps for an individual alert.
    │
    ├── dashboards                  Perses dashboards visulizing relevant metrics.
    │
    ├── Chart.yaml                  Helm chart manifest. Increase the version number when making changes.
    │
    └── plugindefinition.yaml       Links the Helm chart to the Greenhouse platform. Increase the version number when making changes.
```

# Contributing

When contributing to the `kvm-operations` chart, update the respective content and increment the version in the [Chart.yaml](https://github.com/cobaltcore-dev/cloud-compute-operations/blob/main/charts/kvm-operations/Chart.yaml).
If you're using [Greenhouse](https://github.com/cloudoperators/greenhouse), update the version in the [plugindefinition.yaml](https://github.com/cobaltcore-dev/cloud-compute-operations/blob/main/charts/kvm-operations/plugindefinition.yaml) as well and let the operations platform handle the rollout.
