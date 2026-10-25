# Forked Changelog

Released versions of Forked on the App Store, newest first. Each entry is the
version's App Store "What's New" text. Planned work is in the
[roadmap](ROADMAP.md).

## 2026.11.0

Cook with your iPhone in reach, and your plan on your Home Screen.

- Start Cooking shows the ingredients each step needs
- Step timers run on your Lock Screen and in the Dynamic Island, several at
  once
- Host a Meal (Pro): plan a big meal for a date and your guests, scale every
  dish, follow a timeline back from serving, and cook every dish at once with
  Cook Together
- Share any meal as a menu card with photos
- Widgets for your Home Screen and Lock Screen: what's next to cook, your
  plan, and what's left to buy
- Ask Siri "What's next to cook?" or to add something to Shopping, open a
  favorite recipe by name, and find recipes in Spotlight (iOS 18 and later)
- Import a recipe from almost any cooking website: in Library, tap + and
  choose From a Link, then check it before it's saved
- Recipe pages list the tools you'll need and warn about allergens; tap a
  Quick Picks card to open its recipe
- Shopping shows what you're adding and suggests foods as you type
- Pick any recipe for your plan, drinks and desserts included
- Edit nutrition, and create or rename tags and categories
- Changes on your server arrive within minutes, and large libraries download
  faster, with time left shown
- Your plans, Plan History, Household data, and unsent edits are now included
  in iPhone backups
- Households show when someone joins or leaves, or changes the shared plan or
  list
- Allergy and diet matching knows more foods
- Settings › Storage shows what Forked keeps on your iPhone and in iCloud

Importing and editing need Mealie 3.21 or later. Everything you use today
remains free.

## 2026.10.1

Fixes from your launch feedback, thank you.

- Ingredients read as written. Lines that Mealie kept as plain text, like "2
  tablespoons unsalted butter", no longer show just "2 2", and they scale,
  copy, and add to Shopping correctly. Allergy and diet filters now see those
  foods too.
- Behind Cloudflare Access or Pangolin? Add your proxy's request headers under
  Connection Options. They stay in this iPhone's Keychain and go only to your
  server.
- Editing a recipe no longer adds a duplicate tag like "instant-pot" beside
  "Instant Pot".
- The editor's tag and category lists fill in when opened from a recipe.
- Edit Connection checks a plain-HTTP home server without the long wait.

## 2026.10.0

Your whole Mealie library, now native in Forked.

- Library: browse every recipe as photo cards, search ingredients and steps,
  filter by tag, category, favorites, rating, or cook time, and add any recipe
  to your plan or Shopping list
- Recipes are saved for offline reading: big photo, checkable ingredients with
  section headings, numbered steps, and servings that scale the amounts
- Edit recipes, add new ones, and replace photos. Changes save to your server
  and wait safely while you're offline
- Favorite and rate from recipes, Library, and Quick Picks
- If a recipe changed on the server while you were editing, Forked shows both
  versions and lets you choose
- Sign in with your Mealie username and password; Forked never stores the
  password
- Diets like vegan, halal, or dairy free now leave out recipes that don't fit,
  and allergy matching understands more ways of saying things, like "milk" or
  "nut allergy"
- Move Shopping items between sections, and Forked remembers where they go. On
  iPhones with Apple Intelligence, items Forked doesn't recognize are sorted on
  the device
- Reorder plan meals, add My Picks to your plan, and start a step's timer in
  one tap
- Start Cooking keeps the screen on, and Keep Screen On in Settings keeps your
  iPhone awake anywhere in Forked
- Households are more dependable: joining starts as soon as you tap the
  invitation, a sync the organizer turns off stays off, and shared meals fill
  in as soon as their recipe arrives
- Settings now opens from the gear on your Profile tab

Editing, favorites, ratings, and new recipes need Mealie 3.21 or later.
Everything you use today remains free.

## 2026.8.1

Forked Pro is available to buy in the App Store. No other changes from
2026.8.0.

## 2026.8.0

Households: cook from one plan together. A Forked Pro owner can invite up to
four people to share a meal plan and shopping list. Everyone's edits sync
through iCloud, while credentials, dietary preferences, and Plan History stay
private.

Forked Pro, a $9.99 one-time purchase with Family Sharing, also adds:

- Plan History and Use This Plan Again
- Reuse Ingredients, to favor meals that share ingredients
- Avoid Recent Meals

Also new for everyone:

- Nutrition at a glance: calories per serving with a protein, fat, and carb bar
- Quantities read as fractions, like ½ teaspoon, in recipes and Shopping
- Emoji avatars for Chef Profiles, with a picker organized by category
- Swipe between steps while cooking, and step timers start at the time the
  step calls for
- Swipe to remove a cooked meal from your plan
- Undo a Keep in Quick Picks, and saved picks now use a bookmark
- Shopping tells you when an item was merged, and combines duplicates like
  "garlic" and "fresh garlic"
- Setup accepts a pasted server address and shows recipe sync progress
- Review and remove duplicate Chef Profiles
- Tap a tab again to jump back to the top
- Better layouts at the largest text sizes

Everything you use today remains free.

## 2026.7.1

- Improved reliability and safety when reconnecting to or switching recipe
  servers
- Better recovery from slow, interrupted, and malformed server responses while
  keeping saved recipes available
- Improved Shopping edits and cooking-timer restoration
- Accessibility refinements across Quick Picks and app controls

## 2026.7.0

- Your already-synced recipes, Meal Plans, Quick Picks, and Shopping list stay
  ready through slow or temporarily unavailable server connections
- Settings > Sync now shows connection condition and retry timing, with Manual
  Sync always available
- Recipe Detail is easier to read: select and copy text across titles,
  ingredients, and instructions
- Fixed Recipe Detail text overflowing its bounds at larger text sizes
- Original recipe links now open normally in Safari, with Reader available
  when supported

## 2026.5.1

- New global Shopping tab: build one persistent grocery list from meal plans,
  selected My Picks, and manual ingredients
- Smarter shopping merges add compatible quantities together, preserve
  incompatible units, and keep source context
- Sync controls moved into Settings so the main tabs focus on cooking
  workflows
- New Chef Profile controls let you prefer Mealie favorites or ignore
  low-rated recipes without writing changes back to your server
- Meal Plan and Add-a-Meal now use the same profile-aware ranking and
  filtering path
- Shopping polish: search, collapsible sections, bottom-right add panel with
  quantities and units, multi-line paste, swipe to remove, pull to refresh,
  clear checked/all, and share

## 2026.4.35

- More reliable ingredient sync for large Mealie libraries, with live progress
  and automatic retries while Forked is open
- Gentler pacing for slower or proxied Mealie servers, reducing timeout
  pressure during full syncs
- Quick Picks and meal plans prioritize recipes you are viewing, so
  ingredients, allergy checks, and dietary matches catch up sooner
- Mealie favorites and ratings now appear throughout Forked without writing
  changes back to your server
- Faster image loading plus accessibility polish across meal planning,
  profiles, and cooking mode
- Various bug fixes

## 2026.4.3

- Faster, more reliable ingredient sync for large Mealie libraries, with live
  progress while Forked stays open
- Quick Picks and meal plans now prioritize recipes you are viewing, so
  ingredient and dietary checks catch up sooner
- Smoother performance across Quick Picks, meal plans, shopping lists, recipe
  pickers, and settings
- Added Rate Forked / Share Forked actions, improved review prompts, and fixed
  a Step by Step launch crash

## 2026.4

- HTTPS on your LAN: optional support for mkcert and self-signed certs on
  private-network Mealie servers, with clearer onboarding when a private DNS
  name needs a publicly trusted certificate
- Faster, gentler sync that protects weaker Mealie installs from timeout
  pressure, with batched ingredient persistence and live progress while the
  app stays open
- Performance passes across Quick Picks, meal plans, shopping lists, recipe
  pickers, and settings: snappier scrolling, faster reopen, less stutter
- Network reliability behind HTTPS proxies: shared host governor prioritizes
  interactive work and prevents retry amplification
- Full accessibility coverage: all seven applicable App Store accessibility
  labels now supported, plus first-use hints, tap-to-dismiss keyboard, and
  visible selected states
- Various bug fixes and enhancements

## 2026.3

The first release: Quick Picks from your Mealie library, meal plans, Chef
Profiles synced through iCloud, a shopping list that combines ingredients,
step-by-step cooking that keeps the screen on, and optional tips.
