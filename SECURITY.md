# Security Policy

OpenTelemetry Industrial is a community initiative. The receivers and collector distributions in this organization are **experimental** and not yet intended for production use in safety-critical environments.

## Reporting a vulnerability

Please **do not** report security vulnerabilities through public GitHub issues, pull requests, discussions or Slack.

Instead, report them privately through GitHub:

1. Go to the **Security and quality** tab of the affected repository
2. Click **Report a vulnerability**
3. Describe the issue, the affected component and version, and steps to reproduce if possible

We'll acknowledge reports within 7 days and keep you updated on the fix. Once a fix is available, we'll publish a GitHub Security Advisory and credit you, unless you prefer to stay anonymous.

## Supported versions

All components are pre-1.0 and experimental. Only the latest release of each component receives security fixes; please upgrade before reporting.

## Scope

In scope: code in this organization, such as the receivers, collector manifests, CI workflows and simulators.

Out of scope: third-party components referenced by our manifests, for example the OPC UA and MQTT Sparkplug receivers or upstream OpenTelemetry Collector modules. Please report those to their own projects.

Note that Modbus TCP and EtherNet/IP are unauthenticated, unencrypted protocols by design. Issues that come from the protocols themselves, rather than from our code, are out of scope, but we welcome documentation improvements around network segmentation and safe deployment.
