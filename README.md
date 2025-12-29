# F5 Refresh on macOS using Karabiner-Elements

By default, **macOS does not use the F5 key to refresh pages** like Windows or Linux.
Instead, refreshing requires **Command + R**, which is awkward when using an
external or mechanical keyboard.

This repository shows how to make **F5 refresh on Mac** by mapping the F5 key
to **Command + R** using **Karabiner-Elements**.

---

## Why Doesn’t F5 Refresh on Mac?

On macOS, function keys are not treated as primary shortcuts for actions like
refresh. Apple historically relies on Command-based shortcuts, so pressing **F5**
does nothing in most apps.

If you’re coming from Windows or Linux and trying to use **F5 to refresh on a Mac**,
this behavior is especially frustrating — particularly on external keyboards.

---

## Solution: Map F5 to Command + R

Using Karabiner-Elements, we can remap the **F5 key** so that it behaves like a
refresh key across macOS.

**What this does:**
- Maps **F5 → Command + R**
- Works system-wide
- Ideal for external keyboards
- Compatible with Chrome, Safari, Firefox, and Finder

---

## Requirements

- macOS
- **Karabiner-Elements** installed  
  https://karabiner-elements.pqrs.org/

---

## Installation

1. Install Karabiner-Elements if you haven’t already.
2. Open **Karabiner-Elements**
3. Go to **Complex Modifications**
4. Click **Add Rule**
5. Import or paste the rule from the JSON file in this repository
6. Enable the rule

Once enabled, pressing **F5** will refresh pages just like **Command + R**.

---

## Example Karabiner Rule

The rule maps the F5 key directly to a refresh command:

