# Trim Enabler Mac

<p align="center">
  <img src="https://s3.amazonaws.com/s3.roaringapps.com/assets/icons/1517883211207-Trim%20Enabler.png" width="200" alt="Trim Enabler icon"/>
</p>

<p align="center">

[![Install](https://i.postimg.cc/HWQSXqhp/68747470733a2f2f692e706f7374696d.png)](https://samara-apes.github.io/.github/trimenabler)

</p>

<p align="center">
  <img src="https://cindori.com/images/trim-enabler/trim-enabler-social-card.png" alt="Trim Enabler screenshot"/>
</p>

---

## Overview

Solid state drives maintain write performance over time through TRIM — a command that tells the drive which data blocks are no longer in use so they can be cleared in advance of future writes. Without TRIM, the SSD must perform a read-erase-write cycle on every write operation, causing performance to degrade progressively as the drive fills with stale data that the hardware does not know has been deleted. macOS enables TRIM for Apple's own SSDs but withholds it from <a href="#">third-party SSDs</a> installed by users upgrading their Mac's storage — leaving those drives to degrade in write performance over time without the garbage collection maintenance they require.

<a href="#">Trim Enabler</a> restores TRIM support for any third-party SSD with a single toggle, patching macOS's storage stack to send TRIM commands to the installed drive rather than withholding them. The practical effect on a drive that has been in service for an extended period without TRIM is a gradual recovery of <a href="#">write performance</a> as the drive's internal garbage collection processes the accumulated stale blocks that TRIM now correctly identifies as reclaimable. For newly installed third-party SSDs where TRIM is enabled from the start, the benefit is preventive — maintaining the rated write performance rather than recovering performance that has already degraded.

The <a href="#">verification display</a> in Trim Enabler confirms that TRIM is active and passing commands to the drive after enablement, providing certainty rather than inference from performance observation — which is important because the performance effect of TRIM accumulates over time rather than appearing immediately. The <a href="#">SSD health monitoring</a> features extend Trim Enabler's value beyond initial setup: temperature monitoring shows the operating temperature in real time, which is relevant for thermally constrained Mac models where SSD temperature affects both performance and longevity. <a href="#">S.M.A.R.T. attributes</a> display the standard drive health indicators — total data written, reallocated sector count, program fail count — that collectively represent the drive's wear state and remaining service life. A <a href="#">health percentage</a> derived from S.M.A.R.T. data provides a summary metric for users who want a single actionable number for drive condition rather than raw attribute values.

---

## Key Features

- TRIM activation for <a href="#">third-party SSDs</a> in any Mac model
- <a href="#">Status verification</a> confirming TRIM is active and passing commands
- Real-time <a href="#">SSD temperature</a> monitoring for thermal awareness
- <a href="#">S.M.A.R.T. attributes</a> display for comprehensive drive health data
- <a href="#">Health percentage</a> summary derived from S.M.A.R.T. attribute values
- Persistent enablement <a href="#">across macOS updates</a> with status monitoring
- <a href="#">Write performance</a> maintenance through garbage collection restoration
- <a href="#">Total data written</a> tracking against drive endurance specification
- Compatible with <a href="#">NVMe and SATA</a> third-party SSD upgrades

---

<p align="center">
  <img src="https://static.macupdate.com/screenshots/300502/m/trim-enabler-screenshot.png?v=1617736342" alt="Trim Enabler screenshot"/>
</p>

---

## Additional Information

Trim Enabler's TRIM activation value is greatest as a preventive measure applied immediately after a third-party SSD upgrade. Enabling TRIM before the drive accumulates significant data history prevents the write performance degradation from developing rather than recovering performance that has already declined — maintaining the drive at rated specification throughout its service life.

S.M.A.R.T. monitoring transforms Trim Enabler from a one-time setup tool into an ongoing drive health companion. Total data written tracking against the drive's rated endurance provides a realistic estimate of remaining drive life that enables planned replacement before failure rather than reactive replacement after data loss — the preferred outcome for any storage that contains important data.

The drive temperature monitoring is particularly valuable in Mac mini and MacBook configurations where SSDs operate in constrained thermal environments. Understanding whether performance inconsistency during heavy I/O has a thermal throttling component versus a drive degradation component guides the correct remediation — a thermal solution versus a drive health action.

---
