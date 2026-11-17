# CercaSalud Intro Landing Page Specification

## 1. Document Purpose

This document is the product, content, and experience brief for the first CercaSalud website. It is intended to guide copywriting, design, implementation, and review. The page is an introduction and demand-validation surface for Phase 0. It is not an application, a patient portal, an emergency-response channel, or proof that the service is already operational.

The website's job is to make the idea understandable and worthwhile to the family member who makes care decisions, then give that person a low-friction way to express interest. A visitor should be able to explain CercaSalud to another person after one visit.

## 2. Product Context and Scope

CercaSalud is exploring a service for families who worry about an older relative being alone during the day. A wearable device could provide two ways to raise an alert: the wearer can ask for help, or the system can flag a possible anomaly. A monitoring team would verify the situation and, when appropriate, coordinate an in-person response from a qualified local responder.

The intended value is an additional safety net for occasional situations, not constant bedside care. The service is not a hospital, a substitute for emergency services, a diagnostic system, or a permanent nursing service.

### Phase 0 boundary

- Present this as an idea being validated and an early service being prepared.
- The primary conversion is an expression of interest, not a purchase, subscription, emergency call, or medical intake.
- Do not imply that the watch, monitoring center, response network, geographic coverage, or response times are currently available unless the team has verified that they are.
- Keep copy about future operations in conditional or planned language until each capability is real and approved for public claims.
- Do not solicit an alert or emergency message through the website. Clearly say that the form is not monitored for emergencies.

## 3. Audience

### Primary audience

An adult child, relative, or trusted contact who helps make decisions for an older adult. They may live or work away from the older person's home, are balancing work and family responsibilities, and want a practical way to know when attention may be needed. They are likely to be comparing this idea with daily check-ins, asking a neighbor for help, hiring a caregiver, or doing nothing until a problem occurs.

### Secondary audience

An older adult who may wear the device. The page should respect their autonomy and dignity. They are not framed as helpless, burdensome, or incapable. The explanation should make clear that the wearer can initiate a request and that automated alerts are prompts for human verification, not conclusions about their health.

### Audience needs and hesitations

- Understand what happens after an alert, not just what the watch can detect.
- Know whether a real person is involved and what that person is expected to do.
- Understand how this differs from full-time care and from calling emergency services.
- Know whether the service is available in their area and whether it is currently a concept or a live offering.
- Feel that sharing their contact information will lead to a relevant conversation, not unsolicited marketing.

## 4. Communication Goals

The page must answer these questions in this order:

1. What is CercaSalud, in plain language?
2. Who is it for, and what family problem does it address?
3. How can an alert begin, and what happens next?
4. Why might this help compared with having no structured backup or arranging constant care?
5. What can and cannot be expected from it at this stage?
6. What is the next step for someone who is interested?

### Five-second comprehension test

After seeing only the first screen, a visitor should be able to say:

- This is for families supporting an older relative who may be alone at times.
- A wearable may let the person request help or flag a possible issue.
- CercaSalud is exploring a human verification and in-person assistance model.
- The service is being validated; I can register interest, but this page is not an emergency service.

## 5. Positioning and Message Hierarchy

### Core positioning

CercaSalud is a proposed, human-supported safety net for families who cannot always be physically nearby. It connects a simple alert mechanism with human follow-up and, when available and appropriate, local in-person assistance.

### Main benefit

Families can have a clearer plan for noticing and checking a possible urgent situation without assuming that a family member must be present every moment.

### Supporting reasons to believe

- Two possible alert paths: a deliberate request from the wearer and an automated signal that prompts review.
- A human verification step is central to the idea; an alert is not presented as a diagnosis.
- The model is designed around occasional assistance, rather than selling continuous nursing as the only option.
- The older adult remains an active participant and can request help directly.

These are product principles, not permission to claim live capabilities. Public copy must reflect what CercaSalud can actually deliver at launch.

## 6. Voice and Language

- The public page is written in clear, natural Venezuelan Spanish.
- Address the family decision-maker warmly and directly, without guilt or fear tactics.
- Use short sentences, familiar words, and concrete verbs: pedir ayuda, recibir una alerta, verificar, contactar, coordinar.
- Explain technical or medical terms immediately, or avoid them.
- Refer to the older adult as a person with agency. Avoid infantilizing terms and imagery.
- Sound calm and capable, not clinical, alarmist, sentimental, or grandiose.
- Use voseo or tuteo consistently after selecting the preferred regional voice. Do not mix forms within the page.
- Never promise guaranteed prevention, instant response, diagnosis, continuous supervision, or rescue unless operationally verified and legally approved.

### Draft message direction

Suggested headline:

> Si no puedes estar cerca, puede haber una forma de estar pendiente.

Suggested supporting copy:

> CercaSalud está desarrollando una manera de conectar alertas desde un reloj con verificación humana y apoyo presencial cuando haga falta. Para familias que quieren acompañar a una persona mayor, incluso cuando no pueden estar a su lado todo el día.

Suggested primary call to action:

> Quiero conocer el piloto

Suggested availability note near the call to action:

> Estamos validando el servicio y sus zonas de atención. Déjanos tus datos para recibir información cuando tengamos novedades.

This copy is a starting point. The product owner must confirm the maturity and availability language before publication.

## 7. Information Architecture and Section Requirements

The experience is one long, responsive page. Navigation should move to sections on the same page. Do not create a multi-page marketing site for the first release unless testing shows a clear need.

### 7.1 Header

**Purpose:** Identify the service and provide fast access to the explanation and interest form.

**Content:**

- CercaSalud wordmark or text logo.
- Three or fewer links: `Cómo funciona`, `Para quién es`, `Preguntas frecuentes`.
- One clear action: `Quiero conocer el piloto`.

**Behavior:**

- Use a compact header that does not consume excessive vertical space on mobile.
- The action scrolls to the interest form; it must not imply that the user is starting an emergency request.
- Use a visible keyboard focus style. The mobile menu, if needed, must have an accessible name, expanded state, and keyboard operation.

### 7.2 Hero: the idea at a glance

**Purpose:** State audience, concept, value, and Phase 0 status in the first viewport.

**Required content:**

- One specific headline, not a generic slogan.
- One short paragraph describing wearable alert, human verification, and possible in-person support.
- Primary action leading to the form.
- A nearby pre-launch/availability note.
- A human, context-rich visual (art direction in Section 8).

**Layout:**

- The message and image should feel like one composition, not a text card beside an unrelated photo.
- On wide screens, use an intentionally offset or asymmetric split with the headline as the first reading anchor.
- On narrow screens, show headline, explanation, action, then visual or a tightly composed visual that does not push the action far below the fold.
- Avoid oversized empty hero space, floating decorative blobs, and text over a busy photograph.

### 7.3 The family situation

**Purpose:** Show that CercaSalud understands the practical gap, without making visitors feel accused or afraid.

**Core idea:** A relative may be safe and independent while still benefiting from a clear way to ask for help and a plan for checking a possible problem when family is not nearby.

**Copy direction:** Describe ordinary distance and uncertainty, not a dramatic worst-case scenario. Do not imply that families who do not buy a service are neglectful.

**Visual treatment:** A short editorial passage with one real-life detail or supporting photograph. Do not render every paragraph inside a separate card.

### 7.4 How it works

**Purpose:** Explain the dual-trigger mechanism and the human response in a sequence a visitor can retell.

**Use a shared three-step flow:**

1. **Se genera una alerta.** The older adult requests help using the device, or the system flags a possible anomaly. Clearly distinguish the two paths with labels or a simple branching visual.
2. **Una persona verifica.** The monitoring team reviews the alert and tries to understand what is happening. State what contact method is intended only after the operating procedure is confirmed.
3. **Se coordina apoyo.** If the situation calls for it and the service is available in that area, a qualified responder may be coordinated to check in person. Make clear this is not a substitute for the local emergency number.

The diagram must show that both alert paths converge on human review. It must not depict an anomaly as an automatic diagnosis or show dispatch as guaranteed. On small screens, the flow becomes a clear vertical sequence with readable labels; the diagram must not require hover to reveal meaning.

### 7.5 Why this approach may help

**Purpose:** Explain the value, not merely repeat device features.

Organize the benefit around three ideas, but avoid a generic grid of identical icon cards:

- **A way to ask:** The wearer can initiate an alert instead of relying only on someone noticing a problem.
- **A prompt to check:** A possible anomaly can prompt a human to look into the situation; it is not itself a diagnosis.
- **A plan for occasional support:** Families can explore an additional layer of help without describing it as permanent care.

Use grounded language such as `una forma más clara de saber cuándo revisar` rather than absolute claims such as `tranquilidad total` or `nunca estará solo`.

### 7.6 Who it is for and service boundaries

**Purpose:** Help visitors determine fit and prevent mistaken expectations.

State that the idea is intended for families supporting older adults who are independent for much of the day but may need occasional attention or help. Keep this inclusive and avoid implying that age alone means a person needs monitoring.

Include a clearly visible boundary statement:

> CercaSalud no reemplaza los servicios de emergencia, una evaluación médica ni el cuidado continuo. La disponibilidad, cobertura y forma de respuesta dependerán de la zona y de la operación confirmada.

Do not bury this information only in the footer or legal text.

### 7.7 Trust and responsibility

**Purpose:** Answer who is involved and how the family will be treated, without inventing credentials or operational facts.

Include only facts approved by the project owner. Potential topics, if verified, are responder vetting, training, alert review, privacy, and family communication. If these processes are not yet established, label them as design commitments or questions being validated, not completed procedures.

Do not use fabricated testimonials, invented staff biographies, unverifiable partner logos, made-up response-time statistics, or stock badges suggesting certification.

### 7.8 Frequently asked questions

Use a short, keyboard-accessible accordion or a simple visible list. Questions should include:

- ¿CercaSalud ya está disponible?
- ¿En qué zonas funcionará?
- ¿Qué pasa cuando la persona presiona el botón?
- ¿Qué significa una alerta automática?
- ¿La alerta confirma una emergencia o un diagnóstico?
- ¿Esto reemplaza una enfermera o los servicios de emergencia?
- ¿Quién recibiría mis datos y para qué?
- ¿Cómo puedo enterarme del piloto?

Answers must use current, approved facts. If the answer is not known yet, say it is being defined and invite the visitor to register interest. Do not make up coverage or response details to make the page feel complete.

### 7.9 Interest form

**Purpose:** Collect enough information to follow up about validation or a pilot, with minimal friction and minimal sensitive data.

**Suggested fields:**

- Name.
- One contact method: email or WhatsApp number; allow the visitor to choose the preferred method.
- City and general area/municipality, not a full home address.
- Relationship to the older adult (optional, e.g. hijo/a, familiar, otra persona de confianza).
- Main interest or concern (optional, selectable broad categories plus `Prefiero conversarlo`).
- Explicit consent to be contacted about CercaSalud and a link to the privacy notice.

**Do not ask for:** diagnoses, medication lists, medical history, identity document number, exact location, emergency contact details, or detailed descriptions of health events.

**Form behavior:**

- Keep public form capture disabled until a reviewed privacy notice and a contact channel for data deletion requests are published. Enable collection only after the project owner confirms data access, provider handling, purpose, and retention. Treat activation as an explicit owner approval, not merely the presence of a URL.
- Explain why each requested field is needed.
- Mark required fields in text, not color alone.
- Validate on submit and beside the relevant field. Preserve valid entries after an error.
- Show a clear loading state and prevent accidental repeated submissions.
- On success, confirm that the form was received and explain the expected next step without promising a response date unless one is supported.
- On failure, keep the entered information and offer a retry path or an approved contact alternative.
- Never imply that submission is an emergency alert or that someone is monitoring the form in real time.
- Do not send personal information or form values to analytics tools.

**Suggested success copy:**

> Gracias por tu interés. Recibimos tus datos y los usaremos para compartir novedades sobre CercaSalud y conocer mejor las necesidades de las familias en tu zona.

Only say `recibimos` after the backend confirms a successful submission.

### 7.10 Footer

Include the CercaSalud name, a concise scope reminder, privacy notice, contact channel if one is approved, and copyright or business details if applicable. Do not add social links that have no maintained destination. Repeat that the website is not for emergency requests if the form is visible on the page.

## 8. Visual Direction

### Scene and mood

The page should feel like a capable, thoughtful service being considered in a real Venezuelan family's everyday life: daylight at home, a phone within reach, a relative checking in between work and other responsibilities. The mood is human, alert, and reassuring, not clinical or crisis-driven.

### Photography and imagery

- Prefer one strong, authentic-feeling photograph of an older adult and relative interacting naturally, with both shown as adults with agency.
- Do not use distressed seniors, staged hospital scenes, white-coat stock photography, isolated hands, or photos that imply a medical examination.
- If a real product photo exists, show the actual device accurately. Do not invent device capabilities, screen content, brand marks, or sensor readouts.
- Pair the photograph with a simple custom process diagram for the two alert routes and human verification. Use labels and shapes, not decorative medical graphs.
- Use actual project assets where available. If sourcing external images, verify the license and the image URL, optimize the file, and provide meaningful alt text.

### Color and surface

Use a distinctive, energetic but trustworthy palette rather than default hospital white-and-teal. A good starting direction is deep evergreen ink, a vivid leaf/citron accent, a warm coral accent used selectively, and a light neutral background. The dominant color should not be purple, beige, or dark blue. Maintain readable text contrast and never communicate an alert state through color alone.

Suggested semantic roles, to be tuned during implementation:

- `ink`: primary text and high-contrast dark surfaces.
- `paper`: page background, lightly tinted rather than pure white.
- `leaf`: primary brand accent and diagrams.
- `citron`: small emphasis areas and visual wayfinding, not long body text.
- `coral`: one high-priority action or human moment, not every button.
- `muted`: secondary text and dividers, still meeting contrast requirements.

Use broad color fields or image-led sections to create rhythm. Do not place every section in a rounded rectangle. Cards are reserved for genuinely discrete elements, if needed, with restrained corner radii and no nested cards.

### Typography

Choose a highly legible, distinctive sans-serif with a warm human voice and strong Spanish-language accent coverage. Avoid defaulting to Inter/Roboto/Arial or to an ornamental editorial serif. Use one purposeful family if it can carry the full hierarchy; otherwise pair a display face with a highly readable body face. Verify `á`, `é`, `í`, `ó`, `ú`, `ü`, and `ñ` render correctly.

Use clear scale and weight contrast: one assertive hero heading, compact section headings, comfortable body text, and small labels only where they aid scanning. Keep body line length around 65–75 characters on wide screens. Do not reduce body text below a comfortable mobile reading size or use letter spacing as a substitute for hierarchy.

### Layout and composition

- Make the service name and concept visible in the first viewport.
- Prefer a strong left-aligned text edge, deliberate asymmetry, and varied section pacing over a centered stack of identical modules.
- Use full-width section backgrounds or unframed content layouts for page sections. Do not nest cards or place the whole page inside a card.
- Let the process flow be scannable at a glance. Align labels, connectors, and steps consistently.
- Set stable widths and aspect ratios for photos and process graphics to avoid layout shift.
- Keep headings and controls from colliding or overflowing at narrow viewport widths and browser zoom.

## 9. Motion and Interaction

- Motion is optional and subordinate to comprehension. A brief, staggered entrance for the hero content is acceptable if it does not delay reading or interaction.
- Avoid animating layout properties, parallax that impairs reading, pulsing emergency-like alerts, and motion that suggests a device is monitoring the visitor.
- Respect `prefers-reduced-motion` and provide an equally complete static experience.
- Buttons, links, accordion controls, and form states must have visible hover, focus, active, disabled, and error states as applicable.
- Anchor navigation should not hide section headings beneath a sticky header.

## 10. Responsive Requirements

Design mobile first for visitors arriving from WhatsApp or social links on a mid-range phone and potentially inconsistent mobile data.

- At 320 CSS pixels wide, no horizontal scrolling, clipped copy, or overlapping controls.
- Primary action should remain easy to find and tap; use a comfortable touch target of at least 44 by 44 CSS pixels where practical.
- Reflow the hero, diagram, FAQ, and form into a logical single column. Do not merely shrink the desktop layout.
- Keep form labels visible; do not rely on placeholder text as the only label.
- Use input types and mobile keyboard hints appropriate to the field, including email and telephone.
- Photos should crop without cutting off faces, the watch, or the meaningful interaction.
- At tablet and desktop widths, preserve readable line lengths and avoid stretching body copy across the full viewport.
- Test at 320, 375, 768, 1024, and 1440 CSS pixels, plus 200% zoom.

## 11. Accessibility

- Use semantic landmarks and a logical heading hierarchy with one page-level `h1`.
- Ensure all functions work with keyboard alone and focus order follows the reading order.
- Provide strong, visible focus indicators and do not remove the browser outline without an equivalent.
- Ensure text and UI contrast meets WCAG 2.2 AA targets; verify the selected palette rather than assuming it passes.
- Provide alt text for informative imagery and empty alt text for purely decorative imagery.
- Make the alert diagram understandable without color and expose its sequence in text.
- Ensure form labels, required status, inline errors, and submission result are announced accessibly.
- Accordions must use buttons with expanded/collapsed state and support keyboard activation.
- Avoid autoplay audio/video and provide captions or transcripts for any meaningful video.

## 12. Performance, Privacy, and Trust

- Keep the page lightweight, with minimal client-side JavaScript and no unnecessary third-party embeds.
- Compress and correctly size responsive images; lazy-load below-the-fold imagery and do not lazy-load the main hero image if it is the largest content element.
- Avoid blocking font downloads; use a resilient system fallback and prevent font-loading layout shifts.
- Serve the page over HTTPS and explain data collection before submission.
- Collect only the contact and coarse location information required for validation. Define who can access submissions, how they will be used, and a retention/deletion policy before launch.
- Obtain explicit consent for follow-up and link a plain-language privacy notice. Do not pre-check consent.
- Do not load advertising trackers or record form values in analytics. Keep analytics events anonymous and aggregated where possible.
- Do not use an embedded chat widget that could be mistaken for real-time emergency monitoring.

## 13. Measurement and Validation

The page is a validation instrument. Measure whether the explanation is understood and whether visitors take a meaningful next step, not just page views.

Recommended anonymous events:

- `page_view`.
- `hero_cta_click`.
- `how_it_works_view`.
- `interest_form_start`.
- `interest_form_submit_success`.
- `interest_form_submit_error`.

Do not attach names, contact details, health details, or exact location to analytics events. Review aggregate form responses manually under the agreed privacy policy.

Pair quantitative activity with short user tests. Ask a small group of target relatives to visit the page and then explain, without prompting, what CercaSalud does, who responds, whether it is available now, and what it does not replace. Revise any section that produces a wrong or overconfident interpretation.

## 14. Content and Claims Review Checklist

Before publishing, the product owner must verify:

- Whether a device has been selected and what it actually supports.
- Whether automatic alerts exist, what can trigger them, and how uncertain they are.
- Whether a human monitoring process and responder network exist yet.
- Which areas, if any, can be served and under what conditions.
- What happens after a manual or automated alert, including failed contact and escalation.
- Which response-time statements, qualifications, partner names, and privacy practices can be substantiated.
- Whether local legal, privacy, consumer-protection, and healthcare review is needed for the planned claims and data collection.

If any answer is unknown, the page must say it is still being defined or omit the claim. Never fill gaps with plausible-sounding assumptions.

## 15. Definition of Done

The landing page specification is implemented successfully when:

- A target visitor can explain what CercaSalud is, who it is for, how the two alert routes work, and why the idea may help.
- The page clearly identifies the current validation/pre-launch status and does not imply live emergency coverage.
- Manual alerts and possible automated alerts both lead to an understandable human verification step in the explanation.
- No copy promises diagnosis, guaranteed response, prevention, 24/7 care, or unsupported availability.
- The page has a working, consent-based, minimal-interest form with loading, success, and error states.
- The form cannot be mistaken for an emergency contact channel and does not request medical records.
- The site works at the stated mobile widths, supports keyboard and assistive technology, and meets tested contrast requirements.
- Images are relevant, permissioned, optimized, and do not stereotype older adults.
- Performance and form analytics do not expose personal or health information.
- A comprehension test with target visitors produces accurate explanations rather than assumptions the service cannot support.
