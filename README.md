# cloud-threat-hunting-queries

This repository contains a collection of threat hunting queries designed for cloud environments, mainly focusing on identity and access related abuse patterns.

Each query aims to detect suspicious or anomalous behaviors by analyzing cloud audit logs and access activity.

Contents

IAM-infrequent-access – Detects rarely used IAM users or roles.

long-living-keys – Identifies API keys that have not been rotated for a long time.

longliving-unusual-location – Finds long-lived credentials used from unusual geographic locations.

reuse-of-old-keys – Detects reuse of previously rotated or disabled access keys.
