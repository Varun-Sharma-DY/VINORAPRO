# ARCHITECTURE.md — Vinora Website

## 1. Project Objective

Build a professional, responsive, multi-page company website for Vinora LLP.

The website must communicate the company's expertise in custom ERP development and business automation.

The primary conversion objective is to generate qualified discovery-call bookings.

## 2. Proposed Website Pages

The following is the initial proposed structure. Final approval is required before implementation.

### Page 1: Home

Purpose: Communicate Vinora's value proposition and establish credibility.

Proposed sections:
1. Hero section with a strong positioning statement.
2. Supporting explanation of custom ERP and automation.
3. Business problems Vinora solves.
4. The difference between predefined ERP software and fully customised systems.
5. Core service overview.
6. How Vinora works.
7. Industries and business environments served.
8. Credibility and trust elements.
9. Frequently asked questions.
10. Final discovery-call CTA.

### Page 2: Services

Purpose: Explain the scope of Vinora's services.

Potential service categories:
- Custom ERP Development.
- Business Process Automation.
- Custom Software Development.
- System and API Integrations.
- Ongoing Software Support and Enhancement.

Each service should explain:
- What it involves.
- What business problem it solves.
- What the customer can expect.
- Relevant examples, when approved.

### Page 3: About

Purpose: Explain the company's philosophy and approach.

Potential sections:
- Company introduction.
- Why Vinora focuses on customisation.
- Our approach to solving operational problems.
- Our development philosophy.
- How we work with clients.

Do not invent company history, employee numbers or achievements.

### Page 4: Contact

Purpose: Convert interested visitors into qualified enquiries.

Potential elements:
- Discovery-call booking CTA.
- Contact form.
- Business email and phone number (to be supplied).
- Relevant company contact information.

### Future Page: Portfolio / Case Studies

Status: Deferred until the final phase.

The architecture should support future project case studies without requiring a major redesign.

No invented projects or fictional client results.

## 3. Navigation

Proposed navigation:

- Home
- Services
- About
- Contact
- Book a Discovery Call (primary CTA)

Navigation should be consistent across pages.

Mobile navigation must be fully functional and accessible.

## 4. Conversion Flow

Primary conversion:

Visitor → Discovery Call Booking → Business Discussion → Requirement Analysis → Demo → Proposal.

The website must distinguish between booking a discovery call and requesting a software demonstration.

A demo is a later stage in the sales process.

## 5. Contact and Booking Functionality

Final implementation details are pending approval.

Potential requirements:
- Contact enquiry form.
- Discovery-call scheduling integration.
- Form validation.
- Success and error states.
- Spam protection.
- Appropriate confirmation messages.
- Email notifications to the company.

Do not assume that a form is functional merely because it looks complete.

All integrations must be configured and tested before launch.

## 6. Technical Requirements

- Responsive design.
- Mobile-first considerations.
- Cross-browser compatibility.
- Semantic HTML.
- Accessible navigation and forms.
- Optimised images.
- Efficient CSS and JavaScript.
- Good Core Web Vitals.
- SEO-friendly page structure.
- Clean and maintainable code.

The final technology stack must be approved before development.

Do not introduce unnecessary frameworks, dependencies or infrastructure.

## 7. SEO Structure

Every public page should have:
- Unique page title.
- Meta description.
- Proper heading hierarchy.
- Descriptive image alt text.
- Canonical URL where appropriate.
- Social sharing metadata.

Additional requirements:
- sitemap.xml.
- robots.txt.
- Appropriate structured data.
- Search-engine-friendly URLs.

All business information used in structured data must be verified before publication.

## 8. Quality Assurance

Use Playwright for actual browser testing.

Minimum testing requirements:

### Desktop
- 1440px viewport.
- 1280px viewport.

### Mobile
- 375px viewport.
- 390px viewport.

### Functional Tests
- All navigation links.
- All CTAs.
- Mobile menu.
- Contact form.
- Booking functionality.
- Form validation.
- External links.
- Error and success states.

### Visual Tests
- No overlapping elements.
- No horizontal overflow.
- No cut-off content.
- Consistent spacing.
- Readable typography.
- Correct image scaling.
- Appropriate responsive behaviour.

### Accessibility
- Keyboard navigation.
- Visible focus states.
- Sufficient colour contrast.
- Semantic elements.
- Reduced-motion support.

## 9. Performance

Prioritise:
- Fast initial page loading.
- Optimised image formats.
- Minimal unnecessary JavaScript.
- Lightweight animations.
- Lazy loading where appropriate.
- Avoiding unnecessary third-party scripts.

Visual effects must not compromise performance.

## 10. Development Restrictions

- Do not begin implementation before architecture and design approval.
- Do not introduce portfolio content prematurely.
- Do not invent business details.
- Do not introduce unapproved third-party integrations.
- Do not compromise existing brand identity.
- Do not add unnecessary complexity.
- Document major technical decisions.

## 11. Final Acceptance Criteria

The website is ready for launch only when:

- All approved pages are implemented.
- The visual direction is consistent.
- Content is approved.
- Responsive layouts work correctly.
- Navigation and CTAs function.
- Forms and booking integrations work.
- Browser testing is completed.
- SEO essentials are implemented.
- No critical functional or visual issues remain.
- The owner has approved the final website.
