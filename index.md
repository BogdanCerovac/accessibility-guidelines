# Web Content Accessibility Guidelines Overview

This document will help you quickly get up to speed with Web Content Accessibility Guidelines 2.1 (WCAG), and avoid common mistakes people make when designing and developing both websites and native apps.

It gives a short description of the requirements you must meet to ensure that a website or app is accessible under the Public Sector Bodies Accessibility Regulation 2018, and to ensure clients meet their legal obligations under the 2010 Equality Act.

This short description is a simplification. If you're unsure about how to meet a requirement, check the [official Web Content Accessibility Guidelines](https://www.w3.org/TR/WCAG21/).

### Principle 1: Perceivable

Your website/app must present information in ways people can recognise and use, no matter how they consume content (by touch, sound or sight for example).

#### Provide text alternatives for images

* <strong>Text alternatives for images</strong>. Provide a text description for images, and make sure the description serves the same purpose as the image. [More about 1.1.1](/all.html#1-1-1-non-text-content-a)

#### Provide alternatives for audio content, videos and presentations

* <strong>Transcript for audio content</strong>. Provide a transcript for audio content that has no video. The transcript must serve the same purpose as the original content. [More about 1.2.1]()

* <strong>Captions for videos and presentations</strong>. The captions must include all dialogue and important sound-effects. [More about 1.2.2 and 1.2.4]()

* <strong>Text or audio description of videos and presentations</strong>. Provide a text or audio description of videos or presentations. The description must serve the same purpose as the original content. [More about 1.2.3]()

* <strong>Audio description of pre-recorded videos or presentations</strong>. If the video or presentation is prerecorded (rather than live), provide an audio description of the recording (even if you're already provided a text description). [More about 1.2.5]()

#### Create content that can be presented in different ways

* Make sure that the visual structure of information is conveyed in code, so that assistive technologies can understand it. [More about 1.3.1]()

<!-- ALTERNATIVE: * Use elements like headings, lists, tables, fieldsets and legends to make sure that assistive technologies understand the structure of the information presented on screen. [More about 1.3.1]() -->

* Make sure that elements appear in the a logical reading order in website's Document Object Model or the app's View Hierarchy. [More about 1.3.2]()
  
* Do not use colour, size, shape, sound or location as the only way to convey any instruction. [More about 1.3.3]()

* Make sure a page's view is not locked to either horizontal or vertical only, unless this is essential. [More about 1.3.4]()

* [WEB ONLY]. In forms that collect information <strong>about the user</strong>, add autocomplete attributes to identify the purpose of the input. [More about 1.3.5]()

#### Make content easy for people to see and hear

* Do not use colour as the only way to convey information of any kind. [More about 1.4.1]()

* Give people a way to stop audio content if it plays automatically and lasts longer than three seconds, or give them a way to change the volume without changing their system settings. [More about 1.4.2]()

* Make sure that text has enough contrast against the background colour. [More about 1.4.3]()

* Make sure it is possible to complete all tasks when text is resized up to 200%. [More about 1.4.4]()

* Do not use images that contain text (except logos). [More about 1.4.5]()

* All information and functionality must be available a screen that's 320 CCS pixel wide, without needing to scroll horizontally [More about 1.4.10]().

<!-- ALTERNATIVES
* Make sure content will reflow to a single column when zoomed and not produce scrolling in both directions. [More about 1.4.10]()

* All information and functionality must be available when 320 CSS pixel worth of concent fills the full width of the screen, without needing to scroll horizontally [More about 1.4.10](). -->

* Make sure that interactive controls (including visual elements that indicate their states) and important graphics have enough contrast against their adjacent colours. [More about 1.4.11]()

* Users that no information or functionality gets lost if users increase the space between lines, paragraphs, letters and words. [More about 1.4.12]()

* If extra content appears when users focus or hover an element, that extra content is easily dismissable, hoverable and persistent. [More about 1.4.13]()

### Principle 2: Operable

Your website/app must be navigable and usable no matter how someone uses it (without a mouse, with voice commands, or with a screen magnifier for example).

#### Make functionality work with a keyboard

* Make sure every task can be completed using just a keyboard. [More about 2.1.1]()

* 2.1.2 Make sure that keyboard users don't get stuck when navigating through content. [More about 2.1.2](/all.html#2-1-2-no-keyboard-trap-a)

* 2.1.4 <strong>[NEW]</strong> Provide a way to switch off or remap keyboard shortcuts. [More about 2.1.4](/all.html#2-1-4-character-key-shortcuts-a)

#### Guideline 2.2: Give people enough time to read and use content
* 2.2.1 Give people a way to turn off or extend time limits. [More about 2.2.1](/all.html#2-2-1-timing-adjustable-a)
* 2.2.2 Give people a way to stop content that updates frequently, blinks or scrolls automatically. [More about 2.2.2](/all.html#2-2-2-pause-stop-hide-a)

#### Guideline 2.3: Do not cause seizures
* 2.3.1 Do not use content that flashes more than three times a second. [More about 2.3.1](/all.html#2-3-1-three-flashes-or-below-a)

#### Guideline 2.4: Provide ways to help people navigate and find content
* 2.4.1 Give people who do not use a mouse a way to move to the start of the main content. [More about 2.4.1](/all.html#2-4-1-bypass-blocks-a)
* 2.4.2 Give every page a unique and helpful title that indicates the purpose of the page. [More about 2.4.2](/all.html#2-4-2-page-title-a)
* 2.4.3 Make sure that things receive focus in an order that makes sense. [More about 2.4.3](/all.html#2-4-3-focus-order-a)
* 2.4.4 Make sure the purpose of a link is obvious from its link text, or its link text in association with nearby content. [More about 2.4.4](/all.html#2-4-4-link-purpose-in-context-a)
* 2.4.5 Unless a page is a step in a process, give people different ways of finding content (like searching or browsing links). [More about 2.4.5](/all.html#2-4-5-multiple-ways)
* 2.4.6 Provide headings and form labels that will help people find content and complete tasks. [More about 2.4.6](/all.html#2-4-6-headings-and-labels-aa)
* 2.4.7 Make sure that people using a keyboard to navigate can always see where they are on a page. [More about 2.4.7](/all.html#2-4-7-focus-visible-aa)
* 2.5.1 <strong>[NEW]</strong> Do not require complex gestures to do things. [More about 2.5.1](/all.html#2-5-1-pointer-gestures-a)
* 2.5.2 <strong>[NEW]</strong> Do not have controls or user interface components that fire as soon as they are touched. [More about 2.5.2](/all.html#2-5-2-pointer-cancellation-a)
* 2.5.3 <strong>[NEW]</strong> Make sure that for user interface components with a visible label the accessible name matches. [More about 2.5.3](/all.html#2-5-3-label-in-name-a)
* 2.5.4 <strong>[NEW]</strong> Make sure functionality can not only be activated by shaking or tilting the device. [More about 2.5.4](/all.html#2-5-4-motion-actuation-a)

### Principle 3: Understandable

Your service must make information understandable, and make it easy for people to understand how to complete tasks.

#### Guideline 3.1: Make text readable and understandable
* 3.1.1 Identify the language that the content is written in. [More about 3.1.1](/all.html#3-1-1-language-of-page-a)
* 3.1.2 Identify any changes in the default written language of the content. [More about 3.1.2](/all.html#3-1-2-language-of-parts-a)

#### Guideline 3.2: Make things appear and behave in consistent ways
* 3.2.1 Do not cause surprising things to happen (like opening a new page), when someone focuses on something. [More about 3.2.1](/all.html#3-2-1-on-focus-a)
* 3.2.2 Do not cause surprising things to happen when someone interacts with content (like scrolling through a set of options). [More about 3.2.2](/all.html#3-2-2-on-input-a)
* 3.2.3 Make sure that ways to find and navigate content (like search) look and behave the same way when they are used in multiple places. [More about 3.2.3](/all.html#3-2-3-consistent-navigation-aa)
* 3.2.4 Make sure that features look and behave the same way when they are used in multiple places. [More about 3.2.4](/all.html#3-2-4-consistent-identification-aa)

#### Guideline 3.3: Help people avoid and correct mistakes
* 3.3.1 When someone makes a mistake, provide an error message and make it obvious where the mistake was made. [More about 3.3.1](/all.html#3-3-1-error-identification-a)
* 3.3.2 Provide form labels to make it clear what information is expected, and optionally provide extra hints to help people avoid mistakes. [More about 3.3.2](/all.html#3-3-2-labels-or-instructions-a)
* 3.3.3 When someone makes a mistake give them suggestions on how to correct it, but do not offer suggestions that will have a negative impact on security. [More about 3.3.3](/all.html#3-3-3-error-suggestion-a)
* 3.4.4 Give people a way to review and check the information they have entered, and to correct any mistakes they have made. [More about 3.4.4](/all.html#3-3-4-error-prevention-legal-financial-data-a)

### Principle 4: Robust

Your service must work with different browsers and assistive technologies in use now, and use technologies in ways that will make your service usable with the browsers and assistive technologies of the future.

#### Guideline 4.1: Make content compatible with different browsers and assistive technologies
* 4.1.1 Make sure the code of each page does not contain errors that will have a negative impact on the way browsers and assistive technologies work together. [More about 4.1.1](/all.html#4-1-1-parsing-a)
* 4.1.2 Make sure the code of each page enables assistive technologies to discover the purpose of every feature, the way that feature is identified, and the state it is currently in. [More about 4.1.2](/all.html#4-1-2-name-role-value-a)

* 4.1.3 <strong>[NEW]</strong> Make sure status messages are shown in a way that AT understands without recieving focus. [More about 4.1.3](/all.html#4-1-3-status-messages-aa)

## How to meet the WCAG 2.1

Use our primer to find out more about the success criteria to understand how to meet WCAG 2.1. 

View [all success criteria](/all.html), or view those that are related to [content](/content.html), [design](/design.html) or [code](/code.html).