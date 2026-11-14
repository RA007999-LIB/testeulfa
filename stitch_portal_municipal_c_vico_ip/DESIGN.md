---
name: Ipê Cívico
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#43474d'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#74777e'
  outline-variant: '#c3c6ce'
  surface-tint: '#49607c'
  primary: '#001428'
  on-primary: '#ffffff'
  primary-container: '#0f2942'
  on-primary-container: '#7991af'
  inverse-primary: '#b0c9e8'
  secondary: '#805600'
  on-secondary: '#ffffff'
  secondary-container: '#feb63c'
  on-secondary-container: '#6e4900'
  tertiary: '#001133'
  on-tertiary: '#ffffff'
  tertiary-container: '#00245d'
  on-tertiary-container: '#5c8bf1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4ff'
  primary-fixed-dim: '#b0c9e8'
  on-primary-fixed: '#011d35'
  on-primary-fixed-variant: '#314863'
  secondary-fixed: '#ffddb0'
  secondary-fixed-dim: '#ffba46'
  on-secondary-fixed: '#281800'
  on-secondary-fixed-variant: '#614000'
  tertiary-fixed: '#d9e2ff'
  tertiary-fixed-dim: '#b0c6ff'
  on-tertiary-fixed: '#001945'
  on-tertiary-fixed-variant: '#00429c'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
  civic-blue-dark: '#001B3A'
  civic-blue-mid: '#1E3A8A'
  ipe-gold-bright: '#EAB308'
  ipe-gold-deep: '#CA8A04'
  status-regular: '#16A34A'
  status-attention: '#D97706'
  status-irregular: '#DC2626'
  status-regular-bg: '#F0FDF4'
  status-attention-bg: '#FFFBEB'
  status-irregular-bg: '#FEF2F2'
  surface-canvas: '#F8FAFC'
  surface-card: '#FFFFFF'
  border-subtle: '#E2E8F0'
  border-strong: '#94A3B8'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
  headline-md:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  data-mono:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system establishes an authoritative, accessible, and citizen-first digital public service standard for municipal management, with dedicated workflows for urban land regularization (REURB) and property taxation (IPTU). Built around institutional trust and civic transparency, it pairs Brazilian government digital service rigor (Padrão Digital Gov.br) with regional warmth inspired by the golden Ipê.

The aesthetic follows **Corporate / Modern Civic Realism**:
- **Clarity over ornament:** Uncluttered layouts, deliberate structural grids, and explicit visual hierarchies prioritize legal certainty and fiscal accuracy.
- **Inclusivity & e-MAG/WCAG 2.1 AA+ Compliance:** Rigorous contrast ratios, persistent access tools (contrast toggle, dynamic scaling indicators A+/A-), and resilient typographic metrics that avoid truncation or overflow during magnification.
- **Civic Trust:** Dense tabular records, geospatial overlays (orthophoto/cadastral parcels), and audit logs are presented with calm, structured composure rather than decorative flourish.

## Colors

The chromatic architecture provides uncompromised legibility for administrative processing and citizen self-service.

- **Primary (`#0F2942`) & Secondary (`#CA8A04`):** Deep institutional navy anchors structural headers, table headers, and primary actions. Solar Ipê Gold provides luminous focus for high-priority civic notices, action emphasis, and active tabs without compromising text readability (gold elements pairing with `#001B3A` text for AA compliance).
- **Tertiary Gov Blue (`#1351B4`):** Directly aligned with official Gov.br interactive conventions, reserved for standard text links, breadcrumbs, and standard interactive controls.
- **Strict Civic Semaphore (REURB & Cadastral Status):**
  - **Regular (`#16A34A`):** Titulado, Regularizado, Quitado, Certidão Emitida. Paired with `#F0FDF4` background.
  - **Atenção/Pendente (`#D97706`):** Notificação Emitida, Diligência em Aberto, Parcelamento Vigente. Paired with `#FFFBEB`.
  - **Urgente/Irregular (`#DC2626`):** Débito Inscrito em Dívida Ativa, Embargo, Sobreposição Cadastral Crítica. Paired with `#FEF2F2`.
- **High-Contrast Safe Mode:** When high contrast is enabled, canvas tokens switch to pure `#000000`, surfaces to `#121212`, text to `#FFFFFF`, and borders to `#FFFF00` / `#00FFFF`.

## Typography

Inter is implemented across all typographic tiers for its humanist construction, large x-height, clear differentiation of ambiguous glyphs (such as `0` vs `O`, `l` vs `1`), and superior hinting on diverse displays.

- **Cadastral & Number Formatting:** Numeric indicators for Inscrição Imobiliária, Código de Logradouro, CPF/CNPJ, and Valores Venais must use `font-variant-numeric: tabular-nums` to guarantee vertical column alignment across tax calculations and fiscal tables.
- **Dynamic Text Resizing (A+ / A-):** All layout containers rely on `rem` values. Typography accommodates up to 200% scale without horizontal clipping or broken containers.
- **Visual Weight Guidelines:** Never use font weights below `400` on public service interfaces. Subtext and caption labels default to `0.875rem` (`14px`) to preserve readability for senior citizens and low-vision users.

## Layout & Spacing

The layout philosophy follows a controlled, 12-column fluid grid system with structural boundaries to prevent excessively long reading lines on ultra-wide GIS and management screens.

- **Breakpoints:**
  - **Mobile (`< 640px`):** Single column reflow, sticky bottom action bar for primary civic submissions, full-width cadastral cards. Outer margin: `1rem`, gutter: `1rem`.
  - **Tablet (`640px - 1024px`):** 6-column grid with collapsible side navigation, 2-column card arrangements.
  - **Desktop (`> 1024px`):** 12-column grid with a maximum content canvas of `1440px`. Dedicated master-detail split views (e.g., 5 columns orthophoto viewer, 7 columns cadastral inspection data). Outer margin: `2rem`, gutter: `1.5rem`.
- **Rhythm & Proximity:** Form inputs and validation messages maintain an immediate `0.25rem` relation. Form groups are spaced by `1.5rem`. Macro-sections (Tax summary, Property history, Titling documents) are separated by `2rem` or `3rem`.

## Elevation & Depth

Visual hierarchy uses **low-contrast outlines** supplemented by subtle, purposeful tonal separation to maintain a crisp, official document appearance.

- **Ground Level (Canvas):** `#F8FAFC` provides an eye-resting base that distinguishes structural cards from the browser viewport.
- **Surface Level (Cards, Data Sheets):** `#FFFFFF` surfaces bounded by a solid `1px` border (`#E2E8F0`). Avoid heavy drop shadows; depth is conveyed by perimeter definition rather than blurred volume.
- **Active / Floating Overlays (Map Controls, Modals, Dropdowns):**
  - **Elevation 1 (Toolbars, Map controls):** `box-shadow: 0 1px 3px 0 rgb(15 41 66 / 0.1), 0 1px 2px -1px rgb(15 41 66 / 0.1)`. Border: `1px solid #CBD5E1`.
  - **Elevation 2 (Fiscal Detail Drawers, Dialogs):** `box-shadow: 0 10px 15px -3px rgb(15 41 66 / 0.12), 0 4px 6px -4px rgb(15 41 66 / 0.08)`.
- **Orthophoto Map Overlay Tier:** Overlays on satellite and orthophoto rasters must utilize a translucent backdrop `#0F2942` with 85% opacity, paired with a `1px` golden border (`#EAB308`) for selected parcel perimeters.

## Shapes

The shape system adopts **Level 1 (Soft)** roundedness. Crisp geometry reflects municipal institutional rigor, steering away from juvenile pill shapes or overly playful rounded corners.

- **Standard Elements (Inputs, Buttons, Badges):** `4px` (`0.25rem`) border-radius.
- **Cards, Panels, and Table Wrappers:** `8px` (`0.5rem`) border-radius (`rounded-lg`).
- **Modal Dialogs and Orthophoto Control Floating Sheets:** `12px` (`0.75rem`) border-radius (`rounded-xl`).
- **Focus Indicators:** Unrounded or matching element radius with a distinct `2px` offset outline in `#1351B4` (or `#EAB308` in dark/contrast modes) to ensure unambiguous keyboard navigation.

## Components

### Buttons
- **Primary (Civic Action):** `#0F2942` background, `#FFFFFF` text, `4px` radius, minimum touch target of `44px` height. Hover state shifts to `#1E3A8A`.
- **Secondary / Fiscal Action:** Transparent background, `2px` border in `#0F2942`, `#0F2942` text. Hover fills to `#0F2942` with `#FFFFFF` text.
- **Emphasis / Ipê Dourado Action:** `#CA8A04` background with `#001B3A` text for actions requiring high user visibility (e.g., "Emitir DAM/Guia IPTU", "Assinar Termo REURB").
- **Focus State:** `3px` solid `#1351B4` ring with a `2px` white gap.

### Badges & Status Chips
- Height: `24px`, padding: `0 8px`, border-radius: `4px`, font size: `0.75rem`, bold weight.
- **Regular (Aprovado / Regularizado):** Background `#F0FDF4`, border `1px solid #BBF7D0`, text `#16A34A`. Accompanied by a leading checkmark icon.
- **Atenção (Em Análise / Notificado):** Background `#FFFBEB`, border `1px solid #FDE68A`, text `#D97706`. Accompanied by a warning icon.
- **Irregular (Débito / Sobreposição):** Background `#FEF2F2`, border `1px solid #FECACA`, text `#DC2626`. Accompanied by an alert circle icon.

### Form Inputs & Selects
- Height: `44px`, border: `1px solid #94A3B8`, background: `#FFFFFF`, text: `#0F2942`.
- Active / Focus: Border changes to `#1351B4` with a `2px` glow of `#1351B4` at 20% opacity.
- Labels: Always visible outside the field (`body-sm`, bold), explicitly linked via `for` and `id`. Never use placeholder text as a substitute for labels.
- Assistance/Error Text: Positioned below the field, displaying clear instructions with dedicated icons for error states.

### Data Tables (IPTU & REURB Loteamentos)
- Header: `#0F2942` solid background with `#FFFFFF` text or `#F1F5F9` neutral header with `#0F2942` text and uppercase `0.75rem` tracking.
- Row striping: Alternating `#FFFFFF` and `#F8FAFC`. Border dividers: `1px solid #E2E8F0`.
- Data alignment: Text left-aligned; numbers, dates, and currency right-aligned using tabular figures.
- Hover: Entire row highlights with `#F1F5F9` on cursor hover.

### GIS & Orthophoto Map Viewer Cards
- Floating HUD cards overlaid on map canvases have solid `#FFFFFF` backgrounds with an institutional `#0F2942` header banner.
- Layer selectors use custom radio lists with visual swatches showing line color conventions: Blue for lote boundaries, Green for áreas verdes, and Red for áreas non aedificandi or embargos.

### Citizen Notice & REURB Protocol Cards
- Clean cards framed with a `4px` left accent line corresponding to the status color (Green, Yellow, Red, or Civic Blue).
- Header contains clear administrative protocol number in bold monospace, followed by property address, current stage in the REURB workflow, and direct actions.