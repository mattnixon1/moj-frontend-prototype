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
This component was added by a user in the community. It is not intended for use in live services. It is only meant for use in the Alpha and Beta phases of your project.
{% endbanner %}

<!-- {% example "/examples/loading-spinner", 125 %} -->

<div class="govuk-form-group">
    <img alt="A three step process: Ask the user for information, view a summary of that information and ask if they want to add more of the same type of information, if they do it will take them back to the first step to ask the user for information again." src="../../assets/images/loading-spinner-01.png" width="100%">
</div>


### Why is the component needed

There was a need because sometimes user have to wait was sometimes up to 15 seconds due to the amount of data.

We needed a way to show a user that a long running task (in this case a virus scan on uploads) was in progress along with providing progress updates.

## How the component has been used

The solution uses a modal to prevent the user from trying to upload further files during the upload progress and updates 'x of x files uploaded' text as the files are scanned.

### References

- [Indeterminate progress indicator]() - in the GOV.UK community backlog
- [Loading spinner]() - in the GOV.UK community backlog
- [Loading spinner]() - In the NHS community backlog
- [Loading spinner]() - Malcolm from LAA shared in GitHub