---
layout: layouts/community-component.njk
title: Risk RoSH widget
type: component
githuburl: https://github.com/ministryofjustice/moj-frontend/discussions/280
contributors: Todo
eleventyNavigation:
  key: Risk RoSH widget
  parent: Community components
  excerpt: "Use the case list page to make pieces of information about a case easier to scan, prioritise and action for users."
---

{% banner "This is a community component" %}
This component was added by a user in the community. It is not intended for use in live services. It is only meant for use in the Alpha and Beta phases of your project.
{% endbanner %}

<div class="govuk-form-group">
    <img alt="A three step process: Ask the user for information, view a summary of that information and ask if they want to add more of the same type of information, if they do it will take them back to the first step to ask the user for information again." src="../../assets/images/risk-rosh-widget-01.jpg" width="100%">
</div>

## Overview

The widget shows a summary of the Risk of Serious Harm (RoSH) level for an individual.

### Why is the component needed

The widget uses information from the legacy OASys risk assessment system to populate a mini-table showing:
- the individual’s overall RoSH level (low, medium, high, or very high)
- when the RoSH assessment was last updated
- the level risk posed to specific groups or classes of potential victims
- the area (community or custody) in which a particular risk level exists for each group or class

### When to use

Probation staff
Prison staff (where the services overlap or individuals pass between them)
3rd party suppliers of services (for example, interventions providers)

help users quickly see an individual’s overall RoSH score
help users quickly see an individual’s RoSH score for each group/class of potential victims in different contexts
make it easier for users to rapidly understand risk information without navigating away from their immediate task
support third parties who provide services in their assessment of risk (for example, interventions providers receiving a new person on probation)

Use this component/pattern to help users…
quickly absorb and interpret the risk of serious harm posed by an individual
develop a picture of the individual and their risks and needs
share and reuse risk information in a standard way with consistent meaning
Types of scale and call-out for each risk tool:
The information is presented in table form. The RoSH level is set by the probation practitioner based on a clinical assessment and the application of their professional judgement. It uses words rather than numbers. The words used are ‘low’, ‘medium’, ‘high’ and ‘very high’ and these are given unique and consistent colours.

Display both 'custody' and 'community' - when the user would find it beneficial to see both
Display 'custody' only - when a user needs to only understand risk information in the context of a person in prison
Display 'community' only - when a user needs to only understand risk information in the context of a person on probation in the community
Display 'No RoSH' - when a Risk of Serious Harm assessment has not been completed for an individual

## ## How the component has been used

When using this component or pattern, what should be considered when it comes to:
Establishing the potential victims
Based on OASys data, the categories of potential victims are:
- children
- public
- known adult
- staff
- prisoners
- The potential contexts are:
- community
- custody
In any given case, one or more classes of potential victims may be excluded and not all risks will be present across both community and custody. Use N/A for any empty values.

### No RoSH

<div class="govuk-form-group">
    <img alt="A three step process: Ask the user for information, view a summary of that information and ask if they want to add more of the same type of information, if they do it will take them back to the first step to ask the user for information again." src="../../assets/images/risk-rosh-widget-02.jpg" width="100%">
</div>

### Unknown RoSH

<div class="govuk-form-group">
    <img alt="A three step process: Ask the user for information, view a summary of that information and ask if they want to add more of the same type of information, if they do it will take them back to the first step to ask the user for information again." src="../../assets/images/risk-rosh-widget-03.png" width="100%">
</div>

### Unable to obtain the RoSH

<div class="govuk-form-group">
    <img alt="A three step process: Ask the user for information, view a summary of that information and ask if they want to add more of the same type of information, if they do it will take them back to the first step to ask the user for information again." src="../../assets/images/risk-rosh-widget-04.png" width="100%">
</div>

### Accessibility issues

**Unpaid work DAC audit:**  
[DAC Accessibility Report WCAG 2.1 - MOJ - Unpaid Work Assessment - Final (1).pdf]()

**Screen Magnification(Usability)**  
When the screen is magnified to 200%, the box overlaps the text on the page.  
**FIXED** - Breakpoints added for smaller screen sizes

Deciding if someone should be recalled or not - Accessibility issue  
[https://uv2854-moj-making-recall-decisions.uservisionaccessibility.co.uk/content-spills-out-of-container-on-ipad-l.html]()
Resolved

### Research

NO RoSH is now UNKNOWN LEVEL RoSH
Users of The Community payback assessment were assuming NO RoSH = LOW RoSH. Research showed that this is not always the case. A user can exempt themselves from completing a RoSH summary in OASys and therefore no level is assigned.

When UNKNOWN LEVEL is because no RoSH summary has been completed we use a yellow outline along with "A RoSH summary has not been completed for this individual. Check OASys for this persons current assessment status."

When UNKNOWN LEVEL is shown due to the system not being able to obtain the RoSH (whether it's there or not) We use the Grey outline along with the text "Something went wrong. We are unable to show RoSH information at this time. Try again later."

The use of UNKNOWN LEVEL rather than NO RoSH creates a little more uncertainty over RoSH and should encourage a user to double check OASys to understand the person on probations risk of serious harm.

The Grand High Council of Risk UI - December 2022  
[https://miro.com/app/board/uXjVPH939-Y=/?share_link_id=481664550142]()  
No major user problems identified un UR for RoSH component

### Services used

Community Payback Assessment - Public Beta  
Refer and monitor an intervention - Accommodation referral - LIVE  
Manage a workforce - Public Beta  
Deciding if someone should be recalled or not - Public Beta  
Approved Premises - Alpha  
Mange POM cases - Public Beta