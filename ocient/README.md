# Agent Check: Ocient

## Overview

This check monitors [Ocient][1].

Include a high level overview of what this integration does:
- What does your product do (in 1-2 sentences)?
- What value will customers get from this integration, and why is it valuable to them?
- What specific data will your integration monitor, and what's the value of that data?

## Setup

### Installation

To install the Ocient check on your host:


1. Install the [developer toolkit]
(https://docs.datadoghq.com/developers/integrations/python/)
 on any machine.

2. Run `ddev release build ocient` to build the package.

3. [Download the Datadog Agent][2].

4. Upload the build artifact to any host with an Agent and
 run `datadog-agent integration install -w
 path/to/ocient/dist/<ARTIFACT_NAME>.whl`.

### Configuration

!!! Add list of steps to set up this integration !!!

### Validation

!!! Add steps to validate integration is functioning as expected !!!

## Data Collected

### Metrics

Ocient does not include any metrics.

### Service Checks

Ocient does not include any service checks.

### Events

Ocient does not include any events.

## Troubleshooting

Need help? Contact [Datadog support][3].

[1]: **LINK_TO_INTEGRATION_SITE**
[2]: https://app.datadoghq.com/account/settings/agent/latest
[3]: https://docs.datadoghq.com/agent/kubernetes/integrations/
[4]: https://github.com/DataDog/integrations-extras/blob/master/ocient/datadog_checks/ocient/data/conf.yaml.example
[5]: https://docs.datadoghq.com/agent/guide/agent-commands/#start-stop-and-restart-the-agent
[6]: https://docs.datadoghq.com/agent/guide/agent-commands/#agent-status-and-information
[7]: https://github.com/DataDog/integrations-extras/blob/master/ocient/metadata.csv
[8]: https://github.com/DataDog/integrations-extras/blob/master/ocient/assets/service_checks.json
[9]: https://docs.datadoghq.com/help/

