# Stage 07 — Frontend Development

**بالعربية:** تطوير الواجهة الأمامية  
**رقم المرحلة:** 07 من 13

## 1. الهدف

تنفيذ مرحلة **Frontend Development** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

HTML, CSS, JavaScript/TypeScript, React/Next.js or Selected Framework, Responsive Development, Accessibility, Performance, Component Testing

## 3. يعتمد على (Previous Inputs)

Stages 04–06: approved wireframes, Figma design system/screens, technical architecture, API contracts and coding standards. Coordinate contracts with Stage 08.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Inspect repository, framework conventions and approved technical specifications.
2. Set up or follow the agreed frontend structure, routes, design tokens and reusable components.
3. Implement page templates to match approved Figma designs and content hierarchy.
4. Implement responsive layouts, navigation, forms, menus, tables and approved interactions.
5. Implement multilingual routing and correct RTL/LTR behavior when required.
6. Connect to approved APIs/CMS contracts using robust loading, error and empty states.
7. Apply accessibility, semantic HTML, image/font optimization and performance practices.
8. Run linting, type checks, component tests and cross-device visual review.

## 5. المخرجات المطلوبة (Deliverables)

- Implemented frontend source code
- Reusable component library
- Responsive page templates
- Connected UI interactions and API integration
- Frontend tests and build output
- Implementation notes and known issues

## 6. معايير القبول (Acceptance Criteria)

- [ ] Build and agreed code checks pass.
- [ ] Priority screens match approved designs within agreed tolerances.
- [ ] Responsive and RTL/LTR behavior is tested.
- [ ] No critical console/runtime errors remain.
- [ ] Key interactions and API states work or are explicitly documented as blocked.
- [ ] Code is maintainable and follows the agreed architecture.

## 7. Tips & Best Practices

- Inspect the existing repository before changing configuration or dependencies.
- Build shared components first, then assemble page templates.
- Use semantic HTML and accessible labels from the beginning.
- Do not hardcode CMS content if the architecture requires dynamic content.
- Compare implementation screenshots with Figma at agreed breakpoints.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior Frontend Engineer. Before coding, inspect the existing repository, current implementation, package scripts, framework version, design files and Stage 06 technical specification. Do not replace the stack or reorganize the project without a documented reason and approval when required.

Implement the approved Figma designs and wireframes using the selected stack and coding standards. Build reusable, maintainable components and page templates. Match typography, spacing, color, layout, assets and interaction states. Implement responsive behavior across agreed breakpoints, navigation, menus, forms, tables, search and other specified interactions. Support approved language routing and correct RTL/LTR behavior. Integrate only against documented backend/API contracts; coordinate contract changes with the backend owner.

Use semantic HTML, keyboard accessibility, clear labels, optimized images/fonts, appropriate loading strategies and performance-conscious code. Include loading, empty, error and success states. Run lint, type checks, tests and production build. Compare screenshots against approved designs and record deviations. Do not invent content or silently change UX decisions. Deliver source code, test evidence, build status, known issues and backend integration notes.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.
