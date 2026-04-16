# Diamont Family Cabin — Website

This repo holds the single-page website for the cabin. Any change you save here goes live automatically in about a minute.

---

## How to edit the site (no installs, no tools, just GitHub)

Everything you'd normally want to change — text, the nightly rate, rules, the email that gets booking requests, the calendar — is already marked inside the file. You do not need to install anything or learn any code. You just need a web browser and your GitHub account.

### The 60-second version

1. Click **`index.html`** in the file list above.
2. Click the **pencil icon** ✏️ in the top-right of the file view (tooltip: "Edit this file").
3. Press **Ctrl+F** (Windows) or **Cmd+F** (Mac) and type `EDIT:` to jump to editable spots.
4. Change the text you want to change.
5. Scroll to the bottom, click the green **Commit changes…** button, then **Commit changes** again in the popup.
6. Wait about a minute. The live site updates automatically.

That's it. If you mess up, see "Undoing a mistake" below — nothing you do here is permanent.

---

## What the `EDIT:` markers mean

Throughout the file you'll see comments like this:

```html
<!-- EDIT: Nightly rate -->
<div class="fact-row"><span class="fact-key">💵 Rate</span><span class="fact-val">$200 / night</span></div>
```

Those `<!-- EDIT: ... -->` lines are notes to **you**. They don't show up on the website. They just tell you "this is a spot you might want to change."

The rule of thumb:

- **Safe to change:** the plain text between tags. In the example above, `$200 / night` is safe to change to `$225 / night`.
- **Don't touch:** anything between `<` and `>` brackets. Those are instructions for the browser.
- **If you break something by accident:** no problem. See "Undoing a mistake" below.

---

## Common things you'll want to edit

Use **Ctrl+F / Cmd+F** and search for `EDIT:` to jump through all of them. Here are the ones you're most likely to touch:

| What you want to change | Search for |
|---|---|
| Nightly rate | `EDIT: Nightly rate` |
| House rules (add, remove, or reword) | `EDIT: House rules list` |
| Welcome text at the top | `EDIT: Welcome paragraph` |
| Check-in / check-out times | `fact-key">🕐` and `fact-key">🕚` |
| Max guests / sleeping info | `fact-key">🛏` |
| Email that receives booking requests | `EDIT: EMAIL ADDRESS` |
| Google Calendar shown on the page | `EDIT: GOOGLE CALENDAR` |
| Booking steps (1–4) | `EDIT: Step` |
| "Things to do nearby" text | `EDIT: Nearby` |

---

## Undoing a mistake

**Before you commit:** if you haven't clicked "Commit changes" yet, just close the browser tab. Nothing is saved.

**After you commit:** every change is recorded. To undo:

1. Click **`index.html`** in the file list.
2. Click **History** (top-right of the file view).
3. Click the commit you want to go back to.
4. Click the **⋯** menu and choose **Revert** — or just copy the old text from there and paste it back in a new edit.

You literally cannot break the site in a way that can't be undone in about 30 seconds.

---

## Checking that your change worked

After you commit:

1. Wait about a minute.
2. Go to the live site URL (ask the developer if you don't have it).
3. Refresh the page (sometimes a hard refresh — **Ctrl+Shift+R** / **Cmd+Shift+R** — is needed to bust the cache).

If something looks wrong or a piece of the page disappeared, you probably deleted a `<` or `>` bracket by accident. Use **History** (above) to revert and try again.

---

## Things that require the developer (not you)

- Changing photos on the page
- Changing colors, fonts, or the overall layout
- Adding new sections
- Anything where you're not sure what to do

Shoot them a message — it's usually a 5-minute fix on their end.
