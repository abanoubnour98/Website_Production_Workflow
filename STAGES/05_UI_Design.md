# Stage 05 — UI Design

**بالعربية:** تصميم واجهة المستخدم ونظام التصميم  
**رقم المرحلة:** 05 من 13

## 1. الهدف

تنفيذ مرحلة **UI Design** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

UI Design, Visual Design, Design Systems, Figma, Typography, Color Theory, Responsive Design, RTL/LTR Design, Accessibility, Prototyping

## 3. يعتمد على (Previous Inputs)

Stages 01–04: brand guidelines, approved wireframes, user journeys, page templates and approved content.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Establish visual direction based on brand requirements, audience and product positioning.
2. Define color, typography, spacing, grids, borders, shadows, iconography and design tokens.
3. Build reusable components and component variants with documented states.
4. Create high-fidelity screens for each unique page template using real content.
5. Create desktop, tablet and mobile designs and account for content length differences.
6. Create correctly adapted RTL and LTR variants for every required language.
7. Prototype important flows and specify interactions, transitions and responsive behavior.
8. Prepare developer handoff with measurements, tokens, assets and component behavior.

## 5. المخرجات المطلوبة (Deliverables)

- Visual direction and design principles
- Design tokens and component library
- High-fidelity Figma screens
- Desktop/tablet/mobile layouts
- RTL/LTR variants
- Interactive prototype
- Developer handoff and asset specification

## 6. معايير القبول (Acceptance Criteria)

- [ ] All required page templates and language variants are covered.
- [ ] Screens use approved content and reflect wireframes or documented UX changes.
- [ ] Components, typography, spacing and states are consistent.
- [ ] Responsive layouts are explicit, not just scaled desktop screenshots.
- [ ] Accessibility and contrast have been checked.
- [ ] Developers have sufficient handoff detail to implement the design.

## 7. Tips & Best Practices

- Create components and tokens before duplicating screens.
- Use realistic content; placeholder text often hides layout failures.
- RTL is a layout and interaction requirement, not merely right-aligning text.
- Mirror only elements whose meaning is directional; keep brand marks and universal icons correct.
- Design loading, empty, disabled, error and success states where the interface needs them.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior UI Designer, Visual Design Lead and Design Systems Specialist. Use the approved Stage 01–04 research, brand guidelines, content, user flows and wireframes. Create a professional visual system appropriate to the brand and audience.

Define design tokens for color, typography, spacing, grid, borders, elevation, iconography and breakpoints. Build reusable components with documented variants and states. Produce high-fidelity screens for every approved unique page template using real approved content. Design desktop, tablet and mobile layouts. For multilingual projects, create genuine RTL and LTR variants, checking text flow, alignment, navigation, icons, numbers, tables, forms and component behavior.

Prototype the most important user journeys. Include hover, focus, active, disabled, loading, empty, error and success states where relevant. Maintain accessibility, readable text, sufficient contrast and consistent visual hierarchy. Do not add unsupported business claims or deceptive conversion patterns.

Prepare implementation-ready developer handoff: Figma pages and frames, component names, design tokens, asset exports, responsive rules, interaction annotations and known exceptions. Record any deviation from the approved wireframes and explain its UX rationale.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.
