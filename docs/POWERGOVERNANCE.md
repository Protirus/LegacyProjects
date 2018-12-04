# Power Governance

![PowerGovernance](/docs/images/PowerGovernance.png)

> First out the blocks with innovative ideas

> Reduce costs and CO2 emissions with Power Governance, a Symantec Management Platform based PC power management solution.

### Safe Shutdown of Open Applications

**When a workstation is automatically shut down by an enforced Green IT policy, or scheduled compliance policy, the issue of unsaved data on the desktop becomes a serious concern. Open applications can prevent a workstation from shutting down or, if forced to close, can result in the loss of unsaved customer data.**

Power Governance solves this problem by closing applications, saving work, and informing both the administrator and the end user where they can locate their previously unsaved work.

![Power Governance Popup](/docs/images/PowerGovernancePopup.png)

### Fast, Accurate, Customisable Reporting

**Reporting with Power Governance is highly accurate and customisable. Discover how much is saved by adopting a company-wide power setting policy; compare month by month usage in kWh, CO2 emission, and £, $ or €.**

### Power Governance Assessment Report

![Power Governance Report](/docs/images/PowerGovernanceReport.png)

### Features

- **Change the Power State of a PC (logoff / shutdown / hibernate / standby) on a schedule or in real time:**
  - According to rule based logic - idle time / business hours and holiday periods / at Home / network connectivity
  - Allow users to postpone and allow power users to opt out
  - Block out workstations that are currently running critical applications sets

- **Manage safe Power State transitions by archiving open work:**
  - Archive open work including on locked workstations before a power transition roaming archives - retrieve archived work from any PC
- **Set archive retention length and capacity**
- **Supports any language or typeset at the end-point - e.g. English, Arabic, Russian**
- **Records Power State events at the client for analytical reporting Events recorded include:**
  - Logged on / logged Off / idle time / powered off / standby / hibernate / within business hours / holidays
- **Full analytics report KWH, CO2, cost against multiple vendors and against asset information such as location / business unit / department**
- **Extending Wake-on-Lan (WOL) in the enterprise:**
  - WOL Proxy - support WOL event if unsupported on the WAN
  - WOL - Last man standing - Elect a proxy on each subnet to stay awake during mass shutdown
- **Dynamically enforce PC power settings according to business hours / holidays / online / offline**
- **3rd party shutdown support - Archive if a 3rd party tool actions a shutdown**

### Closing Applications

**Out of the box Power Governance closes all Microsoft applications and a large number of additional software packages.**

Power Governance “Close Application” policies are easily created through Power Governance’s Policy Configuration Tool which enables administrators to create custom policies for targeting specific applications.

Power Governance’s Rule Builder enables administrators to build up policies that best meet the needs of their environment.

![Power Governance Client Policy](/docs/images/PowerGovernanceClientPolicy.png)

Exceptions to Power Governance “Close Application” rule logic trigger the creation of a central report which is sent to the administrator. This enables administrators to extend their policy rule set to deal with increasingly complex situations and inconsistent application behavior.

### Policies and Tasks

**Power Governance compliments existing Symantec solutions that require automated and enforced shutdowns, or for a PC to be in a logged off state. Shutdown and logoff tasks can be used in sequence with any Symantec task or policy to provide a safe, policy driven method for closing applications.**

Combining Power Governance with tasks such as Software Delivery and Patch Management, valuable data is not put at risk or compromised, whilst the administrator can guarantee the completion of these critical IT activities.

Extending this further with technologies such as vPro or the enhanced WOL tasks, completes out of band management whilst ensuring the safety of unsaved application data.

### Workflow Integration

**Integration with Symantec’s Workflow solution enables complex tasks to be automated resulting in an elegant power
down of the managed PC.**

![Power Governance Architectural Topology](/docs/images/PowerGovernanceArchitecturalTopology.png)

**Figure 1:** Typical architectural Topology showing location options for saved data during Power Governance enforced shutdown.

---

## **Power Governance** Feature Comparison

| | Power Governance | SMP-Altiris | eiPower |
|-|-|-|-|
| Guarantee safe shutdown by archiving open work | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) | ![cross](/docs/images/cross.png) |
| Archive open work on a locked workstation and then unlock the workstation for others to use | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) | ![cross](/docs/images/cross.png) |
| Block out workstations that are currently running critical application sets | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) | ![cross](/docs/images/cross.png) |
| Manage postponements | ![tick](/docs/images/tick.png) | ![tick](/docs/images/tick.png) Patch Management | N/A |
| Realtime Power Policies and tasks based on idle time | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) | ![cross](/docs/images/cross.png) |
| Allow Power Users to opt out at the desktop | ![tick](/docs/images/tick.png) | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) |
| Multi-lingual and typeset support for pop ups e.g English, Arabic, Russian | ![tick](/docs/images/tick.png) | ![tick](/docs/images/tick.png) | N/A |
| 3rd party shutdown support | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) | ![cross](/docs/images/cross.png) |
| Roaming archives, data retention and volume policies | ![tick](/docs/images/tick.png) | N/A | N/A |
| Business hours and holiday period support | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) | ![cross](/docs/images/cross.png) |
| True Power State to track workstation usage data to trend waste | ![tick](/docs/images/tick.png) | ![cross](/docs/images/cross.png) | ![cross](/docs/images/cross.png) |

| | Power Governance | SMP-Altiris | eiPower |
|-|-|-|-|
| Enforce PC power settings | ✔ Policy | ✔ Task | ✔ Policy |
| Report ON / OFF state for PCs | ✔ * True Heart Beat | ✔ * with Custom Report | ✔ |
| Report KWH via power rating | ✔ * | ✔ NS6 with AMS NS7 Native | ✔ |
| Record Power Events for reporting | ✔ * Restart/Log-OnOff/Lock Unlock | ✔ Log-On/Log-Off | ✔ +Monitor Off/Disk Off |
| Send standby / shutdown on a schedule | ✔ | ✔ | ✔ |
| Sequence Altiris Power Events | ✔ +3rd Party Power Events | ✔ | ✔ |
| Update BIOS setting for WOL support | ✔ | ✔ DCM/HPCM/IBM/Fujitsi | ✘ |
| WOL capability | ✔ | ✔ | ✘ |
| WOL proxy capability | ✔ | ✔ Using DS 6.9 | ✘ |
| Last man standing for WOL | ✔ | ✘ | ✘ |

\* Power Governance supports multiple business hours and holidays for these features

---

## Downloads

![pdf](/docs/images/pdf.png) [Protirus-PG-Comparison.pdf](/docs/Protirus-PG-Comparison.pdf)

![pdf](/docs/images/pdf.png) [Protirus-PG-Datasheet.pdf](/docs/Protirus-PG-Datasheet.pdf)