---
layout: layouts/community.njk
subsection: Get involved
title: Add new component
eleventyNavigation:
  key: Add new component
  parent: Get involved
  order: 14
  excerpt: "For a contribution to be considered for the Design System, the style, component or pattern needs to be useful and unique."
---

The MOJ Design System supports the design, build, and deliver of accessible and consistent services. To guarantee the quality of the design system, all styles, components and patterns need to meet certain criteria.

## Criteria for adding a community component

All new components submitted to the design system must include specific information before being published.

### Minimum criteria for adding a new component to the design system

When adding a new component, you need to include information about:

- the overview of the component
- why the component is needed
- current uses for the component
- when not to use the component

## Add a new component to the design system

<div class="govuk-form-group">
  <h1 class="govuk-label-wrapper">
    <label class="govuk-label govuk-label--m" for="event-name">
      What is the name of the component?
    </label>
  </h1>
  <input class="govuk-input" id="event-name" name="eventName" type="text">
</div>

<div class="govuk-form-group govuk-character-count" data-module="govuk-character-count" data-maxlength="200">
  <h1 class="govuk-label-wrapper">
    <label class="govuk-label govuk-label--m" for="with-hint">
      Overview description of the component
    </label>
  </h1>
  <textarea class="govuk-textarea govuk-js-character-count" id="with-hint" name="withHint" rows="5" aria-describedby="with-hint-info with-hint-hint"></textarea>
  <div id="with-hint-info1" class="govuk-hint govuk-character-count__message">
    You can enter up to 200 characters
  </div>
</div>

<div class="govuk-form-group govuk-character-count" data-module="govuk-character-count" data-maxlength="200">
  <h1 class="govuk-label-wrapper">
    <label class="govuk-label govuk-label--m" for="with-hint">
      Why do you think the component needed?
    </label>
  </h1>
  <textarea class="govuk-textarea govuk-js-character-count" id="with-hint" name="withHint" rows="5" aria-describedby="with-hint-info with-hint-hint"></textarea>
  <div id="with-hint-info2" class="govuk-hint govuk-character-count__message">
    You can enter up to 200 characters
  </div>
</div>

<div class="govuk-form-group govuk-character-count" data-module="govuk-character-count" data-maxlength="200">
  <h1 class="govuk-label-wrapper">
    <label class="govuk-label govuk-label--m" for="with-hint">
      How are you using the component currently?
    </label>
  </h1>
  <textarea class="govuk-textarea govuk-js-character-count" id="with-hint" name="withHint" rows="5" aria-describedby="with-hint-info with-hint-hint"></textarea>
  <div id="with-hint-info3" class="govuk-hint govuk-character-count__message">
    You can enter up to 200 characters
  </div>
</div>

<div class="govuk-form-group govuk-character-count" data-module="govuk-character-count" data-maxlength="200">
  <h1 class="govuk-label-wrapper">
    <label class="govuk-label govuk-label--m" for="with-hint">
      When should people not use the component?
    </label>
  </h1>
  <textarea class="govuk-textarea govuk-js-character-count" id="with-hint" name="withHint" rows="5" aria-describedby="with-hint-info with-hint-hint"></textarea>
  <div id="with-hint-info4" class="govuk-hint govuk-character-count__message">
    You can enter up to 200 characters
  </div>
</div>

## Upload a file

<div class="govuk-form-group">
  <label class="govuk-label" for="file-upload-1">
    Upload a screenshot of your component
  </label>
  <input class="govuk-file-upload" id="file-upload-1" name="fileUpload1" type="file">
</div>

<button type="submit" class="govuk-button" data-module="govuk-button">
  Submit component
</button>

## Integrating "community components"

The MoJ Design System team reviews all newly submitted components.

Once we have all the information about the component and the review is finished, the team will look to remove the "<strong>community component</strong>" tag. This means it is ready for use across all phases of an Agile project.