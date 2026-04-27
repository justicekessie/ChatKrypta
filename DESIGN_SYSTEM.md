# Krypta Chat — Design System (Mobile)

## 1) Foundations
### 1.1 Color Tokens
#### Brand
- `brand.500` #5B5CFF
- `brand.600` #4A4BDB
- `accent.500` #2ED3B7

#### Neutrals (Dark-first)
- `bg.primary` #0B0F1A
- `bg.secondary` #111827
- `surface.1` #151D2E
- `surface.2` #1B2438
- `text.primary` #F3F6FF
- `text.secondary` #A7B0C5
- `stroke.subtle` #2A3550

#### States
- `success` #22C55E
- `warning` #F59E0B
- `error` #EF4444
- `info` #38BDF8

### 1.2 Typography
- Font family: **Inter** (fallback: system sans)
- `display.lg` 34/40 semibold
- `title.lg` 24/30 semibold
- `title.md` 20/26 semibold
- `body.lg` 16/24 regular
- `body.md` 14/20 regular
- `label.sm` 12/16 medium

### 1.3 Spacing (8pt scale)
- `space.1` 4
- `space.2` 8
- `space.3` 12
- `space.4` 16
- `space.5` 20
- `space.6` 24
- `space.8` 32

### 1.4 Radius
- `radius.sm` 8
- `radius.md` 12
- `radius.lg` 16
- `radius.xl` 24
- `radius.pill` 999

### 1.5 Elevation
- `elevation.1` y=1 blur=4 alpha=8%
- `elevation.2` y=4 blur=12 alpha=14%

---

## 2) Component Library
### 2.1 Buttons
- Variants: `primary`, `secondary`, `ghost`, `danger`
- Sizes: `sm`, `md`, `lg`
- States: default, pressed, disabled, loading

### 2.2 Inputs
- Text field, search, OTP field
- Optional left/right icons
- Error + helper text states

### 2.3 Chat Components
- Chat list item
- Message bubble (incoming/outgoing)
- Timestamp + read state ticks
- Secure lock badge
- Composer with attachment tray

### 2.4 Privacy Components
- Biometric unlock sheet
- Hidden preview banner
- Session verification card
- Key change alert toast

### 2.5 Navigation
- Bottom tab bar (5 items)
- Top app bar (title + actions)
- Context action sheet

---

## 3) Interaction Rules
- Tap target min: **44x44 pt**
- Animation duration: 150–250ms
- Use spring easing for sheet transitions
- Haptic on: send, unlock, destructive confirm

---

## 4) Accessibility
- Contrast ratio: WCAG AA minimum
- Dynamic type support
- Semantic labels for screen readers
- Avoid color-only status communication

---

## 5) Theming
- Dark theme is default
- Light theme as first-class variant
- Tokens map via semantic names only (no hardcoded hex in components)

---

## 6) Figma File Structure
1. `00 Foundations`
2. `01 Components`
3. `02 Patterns`
4. `03 Screens Hi‑Fi`
5. `04 Prototype`
6. `05 Handoff`

---

## 7) Handoff Contract (Design → Dev)
For each component include:
- States + variants
- Token references
- Spacing constraints
- Behavior notes
- Accessibility notes
