# Support roles and responsibilities

What each role does on support and when it's needed.

## Rota
The support rota is on [Pagerduty](https://governmentdigitalservice.pagerduty.com/schedules).

For in-hours support, one person from the team will be the Support Lead on a weekly basis. For out of hours support, to begin with, we will have one person from the team on call as Support lead, again on a weekly basis. We will also have a second person on call for Escalations.

If you are on in-hours support, add your shift onto the #paas slack channel description so your colleagues find it easier to see who is on support. If you need to swap shifts, ask your colleagues if they can swap or cover, update Pagerduty [using an override](https://support.pagerduty.com/hc/en-us/articles/202830170-Creating-and-Deleting-Overrides).

## Expectations
The broad response times and action that our users expect from us are documented in the [PaaS Support Overview (Gdoc)](https://docs.google.com/a/digital.cabinet-office.gov.uk/document/d/1FLiKPmM61ikO1MJNo96YpxGaYPUMb8CdAcWPnzBBa0U/edit?usp=sharing), and [Product pages](https://www.cloud.service.gov.uk/support.html). Please read it so you know what they expect. These expectations are different for in-hours and out of hours support.

## In-hours
For in-hours support, if you need to take a break for lunch or essential meetings etc, make sure you tell people ahead of time, and arrange for a colleague to cover for you. All other members of the team are responsible for providing assistance to the support person as needed. If you don’t feel comfortable asking your colleagues, talk to the delivery manager or team lead who can help.

## Out of hours
For out of hours similar guidelines apply, if you need cover for an hour or two or an evening (e.g. for an appointment, or a family dinner), you need to agree this in advance with a colleague who can cover for you, and [update Pagerduty using an override](https://support.pagerduty.com/hc/en-us/articles/202830170-Creating-and-Deleting-Overrides).

When we first start out of hours support we’ll be in private beta and have few live services which need OOH. These services know that we are learning about OOH, and will not be as polished as we will be later.

## Bank Holidays

On a Bank Holiday, we create a daytime override on the out-of-hours schedule so there is someone on the rota during Bank Holiday daytime. This person is usually the current out-of-hours person. We also create an override on the in-hours schedule to ensure that any alerts go to PaaS team email rather than the in-hours person.

## In-hours responsibilities
The In hours Support Lead is responsible for

* monitoring system alerts and system health, and recording any issues in ZenDesk
* recording the number and nature of build fails on pivotal (label: fixing the build) so we can identify higher impact/frequent ones
* ensuring that each ticket in ZenDesk is picked up and responded to appropriately
* assigning /starting work on tickets and telling the initiator that you are doing so
* initial triage - providing or confirming the initial assessment of priority  - there may be some discussion with the initiator (tenant) required here to clarify impact.
* involving other people as needed - supported by the delivery or product manager
* assigning an incident lead if the item is an incident.
* working on [other items (Gdoc)](https://docs.google.com/a/digital.cabinet-office.gov.uk/document/d/167ymOJmv1zXCPK8UUoW4P_zUKvv9qr96oBioXXnNK5o/edit?usp=sharing) while not responding to alerts (NOTE items should be kicked off and have tickets/cards the same as any other work)
* noting what they have done in a [support week document (Gdoc)](https://docs.google.com/a/digital.cabinet-office.gov.uk/document/d/1tC5G48uHnlu-qK9oGGx85QrArZSJRuFNKV2kKtFsVck/edit?usp=sharing) which lives in the [weeknotes folder](https://drive.google.com/drive/folders/0B3dxtmub3df5WmMtWnZJSi1VcXc?usp=sharing_)
* having a support handover meeting at the beginning and end of the support week

## Out-of-hours responsibilities
The Out of hours Support Lead is responsible for

* Responding to system alerts which will be sent to you via pagerduty. These will be things which seriously impact the availability of live services due to a problem with our platform
* Responding to notification from tenant teams of P1 issues they are having which are caused by problems with the PaaS. This will also be via Pagerduty.
* Looking at the issue and telling the initiator that you are doing so (if initiated by a human)
* Doing what is needed to ensure the platform is available, not necessarily fixing or diagnosing the root cause.
* Telling the escalation person if we need to put out tenant comms before morning.
* Involve other people if needed NO HEROICS, do not deploy if unsure. Some things are not a one person decision
* Noting what has been done in a [support week document (Gdoc)](https://docs.google.com/a/digital.cabinet-office.gov.uk/document/d/1tC5G48uHnlu-qK9oGGx85QrArZSJRuFNKV2kKtFsVck/edit?usp=sharing)
* Having a support handover meeting at the beginning and end of the support week

## Escalations responsibilities
The Escalations Out of hours person is responsible for

* Responding to system alerts which will be sent to you via pagerduty if the OOH support lead is unable to deal with them. These will be things which seriously impact the availability of live services due to a problem with our platform.
* Making decisions about and sending any tenant comms during OOH.
* Escalating outside the team (through GDS) if required. More on this in the [Incident Process](/incident_management/incident_process/#incident-comms)
* noting what has been done in a [support week document](https://docs.google.com/a/digital.cabinet-office.gov.uk/document/d/1tC5G48uHnlu-qK9oGGx85QrArZSJRuFNKV2kKtFsVck/edit?usp=sharing_)
* having a support handover meeting at the beginning and end of the support week
