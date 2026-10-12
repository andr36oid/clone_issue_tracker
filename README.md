# andr36oid clone issue tracker

Reports for consoles that need one of andr36oid's **experimental device trees**:
R36S clones (the "EE" clones that shipped with EmuELEC, the Soy Sauce boards, K36,
G80, R36 Max, R36 Ultra and others) and R36S boards the normal files don't fit.

**Support for experimental device trees is very limited.** Nobody on the andr36oid
team owns these consoles. We can only help if you send everything the issue form
asks for, above all the boot files of a system that works on your console.
Reports without those files are closed.

[Open a report](https://github.com/andr36oid/clone_issue_tracker/issues/new/choose)

A genuine R36S, R36S Plus, R46H or R50S that has a problem with the normal files
belongs in the [andr36oid issue tracker](https://github.com/andr36oid/issue_tracker/issues/new/choose) instead.

## Which folder to try

The BOOT drive of every andr36oid card has the folders `Panels`, `Devices` and
`Experimental`, each with a `README.txt` that says which console each folder is
for and how to copy one by hand. The
[andr36oid SD Flasher](https://github.com/andr36oid/andr36oid-sdflasher/releases)
does the copying for you when you choose your console and screen.

After every start andr36oid writes `dtb-hint.txt` on the BOOT drive, with its
guess which folder fits your board.
