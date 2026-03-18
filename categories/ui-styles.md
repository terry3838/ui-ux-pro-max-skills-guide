# UI 스타일 (UI Styles)

## 카테고리 소개
제품의 시각적 방향성을 결정하는 스타일 가이드입니다.

### Minimalism & Swiss Style
- **특징/키워드**: Clean, simple, spacious, functional, white space, high contrast, geometric, sans-serif, grid-based, essential
- **추천 서비스**: Enterprise apps, dashboards, documentation sites, SaaS platforms, professional tools
- **체크리스트**: ☐ Grid-based layout 12-16 columns, ☐ Typography hierarchy clear, ☐ No unnecessary decorations, ☐ WCAG AAA contrast verified, ☐ Mobile responsive grid
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Minimalism & Swiss Style" --desc "Design a minimalist landing page. Use: white space, geometric layouts, sans-serif fonts, high contrast, grid-based structure, essential elements only. Avoid shadows and gradients. Focus on clarity and functionality."`

### Neumorphism
- **특징/키워드**: Soft UI, embossed, debossed, convex, concave, light source, subtle depth, rounded (12-16px), monochromatic
- **추천 서비스**: Health/wellness apps, meditation platforms, fitness trackers, minimal interaction UIs
- **체크리스트**: ☐ Rounded corners 12-16px consistent, ☐ Multiple shadow layers (2-3), ☐ Pastel color verified, ☐ Monochromatic palette checked, ☐ Press animation smooth 150ms
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Neumorphism" --desc "Create a neumorphic UI with soft 3D effects. Use light pastels, rounded corners (12-16px), subtle soft shadows (multiple layers), no hard lines, monochromatic color scheme with light/dark variations. Embossed/debossed effect on interactive elements."`

### Glassmorphism
- **특징/키워드**: Frosted glass, transparent, blurred background, layered, vibrant background, light source, depth, multi-layer
- **추천 서비스**: Modern SaaS, financial dashboards, high-end corporate, lifestyle apps, modal overlays, navigation
- **체크리스트**: ☐ Backdrop-filter blur 10-20px, ☐ Translucent white 15-30% opacity, ☐ Subtle border 1px light, ☐ Vibrant background verified, ☐ Text contrast 4.5:1 checked
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Glassmorphism" --desc "Design a glassmorphic interface with frosted glass effect. Use backdrop blur (10-20px), translucent overlays (rgba 10-30% opacity), vibrant background colors, subtle borders, light source reflection, layered depth. Perfect for modern overlays and cards."`

### Brutalism
- **특징/키워드**: Raw, unpolished, stark, high contrast, plain text, default fonts, visible borders, asymmetric, anti-design
- **추천 서비스**: Design portfolios, artistic projects, counter-culture brands, editorial/media sites, tech blogs
- **체크리스트**: ☐ No border-radius (0px), ☐ No transitions (instant), ☐ Bold typography (700+), ☐ Pure primary colors used, ☐ Visible grid/borders, ☐ Asymmetric layout intentional
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Brutalism" --desc "Create a brutalist design with raw, unpolished, stark aesthetic. Use pure primary colors (red, blue, yellow), black & white, no smooth transitions (instant), sharp corners, bold large typography, visible grid lines, default system fonts, intentional 'broken' design elements."`

### 3D & Hyperrealism
- **특징/키워드**: Depth, realistic textures, 3D models, spatial navigation, tactile, skeuomorphic elements, rich detail, immersive
- **추천 서비스**: Gaming, product showcase, immersive experiences, high-end e-commerce, architectural viz, VR/AR
- **체크리스트**: ☐ WebGL/Three.js integrated, ☐ 3D models loaded, ☐ Parallax 3-5 layers, ☐ Realistic lighting verified, ☐ Complex shadows rendered, ☐ Physics animation smooth 300-400ms
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "3D & Hyperrealism" --desc "Build an immersive 3D interface using realistic textures, 3D models (Three.js/Babylon.js), complex shadows, realistic lighting, parallax scrolling (3-5 layers), physics-based motion. Include skeuomorphic elements with tactile detail."`

### Vibrant & Block-based
- **특징/키워드**: Bold, energetic, playful, block layout, geometric shapes, high color contrast, duotone, modern, energetic
- **추천 서비스**: Startups, creative agencies, gaming, social media, youth-focused, entertainment, consumer
- **체크리스트**: ☐ Block layout with 48px+ gaps, ☐ Large typography 32px+, ☐ 4-6 vibrant colors max, ☐ Animated patterns active, ☐ Scroll-snap enabled, ☐ High contrast verified (7:1+)
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Vibrant & Block-based" --desc "Design an energetic, vibrant interface with bold block layouts, geometric shapes, high color contrast, large typography (32px+), animated background patterns, duotone effects. Perfect for startups and youth-focused apps. Use 4-6 contrasting colors from complementary/triadic schemes."`

### Dark Mode (OLED)
- **특징/키워드**: Dark theme, low light, high contrast, deep black, midnight blue, eye-friendly, OLED, night mode, power efficient
- **추천 서비스**: Night-mode apps, coding platforms, entertainment, eye-strain prevention, OLED devices, low-light
- **체크리스트**: ☐ Deep black #000000 or #121212, ☐ Vibrant neon accents used, ☐ Text contrast 7:1+, ☐ Minimal glow effects, ☐ OLED power optimization, ☐ No white (#FFFFFF) background
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Dark Mode (OLED)" --desc "Create an OLED-optimized dark interface with deep black (#000000), dark grey (#121212), midnight blue accents. Use minimal glow effects, vibrant neon accents (green, blue, gold, purple), high contrast text. Optimize for eye comfort and OLED power saving."`

### Accessible & Ethical
- **특징/키워드**: High contrast, large text (16px+), keyboard navigation, screen reader friendly, WCAG compliant, focus state, semantic
- **추천 서비스**: Government, healthcare, education, inclusive products, large audience, legal compliance, public
- **체크리스트**: ☐ WCAG AAA verified, ☐ 7:1+ contrast checked, ☐ Keyboard navigation tested, ☐ Screen reader tested, ☐ Focus visible 3-4px, ☐ Semantic HTML used, ☐ Touch targets 44x44px
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Accessible & Ethical" --desc "Design with WCAG AAA compliance. Include: high contrast (7:1+), large text (16px+), keyboard navigation, screen reader compatibility, focus states visible (3-4px ring), semantic HTML, ARIA labels, skip links, reduced motion support (prefers-reduced-motion), 44x44px touch targets."`

### Claymorphism
- **특징/키워드**: Soft 3D, chunky, playful, toy-like, bubbly, thick borders (3-4px), double shadows, rounded (16-24px)
- **추천 서비스**: Educational apps, children's apps, SaaS platforms, creative tools, fun-focused, onboarding, casual games
- **체크리스트**: ☐ Border-radius 16-24px, ☐ Thick borders 3-4px, ☐ Double shadows (inner+outer), ☐ Pastel colors used, ☐ Soft bounce animations, ☐ Playful interactions
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Claymorphism" --desc "Design a playful, toy-like interface with soft 3D, chunky elements, bubbly aesthetic, rounded edges (16-24px), thick borders (3-4px), double shadows (inner + outer), pastel colors, smooth animations. Perfect for children's apps and creative tools."`

### Aurora UI
- **특징/키워드**: Vibrant gradients, smooth blend, Northern Lights effect, mesh gradient, luminous, atmospheric, abstract
- **추천 서비스**: Modern SaaS, creative agencies, branding, music platforms, lifestyle, premium products, hero sections
- **체크리스트**: ☐ Mesh/flowing gradients applied, ☐ 8-12s animation loop, ☐ Complementary colors used, ☐ Smooth color transitions, ☐ Iridescent effect subtle, ☐ Text contrast verified
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Aurora UI" --desc "Create a vibrant gradient interface inspired by Northern Lights with mesh gradients, smooth color blends, flowing animations. Use complementary color pairs (blue-orange, purple-yellow), flowing background gradients, subtle continuous animations (8-12s loops), iridescent effects."`

### Retro-Futurism
- **특징/키워드**: Vintage sci-fi, 80s aesthetic, neon glow, geometric patterns, CRT scanlines, pixel art, cyberpunk, synthwave
- **추천 서비스**: Gaming, entertainment, music platforms, tech brands, artistic projects, nostalgic, cyberpunk
- **체크리스트**: ☐ Neon colors used, ☐ CRT scanlines effect, ☐ Glitch animations active, ☐ Monospace font, ☐ Deep black background, ☐ Glow effects applied, ☐ 80s patterns present
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Retro-Futurism" --desc "Build a retro-futuristic (cyberpunk/vaporwave) interface with neon colors (blue, pink, cyan), deep black background, 80s aesthetic, CRT scanlines, glitch effects, neon glow text/borders, monospace fonts, geometric patterns. Use neon text-shadow and animated glitch effects."`

### Flat Design
- **특징/키워드**: 2D, minimalist, bold colors, no shadows, clean lines, simple shapes, typography-focused, modern, icon-heavy
- **추천 서비스**: Web apps, mobile apps, cross-platform, startup MVPs, user-friendly, SaaS, dashboards, corporate
- **체크리스트**: ☐ No shadows/gradients, ☐ 4-6 solid colors max, ☐ Clean lines consistent, ☐ Simple shapes used, ☐ Icon-heavy layout, ☐ High saturation colors, ☐ Fast loading verified
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Flat Design" --desc "Create a flat, 2D interface with bold colors, no shadows/gradients, clean lines, simple geometric shapes, icon-heavy, typography-focused, minimal ornamentation. Use 4-6 solid, bright colors in a limited palette with high saturation."`

### Skeuomorphism
- **특징/키워드**: Realistic, texture, depth, 3D appearance, real-world metaphors, shadows, gradients, tactile, detailed, material
- **추천 서비스**: Legacy apps, gaming, immersive storytelling, premium products, luxury, realistic simulations, education
- **체크리스트**: ☐ Realistic textures applied, ☐ Complex gradients 8-12 stops, ☐ Multi-layer shadows, ☐ Texture overlays present, ☐ Tactile animations smooth, ☐ Depth effect pronounced
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Skeuomorphism" --desc "Design a realistic, textured interface with 3D depth, real-world metaphors (leather, wood, metal), complex gradients (8-12 stops), realistic shadows, grain/texture overlays, tactile press animations. Perfect for premium/luxury products."`

### Liquid Glass
- **특징/키워드**: Flowing glass, morphing, smooth transitions, fluid effects, translucent, animated blur, iridescent, chromatic aberration
- **추천 서비스**: Premium SaaS, high-end e-commerce, creative platforms, branding experiences, luxury portfolios
- **체크리스트**: ☐ Morphing animations 400-600ms, ☐ Chromatic aberration applied, ☐ Dynamic blur active, ☐ Iridescent gradients, ☐ Smooth color transitions, ☐ Premium feel achieved
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Liquid Glass" --desc "Create a premium liquid glass effect with morphing shapes, flowing animations, chromatic aberration, iridescent gradients, smooth 400-600ms transitions. Use SVG morphing for shape changes, dynamic blur, smooth color transitions creating a fluid, premium feel."`

### Motion-Driven
- **특징/키워드**: Animation-heavy, microinteractions, smooth transitions, scroll effects, parallax, entrance anim, page transitions
- **추천 서비스**: Portfolio sites, storytelling platforms, interactive experiences, entertainment apps, creative, SaaS
- **체크리스트**: ☐ Scroll animations active, ☐ Parallax 3-5 layers, ☐ Entrance animations smooth, ☐ Page transitions fluid, ☐ GPU accelerated, ☐ Prefers-reduced-motion respected
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Motion-Driven" --desc "Build an animation-heavy interface with scroll-triggered animations, microinteractions, parallax scrolling (3-5 layers), smooth transitions (300-400ms), entrance animations, page transitions. Use Intersection Observer for scroll effects, transform for performance, GPU acceleration."`

### Micro-interactions
- **특징/키워드**: Small animations, gesture-based, tactile feedback, subtle animations, contextual interactions, responsive
- **추천 서비스**: Mobile apps, touchscreen UIs, productivity tools, user-friendly, consumer apps, interactive components
- **체크리스트**: ☐ Micro-animations 50-100ms, ☐ Gesture-responsive, ☐ Tactile feedback visual/haptic, ☐ Loading spinners smooth, ☐ Success/error states clear, ☐ Hover effects subtle
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Micro-interactions" --desc "Design with delightful micro-interactions: small 50-100ms animations, gesture-based responses, tactile feedback, loading spinners, success/error states, subtle hover effects, haptic feedback triggers for mobile. Focus on responsive, contextual interactions."`

### Inclusive Design
- **특징/키워드**: Accessible, color-blind friendly, high contrast, haptic feedback, voice interaction, screen reader, WCAG AAA, universal
- **추천 서비스**: Public services, education, healthcare, finance, government, accessible consumer, inclusive
- **체크리스트**: ☐ WCAG AAA verified, ☐ 7:1+ contrast all text, ☐ Keyboard accessible (Tab/Enter), ☐ Screen reader tested, ☐ Focus visible 3-4px, ☐ No color-only indicators, ☐ Haptic fallback
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Inclusive Design" --desc "Design for universal accessibility: high contrast (7:1+), large text (16px+), keyboard-only navigation, screen reader optimization, WCAG AAA compliance, symbol-based color indicators (not color-only), haptic feedback, voice interaction support, reduced motion options."`

### Zero Interface
- **특징/키워드**: Minimal visible UI, voice-first, gesture-based, AI-driven, invisible controls, predictive, context-aware, ambient
- **추천 서비스**: Voice assistants, AI platforms, future-forward UX, smart home, contextual computing, ambient experiences
- **체크리스트**: ☐ Voice commands responsive, ☐ Gesture detection active, ☐ AI predictions hidden/revealed, ☐ Progressive disclosure working, ☐ Minimal visible UI, ☐ Smart suggestions contextual
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Zero Interface" --desc "Create a voice-first, gesture-based, AI-driven interface with minimal visible UI, progressive disclosure, voice recognition UI, gesture detection, AI predictions, smart suggestions, context-aware actions. Hide controls until needed."`

### Soft UI Evolution
- **특징/키워드**: Evolved soft UI, better contrast, modern aesthetics, subtle depth, accessibility-focused, improved shadows, hybrid
- **추천 서비스**: Modern enterprise apps, SaaS platforms, health/wellness, modern business tools, professional, hybrid
- **체크리스트**: ☐ Improved contrast AA/AAA, ☐ Soft shadows modern, ☐ Border-radius 8-12px, ☐ Animations 200-300ms, ☐ Focus states visible, ☐ Color hierarchy clear
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Soft UI Evolution" --desc "Design evolved neumorphism with improved contrast (WCAG AA+), modern aesthetics, subtle depth, accessibility focus. Use soft shadows (softer than flat but clearer than pure neumorphism), better color hierarchy, improved focus states, modern 200-300ms animations."`

### Hero-Centric Design
- **특징/키워드**: Large hero section, compelling headline, high-contrast CTA, product showcase, value proposition, hero image/video, dramatic visual
- **추천 서비스**: SaaS landing pages, product launches, service landing pages, B2B platforms, tech companies
- **체크리스트**: ☐ Hero section full viewport height, ☐ Headline visible above fold, ☐ CTA button high contrast, ☐ Background image optimized (WebP), ☐ Text readable on background, ☐ Mobile responsive layout
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Hero-Centric Design" --desc "Design a hero-centric landing page. Use: full-width hero section, compelling headline (60-80 chars), high-contrast CTA button, product screenshot or video, value proposition above fold, gradient or image background, clear visual hierarchy."`

### Conversion-Optimized
- **특징/키워드**: Form-focused, minimalist design, single CTA focus, high contrast, urgency elements, trust signals, social proof, clear value
- **추천 서비스**: E-commerce product pages, free trial signups, lead generation, SaaS pricing pages, limited-time offers
- **체크리스트**: ☐ Single primary CTA visible, ☐ Form fields minimal (3-5), ☐ Trust badges present, ☐ Social proof above fold, ☐ Mobile form optimized, ☐ Loading states implemented, ☐ A/B test ready
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Conversion-Optimized" --desc "Design a conversion-optimized landing page. Use: single primary CTA, minimal distractions, trust badges, urgency elements (limited time), social proof (testimonials), clear value proposition, form above fold, progress indicators."`

### Feature-Rich Showcase
- **특징/키워드**: Multiple feature sections, grid layout, benefit cards, visual feature demonstrations, interactive elements, problem-solution pairs
- **추천 서비스**: Enterprise SaaS, software tools landing pages, platform services, complex product explanations, B2B products
- **체크리스트**: ☐ Feature grid responsive, ☐ Icons consistent style, ☐ Card hover effects smooth, ☐ Alternating sections contrast, ☐ Benefits clearly stated, ☐ Mobile stacks properly
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Feature-Rich Showcase" --desc "Design a feature showcase landing page. Use: grid layout for features (3-4 columns), feature cards with icons, benefit-focused copy, alternating sections, comparison tables, interactive demos, problem-solution pairs."`

### Minimal & Direct
- **특징/키워드**: Minimal text, white space heavy, single column layout, direct messaging, clean typography, visual-centric, fast-loading
- **추천 서비스**: Simple service landing pages, indie products, consulting services, micro SaaS, freelancer portfolios
- **체크리스트**: ☐ Single column centered, ☐ White space generous, ☐ One primary CTA only, ☐ No decorative images, ☐ Page weight < 500KB, ☐ Load time < 2s
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Minimal & Direct" --desc "Design a minimal direct landing page. Use: single column layout, maximum white space, essential content only, one CTA, clean typography, no decorative elements, fast loading, direct messaging."`

### Social Proof-Focused
- **특징/키워드**: Testimonials prominent, client logos displayed, case studies sections, reviews/ratings, user avatars, success metrics, credibility markers
- **추천 서비스**: B2B SaaS, professional services, premium products, e-commerce conversion pages, established brands
- **체크리스트**: ☐ Testimonials with real photos, ☐ Logo grid 6-12 logos, ☐ Star ratings accessible, ☐ Metrics animated on scroll, ☐ Case studies linked, ☐ Mobile carousel works
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Social Proof-Focused" --desc "Design a social proof landing page. Use: testimonials with photos, client logos grid, case study cards, review ratings (stars), user count metrics, success stories, trust indicators, before/after comparisons."`

### Interactive Product Demo
- **특징/키워드**: Embedded product mockup/video, interactive elements, product walkthrough, step-by-step guides, hover-to-reveal features, embedded demos
- **추천 서비스**: SaaS platforms, tool/software products, productivity apps landing pages, developer tools, productivity software
- **체크리스트**: ☐ Demo video loads fast, ☐ Fallback for no-JS, ☐ Step indicators clear, ☐ Hover states obvious, ☐ Mobile touch friendly, ☐ Demo CTA prominent
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Interactive Product Demo" --desc "Design an interactive demo landing page. Use: embedded product mockup, video walkthrough, step-by-step guide, hover-to-reveal features, live demo button, screenshot carousel, feature highlights on interaction."`

### Trust & Authority
- **특징/키워드**: Certificates/badges displayed, expert credentials, case studies with metrics, before/after comparisons, industry recognition, security badges
- **추천 서비스**: Healthcare/medical landing pages, financial services, enterprise software, premium/luxury products, legal services
- **체크리스트**: ☐ Security badges visible, ☐ Certifications verified, ☐ Metrics with sources, ☐ Professional imagery, ☐ Guarantee clearly stated, ☐ Contact info accessible
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Trust & Authority" --desc "Design a trust-focused landing page. Use: certification badges, security indicators, expert credentials, industry awards, case study metrics, compliance logos (GDPR, SOC2), guarantee badges, professional photography."`

### Storytelling-Driven
- **특징/키워드**: Narrative flow, visual story progression, section transitions, consistent character/brand voice, emotional messaging, journey visualization
- **추천 서비스**: Brand/startup stories, mission-driven products, premium/lifestyle brands, documentary-style products, educational
- **체크리스트**: ☐ Story flows naturally, ☐ Scroll reveals smooth, ☐ Sections timed well, ☐ Emotional hooks present, ☐ Mobile story readable, ☐ Skip option available
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Storytelling-Driven" --desc "Design a storytelling landing page. Use: narrative flow sections, scroll-triggered reveals, chapter-like structure, emotional imagery, brand journey visualization, founder story, mission statement, timeline progression."`

### Data-Dense Dashboard
- **특징/키워드**: Multiple charts/widgets, data tables, KPI cards, minimal padding, grid layout, space-efficient, maximum data visibility
- **추천 서비스**: Business intelligence dashboards, financial analytics, enterprise reporting, operational dashboards, data warehousing
- **체크리스트**: ☐ Grid layout 12 columns, ☐ KPI cards responsive, ☐ Tables sortable, ☐ Filters functional, ☐ Loading states for data, ☐ Export functionality
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Data-Dense Dashboard" --desc "Design a data-dense dashboard. Use: multiple chart widgets, KPI cards row, data tables with sorting, minimal padding (8-12px), efficient grid layout, filter sidebar, dense but readable typography, maximum information density."`

### Heat Map & Heatmap Style
- **특징/키워드**: Color-coded grid/matrix, data intensity visualization, geographical heat maps, correlation matrices, cell-based representation, gradient coloring
- **추천 서비스**: Geographical analysis, performance matrices, correlation analysis, user behavior heatmaps, temperature/intensity data
- **체크리스트**: ☐ Color scale clear, ☐ Legend visible, ☐ Tooltips informative, ☐ Colorblind alternatives, ☐ Zoom/pan for geo, ☐ Performance for large data
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Heat Map & Heatmap Style" --desc "Design a heatmap visualization. Use: color gradient scale (cool to hot), cell-based grid, intensity legend, hover tooltips, geographic or matrix layout, divergent color scheme for +/- values, accessible color alternatives."`

### Executive Dashboard
- **특징/키워드**: High-level KPIs, large key metrics, minimal detail, summary view, trend indicators, at-a-glance insights, executive summary
- **추천 서비스**: C-suite dashboards, business summary reports, decision-maker dashboards, strategic planning views
- **체크리스트**: ☐ KPIs 4-6 maximum, ☐ Trends visible, ☐ Status colors clear, ☐ One-page view, ☐ Mobile simplified, ☐ Print-friendly layout
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Executive Dashboard" --desc "Design an executive dashboard. Use: large KPI cards (4-6 max), trend sparklines, high-level summary only, clean layout with white space, traffic light indicators (red/yellow/green), at-a-glance insights, minimal detail."`

### Real-Time Monitoring
- **특징/키워드**: Live data updates, status indicators, alert notifications, streaming data visualization, active monitoring, streaming charts
- **추천 서비스**: System monitoring dashboards, DevOps dashboards, real-time analytics, stock market dashboards, live event tracking
- **체크리스트**: ☐ Live updates working, ☐ Alert sounds optional, ☐ Connection status shown, ☐ Auto-refresh indicated, ☐ Critical alerts prominent, ☐ Offline fallback
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Real-Time Monitoring" --desc "Design a real-time monitoring dashboard. Use: live status indicators (pulsing), streaming charts, alert notifications, connection status, auto-refresh indicators, critical alerts prominent, system health overview."`

### Drill-Down Analytics
- **특징/키워드**: Hierarchical data exploration, expandable sections, interactive drill-down paths, summary-to-detail flow, context preservation
- **추천 서비스**: Sales analytics, product analytics, funnel analysis, multi-dimensional data exploration, business intelligence
- **체크리스트**: ☐ Breadcrumbs clear, ☐ Back navigation easy, ☐ Expand animation smooth, ☐ Context preserved, ☐ Mobile drill works, ☐ Deep links supported
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Drill-Down Analytics" --desc "Design a drill-down analytics dashboard. Use: breadcrumb navigation, expandable sections, summary-to-detail flow, back button prominent, level indicators, context preservation, hierarchical data display."`

### Comparative Analysis Dashboard
- **특징/키워드**: Side-by-side comparisons, period-over-period metrics, A/B test results, regional comparisons, performance benchmarks
- **추천 서비스**: Period-over-period reporting, A/B test dashboards, market comparison, competitive analysis, regional performance
- **체크리스트**: ☐ Period selector works, ☐ Deltas calculated, ☐ Colors meaningful, ☐ Benchmarks shown, ☐ Mobile stacks properly, ☐ Export comparison
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Comparative Analysis Dashboard" --desc "Design a comparison dashboard. Use: side-by-side metrics, period selectors (vs last month), delta indicators (+/-), benchmark lines, A/B comparison tables, winning/losing highlights, percentage change badges."`

### Predictive Analytics
- **특징/키워드**: Forecast lines, confidence intervals, trend projections, scenario modeling, AI-driven insights, anomaly detection visualization
- **추천 서비스**: Forecasting dashboards, anomaly detection systems, trend prediction dashboards, AI-powered analytics, budget planning
- **체크리스트**: ☐ Forecast line distinct, ☐ Confidence bands visible, ☐ Anomalies highlighted, ☐ Scenarios switchable, ☐ Predictions dated, ☐ Accuracy shown
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Predictive Analytics" --desc "Design a predictive analytics dashboard. Use: forecast lines (dashed), confidence intervals (shaded bands), trend projections, anomaly highlights, scenario toggles, AI insight cards, probability indicators."`

### User Behavior Analytics
- **특징/키워드**: Funnel visualization, user flow diagrams, conversion tracking, engagement metrics, user journey mapping, cohort analysis
- **추천 서비스**: Conversion funnel analysis, user journey tracking, engagement analytics, cohort analysis, retention tracking
- **체크리스트**: ☐ Funnel stages clear, ☐ Flow diagram readable, ☐ Conversions calculated, ☐ Cohorts comparable, ☐ Retention trends visible, ☐ Privacy compliant
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "User Behavior Analytics" --desc "Design a user behavior analytics dashboard. Use: funnel visualization, user flow diagrams (Sankey), conversion metrics, engagement heatmaps, cohort tables, retention curves, session replay indicators."`

### Financial Dashboard
- **특징/키워드**: Revenue metrics, profit/loss visualization, budget tracking, financial ratios, portfolio performance, cash flow, audit trail
- **추천 서비스**: Financial reporting, accounting dashboards, portfolio tracking, budget monitoring, banking analytics
- **체크리스트**: ☐ Currency formatted, ☐ Decimals consistent, ☐ P&L clear, ☐ Budget variance shown, ☐ Audit trail complete, ☐ Export to Excel
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Financial Dashboard" --desc "Design a financial dashboard. Use: revenue/expense charts, profit margins, budget vs actual, cash flow waterfall, financial ratios, audit trail table, currency formatting, period comparisons."`

### Sales Intelligence Dashboard
- **특징/키워드**: Deal pipeline, sales metrics, territory performance, sales rep leaderboard, win-loss analysis, quota tracking, forecast accuracy
- **추천 서비스**: CRM dashboards, sales management, opportunity tracking, performance management, quota planning
- **체크리스트**: ☐ Pipeline stages shown, ☐ Deals draggable, ☐ Quotas visualized, ☐ Rankings updated, ☐ Territory clickable, ☐ CRM integration
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Sales Intelligence Dashboard" --desc "Design a sales intelligence dashboard. Use: pipeline funnel, deal cards (kanban), quota gauges, leaderboard table, territory map, win/loss ratios, forecast accuracy, activity timeline."`

### Neubrutalism
- **특징/키워드**: Bold borders, black outlines, primary colors, thick shadows, no gradients, flat colors, 45° shadows, playful, Gen Z
- **추천 서비스**: Gen Z brands, startups, creative agencies, Figma-style apps, Notion-style interfaces, tech blogs
- **체크리스트**: ☐ Hard borders (2-4px), ☐ Hard offset shadows, ☐ High saturation colors, ☐ Bold typography, ☐ No blurs/gradients, ☐ Distinctive 'ugly-cute' look
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Neubrutalism" --desc "Design a neubrutalist interface. Use: high contrast, hard black borders (3px+), bright pop colors, no blur, sharp or slightly rounded corners, bold typography, hard shadows (offset 4px 4px), raw aesthetic but functional."`

### Bento Box Grid
- **특징/키워드**: Modular cards, asymmetric grid, varied sizes, Apple-style, dashboard tiles, negative space, clean hierarchy, cards
- **추천 서비스**: Dashboards, product pages, portfolios, Apple-style marketing, feature showcases, SaaS
- **체크리스트**: ☐ Grid responsive (4→2→1 cols), ☐ Card spans varied, ☐ Rounded corners consistent, ☐ Shadows subtle, ☐ Content fits cards, ☐ Hover scale (1.02)
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Bento Box Grid" --desc "Design a Bento Box grid layout. Use: modular cards with varied sizes (1x1, 2x1, 2x2), Apple-style aesthetic, rounded corners (16-24px), soft shadows, clean hierarchy, asymmetric grid, neutral backgrounds (#F5F5F7), hover effects."`

### Y2K Aesthetic
- **특징/키워드**: Neon pink, chrome, metallic, bubblegum, iridescent, glossy, retro-futurism, 2000s, futuristic nostalgia
- **추천 서비스**: Fashion brands, music platforms, Gen Z brands, nostalgia marketing, entertainment, youth-focused
- **체크리스트**: ☐ Neon colors balanced, ☐ Chrome effects visible, ☐ Glossy buttons styled, ☐ Bubble shapes decorative, ☐ Sparkle animations, ☐ Retro fonts loaded
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Y2K Aesthetic" --desc "Design a Y2K aesthetic interface. Use: neon pink/cyan colors, chrome/metallic textures, bubblegum gradients, glossy buttons, iridescent effects, 2000s futurism, star/sparkle decorations, bubble shapes, tech-optimistic vibe."`

### Cyberpunk UI
- **특징/키워드**: Neon, dark mode, terminal, HUD, sci-fi, glitch, dystopian, futuristic, matrix, tech noir
- **추천 서비스**: Gaming platforms, tech products, crypto apps, sci-fi applications, developer tools, entertainment
- **체크리스트**: ☐ Dark background only, ☐ Neon accents visible, ☐ Glitch effect subtle, ☐ Scanlines optional, ☐ Monospace font, ☐ Terminal aesthetic
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Cyberpunk UI" --desc "Design a cyberpunk interface. Use: neon colors on dark (#0D0D0D), terminal/HUD aesthetic, glitch effects, scanlines overlay, matrix green accents, monospace fonts, angular shapes, dystopian tech feel."`

### Organic Biophilic
- **특징/키워드**: Nature, organic shapes, green, sustainable, rounded, flowing, wellness, earthy, natural textures
- **추천 서비스**: Wellness apps, sustainability brands, eco products, health apps, meditation, organic food brands
- **체크리스트**: ☐ Earth tones dominant, ☐ Organic curves present, ☐ Natural textures subtle, ☐ Green accents, ☐ Rounded everywhere, ☐ Calming feel
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Organic Biophilic" --desc "Design a biophilic organic interface. Use: nature-inspired colors (greens, browns), organic curved shapes, rounded corners (16-24px), natural textures (wood, stone), flowing SVG elements, wellness aesthetic, earthy palette."`

### AI-Native UI
- **특징/키워드**: Chatbot, conversational, voice, assistant, agentic, ambient, minimal chrome, streaming text, AI interactions
- **추천 서비스**: AI products, chatbots, voice assistants, copilots, AI-powered tools, conversational interfaces
- **체크리스트**: ☐ Chat layout responsive, ☐ Typing indicator smooth, ☐ Input always visible, ☐ Context cards styled, ☐ AI responses distinct, ☐ User messages aligned right
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "AI-Native UI" --desc "Design an AI-native interface. Use: minimal chrome, conversational layout, streaming text area, typing indicators (3-dot pulse), context cards, subtle AI accent color (#6366F1), clean input field, response bubbles."`

### Memphis Design
- **특징/키워드**: 80s, geometric, playful, postmodern, shapes, patterns, squiggles, triangles, neon, abstract, bold
- **추천 서비스**: Creative agencies, music sites, youth brands, event promotion, artistic portfolios, entertainment
- **체크리스트**: ☐ Geometric shapes visible, ☐ Colors bold/clashing, ☐ Patterns present, ☐ Layout asymmetric, ☐ Playful decorations, ☐ 80s vibe achieved
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Memphis Design" --desc "Design a Memphis style interface. Use: bold geometric shapes (triangles, squiggles, circles), bright clashing colors, 80s postmodern aesthetic, playful patterns, dotted textures, asymmetric layouts, decorative elements."`

### Vaporwave
- **특징/키워드**: Synthwave, retro-futuristic, 80s-90s, neon, glitch, nostalgic, sunset gradient, dreamy, aesthetic
- **추천 서비스**: Music platforms, gaming, creative portfolios, tech startups, entertainment, artistic projects
- **체크리스트**: ☐ Sunset gradient present, ☐ Neon glow applied, ☐ Retro grid visible, ☐ Glitch effects subtle, ☐ Dreamy atmosphere, ☐ 80s-90s aesthetic
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Vaporwave" --desc "Design a vaporwave aesthetic interface. Use: sunset gradients (pink/cyan/purple), 80s-90s nostalgia, glitch effects, Greek statue imagery, palm trees, grid patterns, neon glow, retro-futuristic feel, dreamy atmosphere."`

### Dimensional Layering
- **특징/키워드**: Depth, overlapping, z-index, layers, 3D, shadows, elevation, floating, cards, spatial hierarchy
- **추천 서비스**: Dashboards, card layouts, modals, navigation, product showcases, SaaS interfaces
- **체크리스트**: ☐ Layers clearly defined, ☐ Shadows show depth, ☐ Overlaps intentional, ☐ Hierarchy clear, ☐ Performance optimized, ☐ Mobile depth maintained
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Dimensional Layering" --desc "Design with dimensional layering. Use: z-index depth (multiple layers), overlapping cards, elevation shadows (4 levels), floating elements, parallax depth, backdrop blur for hierarchy, spatial UI feel."`

### Exaggerated Minimalism
- **특징/키워드**: Bold minimalism, oversized typography, high contrast, negative space, loud minimal, statement design
- **추천 서비스**: Fashion, architecture, portfolios, agency landing pages, luxury brands, editorial
- **체크리스트**: ☐ Typography oversized, ☐ White space extreme, ☐ Black/white dominant, ☐ Single accent only, ☐ Elements minimal, ☐ Statement clear
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Exaggerated Minimalism" --desc "Design with exaggerated minimalism. Use: oversized typography (clamp 3rem-12rem), extreme negative space, black/white primary, single accent color only, bold statements, minimal elements, dramatic contrast."`

### Kinetic Typography
- **특징/키워드**: Motion text, animated type, moving letters, dynamic, typing effect, morphing, scroll-triggered text
- **추천 서비스**: Hero sections, marketing sites, video platforms, storytelling, creative portfolios, landing pages
- **체크리스트**: ☐ Text animations smooth, ☐ Prefers-reduced-motion respected, ☐ Fallback for no-JS, ☐ Mobile performance ok, ☐ Typing effect timed, ☐ Scroll triggers work
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Kinetic Typography" --desc "Design with kinetic typography. Use: animated text, scroll-triggered reveals, typing effects, letter-by-letter animations, morphing text, gradient text fills, oversized hero text, text as the main visual element."`

### Parallax Storytelling
- **특징/키워드**: Scroll-driven, narrative, layered scrolling, immersive, progressive disclosure, cinematic, scroll-triggered
- **추천 서비스**: Brand storytelling, product launches, case studies, portfolios, annual reports, marketing campaigns
- **체크리스트**: ☐ Layers parallax smoothly, ☐ Story flows naturally, ☐ Mobile alternative provided, ☐ Performance optimized, ☐ Skip option available, ☐ Reduced motion fallback
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Parallax Storytelling" --desc "Design a parallax storytelling page. Use: scroll-driven narrative, layered backgrounds (3-5 layers), fixed/sticky sections, cinematic transitions, progressive disclosure, full-screen chapters, depth perception."`

### Swiss Modernism 2.0
- **특징/키워드**: Grid system, Helvetica, modular, asymmetric, international style, rational, clean, mathematical spacing
- **추천 서비스**: Corporate sites, architecture, editorial, SaaS, museums, professional services, documentation
- **체크리스트**: ☐ 12-column grid strict, ☐ Spacing mathematical, ☐ Typography hierarchy clear, ☐ Single accent only, ☐ No decorations, ☐ High contrast verified
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Swiss Modernism 2.0" --desc "Design with Swiss Modernism 2.0. Use: strict grid system (12 columns), Helvetica/Inter fonts, mathematical spacing, asymmetric balance, high contrast, minimal decoration, clean hierarchy, single accent color."`

### HUD / Sci-Fi FUI
- **특징/키워드**: Futuristic, technical, wireframe, neon, data, transparency, iron man, sci-fi, interface
- **추천 서비스**: Sci-fi games, space tech, cybersecurity, movie props, immersive dashboards
- **체크리스트**: ☐ Fine lines 1px, ☐ Neon glow text/borders, ☐ Monospaced font, ☐ Dark/Transparent BG, ☐ Decorative tech markers, ☐ Holographic feel
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "HUD / Sci-Fi FUI" --desc "Design a futuristic HUD (Heads Up Display) or FUI. Use: thin lines (1px), neon cyan/blue on black, technical markers, decorative brackets, data visualization, monospaced tech fonts, glowing elements, transparency."`

### Pixel Art
- **특징/키워드**: Retro, 8-bit, 16-bit, gaming, blocky, nostalgic, pixelated, arcade
- **추천 서비스**: Indie games, retro tools, creative portfolios, nostalgia marketing, Web3/NFT
- **체크리스트**: ☐ Pixelated fonts loaded, ☐ Images sharp (no blur), ☐ CSS box-shadow for pixel borders, ☐ Retro palette, ☐ Blocky layout
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Pixel Art" --desc "Design a pixel art inspired interface. Use: pixelated fonts, 8-bit or 16-bit aesthetic, sharp edges (image-rendering: pixelated), limited color palette, blocky UI elements, retro gaming feel."`

### Bento Grids
- **특징/키워드**: Apple-style, modular, cards, organized, clean, hierarchy, grid, rounded, soft
- **추천 서비스**: Product features, dashboards, personal sites, marketing summaries, galleries
- **체크리스트**: ☐ Grid layout (CSS Grid), ☐ Rounded corners 16-24px, ☐ Varied card spans, ☐ Content fits card size, ☐ Responsive re-flow, ☐ Apple-like aesthetic
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Bento Grids" --desc "Design a Bento Grid layout. Use: modular grid system, rounded corners (16-24px), different card sizes (1x1, 2x1, 2x2), card-based hierarchy, soft backgrounds (#F5F5F7), subtle borders, content-first, Apple-style aesthetic."`

### Spatial UI (VisionOS)
- **특징/키워드**: Glass, depth, immersion, spatial, translucent, gaze, gesture, apple, vision-pro
- **추천 서비스**: Spatial computing apps, VR/AR interfaces, immersive media, futuristic dashboards
- **체크리스트**: ☐ Glass effect visible, ☐ Depth layers clear, ☐ Hover states defined, ☐ Colors vibrant on active, ☐ Floating feel achieved, ☐ Contrast maintained
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Spatial UI (VisionOS)" --desc "Design a VisionOS-style spatial interface. Use: frosted glass panels, depth layers, translucent backgrounds (15-30% opacity), vibrant colors for active states, gaze-hover effects, floating windows, immersive feel."`

### E-Ink / Paper
- **특징/키워드**: Paper-like, matte, high contrast, texture, reading, calm, slow tech, monochrome
- **추천 서비스**: Reading apps, digital newspapers, minimal journals, distraction-free writing, slow-living brands
- **체크리스트**: ☐ Paper background color, ☐ High contrast text, ☐ No animations, ☐ Reading optimized, ☐ Distraction-free, ☐ Print-friendly
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "E-Ink / Paper" --desc "Design an e-ink/paper style interface. Use: high contrast black on off-white, paper texture, no animations (instant transitions), reading-focused, minimal UI chrome, distraction-free, calm aesthetic, monochrome."`

### Gen Z Chaos / Maximalism
- **특징/키워드**: Chaos, clutter, stickers, raw, collage, mixed media, loud, internet culture, ironic
- **추천 서비스**: Gen Z lifestyle brands, music artists, creative portfolios, viral marketing, fashion
- **체크리스트**: ☐ Colors clash intentionally, ☐ Stickers/overlays present, ☐ Layout chaotic but usable, ☐ GIFs optimized, ☐ Mobile scrollable, ☐ Performance acceptable
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Gen Z Chaos / Maximalism" --desc "Design a Gen Z chaos maximalist interface. Use: clashing bright colors, sticker overlays, collage aesthetic, raw/unpolished feel, mixed media, ironic elements, loud typography, GIF-heavy, internet culture references."`

### Biomimetic / Organic 2.0
- **특징/키워드**: Nature-inspired, cellular, fluid, breathing, generative, algorithms, life-like
- **추천 서비스**: Sustainability tech, biotech, advanced health, meditation, generative art platforms
- **체크리스트**: ☐ Organic shapes present, ☐ Animations feel alive, ☐ Generative elements, ☐ Performance monitored, ☐ Mobile fallback, ☐ Accessibility alt content
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Biomimetic / Organic 2.0" --desc "Design a biomimetic organic interface. Use: cellular/fluid shapes, breathing animations, generative patterns, bioluminescent colors, physics-based movement, nature algorithms, life-like elements, flowing gradients."`

### Anti-Polish / Raw Aesthetic
- **특징/키워드**: Hand-drawn, collage, scanned textures, unfinished, imperfect, authentic, human, sketch, raw marks, creative process
- **추천 서비스**: Creative portfolios, artist sites, indie brands, handmade products, authentic storytelling, editorial
- **체크리스트**: ☐ Textures loaded, ☐ Hand-drawn elements present, ☐ Imperfections intentional, ☐ Authentic feel achieved, ☐ Performance ok with textures, ☐ Accessibility maintained
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Anti-Polish / Raw Aesthetic" --desc "Design with anti-polish raw aesthetic. Use: hand-drawn elements, scanned textures, unfinished look, paper/pencil textures, collage style, authentic imperfection, sketch marks, tape/sticker overlays, human touch."`

### Tactile Digital / Deformable UI
- **특징/키워드**: Jelly buttons, chrome, clay, squishy, deformable, bouncy, physical, tactile feedback, press response
- **추천 서비스**: Modern mobile apps, playful brands, entertainment, gaming UI, consumer products, interactive demos
- **체크리스트**: ☐ Press effect visible, ☐ Bounce-back smooth, ☐ Material feels tactile, ☐ Spring physics tuned, ☐ Mobile touch responsive, ☐ Reduced motion option
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Tactile Digital / Deformable UI" --desc "Design a tactile deformable interface. Use: jelly/squishy buttons, press deformation effect, bounce-back animations, chrome/clay materials, spring physics, haptic-like feedback, material response, 3D depth on interaction."`

### Nature Distilled
- **특징/키워드**: Muted earthy, skin tones, wood, soil, sand, terracotta, warmth, organic materials, handmade warmth
- **추천 서비스**: Wellness brands, sustainable products, artisan goods, organic food, spa/beauty, home decor
- **체크리스트**: ☐ Earth tones dominant, ☐ Warm feel achieved, ☐ Textures subtle, ☐ Handmade quality, ☐ Sustainable messaging, ☐ Calming aesthetic
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Nature Distilled" --desc "Design with nature distilled aesthetic. Use: muted earthy colors (terracotta, sand, olive), organic materials feel, warm tones, handmade warmth, natural textures, artisan quality, sustainable vibe, soft gradients."`

### Interactive Cursor Design
- **특징/키워드**: Custom cursor, cursor as tool, hover effects, cursor feedback, pointer transformation, cursor trail, magnetic cursor
- **추천 서비스**: Creative portfolios, interactive experiences, agency sites, product showcases, gaming, entertainment
- **체크리스트**: ☐ Custom cursor works, ☐ Hover morph smooth, ☐ Magnetic pull subtle, ☐ Trail performance ok, ☐ Click feedback visible, ☐ Touch fallback provided
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Interactive Cursor Design" --desc "Design with interactive cursor effects. Use: custom cursor, cursor morphing on hover, magnetic cursor pull, cursor trails, blend mode cursors, click feedback animations, cursor as interaction tool, pointer transformation."`

### Voice-First Multimodal
- **특징/키워드**: Voice UI, multimodal, audio feedback, conversational, hands-free, ambient, contextual, speech recognition
- **추천 서비스**: Voice assistants, accessibility apps, hands-free tools, smart home, automotive UI, cooking apps
- **체크리스트**: ☐ Voice recognition works, ☐ Visual feedback clear, ☐ Listening state obvious, ☐ Speaking animation smooth, ☐ Fallback UI provided, ☐ Accessibility excellent
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Voice-First Multimodal" --desc "Design a voice-first multimodal interface. Use: voice waveform visualization, listening state indicator, speaking animation, minimal visible UI, audio feedback cues, hands-free optimized, conversational flow, ambient design."`

### 3D Product Preview
- **특징/키워드**: 360 product view, rotatable, zoomable, touch-to-spin, AR preview, product configurator, interactive 3D model
- **추천 서비스**: E-commerce, furniture, fashion, automotive, electronics, jewelry, product configurators
- **체크리스트**: ☐ 3D model loads fast, ☐ Rotation smooth, ☐ Zoom works (pinch/scroll), ☐ AR button functional, ☐ Colors switchable, ☐ Mobile touch works
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "3D Product Preview" --desc "Design a 3D product preview interface. Use: 360° rotation, drag-to-spin, pinch-to-zoom, AR preview button, material/color switcher, hotspot annotations, orbit controls, product configurator, smooth rendering."`

### Gradient Mesh / Aurora Evolved
- **특징/키워드**: Complex gradients, mesh gradients, multi-color blend, aurora effect, flowing colors, iridescent, holographic, prismatic
- **추천 서비스**: Hero sections, backgrounds, creative brands, music platforms, fashion, lifestyle, premium products
- **체크리스트**: ☐ Mesh gradient visible, ☐ Colors flow smoothly, ☐ Aurora effect achieved, ☐ Performance acceptable, ☐ Text remains readable, ☐ Mobile renders ok
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Gradient Mesh / Aurora Evolved" --desc "Design with gradient mesh aurora effect. Use: multi-color mesh gradients, flowing color transitions, aurora/northern lights feel, iridescent overlays, holographic shimmer, prismatic effects, smooth color morphing."`

### Editorial Grid / Magazine
- **특징/키워드**: Magazine layout, asymmetric grid, editorial typography, pull quotes, drop caps, column layout, print-inspired
- **추천 서비스**: News sites, blogs, magazines, editorial content, long-form articles, journalism, publishing
- **체크리스트**: ☐ Grid asymmetric, ☐ Typography editorial, ☐ Pull quotes styled, ☐ Drop caps present, ☐ Images large/impactful, ☐ Mobile reflows well
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Editorial Grid / Magazine" --desc "Design an editorial magazine layout. Use: asymmetric grid, pull quotes, drop caps, multi-column text, large imagery, bylines, section dividers, print-inspired typography, article hierarchy, white space balance."`

### Chromatic Aberration / RGB Split
- **특징/키워드**: RGB split, color fringing, glitch, retro tech, VHS, analog error, distortion, lens effect
- **추천 서비스**: Music platforms, gaming, tech brands, creative portfolios, nightlife, entertainment, video platforms
- **체크리스트**: ☐ RGB split visible, ☐ Glitch effect controlled, ☐ Scan lines subtle, ☐ Performance ok, ☐ Readability maintained, ☐ Reduced motion option
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Chromatic Aberration / RGB Split" --desc "Design with chromatic aberration RGB split effect. Use: color channel offset (R/G/B), glitch aesthetic, retro tech feel, VHS error look, lens distortion, scan lines, noise overlay, analog imperfection."`

### Vintage Analog / Retro Film
- **특징/키워드**: Film grain, VHS, cassette tape, polaroid, analog warmth, faded colors, light leaks, vintage photography
- **추천 서비스**: Photography portfolios, music/vinyl brands, vintage fashion, nostalgia marketing, film industry, cafes
- **체크리스트**: ☐ Film grain visible, ☐ Colors faded/warm, ☐ Light leaks present, ☐ Nostalgic feel achieved, ☐ Performance with filters, ☐ Images look vintage
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Vintage Analog / Retro Film" --desc "Design with vintage analog film aesthetic. Use: film grain overlay, faded/desaturated colors, warm sepia tones, light leaks, VHS tracking effect, polaroid frame, analog warmth, nostalgic photography feel."`

### Bauhaus (包豪斯)
- **특징/키워드**: bauhaus, geometric, constructivist, primary colors, hard shadow, bold, tactile, functional, poster, mechanical, architectural
- **추천 서비스**: Mobile-first apps needing high personality, onboarding flows, branding-forward product screens, artisan/design brands, editorial mobile experiences
- **체크리스트**: ☐ Geometric shapes only (circle/square), ☐ Primary color blocking applied, ☐ Hard offset shadows 4px, ☐ border-2 border-black on all elements, ☐ Mechanical press active state, ☐ Outfit Black 900 uppercase headlines, ☐ Safe area (pt-safe pb-safe) respected, ☐ Thumb-friendly h-12/h-14 touch targets, ☐ No hover states (mobile-only), ☐ Vertical rhythm single-column stack
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Bauhaus (包豪斯)" --desc "Design a Bauhaus mobile app. Use strict geometric shapes (circles and squares only), primary color blocking (Red #D02020, Blue #1040C0, Yellow #F0C020), hard 4px offset black shadows, OFF-WHITE canvas (#F0F0F0), massive bold uppercase headlines (Outfit Black 900), rectangular full-width buttons with mechanical press animation. No gradients. No rounded cards. No soft transitions."`

### Minimalist Monochrome
- **특징/키워드**: monochrome, black white, editorial, austere, typographic, sharp, zero radius, high contrast, brutalist, pocket editorial, serif, mechanical
- **추천 서비스**: Luxury fashion e-commerce mobile, editorial publications, high-end portfolio apps, experimental/avant-garde brands, digital exhibitions
- **체크리스트**: ☐ 0px border-radius on ALL elements, ☐ No shadows anywhere, ☐ Instant inversion on every tap (transition-none), ☐ 4px black line separates hero from content, ☐ Safe area respected (pt-safe pb-safe), ☐ h-14 touch targets, ☐ Sticky section headers with border-b, ☐ Typography hero: word spans full screen width, ☐ Paper noise texture on backgrounds, ☐ Menu word-label instead of icon
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Minimalist Monochrome" --desc "Design a minimalist monochrome mobile app. Use ONLY black (#000000) and white (#FFFFFF). Zero border-radius on every element. No shadows — depth is created by 1–4px black borders and color inversion only. Typography is the primary visual: Playfair Display for heroes (text-5xl–text-6xl, tracking-tighter, leading-[0.9]), Source Serif 4 for body, JetBrains Mono for labels/tags. Tap states instantly invert (bg-black text-white). Full-width horizontal rules separate sections. Use the word 'MENU' instead of hamburger icon."`

### Modern Dark (Cinema Mobile)
- **특징/키워드**: dark mode, cinematic, ambient light, glassmorphism, deep black, indigo, glow, blur, atmospheric, reanimated, haptic, premium, layered, frosted glass, linear gradient
- **추천 서비스**: Developer tools, pro productivity apps, fintech/trading dashboards, media/streaming platforms, AI tool interfaces, high-end gaming companion apps
- **체크리스트**: ☐ No pure #000000 backgrounds, ☐ LinearGradient base screen, ☐ Animated ambient blobs (Reanimated, native driver), ☐ BlurView on tab bar and headers, ☐ borderRadius 16 on all cards, ☐ Haptic feedback on every Pressable, ☐ Bezier(0.16,1,0.3,1) easing used, ☐ Accent glow behind primary button, ☐ No solid grey borders (rgba only), ☐ Bottom sheets replace all modals
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Modern Dark (Cinema Mobile)" --desc "Design a cinematic dark mobile app. Background: LinearGradient from #0a0a0f (top) to #020203 (bottom). Add 2–3 absolute animated 'blob' views: circular, blurRadius 30–50, opacity 0.08–0.12, slow Reanimated oscillation. Cards: borderRadius 16, border rgba(255,255,255,0.08) hairline, subtle top-edge shine gradient. Primary button: #5E6AD2, scale press 0.97, haptic on press. BlurView (intensity 20, tint dark) for tab bar and headers. Typography: Inter 700 for headers, 400 for body. Never use pure #000000. Accent glow: rgba(94,106,210,0.2) behind primary actions."`

### SaaS Mobile (High-Tech Boutique)
- **특징/키워드**: saas, electric blue, gradient, fintech, spring animation, dual font, glassmorphism, boutique, premium, calistoga, inter, mono, tactile, haptic, bento
- **추천 서비스**: B2B SaaS mobile dashboards, fintech apps, developer tool mobile companions, marketing analytics apps, HR/operations apps, modern business productivity
- **체크리스트**: ☐ SafeAreaView wraps all screens, ☐ All touch targets ≥ 44×44px, ☐ Spring config used for all transitions, ☐ Gradient buttons (not flat), ☐ Haptic on every Pressable, ☐ Section badges with PulseDot, ☐ Staggered entrance animation on screen mount, ☐ JetBrains Mono for data labels, ☐ Calistoga for hero headlines, ☐ Elevation/shadow on cards
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "SaaS Mobile (High-Tech Boutique)" --desc "Design a high-tech boutique SaaS mobile app. Primary canvas: #FAFAFA (warm off-white). Cards: #FFFFFF with 1pt Slate-200 border, iOS shadow (shadowOpacity:0.1, shadowRadius:10, offset y:4), Android elevation:4, padding 24px, borderRadius 16. Buttons: LinearGradient #0052FF→#4D7CFF, height 56px, borderRadius 16, scale press 0.96 + haptic. Section badges: rounded pill with rgba(0,82,255,0.05) bg and rgba(0,82,255,0.2) border + PulseDot + JetBrains Mono text. Typography: Calistoga for heroes (36–42pt), Inter for body (16–18pt), JetBrains Mono for data labels. All screen transitions: spring (mass:1 damping:15 stiffness:120). Always include SafeAreaView."`

### Terminal CLI (Mobile)
- **특징/키워드**: terminal, cli, matrix green, monospace, hacker, ascii, command line, developer, web3, crypto, sci-fi, OLED, retro-future, field operative
- **추천 서비스**: Developer tools, Web3/blockchain apps, geek-culture apps, ARG games, sci-fi/noir gaming companions, hacker/security tools, creative studio portfolios
- **체크리스트**: ☐ 0px border-radius everywhere, ☐ ASCII-style borders on cards, ☐ Boot sequence on launch, ☐ Blinking cursor component, ☐ Typewriter hook for new content, ☐ Scanline overlay (0.05 opacity), ☐ Haptic on every button press, ☐ Footer status bar component, ☐ hitSlop on all bracketed buttons (44×44dp), ☐ Reduced motion respected
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Terminal CLI (Mobile)" --desc "Design a Mobile Terminal CLI app. Background: #050505 OLED black. ALL text in Matrix Green #33FF00. Font: JetBrains Mono or SpaceMono ONLY — zero border-radius everywhere. ASCII borders using +, -, |, * characters instead of standard containers. Buttons displayed as [ EXECUTE ] or > PROCEED. On press: instantly inverts to green bg + black text + haptic. Cursor: blinking View opacity 0→1 at 500ms. Show boot sequence on launch (fake log scroll). Progress bars as [#####-----] text. Status bar footer: [BATTERY:88%] [NET:CONNECTED]. Scanline overlay: absolute View with repeating 1px horizontal lines at opacity 0.05. Typewriter effect on new data."`

### Kinetic Brutalism (Mobile)
- **특징/키워드**: kinetic, brutalism, motion, marquee, acid yellow, uppercase, oversized, aggressive typography, street, zine, high contrast, scroll-driven, haptic, reanimated
- **추천 서비스**: Immersive storytelling apps, brand flagship mobile, music/culture platforms, sports apps, underground zines, limited-edition product drops, performance dashboards
- **체크리스트**: ☐ Infinite marquee rows (Reanimated, no fade edges), ☐ Hero parallax scroll (scale+opacity Interpolate), ☐ All display text uppercase, ☐ 0px border-radius, ☐ 2px borders, ☐ Acid yellow card flood on press, ☐ Haptic Medium on every interaction, ☐ Font scale helper (windowWidth/375*size), ☐ Safe area for massive headers, ☐ Reduced motion stops marquees
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Kinetic Brutalism (Mobile)" --desc "Design a Kinetic Brutalism mobile app. Canvas: #09090B. Primary accent: Acid Yellow #DFE104 (text: #000000). Typography: Space Grotesk BOLD. Display text: 60–120pt, uppercase, letterSpacing -1, lineHeight 0.9–1.1x. Body: 18–20pt. Labels: 12pt uppercase letterSpacing +2. Add infinite marquee rows (Reanimated, no easing, hard edge clip). Hero text parallax on scroll (Interpolate: scale 1.0→1.3, opacity 1→0). Card press: instantly flood to #DFE104 + flip text to #000. Haptic Medium on every press. 0px radius. 2px solid borders. NO shadows. No gradients. Scale all fonts by (windowWidth / 375 * size) for responsiveness."`

### Flat Design Mobile (Touch-First)
- **특징/키워드**: flat, 2D, no shadow, color blocking, geometric, bold, poster, icon, touch-first, minimal, clean, tailored, cross-platform
- **추천 서비스**: Cross-platform apps (iOS+Android parity), information-dense dashboards, system UI, brand illustration, onboarding flows, marketing pages, icon design
- **체크리스트**: ☐ Zero elevation AND shadowOpacity on all elements, ☐ Color-blocking sections (not borders), ☐ All touch targets ≥ 48×48, ☐ No gradients on flat elements, ☐ Icons inside solid colored containers, ☐ Pressable scale feedback, ☐ Geometric shapes as bg decoration, ☐ Bold flat bottom tabs (no floating), ☐ Primary headlines much larger than body, ☐ 4pt spacing system throughout
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Flat Design Mobile (Touch-First)" --desc "Design a Flat Mobile app. NO shadows (shadowOpacity: 0, elevation: 0). Color creates all hierarchy. Sections: full-width View blocks alternating contrasting bg colors (Blue Hero → White Content → Gray Block). Buttons: solid #3B82F6, borderRadius 8, height 56. Cards: backgroundColor #FFFFFF (on gray bg) or #DBEAFE (blue tint) — no shadow. Text: fontWeight 800 letterSpacing -0.5 (heads), 600 (sub), 400 (body). Inputs: #F3F4F6 bg, focused: borderWidth 2 borderColor #3B82F6. Icons: Lucide strokeWidth 2.5 inside solid colored square/circle. Press feedback: scale 0.97 Pressable. Use position absolute low-opacity geometric shapes (circles, rotated squares) as background decoration."`

### Material You (MD3 Mobile)
- **특징/키워드**: material design 3, md3, tonal surfaces, pills, soft curves, android, md3 easing, state layers, haptic, fab, google
- **추천 서비스**: Android ecosystem apps, cross-platform productivity tools, MD3-based admin panels, data-heavy back-office UI with Material UI
- **체크리스트**: ☐ MD3 color tokens applied (background/surface/container), ☐ All CTAs are pill-shaped, ☐ State-layer overlays instead of opacity 0.5 hacks, ☐ Emphasized easing used for all animations, ☐ Floating label inputs implemented, ☐ FAB uses tertiary color with correct elevation, ☐ Safe areas respected for organic shapes, ☐ No pure white background, ☐ No harsh box-shadows (ambient only)
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Material You (MD3 Mobile)" --desc "Design a Material You (MD3) mobile app. Use #FFFBFE background, #6750A4 primary, #E8DEF8 secondary container, #F3EDF7 surface container. All interactive elements are pill-shaped (borderRadius: 999). Buttons use Pressable with scale: 0.95 on press and state-layer overlays (black 10% or primary 12%). Inputs use filled M3 style: background #E7E0EC with floating label animation on focus. Elevation is tonal (layering containers) plus light shadow/elevation on Android. Animations use emphasized easing (0.2,0,0,1) at 100–400ms. FABs are tertiary-colored rounded squares/circles with level 3 elevation."`

### Neo Brutalism (Mobile)
- **특징/키워드**: neo brutalism, pop art, stickers, thick borders, cream background, hot red, vivid yellow, soft violet, hard offset shadow, mechanical press, collage
- **추천 서비스**: Creative tools, collab platforms, Gen Z marketing & e-commerce, portfolio sites, sticker-book style content apps
- **체크리스트**:  ☐ Hard offset shadow implemented via extra View
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Neo Brutalism (Mobile)" --desc "Design a Mobile Neo-Brutalist app. Background: Cream #FFFDF5. All content blocks: white or violet with borderWidth 4 borderColor #000. Shadows are solid offset blocks (no blur) using an extra View behind offset by 4px or 8px. Typography: Space Grotesk Bold/Black only (700–900). Buttons: 56px tall, 4px border, 0 radius; press animation translates button to cover the shadow. Cards slightly rotated (-1deg, 2deg). Colors: Hot Red #FF6B6B for primary, Yellow #FFD93D for focus/badges, Soft Violet #C4B5FD as tertiary. Animation: spring/linear only, no ease-out luxury motion."`

### Bold Typography (Mobile Poster)
- **특징/키워드**: bold typography, editorial, poster, broadsheet, vermillion, negative space, edge-to-edge type, underline CTA, near-black, warm white
- **추천 서비스**: Creative brand heroes, reading-focused apps, event/exhibition pages, editorial mobile experiences, landing hero sections
- **체크리스트**: ☐ H1 at least 4–5× body size, ☐ All containers 0 radius, ☐ Underline CTA pattern used, ☐ Large vertical gaps between sections, ☐ No shadows or soft corners, ☐ Accent used only for interaction, ☐ Text bleeds to/over screen edges, ☐ Animation timings 200ms, ☐ Accessible contrast ≥ 18:1, ☐ Body text never below 16px
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Bold Typography (Mobile Poster)" --desc "Design a Bold Typography mobile screen. Background #0A0A0A, text #FAFAFA, accent #FF3D00. Use Inter Tight/Inter 600+ for all type; JetBrains Mono for labels. Headline: 56–72px, tracking -1.5, lineHeight 1.1, full-bleed width with slight bleed off-screen. Body: 16–18px, leading 1.6. Buttons: underline CTA (accent text + 2px underline block), or inverted box with 0 radius. No shadows, no rounded corners. Layout: single column, paddingHorizontal 24, vertical gaps 64 between sections. Animation: 200ms, Easing.bezier(0.25,0,0,1), slight slide-up 10px + fade on mount."`

### Academia (Scholarly Mobile)
- **특징/키워드**: academia, library, mahogany, parchment, brass, crimson, serif, drop cap, arch-top, vignette, leather, scholarly, tactile
- **추천 서비스**: Knowledge management apps, deep reading tools, ritual-heavy personal brands, lore-heavy RPG/roleplay apps, culture-specific community platforms
- **체크리스트**: ☐ Mahogany/oak/parchment palette applied, ☐ Brass used on all tappable items, ☐ Arch-top imagery used in hero/cards, ☐ Drop caps & Roman numerals used, ☐ Vignette overlay present, ☐ No sans-serif body fonts, ☐ No neon/bright modern colors, ☐ Animations use non-spring timing, ☐ Inputs use worn-leather style, ☐ Wax seal badges implemented
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Academia (Scholarly Mobile)" --desc "Design a Scholarly Academia mobile app. Background #1C1714 (mahogany), alt surfaces #251E19 (oak), text #E8DFD4 (parchment). Accent brass #C9A962 for CTAs + borders; crimson #8B2635 for wax seals. Typography: Cormorant Garamond (headings), Crimson Pro (body), Cinzel (labels/overlines). Use arch-top hero containers (borderTopRadius 100). Cards: oak bg, 1px wood-grain border. Inputs: worn-leather background, brass focus border. Global vignette overlay and ornate brass dividers (Unicode glyph + gradient line). Animations: no spring, only Timing with Easing.out(Easing.poly(4))."`

### Cyberpunk Mobile HUD
- **특징/키워드**: cyberpunk, neon, glitch, chamfered, orbitron, jetbrains, scanlines, crt, hud, matrix, military, decker
- **추천 서비스**: Gaming dashboards, crypto/cyberpunk apps, sci-fi companion tools, hacker OS skins, data-heavy monitoring HUDs
- **체크리스트**: ☐ Chamfered corners used instead of radius, ☐ Scanline & CRT flicker implemented, ☐ Orbitron + JetBrains Mono typography, ☐ Neon glow shadows on primary buttons, ☐ Glitch animation on active states, ☐ Prompt-style inputs with custom cursor, ☐ HUD corner brackets implemented, ☐ Safe-area system status bar styled, ☐ Reduced motion disables glitch/flicker, ☐ Icons configured with Lucide accent color
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Cyberpunk Mobile HUD" --desc "Design a Cyberpunk mobile HUD. Background #0A0A0F, card #12121A. Accents: #00FF88 (primary), #FF00FF, #00D4FF. Typography: Orbitron for headings, JetBrains Mono for data. All shapes use chamfered corners via SVG or Skia clipPath. Buttons: neon glow shadows, scale 0.98 + haptic on press, optional glitch jitter on active. Global scanline overlay (semi-transparent horizontal lines) and CRT flicker (root opacity 0.98–1). Inputs: prompt style with '>' in accent, custom blinking block cursor. HUD cards use corner brackets and subtle gradients."`

### Bitcoin DeFi (Mobile)
- **특징/키워드**: web3, bitcoin, defi, digital gold, fintech, wallet, orange, glassmorphism, gradient, blur, holographic, trust, precision
- **추천 서비스**: DeFi dashboards, wallets, NFT marketplaces, Web3 social, metaverse utilities, high-tech fintech brands
- **체크리스트**: ☐ Void/dark-matter palette applied, ☐ Bitcoin orange/gold gradient buttons, ☐ BlurView nav implemented, ☐ Monospace for numeric data, ☐ Hairline borders on blocks, ☐ Gradient text on balances, ☐ Pulsing network status indicators, ☐ Ledger vertical timeline, ☐ Haptics on money actions, ☐ SafeArea + FlashList for heavy lists
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Bitcoin DeFi (Mobile)" --desc "Design a Bitcoin DeFi mobile app. Background #030304, cards #0F1115, text #FFFFFF, muted #94A3B8. Primary CTA: LinearGradient #EA580C→#F7931A with orange glow shadow. Typography: Space Grotesk Bold for headings, Inter for body, JetBrains Mono for prices/hashes. Use BlurView (intensity 20) for nav bars and floating panels. Cards as 'blocks' with hairline borders and light orange glow on active. Use grid background (low-opacity 50px grid). Gradient text for key balances via MaskedView and LinearGradient orange→gold. Status indicators pulse using Reanimated. Ledger timelines drawn as vertical gradient line with pulsing dots."`

### Claymorphism (Mobile)
- **특징/키워드**: claymorphism, clay, 3d, soft, bubbly, candy, playful, rounded, squish, tactile, inflate, silicone, haptic, spring
- **추천 서비스**: Children education apps, teen social products, crypto gamification, creative tools, brand mascot-led apps
- **체크리스트**: ☐ Background uses #F4F1FA (no pure white), ☐ Multi-layer clay shadow stack applied, ☐ Cards use blurred glass-clay hybrid, ☐ Buttons squish to scale 0.92 on press, ☐ Spring physics on all interactions, ☐ Nunito Black for headings, ☐ Background blobs drifting, ☐ Haptics on every press, ☐ Nested border radius (card 32, inner 24), ☐ Bento layout with hero span
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Claymorphism (Mobile)" --desc "Design a high-fidelity Claymorphism mobile app. Background #F4F1FA (cool lavender-white, never pure white). Primary CTA: LinearGradient #A78BFA to #7C3AED, borderRadius 20, height 56. Cards: borderRadius 32, backgroundColor rgba(255,255,255,0.7) with BlurView. Multi-layer shadow: outer offset(12,12) rgba(160,150,180,0.2) + highlight offset(-8,-8) white. Typography: Nunito Black 900 for headings (48px hero, 32px section, 22px card), DM Sans Medium 500 for body 16px. Spring animations: scale 0.92 on press, spring back damping 10. Background blobs drift ±20px over 8–10s. Bento 2-column grid with hero card spanning full width. Haptics.impactAsync Light on every button press."`

### Enterprise SaaS (Mobile)
- **특징/키워드**: enterprise, saas, b2b, professional, indigo, violet, gradient, polished, trustworthy, clean, approachable, spring, haptic
- **추천 서비스**: B2B backend management, productivity tools, government and finance mobile apps, SaaS companion apps, enterprise dashboards
- **체크리스트**: ☐ Background #F8FAFC applied, ☐ Indigo→Violet gradient on primary CTA, ☐ Colored card shadows (not gray), ☐ Plus Jakarta Sans typography, ☐ Floating label inputs with Indigo focus, ☐ Scale 0.97 press with haptic Medium, ☐ Bottom Tab Navigation implemented, ☐ Safe Area strict compliance, ☐ Skeletal loading placeholders, ☐ Reduced Motion fallback
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Enterprise SaaS (Mobile)" --desc "Design a Modern Enterprise SaaS mobile app. Background #F8FAFC, surfaces #FFFFFF, primary #4F46E5 (Indigo), secondary #7C3AED (Violet). Typography: Plus Jakarta Sans, ExtraBold 800 for screen titles, Bold 700 for section headers, SemiBold 600 for buttons, Regular 400 for body. Line height 1.1–1.2 for titles, 1.4–1.5 for body. Primary button: full-width, LinearGradient Indigo→Violet, pill-shaped or radius 12, scale 0.95 on press with medium haptic. Cards: white bg, 16pt radius, hairline border, shadow rgba(79,70,229,0.08). Inputs: white bg, 8pt radius, floating label, Indigo border on focus. Bottom Tab Navigation (3–5 items), gradient active tab icon. Screen padding 16–20pt. Vertical rhythm 24pt between sections, 12pt between items. Shared Element Transition for hero cards opening to detail."`

### Sketch Hand-Drawn (Mobile)
- **특징/키워드**: sketch, hand-drawn, handwriting, wobbly, imperfect, paper, kalam, organic, collage, post-it, tape, offset shadow, scribble
- **추천 서비스**: Low-fidelity prototyping, creative brands, children/picturebook apps, education tools, journaling apps, gamified puzzles
- **체크리스트**: ☐ Warm paper background texture applied, ☐ Kalam Bold headings, ☐ Wobbly corner radii on all cards, ☐ Hard offset shadow View (not blur), ☐ Cards slightly rotated, ☐ Button press shifts to cover shadow, ☐ SVG tape/tack decorations, ☐ PatrickHand for inputs, ☐ Jiggle error animation, ☐ Minimum 48x48 touch targets
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Sketch Hand-Drawn (Mobile)" --desc "Design a Hand-Drawn (Sketch) mobile app. Background #FDFBF7 (warm paper texture). Typography: Kalam Bold for headings (high weight, felt-tip style), PatrickHand Regular for body (human but legible). Colors: Pencil Black #2D2D2D for all text and borders, Red Marker #FF4D4D for accents, Blue Ballpoint #2D5DA1for input focus. Cards: white background, wobbly corner radii (e.g., 15/25/20/10), borderWidth 3, rotate -1deg or +1deg. Hard offset shadow implemented as a second View behind the card offset 4px right and 4px down. Buttons: Post-it yellow #FFF9C4 for primary CTA, press state shifts the button (translateX 4, translateY 4) to cover the shadow. Inputs: PatrickHand font, wobbly border, focus changes to Blue Ballpoint. Add absolute SVG tape and tack decorations. Error: jiggle animation -2deg to +2deg. All touch targets minimum 48x48."`

### Neumorphism (Mobile)
- **특징/키워드**: neumorphism, soft ui, dual shadow, extruded, inset, clay surface, monochromatic, cool grey, haptic, ceramic, physical, depth
- **추천 서비스**: Minimal hardware controls, smart home apps, aesthetic utility tools, health monitors, brand showcase pages
- **체크리스트**: ☐ Single #E0E5EC base applied across all screens, ☐ Dual shadow (light+dark) implemented via nested View, ☐ Extruded resting state on cards/buttons, ☐ Inset concave state on inputs, ☐ Scale 0.97 press + shadow opacity interpolation, ☐ Haptics Light on all presses, ☐ No black shadows or white backgrounds, ☐ Nested depth pattern (extruded→inset), ☐ Accent #6C63FF on active/focus only, ☐ 8pt grid spacing
- **프롬프트 예시**: `/ui-ux-pro-max:plan --style "Neumorphism (Mobile)" --desc "Design a Neumorphism (Soft UI) mobile app. Entire background is a single color #E0E5EC (Cool Clay). No other background colors. Dual shadows: outer dark shadowColor rgba(163,177,198,0.7) offset(6,6) radius 10 + outer light #FFFFFF offset(-6,-6) radius 10 using nested View or react-native-shadow-2. Extruded (convex) for resting buttons and cards. Inset (concave) for inputs and pressed states. Buttons: height 56, borderRadius 16, scale 0.97 on press with shadow opacity→0.4, Haptics.impactAsync Light. Cards: padding 24, borderRadius 32, nested inner icon container uses inset style. Inputs: height 50, borderRadius 16, backgroundColor #E0E5EC (NOT white), inset depth effect, focus borderColor #6C63FF width 1.5. Typography: Plus Jakarta Sans Bold or System. Heading 24–32pt, body 16pt, caption 12pt, letterSpacing -0.5 for headings. Animation: 250ms Bezier(0.4,0,0.2,1). No black shadows, no pure white backgrounds."`

