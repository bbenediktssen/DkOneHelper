# DkOne Helper

A small Microsoft Edge extension that duplicates a filled-in work journal entry across several days on www.dkone.is.

**Unofficial.** DkOne Helper is not made by, endorsed by or affiliated with DKONE.

## What it does

When the "Skrá vinnu" (Add work) dialog is open, the extension adds a bar above the Vista button with a number box and a **Duplicate** button.

1. Fill in the entry as you normally do: project, phase, task, text, hours, billing and any cost lines.
2. Enter how many days you want in the bar.
3. Press **Duplicate**. A summary of the entry and every date is shown. Nothing is saved until you confirm.

The form you filled in is saved as the first entry. The remaining entries are created on the following days with the same project, phase, task, text, hours, billing setting and cost lines. A Stop button interrupts a run. The Duplicate button is disabled whenever Vista is disabled.

Not copied: Víddir, Akstur and Tilvísun. If these differ from your original entry, the extension stops instead of saving.

Always check the entries it creates in the journal.

## Privacy

DkOne Helper does not collect, store or transmit any data. It has no background script, makes no network requests, uses no analytics and loads no remote code. It reads the values of the entry form that is open on the page, only when you press Duplicate, and uses them to fill in the same form again on the same page. The extension requests no permissions beyond running on https://www.dkone.is.
