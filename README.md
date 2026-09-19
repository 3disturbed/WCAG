# Darks Guide To WCAG

> A practical, sector-aware reference for **WCAG 2.2**. This companion file covers the implementation and audit bases behind the interactive HTML guide.

## 1. What this guide is

WCAG 2.2 is a W3C Recommendation for making web content more accessible. It has **13 guidelines** under four principles — **Perceivable, Operable, Understandable and Robust (POUR)** — and testable success criteria at **A, AA and AAA**. WCAG 2.2 adds nine criteria compared with WCAG 2.1 and removes obsolete 4.1.1 Parsing.

**Common target:** Level AA is widely used as an organisational and regulatory baseline. Level AAA contains additional enhancements and W3C does not recommend requiring whole sites to satisfy every AAA criterion as a general policy.

This file is explanatory, not a substitute for the normative W3C text and not legal advice.

## 2. Sector toggle model

The HTML resource includes sector lenses. **They do not switch WCAG rules off.** They change priority highlights, examples and legal/context notes while preserving the complete list of criteria.

### Charity & nonprofit

Prioritise donations, membership, events, campaigns, volunteer journeys, PDFs and third-party fundraising tools.

**Context:** In the UK, some charities are directly covered by the Public Sector Bodies Accessibility Regulations; others may be exempt from those regulations, but service providers can still have duties to make reasonable adjustments under equality law.

**High-priority criteria in this lens:** 1.1.1, 1.3.1, 1.4.1, 1.4.3, 1.4.10, 1.4.11, 2.1.1, 2.4.7, 2.5.8, 3.2.6, 3.3.1, 3.3.2, 3.3.4, 3.3.7, 3.3.8, 4.1.2, 4.1.3.

- Test the full donation journey, including any embedded payment provider.
- Make downloadable campaign packs, annual reports and grant PDFs accessible.
- Give event and volunteer forms clear labels, errors and confirmation messages.
- Do not allow fundraising urgency timers or pop-ups to trap or pressure keyboard/screen-reader users.

### Public sector

Treat WCAG 2.2 AA, accessible documents and an accessibility statement as core service requirements.

**Context:** UK public-sector websites and mobile apps generally need to meet WCAG 2.2 AA and publish an accessibility statement, subject to the regulations and exemptions.

**High-priority criteria in this lens:** 1.1.1, 1.2.2, 1.2.4, 1.3.1, 1.3.5, 1.4.3, 1.4.10, 1.4.11, 1.4.12, 2.1.1, 2.4.1, 2.4.7, 2.4.11, 2.5.7, 2.5.8, 3.1.1, 3.2.6, 3.3.1, 3.3.2, 3.3.7, 3.3.8, 4.1.2, 4.1.3.

- Maintain an accessibility statement and update it after audits or major service changes.
- Include PDFs, Word documents, maps, forms, intranets and third-party components in scope where applicable.
- Use manual testing and testing with disabled users, not automated scans alone.

### Education

Focus on learning content, video, documents, assessments, virtual learning environments and complex reading.

**Context:** Education accessibility duties vary by institution and content. UK public-sector education bodies may be covered by the public-sector accessibility rules; schools have specific partial exemptions, so scope should be checked carefully.

**High-priority criteria in this lens:** 1.1.1, 1.2.2, 1.2.4, 1.2.5, 1.3.1, 1.3.2, 1.4.3, 1.4.10, 2.1.1, 2.2.1, 2.4.6, 2.4.7, 3.1.1, 3.3.1, 3.3.2, 3.3.7, 4.1.2.

- Caption teaching video and provide usable alternatives for diagrams and recorded lectures.
- Ensure assessments work with keyboard, zoom and assistive technology and do not create avoidable timing barriers.
- Check learning-platform and third-party tool accessibility before procurement.

### Healthcare

Prioritise appointments, medication information, forms, identity, urgent information and low-cognitive-load journeys.

**Context:** Healthcare services often carry heightened practical risk because inaccessible information can block access to care. Public NHS and other public-sector services are generally within UK public-sector accessibility requirements.

**High-priority criteria in this lens:** 1.1.1, 1.3.1, 1.3.5, 1.4.1, 1.4.3, 1.4.10, 2.1.1, 2.2.1, 2.4.7, 2.4.11, 2.5.8, 3.1.1, 3.2.6, 3.3.1, 3.3.2, 3.3.3, 3.3.4, 3.3.7, 3.3.8, 4.1.3.

- Never encode urgency, medication status or errors by colour alone.
- Make appointment, triage and prescription journeys resilient to timeouts and errors.
- Use plain language and consistent help; provide accessible alternatives to complex authentication.

### Business & e-commerce

Concentrate on product discovery, account access, basket, checkout, payments, support and transactional errors.

**Context:** WCAG is not itself a UK statute, but businesses providing services to the public can have equality-law duties to avoid disadvantaging disabled customers and to make reasonable adjustments.

**High-priority criteria in this lens:** 1.1.1, 1.3.5, 1.4.1, 1.4.3, 1.4.10, 1.4.11, 2.1.1, 2.4.7, 2.5.3, 2.5.7, 2.5.8, 3.2.4, 3.3.1, 3.3.2, 3.3.3, 3.3.4, 3.3.7, 3.3.8, 4.1.2, 4.1.3.

- Test search, filters, product variants, basket, checkout and payment confirmation entirely by keyboard.
- Make validation errors specific and preserve entered data.
- Check third-party payment, chat, cookie and review widgets.

### Content & media

Prioritise images, video, audio, live streams, reading experience, embeds and publishing workflows.

**Context:** Legal duties depend on the organisation and service, but accessible publishing reduces exclusion and makes content usable across a wider range of devices and assistive technologies.

**High-priority criteria in this lens:** 1.1.1, 1.2.1, 1.2.2, 1.2.4, 1.2.5, 1.3.1, 1.4.3, 1.4.4, 1.4.10, 1.4.12, 1.4.13, 2.1.1, 2.4.2, 2.4.6, 2.4.7, 3.1.1, 4.1.2.

- Build captions, transcripts, alt text and audio description into the editorial workflow.
- Check carousels, infinite scroll, autoplay, embeds and live players with keyboard and screen readers.
- Avoid publishing text baked into images when real HTML text is practical.

## 3. UK context

- UK public-sector websites and mobile apps generally need to meet **WCAG 2.2 AA** and publish an accessibility statement, subject to the Public Sector Bodies (Websites and Mobile Applications) (No. 2) Accessibility Regulations 2018 and applicable exemptions.
- GOV.UK guidance says public-sector bodies include some charities and other NGOs. It also notes that charities may be exempt from those specific regulations unless, for example, they are mostly publicly financed, provide services essential to the public, or are aimed at disabled people.
- Separate equality-law duties can apply to service providers. The Equality Act 2010 framework includes a duty to make reasonable adjustments where disabled people would otherwise be placed at a substantial disadvantage.
- Determine the exact legal scope for your organisation rather than treating this guide as legal advice.

## 4. Colour and visual rules you will use constantly

- **1.4.3 Contrast (Minimum), AA:** at least **4.5:1** for normal text and **3:1** for large text, subject to WCAG exceptions.
- **1.4.6 Contrast (Enhanced), AAA:** at least **7:1** normal and **4.5:1** large, subject to exceptions.
- **1.4.11 Non-text Contrast, AA:** important interface controls, states and meaningful graphical objects generally need **3:1** contrast against adjacent colours.
- **1.4.1 Use of Color, A:** never make colour the only way to communicate a state, error, category or action.
- **1.4.10 Reflow, AA:** ordinary content must reflow at narrow/400%-equivalent layouts without requiring two-dimensional scrolling.
- **1.4.12 Text Spacing, AA:** user-applied text-spacing changes must not break content or functionality.
- **2.4.7 Focus Visible, AA** and **2.4.11 Focus Not Obscured (Minimum), AA:** keyboard focus must be visible and not completely hidden by your own overlays/sticky content.

## 5. Complete WCAG 2.2 checklist

# Perceivable

## Guideline 1.1 Text Alternatives

### 1.1.1 Non-text Content — Level A

Give meaningful images, icons and other non-text content an equivalent text alternative; mark decoration so assistive technology can ignore it.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/non-text-content

## Guideline 1.2 Time-based Media

### 1.2.1 Audio-only and Video-only (Prerecorded) — Level A

Provide an equivalent alternative for prerecorded audio-only or video-only material.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/audio-only-and-video-only-prerecorded

### 1.2.2 Captions (Prerecorded) — Level A

Caption prerecorded synchronized video with spoken information and meaningful sounds.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded

### 1.2.3 Audio Description or Media Alternative (Prerecorded) — Level A

Provide audio description or an equivalent text-based media alternative for relevant prerecorded video information.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/audio-description-or-media-alternative-prerecorded

### 1.2.4 Captions (Live) — Level AA

Provide captions for live synchronized audio and video.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/captions-live

### 1.2.5 Audio Description (Prerecorded) — Level AA

Provide audio description for important visual information in prerecorded synchronized video.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/audio-description-prerecorded

### 1.2.6 Sign Language (Prerecorded) — Level AAA

Provide sign-language interpretation for prerecorded synchronized audio content.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/sign-language-prerecorded

### 1.2.7 Extended Audio Description (Prerecorded) — Level AAA

Where normal pauses are not enough, provide an extended version that makes room for the necessary audio description.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/extended-audio-description-prerecorded

### 1.2.8 Media Alternative (Prerecorded) — Level AAA

Provide a complete text alternative for prerecorded synchronized media and prerecorded video-only media.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/media-alternative-prerecorded

### 1.2.9 Audio-only (Live) — Level AAA

Provide a text alternative that communicates equivalent information for live audio-only content.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/audio-only-live

## Guideline 1.3 Adaptable

### 1.3.1 Info and Relationships — Level A

Use real headings, labels, lists, tables and other semantics so structure and relationships are available programmatically.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships

### 1.3.2 Meaningful Sequence — Level A

Make sure the programmatic reading order preserves meaning when sequence matters.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/meaningful-sequence

### 1.3.3 Sensory Characteristics — Level A

Do not give instructions that depend only on shape, size, position, direction or sound.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/sensory-characteristics

### 1.3.4 Orientation — Level AA

Allow content to work in portrait and landscape unless one orientation is genuinely essential.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/orientation

### 1.3.5 Identify Input Purpose — Level AA

Use supported autocomplete and semantics so common personal-data fields expose their purpose.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/identify-input-purpose

### 1.3.6 Identify Purpose — Level AAA

Expose the purpose of interface components, icons and regions programmatically where markup allows it.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/identify-purpose

## Guideline 1.4 Distinguishable

### 1.4.1 Use of Color — Level A

Do not use colour as the only way to communicate meaning, status, required fields or errors.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/use-of-color

### 1.4.2 Audio Control — Level A

Give users a way to stop, pause or independently control audio that starts automatically and continues for more than three seconds.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/audio-control

### 1.4.3 Contrast (Minimum) — Level AA

Provide at least 4.5:1 contrast for normal text and 3:1 for large text, subject to WCAG exceptions.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum

### 1.4.4 Resize Text — Level AA

Text must remain usable when resized up to 200% without requiring assistive technology.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/resize-text

### 1.4.5 Images of Text — Level AA

Use real text instead of images of text when the same visual presentation can reasonably be achieved with text.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/images-of-text

### 1.4.6 Contrast (Enhanced) — Level AAA

Aim for at least 7:1 contrast for normal text and 4.5:1 for large text, subject to WCAG exceptions.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced

### 1.4.7 Low or No Background Audio — Level AAA

Make speech in prerecorded audio easy to hear by avoiding or reducing competing background sound.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/low-or-no-background-audio

### 1.4.8 Visual Presentation — Level AAA

Offer highly readable presentation options for blocks of text, including manageable width, spacing, alignment and user-selected colours.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/visual-presentation

### 1.4.9 Images of Text (No Exception) — Level AAA

Use text rather than images of text except where the image is essential or purely decorative.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/images-of-text-no-exception

### 1.4.10 Reflow — Level AA

At 400% zoom / narrow viewport, content should reflow without two-dimensional scrolling except where a two-dimensional layout is essential.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/reflow

### 1.4.11 Non-text Contrast — Level AA

Important interface controls, states and meaningful graphics need at least 3:1 contrast against adjacent colours.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast

### 1.4.12 Text Spacing — Level AA

Content must still work when users increase line, paragraph, letter and word spacing to WCAG test values.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/text-spacing

### 1.4.13 Content on Hover or Focus — Level AA

Extra content triggered by hover or keyboard focus should be dismissible, hoverable where appropriate, and persistent long enough to use.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/content-on-hover-or-focus

# Operable

## Guideline 2.1 Keyboard Accessible

### 2.1.1 Keyboard — Level A

Make all functionality operable from a keyboard where the task does not inherently require path-dependent input.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/keyboard

### 2.1.2 No Keyboard Trap — Level A

Users must be able to move keyboard focus into and back out of every component.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/no-keyboard-trap

### 2.1.3 Keyboard (No Exception) — Level AAA

Make all functionality keyboard operable without relying on exceptions for path-dependent input.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/keyboard-no-exception

### 2.1.4 Character Key Shortcuts — Level A

If a single printable character triggers a shortcut, let users turn it off, remap it or ensure it only works while the relevant component has focus.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/character-key-shortcuts

## Guideline 2.2 Enough Time

### 2.2.1 Timing Adjustable — Level A

Let users turn off, extend or adjust time limits unless the timing is genuinely essential or otherwise exempt.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/timing-adjustable

### 2.2.2 Pause, Stop, Hide — Level A

Give users control over moving, blinking, scrolling or auto-updating information when required by the criterion.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/pause-stop-hide

### 2.2.3 No Timing — Level AAA

Avoid time limits unless they are essential or relate to real-time events.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/no-timing

### 2.2.4 Interruptions — Level AAA

Allow users to postpone or suppress interruptions except in an emergency.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/interruptions

### 2.2.5 Re-authenticating — Level AAA

After authentication expires, preserve the user's data so they can continue after signing in again.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/re-authenticating

### 2.2.6 Timeouts — Level AAA

Warn users about inactivity timeouts that could cause data loss unless data is preserved for a long period.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/timeouts

## Guideline 2.3 Seizures and Physical Reactions

### 2.3.1 Three Flashes or Below Threshold — Level A

Do not include content that flashes more than three times in one second unless it stays below the defined flash thresholds.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/three-flashes-or-below-threshold

### 2.3.2 Three Flashes — Level AAA

Do not include any content that flashes more than three times in one second.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/three-flashes

### 2.3.3 Animation from Interactions — Level AAA

Allow motion animation triggered by interaction to be disabled unless the animation is essential.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions

## Guideline 2.4 Navigable

### 2.4.1 Bypass Blocks — Level A

Provide a way to skip repeated blocks, such as a skip link or appropriate landmarks.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/bypass-blocks

### 2.4.2 Page Titled — Level A

Give each page a descriptive title that identifies its topic or purpose.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/page-titled

### 2.4.3 Focus Order — Level A

Keyboard focus should move in an order that preserves meaning and operability.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/focus-order

### 2.4.4 Link Purpose (In Context) — Level A

Make the purpose of each link understandable from its text or its programmatically associated context.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/link-purpose-in-context

### 2.4.5 Multiple Ways — Level AA

Provide more than one way to find pages in a set, except where a page is part of a process.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/multiple-ways

### 2.4.6 Headings and Labels — Level AA

Use headings and labels that clearly describe their topic or purpose.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/headings-and-labels

### 2.4.7 Focus Visible — Level AA

Keyboard users must be able to see which element currently has focus.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/focus-visible

### 2.4.8 Location — Level AAA

Give users information about where they are within a set of pages.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/location

### 2.4.9 Link Purpose (Link Only) — Level AAA

Make each link's purpose understandable from the link text alone, except where purpose would be ambiguous to everyone.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/link-purpose-link-only

### 2.4.10 Section Headings — Level AAA

Use section headings to organise content.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/section-headings

### 2.4.11 Focus Not Obscured (Minimum) — Level AA

When an element receives keyboard focus, it must not be entirely hidden by author-created content such as sticky headers or overlays.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum

### 2.4.12 Focus Not Obscured (Enhanced) — Level AAA

When an element receives keyboard focus, no part of its focus indicator should be hidden by author-created content.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-enhanced

### 2.4.13 Focus Appearance — Level AAA

Provide a sufficiently large and contrasting visible focus indicator, meeting WCAG's defined size and contrast requirements.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance

## Guideline 2.5 Input Modalities

### 2.5.1 Pointer Gestures — Level A

Provide a single-pointer alternative to multipoint or path-based gestures unless the gesture itself is essential.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/pointer-gestures

### 2.5.2 Pointer Cancellation — Level A

Avoid firing important actions on pointer-down; allow cancellation, reversal or another safeguard where applicable.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/pointer-cancellation

### 2.5.3 Label in Name — Level A

For controls with visible text labels, include that visible wording in the accessible name so voice-control users can target it.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/label-in-name

### 2.5.4 Motion Actuation — Level A

Provide conventional controls for functions triggered by device or user motion and allow motion activation to be disabled unless essential.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/motion-actuation

### 2.5.5 Target Size (Enhanced) — Level AAA

Provide pointer targets of at least 44 by 44 CSS pixels unless an exception applies.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/target-size-enhanced

### 2.5.6 Concurrent Input Mechanisms — Level AAA

Do not restrict users to one input method when the platform supports other input methods, unless restriction is essential.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/concurrent-input-mechanisms

### 2.5.7 Dragging Movements — Level AA

Anything that requires dragging must also be achievable without dragging using a single-pointer interaction, unless dragging is essential.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements

### 2.5.8 Target Size (Minimum) — Level AA

Provide pointer targets at least 24 by 24 CSS pixels, or satisfy one of WCAG's spacing or exception conditions.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum

# Understandable

## Guideline 3.1 Readable

### 3.1.1 Language of Page — Level A

Identify the default human language of each page in code.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/language-of-page

### 3.1.2 Language of Parts — Level AA

Identify changes of language within content when pronunciation or interpretation depends on them.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/language-of-parts

### 3.1.3 Unusual Words — Level AAA

Provide definitions or explanations for unusual, specialised or restricted-use words and phrases.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/unusual-words

### 3.1.4 Abbreviations — Level AAA

Provide a way to identify the expanded form or meaning of abbreviations.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/abbreviations

### 3.1.5 Reading Level — Level AAA

When content requires advanced reading ability, provide a simpler version or supplementary explanation.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/reading-level

### 3.1.6 Pronunciation — Level AAA

Provide pronunciation information where the meaning of words is ambiguous without it.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/pronunciation

## Guideline 3.2 Predictable

### 3.2.1 On Focus — Level A

Receiving focus alone must not unexpectedly trigger a change of context.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/on-focus

### 3.2.2 On Input — Level A

Changing a form control must not unexpectedly change context unless users have been told beforehand.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/on-input

### 3.2.3 Consistent Navigation — Level AA

Keep repeated navigation mechanisms in a consistent relative order across a set of pages unless the user changes them.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/consistent-navigation

### 3.2.4 Consistent Identification — Level AA

Components with the same function should be identified consistently across the site.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/consistent-identification

### 3.2.5 Change on Request — Level AAA

Only initiate changes of context at the user's request or provide a way to disable automatic changes.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/change-on-request

### 3.2.6 Consistent Help — Level A

When help options repeat across pages, keep them in a consistent relative location/order.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/consistent-help

## Guideline 3.3 Input Assistance

### 3.3.1 Error Identification — Level A

Identify input errors clearly and describe them in text.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/error-identification

### 3.3.2 Labels or Instructions — Level A

Provide labels or instructions when users need to enter information.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/labels-or-instructions

### 3.3.3 Error Suggestion — Level AA

When an error can be corrected with a known suggestion, provide that suggestion unless doing so would compromise purpose or security.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/error-suggestion

### 3.3.4 Error Prevention (Legal, Financial, Data) — Level AA

For important legal, financial or data-changing submissions, provide reversal, validation or a review-and-confirm step.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/error-prevention-legal-financial-data

### 3.3.5 Help — Level AAA

Provide context-sensitive help where appropriate.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/help

### 3.3.6 Error Prevention (All) — Level AAA

For any submission, provide reversal, validation or review-and-confirm safeguards.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/error-prevention-all

### 3.3.7 Redundant Entry — Level A

Do not make users re-enter information already supplied in the same process unless necessary; auto-populate or make it selectable where possible.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry

### 3.3.8 Accessible Authentication (Minimum) — Level AA

Do not require a cognitive-function test in authentication unless an allowed alternative or assistance mechanism is provided.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-minimum

### 3.3.9 Accessible Authentication (Enhanced) — Level AAA

Avoid cognitive-function authentication tests, with only the narrower WCAG exceptions.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-enhanced

# Robust

## Guideline 4.1 Compatible

### 4.1.2 Name, Role, Value — Level A

Expose the name and role of interface components and keep states, properties and values available to assistive technology.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/name-role-value

### 4.1.3 Status Messages — Level AA

Announce important status messages to assistive technology without forcing focus to move to them.

W3C understanding page: https://www.w3.org/WAI/WCAG22/Understanding/status-messages

## 6. Content and editorial checklist

- Use one descriptive page title and a logical heading hierarchy.
- Use meaningful link text; avoid repeated vague links such as “click here” where context does not make purpose clear.
- Give informative images purposeful alt text. Mark decorative images so assistive technology can ignore them.
- Provide captions for video when required, and audio description/media alternatives for important visual information under the applicable criteria.
- Write persistent form labels and concise instructions.
- Identify errors in text, associate them with the relevant field, and give a correction suggestion when it is known.
- Keep help mechanisms in a consistent place across repeated journeys.
- Use plain, direct language where possible; explain specialist terms when your audience may not know them.
- Do not publish essential information only as text baked into an image.
- Describe the conclusion or data behind charts and infographics in accessible text.

## 7. Forms, donations, payments and accounts

- Use native HTML controls first; custom controls require correct name, role, state, keyboard behaviour and focus management.
- Use `autocomplete` tokens for supported common personal-data inputs.
- Never use placeholder text as the only label.
- Preserve entered data after validation errors.
- For legal, financial or destructive submissions, provide a reversible action, validation or review/confirmation step as required by 3.3.4.
- Avoid repeated entry of information already supplied in the same process unless it is necessary or exempt.
- Authentication should not rely on memory/puzzle tests without the alternatives/assistance allowed by WCAG 2.2.
- Test third-party payment, donation, chat, cookie and CAPTCHA tools as part of the real end-to-end journey.

## 8. Keyboard and focus

- Every interactive element must be reachable and operable by keyboard unless the task inherently requires path-dependent input.
- Focus order must follow a sensible sequence.
- Never trap keyboard focus.
- Use a clearly visible focus indicator; do not remove browser focus outlines unless you replace them with something at least as usable.
- Sticky headers, cookie banners and overlays must not completely hide the focused control.
- Modals should move focus appropriately, constrain it while open where needed, close with an understandable mechanism, and restore focus sensibly.

## 9. Documents and PDFs

- Prefer accessible HTML when a document does not need to be a document.
- Use document styles for headings and lists rather than visual formatting alone.
- Set title and language metadata.
- Add alt text and proper table headers.
- Check reading order and tag order in exported PDFs.
- Check links, colour contrast and form-field labels.
- Re-test the exported PDF: accessible source files do not guarantee an accessible PDF.

## 10. Testing approach

1. **Automated:** use tools such as axe/Lighthouse to catch machine-detectable failures.
2. **Keyboard:** complete representative tasks with no mouse.
3. **Zoom/reflow:** test text resize and narrow/400%-equivalent layouts.
4. **Screen reader:** check representative flows, names, roles, states, headings, landmarks and live/status messages.
5. **Content review:** inspect alt text, labels, errors, captions, links and plain-language quality.
6. **Disabled-user testing:** include people with relevant access needs in research and task testing.
7. **Regression:** retest after CMS, design-system, cookie, chat, payment and supplier changes.

## 11. Accessibility statement / governance checklist

- State the service or website covered.
- Explain the level of compliance and known non-accessible content.
- Give accessible ways to report problems and request information in another format.
- Explain the enforcement/escalation route where legally required.
- Record when the statement was prepared and last reviewed.
- Keep an internal issue register with owner, severity, affected user journey, criterion, fix, retest and target date.
- Put accessibility requirements into procurement and supplier contracts, not just post-launch audits.

## 12. Primary sources

- W3C WCAG 2.2: https://www.w3.org/TR/WCAG22/
- W3C How to Meet WCAG 2.2 Quick Reference: https://www.w3.org/WAI/WCAG22/quickref/
- W3C WCAG overview: https://www.w3.org/WAI/standards-guidelines/wcag/
- GOV.UK public-sector accessibility requirements: https://www.gov.uk/guidance/accessibility-requirements-for-public-sector-websites-and-apps
- GOV.UK accessibility statement guidance: https://www.gov.uk/guidance/make-your-website-or-app-accessible-and-publish-an-accessibility-statement
- GOV.UK Equality Act disability guide for service providers: https://www.gov.uk/government/publications/equality-act-guidance/disability-quick-start-guide-for-service-providers-html

---
**Version note:** Built around WCAG 2.2. W3C published WCAG 2.2 as a Recommendation on 5 October 2023 and records an update dated 12 December 2024. Always use the W3C source for formal conformance decisions.
