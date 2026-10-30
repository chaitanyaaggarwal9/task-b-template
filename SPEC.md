# Challenge: My Medicine Reminders

Build a one-page reminder list for **fictional** medicines. The starting list is in `src/data.json`.
Build it in `src/App.tsx` (you may add more components). `App` must stay the **default export**.
Nothing needs to be saved: the list can reset when the page reloads.

Use the **exact words** shown in quotes below: the checker looks for them.

## Requirements

1. **Heading.** The page has one main heading (`h1`): "My Medicine Reminders".
2. **The list.** Show a list labelled "Medicines" (`aria-label="Medicines"`) with one item per medicine. Each item shows the name, dose and time (for example "Allergy syrup, 5 ml, 08:00"). The list is sorted by time, earliest first.
3. **Add a medicine.** A form with three inputs labelled "Medicine name", "Dose" and "Time" (a time input) and a button "Add". Clicking "Add" puts the new medicine in the list, in the right place by time, and clears the inputs.
4. **Name required.** If "Medicine name" is empty when you click "Add", nothing is added and the page shows "Please enter a medicine name".
5. **Taken checkbox.** Each item has a checkbox labelled "Taken: " followed by the medicine name (for example "Taken: Vitamin D"). A taken medicine is shown crossed out.
6. **Progress.** The page shows how many are taken, for example "1 of 4 taken". It updates when checkboxes change and when medicines are added or deleted.
7. **Delete.** Each item has a button labelled "Delete " followed by the medicine name (for example "Delete Eye drops") that removes it from the list.
8. **Filter.** Three buttons, "All", "To take" and "Taken", change which items are shown. "All" is selected at the start.
9. **Empty list.** When there are no medicines in the list, the page shows "No medicines yet".
10. **Disclaimer.** The page shows this exact sentence: "This is a practice app. It does not give medical advice."

## Tips

- Ask Claude for a plan first, then let it build one requirement at a time.
- Run `npm run dev` (ask Claude) and open the link to look at your page.
- Make it look good with Tailwind CSS classes, but finish the requirements first.
