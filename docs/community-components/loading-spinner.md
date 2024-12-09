---
layout: layouts/community-component.njk
title: Loading spinner
type: component
githuburl: https://github.com/ministryofjustice/moj-frontend/discussions/237
contributors: Todo
eleventyNavigation:
  key: Loading spinner
  parent: Community components
  excerpt: "Use the case list page to make pieces of information about a case easier to scan, prioritise and action for users."
---

{% banner "This is a community component" %}
This component was added by a user in the community. It is only meant for use in the alpha and beta phases of your project as it is not yet fully integrated into the design system. This is because some key bits of information for the component have not yet been added.

Once all information is provided, the community tag will be removed and it will be ready to use in live environments.
{% endbanner %}

<!-- {% example "/examples/loading-spinner", 125 %} -->

<div class="govuk-form-group">
    <img alt="A three step process: Ask the user for information, view a summary of that information and ask if they want to add more of the same type of information, if they do it will take them back to the first step to ask the user for information again." src="../../assets/images/loading-spinner-01.png" width="100%">
</div>

## Overview of the component

When the page requires information and the user needs to wait for a process to finish then a loading spinner is displayed. This is to show the user that the page is still working and not frozen.

<h3 class="govuk-heading-m">Why is the component needed <span class="govuk-link govuk-body"><a href="">Edit</a></h1>

There was a need because sometimes user have to wait was sometimes up to 15 seconds due to the amount of data.

<h2 class="govuk-heading-l">Current uses for the component <span class="govuk-link govuk-body"><a href="">Edit</a></h1>

We needed a way to show a user that a long running task (in this case a virus scan on uploads) was in progress along with providing progress updates.

There was a need because sometimes user have to wait was sometimes up to 15 seconds due to the amount of data.

<h2 class="govuk-heading-l">When not to use the component <span class="govuk-link govuk-body"><a href="">Edit</a></h1>

Don't use it when the user is still able to interact with the page.

<!--
### References

- [Indeterminate progress indicator]() - in the GOV.UK community backlog
- [Loading spinner]() - in the GOV.UK community backlog
- [Loading spinner]() - In the NHS community backlog
- [Loading spinner]() - Malcolm from LAA shared in GitHub
-->