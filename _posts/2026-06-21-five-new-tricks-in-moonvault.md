---
title: "Five New Tricks in Moonvault"
description: "Meet Moonvault's latest tools for reusable encounters, combined random tables, vault diagnostics, calmer navigation, and Brazilian Portuguese support."
---

The party has ignored the marked road, befriended the suspicious statue, and adopted the monster you prepared as a villain. Excellent. Moonvault has acquired a few new tricks for exactly this sort of evening.

Across the latest releases, we have added **reusable encounters**, a **Generator Workbench**, **Vault Health Check**, broader **Brazilian Portuguese support**, and a calmer sidebar and page toolbar. The goal is simple: spend less time wrestling the vault and more time deciding what the glass hound wants in exchange for the key.

For our tour, we built *The Glass Marches*. The Amber Company is following silver pawprints toward an abandoned tollhouse, while reflections behave with the confidence of people who know something we do not.

## Trick 1: Find the serious tools without losing the common ones

The top of the sidebar now keeps **Calendar**, **Session**, **Note**, and the create menu close at hand. Filters and campaign context can collapse when you do not need them, the dice tray can shrink, and the larger prep workflows live together under **Tools**.

That gives the page list more room without burying the useful machinery. The Tools menu also shows how many prepared encounters and random tables are available, so you can tell whether the cupboard contains adventure or merely a very dramatic spoon.

<figure class="post-screenshot">
  <a href="/assets/blog/five-new-tricks-in-moonvault/01-sidebar-tools.png" target="_blank" rel="noopener">
    <img src="/assets/blog/five-new-tricks-in-moonvault/01-sidebar-tools.png" alt="Moonvault sidebar with the compact Tools menu open above a populated Glass Marches campaign" loading="lazy">
  </a>
  <figcaption>The compact Tools menu keeps reusable encounters and generators close without crowding everyday creation actions. Open the full-size view.</figcaption>
</figure>

Page controls received the same treatment. Navigation, save and pin status, editor mode, and page actions now form a clearer toolbar. Player visibility, PDF export, and deletion sit inside one localized **Page** menu, where dangerous buttons can brood together under supervision.

## Trick 2: Reuse a battle without disturbing the original

Open **Tools → Encounter Library** to search the prepared Encounter pages in the current campaign.

The library is for the battle you prepared beautifully and would rather not rebuild from memory. Choose **Remix copy** and Moonvault creates a fresh encounter, resets reusable combat state such as HP, initiative, and conditions, and leaves the source encounter untouched. You can also attach the copy to a Session while making it.

In *The Glass Marches*, **Hounds at the Tollhouse** contains Splinter and Glint, two glass hounds guarding a bell rope beneath a mirrored ceiling. The original remains the canonical ambush; the remix is free to become whatever alarming variation tonight's table deserves.

<figure class="post-screenshot">
  <a href="/assets/blog/five-new-tricks-in-moonvault/02-encounter-library.png" target="_blank" rel="noopener">
    <img src="/assets/blog/five-new-tricks-in-moonvault/02-encounter-library.png" alt="Encounter Library showing Hounds at the Tollhouse with two participants and the Remix copy action" loading="lazy">
  </a>
  <figcaption>Search, open, or remix a prepared encounter while keeping its original combat state intact. Open the full-size view.</figcaption>
</figure>

The workflow now explains its prerequisites, offers useful empty states, and provides direct creation actions when something is missing. It should feel like a guide at the dungeon entrance, not a locked door labeled “perhaps later.”

## Trick 3: Turn small random tables into larger answers

The **Generator Workbench** combines existing Random Table pages into a single result. Add the tables you need, choose how many results each produces, and press **Generate combined result**.

Each part can be rerolled independently. Keep the excellent roadside omen, replace the unhelpful treasure, then save the final result and its recipe as an ordinary Markdown Note. The recipe remains portable with the rest of the vault rather than disappearing into a mysterious private database.

Our **Roadside Omens** table produced: “The next shadow points toward the Tollhouse.” That is either useful foreshadowing or the sort of navigation advice that gets a party eaten. In both cases, it belongs in the session notes.

<figure class="post-screenshot">
  <a href="/assets/blog/five-new-tricks-in-moonvault/03-generator-workbench.png" target="_blank" rel="noopener">
    <img src="/assets/blog/five-new-tricks-in-moonvault/03-generator-workbench.png" alt="Generator Workbench showing a Roadside Omens result ready to reroll or save as Tollhouse Expedition" loading="lazy">
  </a>
  <figcaption>Generate a larger prompt, reroll only the weak pieces, and save the result and recipe as Markdown. Open the full-size view.</figcaption>
</figure>

Use it for shops, rumors, treasure parcels, travel complications, NPC prompts, or any other moment where several small tables can conspire to produce one table-ready answer.

## Trick 4: Check the vault before the broken link checks you

Open the command palette and choose **Check vault health**. Moonvault scans the local vault for:

- Broken wikilinks.
- Missing local assets.
- Duplicate stable IDs.
- Invalid world or campaign ownership.
- Relationship references that point nowhere.

The report is navigable, so selecting an issue takes you to the page that needs attention. Duplicate IDs have an explicit safe repair; Moonvault does not rewrite your authored Markdown prose while pretending it knows what the ancient prophecy meant.

This is particularly handy before a session, an export, or a large vault move. Five quiet minutes of diagnostics can prevent the traditional mid-game ritual of clicking a link and staring into the void.

## Trick 5: Run more of Moonvault in Brazilian Portuguese

Moonvault's localization foundation now supports **English and Brazilian Portuguese** across a growing set of everyday surfaces. Recent work expanded pt-BR through the welcome flow, sidebar navigation, common command-palette actions, Settings, update notices, import actions, template editing, starter templates, and blank-page scaffolds.

The new Encounter Library, Generator Workbench, Vault Health Check, and reorganized sidebar controls also include Brazilian Portuguese copy. Localization is still expanding rather than complete, but a newly created pt-BR vault now starts with Portuguese templates and much more of the normal workflow speaks the table's language from the beginning.

## Pack these tricks for the next session

Before the party arrives:

- Open **Tools** and confirm your reusable encounters and tables are ready.
- Remix one encounter instead of rebuilding it.
- Combine a few tables into a rumor, journey, or treasure result.
- Run **Check vault health** before broken references become table drama.
- Collapse the controls you do not need and give the page list room to breathe.

The latest Moonvault is quieter where it should be, more helpful where a workflow needs explaining, and considerably better at reusing the preparation you already did.

Now return to the Glass Marches. The bell has rung beneath the road, and somebody's reflection has arrived early.
