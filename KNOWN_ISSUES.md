# Known issues

Problems we know about in the current release of Forked, what to do in the
meantime, and the release that fixes them. Check here before
[reporting a bug](https://github.com/Knownframe/forked-for-mealie/issues/new?template=bug_report.yml).
Fixed issues stay listed for one release with the version that fixed them.
Planned releases can move; see the [roadmap](ROADMAP.md).

## Recipes

### Recipe times are missing with Mealie 3.29 or later

Mealie 3.29 changed how it stores a recipe's prep, cook, and total times, and
Forked 2026.11.0 didn't read the new format. Recipes from Mealie 3.29 and later
showed no times, and cook-time filters in Quick Picks and Plan couldn't use
them. Nothing was lost: the times stayed on your server.

- **Affects:** Forked 2026.11.0 and earlier, with Mealie 3.29 or later.
- **Workaround:** see a recipe's times in Mealie's web app.
- **Fix:** fixed in 2026.11.1. Update Forked from the App Store, and times come
  back on their own; there's nothing to resync.

## Households

### Items a member added can go missing after they leave and rejoin

If a Household member leaves and rejoins, or the organizer removes them,
items they added to the shared plan or Shopping list before that may be
missing on their phone, and on the phone of anyone who joins later. Nothing is
lost: members who already had those items still have them.

- **Affects:** Forked 2026.8.0 and later.
- **Workaround:** add a missing item again.
- **Fix planned:** 2026.12.

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
- **Fix planned:** 2026.12, on iOS 26: timers that ring like the Clock app's
  until you stop them.

## Shopping

### Item names lose their capitals

An item you type, like "BBQ sauce", is saved as "Bbq Sauce".

- **Workaround:** none; the item itself is unaffected.
- **Fix planned:** 2026.12.
