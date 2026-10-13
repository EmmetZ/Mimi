# Settings organization and editing flow

The growing settings page mixed current-session choices, provider models,
connection credentials and configuration management. Credential editing changed
page height when opened, status icons depended on hover, and the subtitle page
used a different container/background from its siblings.

## Responsibilities

- Subtitles: appearance, preview, placement and display behavior.
- Audio & Languages: input sources, active configuration, recognition language
  and translation target. Current language controls have one settings-page home. Original-only is one
  choice in the target picker, without a second skip-translation switch.
- Models & Services: provider configurations, available model/route choices,
  workspace/address, connection credentials, language presets, proxies and
  configuration management. Presets describe a configuration's saved selection;
  they do not duplicate the live source/target editor.
- Save & Export: opt-in local history/audio and existing export actions.
- General: application preferences, updates and advanced diagnostics.

Retain native and existing hash navigation targets. A new category must not
break tray/overlay links to the active configuration or Apple resource setup.
All pages share the same canvas, field alignment, section rhythm, neutral colors,
button sizes and Lucide icon family. Use flat sections rather than a card around
each group. The subtitle preview itself remains distinct from its appearance
controls. Keep explicit actions, readable state labels and normal-size errors;
non-essential explanations remain in the existing help tooltips.

## Editing

Saved connection inputs stay in the same place, masked by default. The inline
view action alone reads a saved key; viewing is not an edit. Save and Cancel
appear for a replacement draft; success or cancellation discards that draft,
while a failed save keeps it for retry. Preserve reveal invalidation on blur,
hide, navigation, deletion and unmount. Safe editor metadata may load when the
form is visible; it must not contain saved secrets.

Qwen-MT model selection has its own model section. Custom recognition and text
models remain editable without exposing or re-entering an unchanged saved key.
Changing a destination still requires appropriate fresh authentication. Editing
an already configured inactive profile saves it without implicitly selecting
it. Copy and Delete stay together in configuration management; deletion uses
its standard confirmation modal. Names remain single-line automatic fields
without a chevron that resembles a selection menu.

New desktop Alibaba configurations start with LiveTranslate. An incomplete
empty workspace may persist as setup metadata; session and check validation
still rejects it before provider access. Saving a key alone does not activate
an unfinished route. Existing profiles, explicit ASR + MT and duplicates keep
their saved mode. Current language choices use the shared capability rules.

Product-facing settings, overlay/tray labels, native window/display names and
Android strings use Mimi. Preserve application identifiers, storage keys,
signing requirements, binary/update filenames and canonical installation paths.

## Configuration list density

Keep the four explicit Use / Edit / Copy / Delete actions in one horizontal
strip aligned with the profile heading. Let the whole strip move below the
identity when the available width is insufficient; at minimum width, omit
redundant action icons while keeping their text and accessible names. Do not
force a two-by-two action grid that determines the height of otherwise short
rows. Keep the destructive action visually distinct.

Align the recognition mark with the title, including mixed-provider profiles.
Avoid repeating a recognition provider already used as the profile title;
retain distinct custom recognizer names and the independent translation route.
Normal credential information belongs in adjacent help. Missing/unavailable
credentials remain visible, and the active marker belongs beside the title.
Use the same artwork dimensions as its icon slot to prevent marks crowding text.

## Verification

Use synthetic browser fixtures for clicks, responsive geometry and review
screenshots; distinguish them from native-device evidence. Check all eight UI
languages at minimum/default widths and light/dark themes, including platform
input controls. Cover saved/missing credentials, cancellation, delayed results,
failed saves, model-only edits, active/paused guards, category navigation and
confirmation cancellation. Actual provider calls, capture and recording need
separate user authorization.
