# Stage 04 — UX Planning & Wireframing

**بالعربية:** تخطيط تجربة المستخدم والوايرفريم  
**رقم المرحلة:** 04 من 13

## 1. الهدف

تنفيذ مرحلة **UX Planning & Wireframing** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

UX Research, Information Architecture, User Journey Mapping, Wireframing, Content Layout, Interaction Design, Conversion UX, Accessibility

## 3. يعتمد على (Previous Inputs)

Stages 01–03: audience research, approved sitemap, page inventory, content briefs and available final/near-final copy.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Translate the site architecture into clear navigation and page relationships.
2. Define primary user journeys and the key tasks users need to complete.
3. Group pages into reusable page templates based on content purpose and interaction needs.
4. Create low-fidelity wireframes for each unique template using approved content and hierarchy.
5. Define placement and behavior of navigation, breadcrumbs, headings, tables, forms, CTAs, trust elements and related content.
6. Specify mobile-first behavior, responsive changes, empty/error/success states and accessibility considerations.
7. Review wireframes against search intent, content completeness and internal-linking requirements.

## 5. المخرجات المطلوبة (Deliverables)

- Information architecture and navigation map
- User flows and journey maps
- Page-template inventory
- Low-fidelity desktop/mobile wireframes
- Component and interaction requirements
- UX annotations and open decisions

## 6. معايير القبول (Acceptance Criteria)

- [ ] All priority page templates are represented.
- [ ] Wireframes use real or approved representative content, not generic filler.
- [ ] Navigation and user journeys are understandable and testable.
- [ ] Important content and internal links have logical locations.
- [ ] Responsive and RTL/LTR requirements are specified.

## 7. Tips & Best Practices

- Design templates, not a separate unique layout for every article with the same content structure.
- Validate page hierarchy before visual decoration.
- Avoid adding sections only because competitors have them; each element must serve a user need.
- Make the main page task clear and reduce unnecessary interaction steps.
- Show realistic content lengths to prevent later layout problems.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior UX Designer and Information Architect. Review the approved Stage 01 audience research, Stage 02 sitemap and internal-linking plan, and Stage 03 content briefs and copy. Identify user goals and convert the approved architecture into practical user journeys, navigation and reusable page templates.

Create low-fidelity wireframes for every unique page template. Use the actual approved content or representative content with realistic length. Define the order and placement of headings, text, images, tables, cards, forms, CTAs, breadcrumbs, trust elements, FAQs and related content. Specify navigation behavior, user flows, responsive layout changes, mobile navigation, accessibility needs, and empty, loading, error, success, hover and focus states where applicable.

Explain why key sections appear in their selected positions. Ensure the design supports the intended search intent and preserves useful internal-link relationships. Do not create visual styling or change approved content strategy at this stage. Identify content gaps or UX conflicts and send them back for resolution rather than hiding them. Deliver wireframes, annotations, user flows and a page-template map ready for UI design.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.
