
# How to Threat Model

We already do a fair amount of threat modeling. At its most basic level, threat modeling asks:

| <h2> What could possibly go wrong? </h2> | ![alt text](/images/pez_gun_med.jpg "They'll take my Pez from my cold, dead hands.") |
|--|--|

<br /><br />

Using threat modeling to identify a system's particular set of risks, we can control the ones that are most likely and most dangerous.

<br /><br /><br />

### Some everyday examples:
_(This is where we get audience input!)_

<br />

**Asset:** House <br />
**Threat:**<br />
**Control(s):** 

<br /><br /><br />

**Asset:** Vehicle <br />
**Threat:**<br />
**Control(s):** 

<br /><br /><br />

**Asset:** Foot <br />
**Threat:** Legos left on floor <br />
**Control(s):** 

<br /><br /><br /><br /><br /><br />

### Many have brought some rigor to the process

#### Threat modeling according to the [TM Manifesto](https://www.threatmodelingmanifesto.org) and [Adam Shostack's Four Question Framework](https://github.com/adamshostack/4QuestionFrame):

* What are we working on? (Asset)
* What can go wrong? (Threat)
* What are we going to do about it? (Control)
* Did we do a good enough job? (Test/QA)

In other words:
* What is the system?
* What can threaten the system?
* How can we protect against those threats?
* Get feedback/validate.

<br /><br /><br />

#### Threat modeling according to [OWASP](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html):

1. Document how data flows through a system to identify where the system might be attacked.
1. Document as many potential threats to the system as possible.
1. Document security controls that may be put in place to reduce the likelihood or impact of a potential threat.

<br /><br />

#### Threat modeling according to [AWS](https://aws.amazon.com/blogs/security/how-to-approach-threat-modeling/):

1. Identify assets, actors, entry points, components, use cases, and trust levels, and include these in a design diagram.
1. Identify a list of threats.
1. Per threat, identify mitigations, which may include security control implementations.
1. Create and review a risk matrix to determine if the threat is adequately mitigated.


<br /><br />

[Next slide](talk_threat_model_demo.md)

