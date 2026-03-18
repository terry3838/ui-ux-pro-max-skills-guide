# UX 가이드라인 (UX Guidelines)

## 핵심 Do's & Don'ts

### Navigation - Smooth Scroll (위험도: High)
- **✅ Do**: Use scroll-behavior: smooth on html element
  - 예시: `html { scroll-behavior: smooth; }`
- **❌ Don't**: Jump directly without transition
  - 예시: `<a href='#section'> without CSS`

### Navigation - Sticky Navigation (위험도: Medium)
- **✅ Do**: Add padding-top to body equal to nav height
  - 예시: `pt-20 (if nav is h-20)`
- **❌ Don't**: Let nav overlap first section content
  - 예시: `No padding compensation`

### Navigation - Active State (위험도: Medium)
- **✅ Do**: Highlight active nav item with color/underline
  - 예시: `text-primary border-b-2`
- **❌ Don't**: No visual feedback on current location
  - 예시: `All links same style`

### Navigation - Back Button (위험도: High)
- **✅ Do**: Preserve navigation history properly
  - 예시: `history.pushState()`
- **❌ Don't**: Break browser/app back button behavior
  - 예시: `location.replace()`

### Navigation - Deep Linking (위험도: Medium)
- **✅ Do**: Update URL on state/view changes
  - 예시: `Use query params or hash`
- **❌ Don't**: Static URLs for dynamic content
  - 예시: `Single URL for all states`

### Navigation - Breadcrumbs (위험도: Low)
- **✅ Do**: Use for sites with 3+ levels of depth
  - 예시: `Home > Category > Product`
- **❌ Don't**: Use for flat single-level sites
  - 예시: `Only on deep nested pages`

### Animation - Excessive Motion (위험도: High)
- **✅ Do**: Animate 1-2 key elements per view maximum
  - 예시: `Single hero animation`
- **❌ Don't**: Animate everything that moves
  - 예시: `animate-bounce on 5+ elements`

### Animation - Duration Timing (위험도: Medium)
- **✅ Do**: Use 150-300ms for micro-interactions
  - 예시: `transition-all duration-200`
- **❌ Don't**: Use animations longer than 500ms for UI
  - 예시: `duration-1000`

### Animation - Reduced Motion (위험도: High)
- **✅ Do**: Check prefers-reduced-motion media query
  - 예시: `@media (prefers-reduced-motion: reduce)`
- **❌ Don't**: Ignore accessibility motion settings
  - 예시: `No motion query check`

### Animation - Loading States (위험도: High)
- **✅ Do**: Use skeleton screens or spinners
  - 예시: `animate-pulse skeleton`
- **❌ Don't**: Leave UI frozen with no feedback
  - 예시: `Blank screen while loading`

### Animation - Hover vs Tap (위험도: High)
- **✅ Do**: Use click/tap for primary interactions
  - 예시: `onClick handler`
- **❌ Don't**: Rely only on hover for important actions
  - 예시: `onMouseEnter only`

### Animation - Continuous Animation (위험도: Medium)
- **✅ Do**: Use for loading indicators only
  - 예시: `animate-spin on loader`
- **❌ Don't**: Use for decorative elements
  - 예시: `animate-bounce on icons`

### Animation - Transform Performance (위험도: Medium)
- **✅ Do**: Use transform and opacity for animations
  - 예시: `transform: translateY()`
- **❌ Don't**: Animate width/height/top/left properties
  - 예시: `top: 10px animation`

### Animation - Easing Functions (위험도: Low)
- **✅ Do**: Use ease-out for entering ease-in for exiting
  - 예시: `ease-out`
- **❌ Don't**: Use linear for UI transitions
  - 예시: `linear`

### Layout - Z-Index Management (위험도: High)
- **✅ Do**: Define z-index scale system (10 20 30 50)
  - 예시: `z-10 z-20 z-50`
- **❌ Don't**: Use arbitrary large z-index values
  - 예시: `z-[9999]`

### Layout - Overflow Hidden (위험도: Medium)
- **✅ Do**: Test all content fits within containers
  - 예시: `overflow-auto with scroll`
- **❌ Don't**: Blindly apply overflow-hidden
  - 예시: `overflow-hidden truncating content`

### Layout - Fixed Positioning (위험도: Medium)
- **✅ Do**: Account for safe areas and other fixed elements
  - 예시: `Fixed nav + fixed bottom with gap`
- **❌ Don't**: Stack multiple fixed elements carelessly
  - 예시: `Multiple overlapping fixed elements`

### Layout - Stacking Context (위험도: Medium)
- **✅ Do**: Understand what creates new stacking context
  - 예시: `Parent with z-index isolates children`
- **❌ Don't**: Expect z-index to work across contexts
  - 예시: `z-index: 9999 not working`

### Layout - Content Jumping (위험도: High)
- **✅ Do**: Reserve space for async content
  - 예시: `aspect-ratio or fixed height`
- **❌ Don't**: Let images/content push layout around
  - 예시: `No dimensions on images`

### Layout - Viewport Units (위험도: Medium)
- **✅ Do**: Use dvh or account for mobile browser chrome
  - 예시: `min-h-dvh or min-h-screen`
- **❌ Don't**: Use 100vh for full-screen mobile layouts
  - 예시: `h-screen on mobile`

### Layout - Container Width (위험도: Medium)
- **✅ Do**: Limit max-width for text content (65-75ch)
  - 예시: `max-w-prose or max-w-3xl`
- **❌ Don't**: Let text span full viewport width
  - 예시: `Full width paragraphs`

### Touch - Touch Target Size (위험도: High)
- **✅ Do**: Minimum 44x44px touch targets
  - 예시: `min-h-[44px] min-w-[44px]`
- **❌ Don't**: Tiny clickable areas
  - 예시: `w-6 h-6 buttons`

### Touch - Touch Spacing (위험도: Medium)
- **✅ Do**: Minimum 8px gap between touch targets
  - 예시: `gap-2 between buttons`
- **❌ Don't**: Tightly packed clickable elements
  - 예시: `gap-0 or gap-1`

### Touch - Gesture Conflicts (위험도: Medium)
- **✅ Do**: Avoid horizontal swipe on main content
  - 예시: `Vertical scroll primary`
- **❌ Don't**: Override system gestures
  - 예시: `Horizontal swipe carousel only`

### Touch - Tap Delay (위험도: Medium)
- **✅ Do**: Use touch-action CSS or fastclick
  - 예시: `touch-action: manipulation`
- **❌ Don't**: Default mobile tap handling
  - 예시: `No touch optimization`

### Touch - Pull to Refresh (위험도: Low)
- **✅ Do**: Disable where not needed
  - 예시: `overscroll-behavior: contain`
- **❌ Don't**: Enable by default everywhere
  - 예시: `Default overscroll`

### Touch - Haptic Feedback (위험도: Low)
- **✅ Do**: Use for confirmations and important actions
  - 예시: `navigator.vibrate(10)`
- **❌ Don't**: Overuse vibration feedback
  - 예시: `Vibrate on every tap`

### Interaction - Focus States (위험도: High)
- **✅ Do**: Use visible focus rings on interactive elements
  - 예시: `focus:ring-2 focus:ring-blue-500`
- **❌ Don't**: Remove focus outline without replacement
  - 예시: `outline-none without alternative`

### Interaction - Hover States (위험도: Medium)
- **✅ Do**: Change cursor and add subtle visual change
  - 예시: `hover:bg-gray-100 cursor-pointer`
- **❌ Don't**: No hover feedback on clickable elements
  - 예시: `No hover style`

### Interaction - Active States (위험도: Medium)
- **✅ Do**: Add pressed/active state visual change
  - 예시: `active:scale-95`
- **❌ Don't**: No feedback during interaction
  - 예시: `No active state`

### Interaction - Disabled States (위험도: Medium)
- **✅ Do**: Reduce opacity and change cursor
  - 예시: `opacity-50 cursor-not-allowed`
- **❌ Don't**: Confuse disabled with normal state
  - 예시: `Same style as enabled`

### Interaction - Loading Buttons (위험도: High)
- **✅ Do**: Disable button and show loading state
  - 예시: `disabled={loading} spinner`
- **❌ Don't**: Allow multiple clicks during processing
  - 예시: `Button clickable while loading`

### Interaction - Error Feedback (위험도: High)
- **✅ Do**: Show clear error messages near problem
  - 예시: `Red border + error message`
- **❌ Don't**: Silent failures with no feedback
  - 예시: `No indication of error`

### Interaction - Success Feedback (위험도: Medium)
- **✅ Do**: Show success message or visual change
  - 예시: `Toast notification or checkmark`
- **❌ Don't**: No confirmation of completed action
  - 예시: `Action completes silently`

### Interaction - Confirmation Dialogs (위험도: High)
- **✅ Do**: Confirm before delete/irreversible actions
  - 예시: `Are you sure modal`
- **❌ Don't**: Delete without confirmation
  - 예시: `Direct delete on click`

### Accessibility - Color Contrast (위험도: High)
- **✅ Do**: Minimum 4.5:1 ratio for normal text
  - 예시: `#333 on white (7:1)`
- **❌ Don't**: Low contrast text
  - 예시: `#999 on white (2.8:1)`

### Accessibility - Color Only (위험도: High)
- **✅ Do**: Use icons/text in addition to color
  - 예시: `Red text + error icon`
- **❌ Don't**: Red/green only for error/success
  - 예시: `Red border only for error`

### Accessibility - Alt Text (위험도: High)
- **✅ Do**: Descriptive alt text for meaningful images
  - 예시: `alt='Dog playing in park'`
- **❌ Don't**: Empty or missing alt attributes
  - 예시: `alt='' for content images`

### Accessibility - Heading Hierarchy (위험도: Medium)
- **✅ Do**: Use sequential heading levels h1-h6
  - 예시: `h1 then h2 then h3`
- **❌ Don't**: Skip heading levels or misuse for styling
  - 예시: `h1 then h4`

### Accessibility - ARIA Labels (위험도: High)
- **✅ Do**: Add aria-label for icon-only buttons
  - 예시: `aria-label='Close menu'`
- **❌ Don't**: Icon buttons without labels
  - 예시: `<button><Icon/></button>`

### Accessibility - Keyboard Navigation (위험도: High)
- **✅ Do**: Tab order matches visual order
  - 예시: `tabIndex for custom order`
- **❌ Don't**: Keyboard traps or illogical tab order
  - 예시: `Unreachable elements`

### Accessibility - Screen Reader (위험도: Medium)
- **✅ Do**: Use semantic HTML and ARIA properly
  - 예시: `<nav> <main> <article>`
- **❌ Don't**: Div soup with no semantics
  - 예시: `<div> for everything`

### Accessibility - Form Labels (위험도: High)
- **✅ Do**: Use label with for attribute or wrap input
  - 예시: `<label for='email'>`
- **❌ Don't**: Placeholder-only inputs
  - 예시: `placeholder='Email' only`

### Accessibility - Error Messages (위험도: High)
- **✅ Do**: Use aria-live or role=alert for errors
  - 예시: `role='alert'`
- **❌ Don't**: Visual-only error indication
  - 예시: `Red border only`

### Accessibility - Skip Links (위험도: Medium)
- **✅ Do**: Provide skip to main content link
  - 예시: `Skip to main content link`
- **❌ Don't**: No skip link on nav-heavy pages
  - 예시: `100 tabs to reach content`

### Performance - Image Optimization (위험도: High)
- **✅ Do**: Use appropriate size and format (WebP)
  - 예시: `srcset with multiple sizes`
- **❌ Don't**: Unoptimized full-size images
  - 예시: `4000px image for 400px display`

### Performance - Lazy Loading (위험도: Medium)
- **✅ Do**: Lazy load below-fold images and content
  - 예시: `loading='lazy'`
- **❌ Don't**: Load everything upfront
  - 예시: `All images eager load`

### Performance - Code Splitting (위험도: Medium)
- **✅ Do**: Split code by route/feature
  - 예시: `dynamic import()`
- **❌ Don't**: Single large bundle
  - 예시: `All code in main bundle`

### Performance - Caching (위험도: Medium)
- **✅ Do**: Set appropriate cache headers
  - 예시: `Cache-Control headers`
- **❌ Don't**: No caching strategy
  - 예시: `Every request hits server`

### Performance - Font Loading (위험도: Medium)
- **✅ Do**: Use font-display swap or optional
  - 예시: `font-display: swap`
- **❌ Don't**: Invisible text during font load
  - 예시: `FOIT (Flash of Invisible Text)`

### Performance - Third Party Scripts (위험도: Medium)
- **✅ Do**: Load non-critical scripts async/defer
  - 예시: `async or defer attribute`
- **❌ Don't**: Synchronous third-party scripts
  - 예시: `<script src='...'> in head`

### Performance - Bundle Size (위험도: Medium)
- **✅ Do**: Monitor and minimize bundle size
  - 예시: `Bundle analyzer`
- **❌ Don't**: Ignore bundle size growth
  - 예시: `No size monitoring`

### Performance - Render Blocking (위험도: Medium)
- **✅ Do**: Inline critical CSS defer non-critical
  - 예시: `Critical CSS inline`
- **❌ Don't**: Large blocking CSS files
  - 예시: `All CSS in head`

### Forms - Input Labels (위험도: High)
- **✅ Do**: Always show label above or beside input
  - 예시: `<label>Email</label><input>`
- **❌ Don't**: Placeholder as only label
  - 예시: `placeholder='Email' only`

### Forms - Error Placement (위험도: Medium)
- **✅ Do**: Show error below related input
  - 예시: `Error under each field`
- **❌ Don't**: Single error message at top of form
  - 예시: `All errors at form top`

### Forms - Inline Validation (위험도: Medium)
- **✅ Do**: Validate on blur for most fields
  - 예시: `onBlur validation`
- **❌ Don't**: Validate only on submit
  - 예시: `Submit-only validation`

### Forms - Input Types (위험도: Medium)
- **✅ Do**: Use email tel number url etc
  - 예시: `type='email'`
- **❌ Don't**: Text input for everything
  - 예시: `type='text' for email`

### Forms - Autofill Support (위험도: Medium)
- **✅ Do**: Use autocomplete attribute properly
  - 예시: `autocomplete='email'`
- **❌ Don't**: Block or ignore autofill
  - 예시: `autocomplete='off' everywhere`

### Forms - Required Indicators (위험도: Medium)
- **✅ Do**: Use asterisk or (required) text
  - 예시: `* required indicator`
- **❌ Don't**: No indication of required fields
  - 예시: `Guess which are required`

### Forms - Password Visibility (위험도: Medium)
- **✅ Do**: Toggle to show/hide password
  - 예시: `Show/hide password button`
- **❌ Don't**: No visibility toggle
  - 예시: `Password always hidden`

### Forms - Submit Feedback (위험도: High)
- **✅ Do**: Show loading then success/error state
  - 예시: `Loading -> Success message`
- **❌ Don't**: No feedback after submit
  - 예시: `Button click with no response`

### Forms - Input Affordance (위험도: Medium)
- **✅ Do**: Use distinct input styling
  - 예시: `Border/background on inputs`
- **❌ Don't**: Inputs that look like plain text
  - 예시: `Borderless inputs`

### Forms - Mobile Keyboards (위험도: Medium)
- **✅ Do**: Use inputmode attribute
  - 예시: `inputmode='numeric'`
- **❌ Don't**: Default keyboard for all inputs
  - 예시: `Text keyboard for numbers`

### Responsive - Mobile First (위험도: Medium)
- **✅ Do**: Start with mobile styles then add breakpoints
  - 예시: `Default mobile + md: lg: xl:`
- **❌ Don't**: Desktop-first causing mobile issues
  - 예시: `Desktop default + max-width queries`

### Responsive - Breakpoint Testing (위험도: Medium)
- **✅ Do**: Test at 320 375 414 768 1024 1440
  - 예시: `Multiple device testing`
- **❌ Don't**: Only test on your device
  - 예시: `Single device development`

### Responsive - Touch Friendly (위험도: High)
- **✅ Do**: Increase touch targets on mobile
  - 예시: `Larger buttons on mobile`
- **❌ Don't**: Same tiny buttons on mobile
  - 예시: `Desktop-sized targets on mobile`

### Responsive - Readable Font Size (위험도: High)
- **✅ Do**: Minimum 16px body text on mobile
  - 예시: `text-base or larger`
- **❌ Don't**: Tiny text on mobile
  - 예시: `text-xs for body text`

### Responsive - Viewport Meta (위험도: High)
- **✅ Do**: Use width=device-width initial-scale=1
  - 예시: `<meta name='viewport'...>`
- **❌ Don't**: Missing or incorrect viewport
  - 예시: `No viewport meta tag`

### Responsive - Horizontal Scroll (위험도: High)
- **✅ Do**: Ensure content fits viewport width
  - 예시: `max-w-full overflow-x-hidden`
- **❌ Don't**: Content wider than viewport
  - 예시: `Horizontal scrollbar on mobile`

### Responsive - Image Scaling (위험도: Medium)
- **✅ Do**: Use max-width: 100% on images
  - 예시: `max-w-full h-auto`
- **❌ Don't**: Fixed width images overflow
  - 예시: `width='800' fixed`

### Responsive - Table Handling (위험도: Medium)
- **✅ Do**: Use horizontal scroll or card layout
  - 예시: `overflow-x-auto wrapper`
- **❌ Don't**: Wide tables breaking layout
  - 예시: `Table overflows viewport`

### Typography - Line Height (위험도: Medium)
- **✅ Do**: Use 1.5-1.75 for body text
  - 예시: `leading-relaxed (1.625)`
- **❌ Don't**: Cramped or excessive line height
  - 예시: `leading-none (1)`

### Typography - Line Length (위험도: Medium)
- **✅ Do**: Limit to 65-75 characters per line
  - 예시: `max-w-prose`
- **❌ Don't**: Full-width text on large screens
  - 예시: `Full viewport width text`

### Typography - Font Size Scale (위험도: Medium)
- **✅ Do**: Use consistent modular scale
  - 예시: `Type scale (12 14 16 18 24 32)`
- **❌ Don't**: Random font sizes
  - 예시: `Arbitrary sizes`

### Typography - Font Loading (위험도: Medium)
- **✅ Do**: Reserve space with fallback font
  - 예시: `font-display: swap + similar fallback`
- **❌ Don't**: Layout shift when fonts load
  - 예시: `No fallback font`

### Typography - Contrast Readability (위험도: High)
- **✅ Do**: Use darker text on light backgrounds
  - 예시: `text-gray-900 on white`
- **❌ Don't**: Gray text on gray background
  - 예시: `text-gray-400 on gray-100`

### Typography - Heading Clarity (위험도: Medium)
- **✅ Do**: Clear size/weight difference
  - 예시: `Bold + larger size`
- **❌ Don't**: Headings similar to body text
  - 예시: `Same size as body`

### Feedback - Loading Indicators (위험도: High)
- **✅ Do**: Show spinner/skeleton for operations > 300ms
  - 예시: `Skeleton or spinner`
- **❌ Don't**: No feedback during loading
  - 예시: `Frozen UI`

### Feedback - Empty States (위험도: Medium)
- **✅ Do**: Show helpful message and action
  - 예시: `No items yet. Create one!`
- **❌ Don't**: Blank empty screens
  - 예시: `Empty white space`

### Feedback - Error Recovery (위험도: Medium)
- **✅ Do**: Provide clear next steps
  - 예시: `Try again button + help link`
- **❌ Don't**: Error without recovery path
  - 예시: `Error message only`

### Feedback - Progress Indicators (위험도: Medium)
- **✅ Do**: Step indicators or progress bar
  - 예시: `Step 2 of 4 indicator`
- **❌ Don't**: No indication of progress
  - 예시: `No step information`

### Feedback - Toast Notifications (위험도: Medium)
- **✅ Do**: Auto-dismiss after 3-5 seconds
  - 예시: `Auto-dismiss toast`
- **❌ Don't**: Toasts that never disappear
  - 예시: `Persistent toast`

### Feedback - Confirmation Messages (위험도: Medium)
- **✅ Do**: Brief success message
  - 예시: `Saved successfully toast`
- **❌ Don't**: Silent success
  - 예시: `No confirmation`

### Content - Truncation (위험도: Medium)
- **✅ Do**: Truncate with ellipsis and expand option
  - 예시: `line-clamp-2 with expand`
- **❌ Don't**: Overflow or broken layout
  - 예시: `Overflow or cut off`

### Content - Date Formatting (위험도: Low)
- **✅ Do**: Use relative or locale-aware dates
  - 예시: `2 hours ago or locale format`
- **❌ Don't**: Ambiguous date formats
  - 예시: `01/02/03`

### Content - Number Formatting (위험도: Low)
- **✅ Do**: Use thousand separators or abbreviations
  - 예시: `1.2K or 1,234`
- **❌ Don't**: Long unformatted numbers
  - 예시: `1234567`

### Content - Placeholder Content (위험도: Low)
- **✅ Do**: Use realistic sample data
  - 예시: `Real sample content`
- **❌ Don't**: Lorem ipsum everywhere
  - 예시: `Lorem ipsum`

### Onboarding - User Freedom (위험도: Medium)
- **✅ Do**: Provide Skip and Back buttons
  - 예시: `Skip Tutorial button`
- **❌ Don't**: Force linear unskippable tour
  - 예시: `Locked overlay until finished`

### Search - Autocomplete (위험도: Medium)
- **✅ Do**: Show predictions as user types
  - 예시: `Debounced fetch + dropdown`
- **❌ Don't**: Require full type and enter
  - 예시: `No suggestions`

### Search - No Results (위험도: Medium)
- **✅ Do**: Show 'No results' with suggestions
  - 예시: `Try searching for X instead`
- **❌ Don't**: Blank screen or '0 results'
  - 예시: `No results found.`

### Data Entry - Bulk Actions (위험도: Low)
- **✅ Do**: Allow multi-select and bulk edit
  - 예시: `Checkbox column + Action bar`
- **❌ Don't**: Single row actions only
  - 예시: `Repeated actions per row`

### AI Interaction - Disclaimer (위험도: High)
- **✅ Do**: Clearly label AI generated content
  - 예시: `AI Assistant label`
- **❌ Don't**: Present AI as human
  - 예시: `Fake human name without label`

### AI Interaction - Streaming (위험도: Medium)
- **✅ Do**: Stream text response token by token
  - 예시: `Typewriter effect`
- **❌ Don't**: Show loading spinner for 10s+
  - 예시: `Spinner until 100% complete`

### Spatial UI - Gaze Hover (위험도: High)
- **✅ Do**: Scale/highlight element on look
  - 예시: `hoverEffect()`
- **❌ Don't**: Static element until pinch
  - 예시: `onTap only`

### Spatial UI - Depth Layering (위험도: Medium)
- **✅ Do**: Use glass material and z-offset
  - 예시: `.glassBackgroundEffect()`
- **❌ Don't**: Flat opaque panels blocking view
  - 예시: `bg-white`

### Sustainability - Auto-Play Video (위험도: Medium)
- **✅ Do**: Click-to-play or pause when off-screen
  - 예시: `playsInline muted preload='none'`
- **❌ Don't**: Auto-play high-res video loops
  - 예시: `autoplay loop`

### Sustainability - Asset Weight (위험도: Medium)
- **✅ Do**: Compress and lazy load 3D models
  - 예시: `Draco compression`
- **❌ Don't**: Load 50MB textures
  - 예시: `Raw .obj files`

### AI Interaction - Feedback Loop (위험도: Low)
- **✅ Do**: Thumps up/down or 'Regenerate'
  - 예시: `Feedback component`
- **❌ Don't**: Static output only
  - 예시: `Read-only text`

### Accessibility - Motion Sensitivity (위험도: High)
- **✅ Do**: Respect prefers-reduced-motion
  - 예시: `@media (prefers-reduced-motion)`
- **❌ Don't**: Force scroll effects
  - 예시: `ScrollTrigger.create()`

