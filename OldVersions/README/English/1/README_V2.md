
***

# QMEFS (Quantum Meadows ETERNAL File System)

**proposal for a perfect file system**

_Version 3 (2022, Tuesday, August 23rd at 4:40 pm)_

## Simplified overview

**Capacity:** `115.792 Quattuorvigintillion bits` (`14.474 Quattuorvigintillion bytes`) or `2^256` bytes

**Bit type:** `256` (256 bit, is able to run on 128 bit or higher devices)

**Date range:** `The beginning of time (the start of the Big Bang, or ~13,787,000,000 BCE) to as far as the 256 bit integer can go from there in planck seconds`

**Allowed characters:** _All, except for_ `/`

**Mode:** _Switchable with commands,_ **default** _is_ `COW (Copy-On-Write)`

**Max files per directory:** `340,282,366,920,938,463,463,374,607,431,768,211,455` or `2^128`

**Max number of directories:** `340,282,366,920,938,463,463,374,607,431,768,211,455` or `2^128`

**Max file size per file:** `340,282,366,920,938,463,463,374,607,431,768,211,455 bytes` or `2^128`

**Reference to names of large numbers:** [`CSV table`](/Docs/Names-of-large-numbers/Table/CSV/NameOfLargeNumbers_Table.csv)

## Full specification

| Variable | Conditions |
|---|---|
| **Maximum capacity (yottabytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000,000,000,000,000,000,000,000 Yottabytes` |
| **Maximum capacity (zettabytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000,000,000,000,000,000,000 Zettabytes` |
| **Maximum capacity (exabytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000,000,000,000,000,000 Exabytes` |
| **Maximum capacity (petabytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000,000,000,000,000 Petabytes` |
| **Maximum capacity (terabytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000,000,000,000 Terabytes` | 
| **Maximum capacity (gigabytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000,000,000 Gigabytes` |
| **Maximum capacity (megabytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000,000 Megabytes` |
| **Maximum capacity (kilobytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8,000 Kilobytes` |
| **Maximum capacity (bytes):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 / 8 bytes` |
| **Maximum capacity (bits):** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 bits` |
| **Word size:** | `256 bit` |
| **Allowed characters:** | `All except for one` |
| **Disallowed characters:** | `/` |
| **Default date format:** | `YYYY/MM/DD` |
| **Date start:** | `~13,787,000,000 BCE` |
| **Date end:** | `Unknown, at least 312,000,000,000,000 CE` |
| **Date range:** | `115,​792,​089,​237,​316,​195,​423,​570,​985,​008,​687,​907,​853,​269,​984,​665,​640,​564,​039,​457,​584,​007,​913,​129,​639,​935 planck seconds` |
| **External device support:** | `True` |
| **Internal device support:** | `True` | 
| **Default date resolution:** | `Planck seconds` |
| **Secondary date resolution:** | `Nanoseconds` |
| **Deduplication:** | `Optional (not enabled by default)` |
| **Unicode:** | `Supports any version of Unicode` |
| **Max files per directory:** | `340,282,366,920,938,463,463,374,607,431,768,211,455` |
| **Max number of directories:** | `340,282,366,920,938,463,463,374,607,431,768,211,455` |
| **Max file size per file:** | `340,282,366,920,938,463,463,374,607,431,768,211,455 bytes` |
| **Maximum file path:** | `2,147,483,647 ASCII characters per line` |
| **Other specs:** | `Unlisted/coming soon` |
| **Mode 1:** | `Copy-on-Write (COW)` |
| **Mode 2:** | `Read only` |
| **Mode 3:** | `Unspecified` |
| **Mode 4:** | `Unspecified` |
| **Tree 1:** | `B-Tree` |
| **Tree 2:** | `Unspecified` |
| **RAID support:** | `Unknown` |
| **Hard Disk Drive support:** | `False` |
| **Solid State Drive support:** | `True` |
| **Tape Drive support:** | `Unspecified` |
| **Flash memory support:** | `True` |
| **Drive compression:** | `Optional (disabled by default)` |
| **Data encryption:** | `True (disabled by default)` |
| **Supported encryption types:** | `Unknown` |
| **Compatible hardware:** | [`DeciCube`](https://github.com/seanpm2001/DeciCube/), `Other/unknown` |

## Credits

**Creator:** [`@seanpm2001`](https://github.com/seanpm2001/)

### Inspirations:

* OpenZFS
* NTFS
* ext4
* Btrfs

## Clarifications

* ETERNAL is NOT a misspelling of External. The file system supports both internal and external drives, and also is meant to last an eternity.

* A 128 bit or better processor is required to operate the file system, a 256 bit processor isn't required, but is recommended. The file system cannot run on 127 bits or lower, which includes 64 bit, 32 bit, 16 bit, 8 bit, etc.

* This file system is designed for the QMeadows operating system, but can run on other Linux distributions once you add support for it

* Some people don't say the `FS` line when referring to a file system by name. On 2022, August 23rd, I escaped confusion regarding `Btrfs` being referred to as `BTR`, which originally made me think `BTR` and `BTRFS` were 2 different file systems, which led to major confusion when I couldn't find anything on the `BTR` file system, which doesn't exist. When referring to QMEFS, please also mention the `FS` part of the name to avoid confusion.

> In short, **Don't** refer to it as `QME` or `QM`

***

### File info

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `2 (2022, Tuesday, August 23rd at 4:40 pm PST)`

**Line count (including blank lines and compiler line):** `168`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

_Note that on 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

**You may need special rendering support for the `<details>` HTML tag being used in this document**

</details>

***

## File history

<details><summary><p lang="en"><b>Click/tap here to expand/collapse the file history section for this project</b></p></summary>

<details><summary><p lang="en"><b>Version 1 (2022, Monday, August 22nd at 1:21 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Started the file
- [x] Added the `title` section
- [x] Added the main table
- [x] Added the `Credits` section
- - [x] Added the `Inspirations` subsection
- [x] Added the `file info` section
- [x] Added the `file history` section
- [ ] No other changes in version 1

</details>

<details><summary><p lang="en"><b>Version 2 (2022, Tuesday, August 23rd at 4:40 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `title` section
- [x] Added the `Simplified overview` section
- [x] Renamed the main table section to the `Full specification` section
- - [x] Updated the main table
- [x] Added the `Clarifications` subsection
- [x] Updated the `file info` section
- [x] Updated the `file history` section
- [ ] No other changes in version 2

</details>

</details>

***
