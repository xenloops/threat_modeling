
# How to Threat Model

We already do a fair amount of threat modeling:

<br /><br />

**Asset:** House and possessions <br />
**Threat:** Fire <br />
**Control:** Maintain smoke detectors <br />

<br /><br /><br />

**Asset:** Vehicle <br />
**Threat:** Theft <br />
**Control:** Lock doors <br />
**Control:** Set alarm <br />
**Control:** Don't leave valuables in vehicle/plain sight <br />
**Control:** Drive a beater <br />

<br /><br /><br />

**Asset:** Foot <br />
**Threat:** Legos left on floor <br />
**Control:** Watch where you step <br />
**Control:** Wear shoes in house <br />
**Control:** Train kids to clean up when they're done playing <br />

<br /><br />

By using threat modeling to identify a system's particular set of risks, we can then counter the ones that are most likely and most dangerous.

<br /><br /><br /><br /><br /><br />

### Process

#### Threat modeling according to the [TM Manifesto](https://www.threatmodelingmanifesto.org) and [Adam Shostack's Four Question Framework](https://github.com/adamshostack/4QuestionFrame):

* What are we working on? (Asset)
* What can go wrong? (Threat)
* What are we going to do about it? (Control)
* Did we do a good enough job? (Feedback/reflection)

In other words:
* What is the system?
* What threatens the system?
* How can we protect against those threats?
* Get feedback.

<br /><br />

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


