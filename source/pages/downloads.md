---
title: Downloads
layout: default
active: downloads
mycss: argo-sched.css
---
## ImplemenationGuide Resource

The [{{site.data.fhir.igName}} ImplementationGuide](ImplementationGuide-ig.html) resource defines the logical content and the important pages published in this IG and can be downloaded in both xml and JSON.

## Validator Pack and Definitions

The following file contains all the value sets, profiles, extensions, list of pages and urls in the IG, etc defined as part of the this Implementation Guide.:

- [Validator Pack](validator.pack)

In addition there are format specific definitions files.
- [XML](definitions.xml.zip)
- [JSON](definitions.json.zip)
- [TTL](definitions.ttl.zip)

These files should be the first choice whenever generating any implementation artifacts since they contain all of the rules about what makes these US-Core profiles valid. Implementers will still need to be familiar with the content of the specification and profiles that apply in order to make a conformant implementation.  See the overview on [validating FHIR profiles and resources]({{ site.data.fhir.path }}/validation.html)

## Schematrons

Schematrons for the profiles defined in this guide are also available and listed below:

<li><a href="slot-bundle.sch">Argonaut Slot Bundle Profile</a></li>
<li><a href="prefetch-slot.sch">Argonaut Prefetch Slot Profile</a></li>
<li><a href="extension-subscription-triggerevent.sch">Subscription Trigger Event Extension</a></li>
<li><a href="extension-status-reason.sch">Reason for current status</a></li>
<li><a href="extension-subscription-payloadprofile.sch">Subscription Payload Profile Extension</a></li>
<li><a href="extension-subscription-eventfocus.sch">Subscription Event Focus Extension</a></li>
<li><a href="avail-bundle.sch">Argonaut Appointment Bundle Profile</a></li>
<li><a href="argo-sub-notif.sch">Argonaut Scheduling Subscription Profile</a></li>
<li><a href="argo-sched-notif.sch">Argonaut Scheduling Schedule Notification Profile</a></li>
<li><a href="argo-coverage.sch">Argonaut Coverage Profile</a></li>
<li><a href="argo-appt.sch">Argonaut Appointment Profile</a></li>

## Examples

All the examples that are used in this guide are available for download:

- [XML](examples.xml.zip)
- [JSON](examples.json.zip)
- [TTl](examples.ttl.zip)

<br />
