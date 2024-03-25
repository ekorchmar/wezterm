---
tags:
  - appearance
---

# `wayland_kwin_blur = false`

Informs KWin on Wayland that the backdrop of the window should or should not be blurred.
Only has effect when combined with `window_background_opacity < 1.0`, or if the window is made
transparent by the compositor means.

As of time of writing, only KWin provides Wayland protocol extension to support this feature.

See also [win32_system_backdrop](win32_system_backdrop.md) and
[macos_window_background_blur](macos_window_background_blur.md) for blur effects on other platforms.

