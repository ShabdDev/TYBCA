# CA-311-MJ-P UI-UX Practical — Slip 12 — Part 2

**University:** Savitribai Phule Pune University  
**Course:** T.Y.BCA NEP — CA-311-MJ-P User Interface and User Experience (UI-UX) Design  
**Practical duration:** 3 Hours | **Maximum marks:** 35  
**Slip:** 12  
**File purpose:** Q2 + OR — Create an accessible online-payment form and prototype appropriate validation and error states.

> This file is written as an exam-execution guide. Follow the steps in order and do not skip the verification steps.


Create an accessible online-payment form and prototype appropriate validation and error states.

**Marks:** 20


## Required screens / frames

Create these top-level frames in this order:

1. `Payment Form`
2. `Error State`
3. `Success State`

**Prototype flow:** ['Form → validation error or successful payment']




## Figma setup — do this before starting

1. Open a browser and sign in to Figma.
2. From the Figma home screen, create a new **Design file**.
3. Rename the file to `CA-311-UIUX-Slip-N` where `N` is the slip number.
4. Create pages in the left Pages panel:
   - `01-Q1`
   - `02-Q2`
   - `03-OR`
   - `04-Viva`
5. Keep the work for each question on its own page so the examiner can find it quickly.
6. For a mobile UI, select the **Frame tool** (`F` or `A`) and choose a suitable phone preset. For a web UI, use a suitable desktop frame.
7. Rename every top-level frame clearly, for example `Q2-Home`, `Q2-Search`, `Q2-Checkout`.
8. Use **Auto layout** (`Shift + A`) for lists, buttons, cards, navigation bars and repeated content. This makes spacing and resizing easier.
9. Keep a consistent 8px spacing rhythm where practical, align elements to a clear grid, and keep text readable.
10. Save/allow Figma to autosave. Before submission, open the prototype with **Present** and test every required interaction.
11. For submission, click **Share** and copy the Figma file/prototype link if your practical requires a link.

Figma's current documentation confirms that frames are the main containers for UI designs and support layout guides, constraints, auto layout and prototyping. Auto layout can be applied with `Shift + A`; prototype interactions are created from the Prototype tab by connecting a hotspot to a destination and choosing a trigger, action and animation. citeturn0search2turn0search0turn0search1


## Question — Main option

> Create an accessible online-payment form and prototype appropriate validation and error states.

**Marks:** 20

## Step 1 — Create the Q2 page and frames

1. Open the `02-Q2` page.
2. Select the Frame tool (`F` or `A`).
3. Create the first top-level frame.
4. Set a consistent device/desktop size appropriate to the question.
5. Duplicate the frame for the remaining screens so the device dimensions remain consistent.
6. Rename every frame using the names below.

## Required screens / frames

Create these top-level frames in this order:

1. `Payment Form`
2. `Error State`
3. `Success State`

**Prototype flow:** ['Form → validation error or successful payment']


## Step 2 — Build the visual structure

1. Create the screen background.
2. Create the header/app bar.
3. Add the main title and supporting text.
4. Add the primary content sections.
5. Build repeated cards/lists using Auto layout (`Shift + A`).
6. Use consistent padding, gaps, corner radius, text sizes and icon sizes.
7. Add primary CTA buttons with clear action labels.
8. Add secondary actions only where they support the task.
9. Use realistic sample data instead of leaving major fields blank.
10. Keep important actions visible without requiring unnecessary scrolling.
11. Rename important layers so the Prototype panel is easy to understand.

## Step 3 — Make reusable components where appropriate

1. Build one primary button.
2. Select the button frame and create a component using the component control in the toolbar/right sidebar.
3. Duplicate/use instances for other primary actions.
4. Repeat for cards, navigation items, status badges or input fields when the same pattern appears more than once.
5. If states are needed, create variants such as Default / Pressed / Disabled / Error and keep the visual difference clear.

## Step 4 — Create the prototype

1. Open the **Prototype** tab in the right sidebar.
2. Select the first hotspot, normally a button, card or navigation item.
3. Drag the prototype node to the destination frame, or use **Add** in the Interactions section.
4. Set the trigger to `On click` (or `On tap` when the prototype device uses touch terminology).
5. Set the action to `Navigate to` for normal screen changes.
6. Select a simple animation such as `Dissolve` or `Smart animate` where matching layers make the transition meaningful.
7. Repeat until the required flow is connected.
8. Add a starting point to the first frame/flow.
9. Click **Present** and test every connection from start to finish.

Figma defines an interaction using a trigger, action, destination and animation; connections can be made from a hotspot to another top-level frame. citeturn0search1turn0search10

## Step 5 — Add overlays when the task needs them

Use an overlay for menus, confirmation dialogs, filters, date pickers, tooltips or similar content that should appear above the current screen.

1. Create the overlay as a frame.
2. Select the triggering button/icon.
3. In Prototype, connect it to the overlay frame.
4. Set action to `Open overlay`.
5. Choose an appropriate position.
6. Enable `Close when clicking outside` when appropriate.
7. Add a background behind the overlay if the design needs a modal effect.
8. Test opening and closing the overlay.

Figma's overlay workflow uses an `Open overlay` action and supports position, outside-click closing and background settings. citeturn0search5

## Step 6 — Test the complete practical

Run the prototype in **Present** mode and check:

- [ ] First screen opens.
- [ ] Every primary CTA works.
- [ ] Back/cancel actions work where needed.
- [ ] No important button is disconnected.
- [ ] Text is readable.
- [ ] Cards and controls are aligned.
- [ ] Required screens are included.
- [ ] Error/success/confirmation states behave as intended.
- [ ] The final state clearly communicates completion.

## Step 7 — Final presentation

1. Arrange the main screens left-to-right in logical order.
2. Keep the OR solution on the `03-OR` page rather than mixing it with the main answer.
3. Add a small label above each screen if useful.
4. Present the prototype once before submission.
5. Click **Share** if a link is required and copy the appropriate link.

Figma's sharing workflow uses the **Share** button and allows file/prototype sharing depending on the available plan and permissions. citeturn0search11


## Detailed Figma build procedure

### A. Create the visual design

1. On `02-Q2`, create the first screen using the Frame tool.
2. Choose the appropriate mobile/desktop frame size.
3. Add a background layer.
4. Add the header/navigation.
5. Add the screen title.
6. Add the primary content.
7. Add all controls required by the question.
8. Use Auto layout for repeated rows, cards, menus and button contents.
9. Use consistent typography and spacing.
10. Use components for repeated UI.
11. Duplicate the screen frame when creating the next state/screen.
12. Change only the content that should change between states.
13. Rename layers and frames clearly.

### B. Create interactions

1. Select the clickable object.
2. Open **Prototype** in the right sidebar.
3. Drag the prototype node to the destination frame.
4. Set the trigger to `On click`/`On tap`.
5. Select the appropriate action:
   - `Navigate to` for another screen.
   - `Open overlay` for a modal/menu/filter.
   - `Back` for returning to the previous state where appropriate.
6. Select a transition such as Dissolve or Smart animate.
7. Repeat for every required path.
8. Set the first frame as the flow starting point.
9. Click **Present**.
10. Perform the flow exactly as a user would and fix every broken connection.

Figma's prototype model uses a hotspot, connection and destination, with trigger/action/animation settings. citeturn0search1

### C. Use Smart Animate only when useful

If two frames contain matching layers and you want a smooth change:

1. Keep the corresponding layer names/hierarchy consistent.
2. Create the prototype connection.
3. Set animation to `Smart animate`.
4. Set a short duration such as 300ms–500ms for a normal UI transition.
5. Preview the result.

Figma's Smart Animate works by matching layers between frames and animating their changes. citeturn0search4

### D. Final examiner check

- [ ] Main question is fully covered.
- [ ] Required number of screens/steps is present.
- [ ] Every required field is visible.
- [ ] Main CTA is obvious.
- [ ] Prototype starts at the correct screen.
- [ ] All required interactions work.
- [ ] No accidental dead ends.
- [ ] OR solution is separated.
- [ ] File/page/frame names are clear.
- [ ] Prototype has been tested in Present mode.

## Validation-specific implementation

Create three states:
1. **Default:** empty/ready form.
2. **Error:** invalid or missing fields with specific inline messages.
3. **Success:** valid submission with confirmation.

Example errors:
- Card number: `Enter a valid card number.`
- Expiry: `Enter a valid expiry date.`
- CVV: `Enter a 3-digit CVV.`

Connect the Pay button to the appropriate state for demonstration. Do not make error messages depend only on red colour.



# Q2 Main — Final submission checklist

- [ ] Question is written clearly.
- [ ] All required screens/steps are present.
- [ ] All required Figma elements are visible.
- [ ] Prototype interactions have been tested where required.
- [ ] Frame/layer names are clear.
- [ ] Design is aligned and readable.
- [ ] Main Q2 is ready for examination.
