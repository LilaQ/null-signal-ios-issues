# NULL//SIGNAL – Help and support

[Deutsch](../de-DE/support.md)

## Contact

For questions about the game or technical problems, contact the developer through [NULL//SIGNAL GitHub Issues](https://github.com/LilaQ/null-signal-ios-issues/issues). Posting requires a GitHub account. Existing answers can be read without signing in.

Issues and replies are public. Describe the problem using your app version, iOS/iPadOS version, device model and brief steps to reproduce it. Do not post personal information, payment receipts, passwords, save files, screenshots or logs. The app does not upload diagnostics on your behalf. GitHub is governed by its [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Getting started and getting unstuck

NULL//SIGNAL is a fictional hacker game simulated locally on your device. Commands operate only on the game world. Do not enter real internet addresses or credentials in the terminal.

- `help` lists commands; `help scan`, for example, explains scan syntax.
- `phase`, `objectives` and `status` show your current assignment and state.
- `hint` provides a hint. Reading and planning do not increase alarm.
- `retry confirm` returns the current run to its last phase or foothold checkpoint. Later actions and changes are lost; terminal history is retained.
- Completed operations can be replayed. Previously reached endings remain saved.

Open settings with `···` to change language, larger text, sound, haptics and reduced motion. The game supports English and German and a hardware keyboard. On iPhone, switch between the terminal and tool views.

## Rig and new runs

Open **Settings → Rig** to choose modules for Core, Relay and Analyzer. Campaign completions unlock 18 specializations regardless of rank. Benefits and drawbacks change the alarm costs of specific actions. Stock equipment remains available for free at all times.

Your selection applies to new runs in the campaign, side jobs, contracts and practice. `rig` shows the active equipment. An ongoing attempt keeps its rig, including after `retry confirm`. To restart the entire operation with your new selection, type `restart confirm`: the ongoing attempt is discarded; earned endings and your first campaign decision remain intact. `man rig` explains the details.

The fourth tab, **Daemon**, lets you choose one of twelve terminal helpers. The alarm sentinel is available immediately; campaign completions unlock the others. Helpers report only already observed states, execute no commands and change neither alarm costs nor rank. `daemon` shows your active helper; `man daemon` explains the limits. Selections follow the same new-run rules as rig modules.

## Credits and terminal styles

`credits` shows your earned in-game currency and its rules. First campaign completions pay 180 credits; first side-job completions pay 90. Each first rated outcome of these operations adds 25 regardless of rank. Each complete archive thread pays 120. Each contract pays 60 on its first completion, 30 on its second, 15 on its third and nothing thereafter. Practice pays no credits. Existing completions are credited once; unknown earlier repetitions are not estimated.

**Settings → Terminal style** offers 24 cosmetic variants. Your base style is free; every other variant displays its price in in-game credits. Once unlocked, selecting it again is free. Selections apply immediately in every workspace without changing active access or command drafts. Credits, unlocks and your selection are stored locally. A failed unlock is not charged if saving fails; you can retry saving.

Credits cannot be bought with real money. Tools, privileges and solutions cost no credits. `man credits` explains the system in the game.

## Hidden correspondence

Campaign systems contain twelve optional archive threads with 60 files in total. Three complete threads can be found in the free act. `ls` lists files on your current host; `cat` reads and `download` copies using normal access privileges and alarm costs. Read saved parts under **Archive → Correspondence**. Unseen texts and titles are not revealed. You may find the parts in any order.

Archive copies remain readable after checkpoint restarts, replays and loss of purchase entitlement. This does not restore files to a rewound operation cache or change endings or unlocks. Reading alone creates no archive copy. `man deadletters` explains the distinction.

## Optional mastery ranks

Each new completion earns C, B, A or S. `mastery` shows thresholds per outcome; `man mastery` explains them. Ratings consider active operations, total generated alarm, checkpoint restarts and hint requests. Reading, syntax errors and thinking time do not count. Hints affect only the optional rank, never story progress or regular rewards. The archive retains best mastery and lowest peak alarm separately. Older runs receive no estimated rank; a replay records the required values.

## Free operations and the campaign purchase

The first eight operations are free. One non-consumable in-app purchase permanently unlocks the remaining 17. There is no subscription, advertising or purchasable energy. You still progress through the campaign by playing: buying does not skip earlier operations.

Open **Settings → Job board** for 36 additional side jobs: twelve free and 24 included in the same full game purchase. Each job lists its required campaign completion. Locked briefings can already be read. Change the job type in the board to filter the list. Side jobs save their runs and outcomes independently of the campaign.

**Settings → Contracts** provides 50 replayable variants. Twenty are free; 30 are included in the full game purchase. Variants combine different access models with different operational objectives. Each contract lists its required campaign completion. These runs also have separate saves and their own archive.

The 15 **Practice networks** in Settings are free and immediately selectable. Their separate saves affect neither campaign progress nor campaign achievements.

Open **Full game → Restore purchases** if a previously purchased unlock is missing. Use the Apple Account used for the purchase and a connection to the App Store. Pending purchases unlock automatically after approval. During a store outage, free operations and purchases already verified locally by Apple remain playable. New purchases and restoration require an App Store connection.

After a refund or another loss of purchase entitlement, the additional content is locked. Its saved progress is not deleted. Apple handles [refund requests](https://support.apple.com/en-us/118223).

## Saved progress and data

Progress, unfinished command drafts, history and settings are stored on your device. The app does not provide its own cloud synchronization or game account. Restoring a purchase restores access, not a lost save. Device backups may contain app data; availability and restoration depend on your Apple or computer backup settings.

If the app reports a save error, do not delete it as your first troubleshooting step. Describe the message to support without attaching files. The app attempts to use readable local backup copies and does not intentionally overwrite an unknown or unreadable save.

To remove local app data, delete the app in iOS/iPadOS Settings. **Offload App** keeps documents and data, so it does not erase them. Manage existing device backups separately in your backup settings. Deleting the app does not cancel a purchase. It also does not delete public GitHub posts you have written.
