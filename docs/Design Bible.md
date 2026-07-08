# 🌸 Clock Widget Golden Master v2.0

Status: Locked  
Version: 2.0  
Role: Foundation component for the widget collection

---

# Design Intent

The Clock Widget establishes the visual identity of the entire widget collection.

The design goal is:
- Elegant
- Minimal
- Calm
- Premium
- Easy to read
- Compatible with Notion dashboards

The widget should feel like a modern digital desk accessory rather than a decorative element.

---

# Layout System

## Structure

Two-panel clock layout:

- Left panel: Hours
- Right panel: Minutes

The two panels are intentionally separated to create visual breathing room.

Layout:

[ HOURS ]   [ MINUTES ]

---

# Dimensions

## Widget proportions

The widget maintains a vertical card format.

Base dimensions:
- Width: 180px per block
- Height: 240px per block

Responsive scaling:
- Uses CSS clamp() to resize proportionally.

---

# Spacing

## Block separation

Gap:
- 10px

The separation between blocks is an important part of the design identity.

---

# Corner System

Corner radius:
- 42px

Rule:
- Outer corners are rounded.
- Inner corners remain square to preserve the split-card appearance.

---

# Typography

## Primary numbers

Font:
- Montserrat

Weight:
- 900 (Extra Bold)

Purpose:
- Strong visual hierarchy
- High readability
- Modern geometric appearance

Number style:
- Tabular numerals
- Tight letter spacing

---

## Secondary labels

Elements:
- Day of week
- AM/PM indicator

Font:
- Montserrat

Weight:
- 800

Position:
- Bottom aligned

---

# Color System

## Default Theme

Name:
🌆 Dusty Rose

Mood:
Warm, elegant, soft, feminine, mature

---

## Hours Block

Color:

rgba(221,176,168,0.92)

Text:
White (#FFFFFF)

---

## Minutes Block

Color:

rgba(243,232,225,0.92)

Text:

#7E6A63

---

# Effects

## Frosted Glass

Blur:
10px

Usage:
Subtle only.

The effect should enhance softness without distracting from readability.

---

# Alignment Rules

Day of week:
- Bottom left
- 16px margin

AM/PM:
- Bottom right
- 16px margin

Both labels share the same baseline for visual balance.

---

# Do Not Change in Golden Master

The following are locked:

✅ Two-block structure  
✅ 10px separation  
✅ Dusty Rose + Cream default colors  
✅ Montserrat typography  
✅ Rounded outer corners  
✅ Minimal aesthetic  

Experiments should happen only in development versions.

---

# Future Extensions

Possible additions for development versions:

- Theme selector
- User customization
- Day/night mode
- 12/24 hour format
- Additional widgets using the same design system










## Changelog

v2.0
- Established Golden Master
- Locked typography
- Locked spacing system
- Locked Dusty Rose theme
