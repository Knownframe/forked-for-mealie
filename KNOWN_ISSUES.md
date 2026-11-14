# Known issues

Problems we know about in the current release of Forked, what to do in the
meantime, and the release that fixes them. Check here before
[reporting a bug](https://github.com/Knownframe/forked-for-mealie/issues/new?template=bug_report.yml).
Fixed issues stay listed for one release with the version that fixed them.
Planned releases can move; see the [roadmap](ROADMAP.md).

## Recipes

### Allergy and diet warnings only recognize English ingredient names

Forked matches allergies and diets against English ingredient names, so a
recipe written in another language may not be flagged: "arachide" isn't
matched as peanut, for example. Forked can't guarantee allergen safety in any
language, and this gap makes it easier to miss something.

- **Affects:** all versions of Forked, with recipes that aren't in English.
- **Workaround:** check those recipes' ingredients yourself.
- **Fix planned:** French in 2027, along with translating the app; other
  languages after that.

## Households

### Items a member added can go missing after they leave and rejoin

If a Household member leaves and rejoins, or the organizer removes them,
items they added to the shared plan or Shopping list before that may be
missing on their phone, and on the phone of anyone who joins later. Nothing is
lost: members who already had those items still have them.

- **Affects:** Forked 2026.8.0 through 2026.11.1.
- **Workaround:** add a missing item again.
- **Fix:** fixed in 2026.12.

### Members see a hosted meal's dishes as ordinary meals

When the organizer hosts a meal and shares the Plan, members don't see it as a
hosted meal: its dishes show among their week's meals, labelled with the
meal's name, without the serving time, guests, or timeline. Nothing is lost:
the hosted meal is complete on the organizer's phone.

- **Affects:** Forked 2026.11.0 and later, in a Household that shares the Plan.
- **Workaround:** the organizer runs the day from their phone. Since 2026.12,
  a member who starts a new plan or clears the week keeps the hosted dishes.
- **Fix planned:** 2027.1, when hosted meals sync to every member.

### "Copy Link" in the sharing sheet doesn't invite anyone

In Apple's Household sharing sheet, **Copy Link** copies a link that only
people already invited can open. Anyone else sees that the item is
unavailable. Forked can't remove that button from Apple's sheet.

- **Workaround:** choose **Invite with Link** and send the link it makes.

## Cooking

### A finished timer chimes once and is silent in silent mode

When a step timer ends, your iPhone plays the notification sound once, and
not at all when the ring switch is set to silent. The Lock Screen and Dynamic
Island show Done, and the notification repeats it.

- **Workaround:** keep the ring switch on while you cook, or keep an eye on the
  Lock Screen.
- **Fix:** fixed in 2026.12 on iOS 26: timers ring like the Clock app's until
  you stop them, even in silent mode.

## Shopping

### Item names lose their capitals

An item you type, like "BBQ sauce", is saved as "Bbq Sauce".

- **Workaround:** none; the item itself is unaffected.
- **Fix:** fixed in 2026.12.
