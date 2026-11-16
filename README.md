# ZBox

Snappy, secure, accessible email client for Windows.

**Release candidate RC26.11.15. Windows only.** The last testing
build before the stable release. It is close to finished, and your
reports help us get the last details right.

ZBox is a snappy, secure and fully accessible email client, made by
ZAPPS SOFTWARE LTD (development team: Harith and Mesar).
We made it to give everyone, blind and low-vision users included, a
real, feature-packed alternative to the bloated and sluggish email
programs out there. Accessibility is built in from the start, not
added later: no decorative clutter, every control named, every
important state also given as text, and HTML mail tamed so your
screen reader gets the message and nothing else. It is tested with
NVDA and JAWS.

ZBox has no speech of its own and never will. Announcements go to
whichever screen reader you are running, in your own voice, rate and
settings.

What you get, in short:

- Gmail, Outlook.com, Microsoft 365, JMAP and any IMAP account, side
  by side, with unified folders, threads, search across every
  account, filters, templates and an address book.
- Mail brought over from Thunderbird, Outlook, Outlook Express,
  Windows Live Mail, .mbox and .eml files, free in every edition.
- OpenPGP and S/MIME encryption and signing, remote content blocked
  by default, a tracker, ad and phishing check, and an app lock with
  Windows Hello, a security key or your master password.
- One portable folder with no installer, and Private No-Trace for
  reading your mail from a USB stick on a computer that is not yours.
- 50 interface languages, nine themes, and sound themes of your own.
- No analytics, no telemetry, no advertising. See the privacy policy
  below.

## [Keyboard shortcuts: jump to the full list](#keyboard-shortcuts)

## Contents

1. [Getting it](#getting-it)
2. [What's new](#whats-new)
3. [Features](#features)
4. [First run](#first-run)
5. [Linking an account](#linking-an-account)
6. [The master password, and moving the folder](#the-master-password-and-moving-the-folder)
7. [Private No-Trace](#private-no-trace)
8. [Pro features and licenses](#pro-features-and-licenses)
9. [HTML mail](#html-mail)
10. [Keyboard shortcuts](#keyboard-shortcuts)
11. [Interface languages](#interface-languages)
12. [Privacy policy](#privacy-policy)
13. [Reporting a bug](#reporting-a-bug)
14. [Licence](#licence)
15. [Credits and third-party components](#credits-and-third-party-components)

## Getting it

Download the zip from [ZApps](https://zapps.ltd), unzip it anywhere
you like, and run `ZBox.exe`.

Downloads and updates: go to https://zapps.ltd for ZBox and other apps downloads.

There is no installer. The whole folder is the app: put it on a USB
stick, an external drive or your desktop, and it writes nothing
outside itself. Nothing is added to the registry, nothing is left
behind if you delete the folder.

## What's new

In this version, the release candidate RC26.11.15:

1. Private mode is now Private No-Trace, set for a portable copy made
   with Tools, Portable Private Pro Features (trial testing). That tab
   makes a copy for a USB stick or another drive: with your accounts
   and the master password on, with the master password off, or a new,
   empty copy. A shield badge and the window title show when Private
   No-Trace is on. The Windows+Ctrl+Shift+P hotkey is gone. See
   Private No-Trace below.
2. Hide ZBox from screen recording and sharing, on in a Private
   No-Trace copy. It cannot stop a camera pointed at the screen, and
   it does not touch a keylogger or other spyware already on the
   computer.
3. Export Accounts and Settings can carry the account passwords and
   Microsoft sign-ins, protected by a password you type; Import asks
   for it.
4. Create Filter from Message, in the Message menu and as Message
   Filter in the message list's context menu, starts a filter rule
   from the sender, as in Thunderbird.
5. Adding an account finds the mail servers of domains ZBox does not
   know from their DNS records. Ports 993 and 465 always use SSL/TLS.
6. A missing Drafts or Sent folder is created on the server the first
   time it is needed.
7. Setup can go on without a master password.
8. The licence page lists every third-party component and its licence
   in one 3rd Party Licenses list.
9. A new look: three new themes, Neon, Aurora and Pulse, and the other
   themes retuned with stronger contrast. Each theme colours the title
   bars on Windows 11, draws a glow line above the tabs and shows
   unread messages and folders in its accent colour. Windows fade in
   and out, and the tray icon shows unread mail and glows when new
   mail arrives. All of it is for the eye only and never changes what
   a screen reader reads. It stays off with Windows High Contrast, and
   nothing moves when Windows animations are off.
10. Import Mail from Other Programs, in Tools, Import and Export, free
    in every edition. It reads Thunderbird (an exported backup zip
    file, Thunderbird Portable or a profile folder, with its accounts,
    address books and saved passwords), .mbox files, a folder of .eml
    files, Outlook data files (.pst, Outlook 2003 and later), Outlook
    Express (.dbx) and Windows Live Mail, chosen by hand or found
    automatically. IMAP accounts are added and their mail stays on the
    server; the rest is copied into Local Folders or into any
    account's server, Outlook.com and Hotmail included. It can be
    stopped and run again, and nothing is copied twice.
11. Local Folders, mail kept in ZBox's own folder, last in the folder
    tree in every view and closed, with an Inbox and a Trash folder.
    Move To and Copy To work between Local Folders and your accounts.
    It is never offered under Private No-Trace, and a portable copy
    warns that Local Folders is not encrypted.
12. View, Folders, Combined (Pro, in trial testing): the Unified
    Folders on top, then every account and Local Folders.
13. A folder you have opened once opens at once from a header index
    kept in ZBox's cache folder, and ZBox then fetches only new
    messages, changed flags and removals. Clear Offline Message Cache
    Now clears it. It is not kept under Private No-Trace.
14. Search looks through all accounts at the same time, much faster,
    and each result shows the account and folder it is in.
15. Without a screen reader ZBox stays silent. With Windows Magnifier
    or ZoomText running and speech on in Settings, it uses the Windows
    voice.
16. Pin to Top (Pro, trial testing), in a folder's context menu,
    lists that folder again at the very top of the folder tree, with
    its account's name and its unread count.
17. Sync with Inbox (Pro, trial testing), in a folder's context menu,
    shows that folder's unread messages in its account's Inbox and in
    the Unified Inbox, each ending with the folder's name. Nothing
    changes on the server.
18. Help, About ZBox opens the About page in your web browser, with
    links to ZApps, ZBox support, Google App Passwords and the License
    page.
19. Update checks ask the ZApps website, are off unless you turn them
    on, and ask once before the first check. A newer version is shown
    with a link to ZApps; ZBox downloads nothing by itself.
20. When a server refuses an account's password, ZBox tries again
    after 10 seconds, after 10 more, then twice 20 seconds apart, then
    stops trying that account. The folder tree says "(sign-in failed)"
    after its name until a sign-in works, you correct it in Account
    and Identities Settings, or ZBox starts again.
21. A faster start: the Windows voice is prepared only when it is
    needed.
22. Himalaya 2.2.1: a Bcc address is no longer visible to the other
    recipients.
23. JMAP accounts. Add Account has a Server type choice on its server
    page: IMAP and SMTP, or JMAP. For JMAP, ZBox finds the server's
    address from your email address where the provider publishes it;
    sign in with your password, an app password or an API token. New
    mail arrives through the server's own push, and everything else
    works as for IMAP accounts.
24. Servers that accept only older encryption, Spectrum's among them,
    are reached through a bridge inside ZBox on your computer. The
    connection to the server stays encrypted and its certificate is
    checked; other servers are not affected. ZBox finds such servers
    by itself when one drops the connection while it is being secured.
25. Spectrum addresses: roadrunner.com, bresnan.net, adelphia.net,
    elmore.rr.com and twmi.rr.com are recognised, and for a linked
    pair such as berkshire.rr.com Add Account fills in the first
    address, nycap.rr.com, as the login email.
26. Update checks also look at ZBox's release page on GitHub, so a
    newer version still shows up if the ZApps website is busy or down.
    Whichever has the newer version wins.
27. ZBox checks its own program files each time it starts. If any
    were changed, it keeps working with the free features and tells
    you it is best to download it again from ZApps.
28. Pro features in this release candidate: everyone already using
    ZBox with an account by 1 December 2026 keeps the Pro features for
    good in the stable release. A copy first used later gets a 15-day
    trial. On 1 January 2027 this release candidate turns its Pro
    features off for everyone, so please move to the stable release
    by then; nothing you have is lost. See Pro features and licenses
    below.
29. Help, (Testing) Pro License: a first try of the new license
    request. Choose a period and press the button: ZBox copies your
    Installation ID and opens a message to ZApps support with it
    filled in, ready for you to send.
30. The privacy policy now covers the GitHub update check, the
    Installation ID and the optional online Pro activation.
31. All of this in every interface language, and in the user guide.

<details>
<summary>Earlier: testing beta 26.10.11</summary>

1. Templates, as in Thunderbird and Outlook. Compose, Save as Template
   keeps the message you are writing in the Templates folder of its
   account, which shows with the standard folders and in Unified
   Folders. Opening a template starts a new message from it, and
   Ctrl+T inserts any of your templates, from every account, at the
   cursor. ZBox keeps an encrypted copy of them, so the list opens at
   once and works offline.
2. S/MIME sending. Encrypt and Digitally Sign use your own S/MIME
   certificate when the sending address has no OpenPGP key. Signers'
   and recipients' certificates are checked for revocation.
3. Web and e-mail addresses in the messages you write arrive as links
   the recipient can open.
4. Alt with a menu's letter opens that menu even from inside the
   message body.
5. If HTML mail stops loading, ZBox restarts its own web view, so it
   can no longer hold up the screen reader and the keyboard.
6. New mail is heard as soon as the server shows it while ZBox is in
   the system tray or minimized.
7. Ctrl+Shift+F opens Search again after the Search tab was closed.
8. All of this in every interface language, and in the user guide.

</details>

<details>
<summary>Earlier: testing beta 26.10.09</summary>

1. 22 more interface languages, 50 in all. See Interface languages
   below.
2. Moving through the From list in a new message, reply or forward no
   longer speaks the signature, Cc and Bcc, or encryption notices. Those
   settings still follow the account or identity you choose.

</details>

<details>
<summary>Earlier: testing beta 26.10.05</summary>

1. OpenPGP. Read and write encrypted and signed mail, with the
   OpenPGP Key Manager in Tools for your keys and your contacts' keys.
2. S/MIME reading. Tools, S/MIME Certificate Manager imports your own
   certificate (a .p12 or .pfx file) and other people's certificates.
   Signed and encrypted S/MIME mail opens with its status above the
   message. Sending S/MIME mail comes later.
3. Private mode, for using ZBox from a USB drive on a computer that
   is not yours. It is now Private No-Trace; see Private No-Trace
   below.
4. Outlook.com, Hotmail, Live and MSN accounts work through Microsoft
   Graph, so IMAP no longer has to be turned on in Outlook.com.
5. A Search tab (Ctrl+Shift+F): words in every account or one folder,
   dates, unread, flagged and attachments, and every message action on
   the results.
6. Address suggestions while writing come only from people you wrote
   to and contacts you saved. Down Arrow in To, Cc or Bcc opens them.
7. Settings in seven categories in a list, with real values in place
   of sliders.
8. Spoken announcements follow your screen reader on their own, and
   information-only popups are now short notices that never take
   focus.
9. Sent, Drafts, Trash, Junk and Archive are found from your server's
   own markings, so folder names in any language work.
10. Ctrl+Z undoes a delete, archive or junk action from the message
    list, the search results, the folder tree or an open message, and
    in a text field only undoes typing.
11. Sort By and Columns for the message list.
12. Everything ZBox keeps now stays in its folder, the browser data of
    HTML mail included, and its own records are encrypted.
13. All of this in every interface language.

</details>

<details>
<summary>Earlier: testing beta 26.10.02</summary>

1. Microsoft sign-in for Outlook.com, Hotmail, Live, MSN and
   Microsoft 365. Sign in on Microsoft's own page in your browser, or
   with a code on any device. ZBox keeps only an encrypted sign-in
   token, never your Microsoft password.
2. Block This Sender, in the message list's context menu in an Inbox
   or Junk folder. That sender's messages move to Trash at once, and
   so does their new mail, including mail that arrived while ZBox was
   closed. For a mailing list post, only that member is blocked, never
   the whole list. Unblock This Sender, in Trash, takes it back.
3. Only the Inbox and the Archive keep an offline copy. Every other
   folder is read from the server with nothing kept on disk, and Sent,
   Drafts, Trash and Junk open at once from a list remembered while
   ZBox runs.
4. At startup the first message list comes straight from the server,
   so mail deleted or moved elsewhere while ZBox was closed does not
   show up, and focus stays on the top message until you move it.
5. A privacy policy, now printed in full below.

</details>

## Features

### Accessibility

- Accessible from the start for everyone who uses it, blind and
  low-vision users included. Tested with NVDA and JAWS.
- Announcements go through your own screen reader, on by default
  while one is running, with one switch for all speech.
- Information-only messages are short notices that never take focus.
- Single-key actions in the message list, which can be turned off.
- Tuning for HTML mail with a screen reader: how long the reader stays
  quiet when a message opens, and how long announcements stay.
- A Keyboard Shortcuts page in Help (F1), and the full list below.

### Accounts and sign-in

- IMAP and SMTP through the Himalaya mail client, with the servers
  filled in for known providers.
- Microsoft sign-in for Outlook.com, Hotmail, Live, MSN and
  Microsoft 365. Personal Microsoft accounts work through Microsoft
  Graph.
- Gmail and others with an app password.
- JMAP accounts, such as Fastmail with an API token, with new mail
  through the server's own push.
- Servers that accept only older encryption, such as Spectrum's,
  through a bridge on your computer, with the connection to the
  server still encrypted and checked.
- Sent, Drafts, Trash, Junk and Archive found from your server's own
  markings, in any language.
- Extra identities, each with its own signature, Reply-To address,
  Cc and Bcc, Drafts and Sent folders and outgoing server.
- Mute, pause or disable an account.
- Import mail, accounts and address books from Thunderbird, Outlook,
  Outlook Express, Windows Live Mail, .mbox files and .eml files, free
  in every edition.

### Reading mail

- HTML mail through Microsoft Edge WebView2, prepared for screen
  readers, with a plain Text view always one key away (Ctrl+B).
- Threads, a conversation view, and related messages across folders.
- Watch Thread and Ignore Thread, with filters for watched and ignored
  threads.
- Unified folders that combine one folder type from every account, and
  a Combined view with them on top and every account below.
- Local Folders for mail kept on your computer, last in every folder
  view.
- Folders you have opened open at once from a header index, and then
  only what changed is fetched.
- Sort By and Columns for the message list.
- Message headers above the message, a message font size and reading
  font of your own, and the sender announced with Ctrl+U.
- Save a message as a file, open saved .eml messages, save every
  attachment at once to a folder you choose, and view or copy the full
  message headers.

### Writing mail

- A formatted editor with spell check, signatures and draft autosave.
- Address suggestions only from people you wrote to and contacts you
  saved.
- Preview a message as it will be sent, and a word count.
- Templates kept on the server as in Thunderbird and Outlook, and
  inserted with Ctrl+T from a copy kept offline.
- Web and e-mail addresses sent as links.
- An address book with groups, vCard and CSV import and export.

### Finding and organizing

- A Search tab across every account, by words, dates, unread,
  flagged and attachments, with every message action on the results.
- Message filters, Block This Sender and Unblock This Sender.
- Move or copy messages by typing part of a folder name.
- Move or copy messages between your accounts and Local Folders.
- Undo (Ctrl+Z) for delete, archive and junk actions.
- Subscribe to server folders, mark a folder read, empty Trash and
  Junk, or let ZBox clear old Trash and Junk after the number of days
  you choose.
- Pin a folder to the top of the folder tree, or show its unread
  messages in the Inbox (Pro, trial testing).

### Security and privacy

- OpenPGP encryption and signing, key discovery from a mail provider
  and from keys.openpgp.org, publishing your key, Autocrypt headers,
  and your public key attached on request.
- S/MIME: signed and encrypted mail read and sent with your own
  certificate from the S/MIME Certificate Manager, and certificates
  checked for revocation.
- Private No-Trace, for reading mail from a portable copy on a
  computer that is not yours, and ZBox hidden from screen recording
  and sharing.
- Remote content blocked by default, an ad and tracker blocklist, a
  phishing link check, and optional junk rules that never guess.
- App lock with a Windows Hello passkey, a FIDO2 security key or the
  master password.
- Passwords and sign-in tokens encrypted, and ZBox's own records
  encrypted too.

### Portable and practical

- One folder, no installer, nothing written outside it.
- An offline copy of the Inbox and the Archive.
- Optional update checks through the ZApps website and ZBox's GitHub
  release page, off unless you turn them on.
- A check of its own program files at every start.
- Export and import your accounts and settings, with their passwords
  protected by a password you choose, or without them.
- Portable copies for a USB stick or another drive, from Tools,
  Portable Private Pro Features.
- Minimize or close to the system tray, start with Windows, stay
  maximized, and a desktop shortcut.
- Settings for how long cached messages are kept.
- Nine interface themes, and sound themes you can add your own to.
- 50 interface languages, listed under Interface languages below.

## First run

1. A licence appears before anything else. Decline and ZBox exits
   and removes the empty folder it was about to create.
2. You are asked to set a master password. Do it, and write it down
   somewhere safe. See the warning below. Continue setup without a
   master password goes on without one.
3. The New Account wizard opens.

## Linking an account

Type your email address and the wizard fills in the servers for
providers it knows. Every field stays editable, and any IMAP/SMTP
provider can be entered by hand.

### Gmail

Gmail refuses your normal Google password in a mail program. ZBox
signs in with a Google app password instead. To get one:

1. Turn on 2-Step Verification for your Google account. Open
   https://myaccount.google.com/security and, under how you sign in
   to Google, turn on 2-Step Verification. App passwords are not
   offered until it is on.
2. Open https://myaccount.google.com/apppasswords and sign in if
   asked.
3. Create an app password and name it ZBox. Google shows it once, as
   16 letters in groups of four. Copy it.
4. Remove the empty spaces from it, so it is 16 letters with no
   spaces.
5. In the ZBox New Account wizard, type your Gmail address, and paste
   the app password where the wizard asks for the password.
6. Press Test Connection, then Finish.

If the app passwords page says the setting is not available,
2-Step Verification is still off, or the account is a work, school
or Advanced Protection account that does not allow app passwords.

Changing your Google password cancels every app password. Create a
new one the same way, and enter it in Tools > Account and Identities
Settings, in the New password field. The About page (Help > About
ZBox) links to Google's own app password instructions.

### Outlook.com, Hotmail, Live and Microsoft 365

These accounts sign in with your Microsoft account, not a password.
On the wizard's Login page, choose Microsoft account as the sign-in
method; it is chosen for you for Outlook.com, Hotmail and Live
addresses. Then sign in on Microsoft's own page in your browser, or
with a code on any device. The server settings are filled in for you.
Outlook.com, Hotmail, Live and MSN accounts work through Microsoft
Graph, so IMAP does not have to be turned on in Outlook.com.

Some work or school accounts need their administrator to approve
ZBox once before it can sign in. Gmail signs in with an app password,
as above.

### Other providers

Anything else with plain IMAP and SMTP should work: Yahoo, Fastmail,
your own server, a work account that still allows app passwords.

## The master password, and moving the folder

Read this part before you copy ZBox anywhere.

Your account passwords are encrypted on disk, and on this computer
Windows itself holds the key, which is why ZBox opens silently here.
That key does not travel. Copy the folder to another computer and
the master password is the only thing that can open your saved
passwords there.

So: set a master password on the computer you set ZBox up on,
**before** you move the folder. If you move it without one, every
account has to be signed in to its server again on the new machine.

It is never stored anywhere, so it cannot be recovered. Write it
down.

ZBox also recognises each computer by a fingerprint. Open the folder
on a machine it does not know and it locks and asks for the master
password, then remembers that machine.

## Private No-Trace

For reading mail from a USB drive on a computer that is not yours.
Make the copy with Tools, Portable Private Pro Features: choose a copy
with accounts and the master password on, check Private No-Trace,
choose the target folder and press Create Portable ZBox. The copy
starts in Private No-Trace. A shield badge shows at the top of the
window, the title ends with Private No-Trace, and the first item in
Tools says so.

While it is on, ZBox reads your mail from the server and keeps it in
memory only. No offline copies, saved messages or debug logs are kept,
and Offline, Synchronize Now and the cache clean-up options are off.
Opened attachments and the browser data of HTML mail are deleted when
ZBox closes. Closing also ends the programs ZBox started, empties the
clipboard, and stops trusting the computer, unless Private No-Trace
was turned on from it. If the drive is lost, only encrypted files are
left on it.

Hide ZBox from screen recording and sharing is on in such a copy:
screen recorders and sharing tools such as OBS, Teams and the Snipping
Tool see ZBox as blank, while you see it normally. It cannot stop a
camera pointed at the screen, and it does not touch a keylogger or
other spyware already on the computer. Turn it off in the tab if it
gets in the way of remote support.

Limits: Windows itself keeps some records no program can remove, such
as its list of USB drives, the page file, and antivirus and network
logs. A program that was already open when it took an attachment
cannot be told apart from your other work, so it is not closed.

Advice: close every opened attachment yourself before closing ZBox,
above all those opened with Windows' own programs such as Notepad or
Windows Media Player. Their processes cannot always be ended without
extra permissions.

## Pro features and licenses

Most of ZBox is free in every edition, mail import included. The Pro
features are the Combined folder view, Pin to Top, Sync with Inbox
and the portable copies with Private No-Trace, from Tools, Portable
Private Pro Features.

If you were already using ZBox with an account by 1 December 2026,
you keep the Pro features for good: just move to the stable release
when it comes out. A copy first used after that gets a 15-day trial.
This release candidate turns its Pro features off for everyone on
1 January 2027, to make sure everybody moves to the stable release,
and nothing you have is lost on the way.

Paid Pro licenses are on their way, for one month, three months, six
months or a year. A license is a small file you import, so there is
no long key to type. It works on one computer, matched by the short
Installation ID that ZBox shows you, and it is checked on your
computer with no connection needed. If you would rather activate
online, ZBox checks with the ZApps licensing server only when you
activate and again as your license's end date comes near, never every
day. Changing your computer? Ask us, and your license moves to the new
one with the same end date.

To try the request in this release candidate, use Help, (Testing) Pro
License.

## HTML mail

Messages render through Microsoft Edge WebView2, which most Windows
machines already have. If HTML mail does not render, Settings has a
legacy engine option and a way to use a bundled runtime instead.
Text view (Ctrl+B toggles) always works regardless.

## Keyboard shortcuts

The same list is in ZBox under Help, Keyboard Shortcuts (F1).

<details>
<summary>Show all keyboard shortcuts</summary>

### General

- F6: move between panes.
- Ctrl+Tab and Ctrl+Shift+Tab: next and previous tab.
- Ctrl+W or Ctrl+F4: close the current tab.
- Escape: collapse an expanded thread in the message list; otherwise
  close the current tab, asking first if a message being written has
  unsaved changes.
- Application key or Shift+F10: context menu of the focused item.
- F1: Keyboard Shortcuts.
- Ctrl+Shift+Q: exit ZBox, even when Close to the system tray is on.
- Ctrl+Shift+Delete: clear the offline message cache (ZBox's own
  copies only, nothing on any server).

### Mail

- Ctrl+N: new message.
- Ctrl+Shift+N: new email account.
- F5: get new mail for the current account.
- Shift+F5: get new mail for all accounts.
- Ctrl+Shift+J: jump to the Inbox message list.
- Ctrl+Y: go to the folder list.
- Enter on a closed account or folder in the folder list: open it,
  like Right Arrow.
- Ctrl+Shift+B: Address Book.
- Ctrl+Shift+F: Search tab.
- Ctrl+Shift+T: show related messages.

### The message list

- On a collapsed thread, Delete, Archive, Flag, Junk, Move and Copy
  act on the whole thread. Expand it first (Right Arrow) to act on
  one message.
- Ctrl+A: select all messages.
- Ctrl+Shift+L: load more messages.
- Delete: move to Trash.
- Shift+Delete: delete permanently.
- Ctrl+Z: undo the last Delete, Archive, Mark as Junk or Mark as Not
  Junk. Also works in the Search results, the folder tree and an
  open message.
- S: flag or unflag.
- A: archive.
- J: mark as junk.
- Shift+J: mark as not junk.
- W: Watch Thread on or off.
- K: Ignore Thread on or off.
- M: Move To menu of folders.
- Shift+M: move by typing part of a folder name.
- C: Copy To menu of folders.
- The single keys S, A, J, W, K, M, Shift+M and C are on by default
  and can be turned off in Settings.
- Enter or Space on a collapsed thread: open its newest unread
  message (the newest if all are read) in one tab.
- Right Arrow on a collapsed thread: show its messages without
  opening any.
- Left Arrow: collapse the thread the selection is in.
- Ctrl+Shift+O: open the message in conversation view.
- Star: expand all threads. Backslash: collapse all threads.

### An open message

- Ctrl+R: reply.
- Ctrl+Shift+R: reply all.
- Ctrl+L: forward.
- Ctrl+Delete or Ctrl+D: move to Trash. Shift+Delete: delete
  permanently.
- Alt+A: archive, only while the message body has focus.
- Ctrl+Shift+Page Down and Ctrl+Shift+Page Up: next and previous
  message in the thread, in the same tab.
- Ctrl+B: switch between Text and HTML view.
- Ctrl+P: print. Ctrl+Shift+P: print preview.
- Ctrl+S: save message as a file.
- Ctrl+U: announce sender name and address.
- Ctrl+Shift+U: announce the sender and copy the address.
- Ctrl+Shift+I: show remote content in this message.
- Ctrl+Shift+Equals, Ctrl+Shift+Minus, Ctrl+Shift+0: larger, smaller
  and reset message font size.

### Writing a message

- Ctrl+Enter or Alt+S: send.
- Ctrl+S: save draft.
- Ctrl+Shift+A: attach a file.
- Ctrl+Shift+S: insert the signature of the account in From.
- Ctrl+T: insert a template, chosen from the templates of all your accounts.
- Ctrl+Shift+V: paste as quotation.
- Ctrl+Shift+W: word count.
- Ctrl+Shift+P: preview the message as it will be sent.
- Down Arrow in To, Cc or Bcc: open address suggestions. Enter or Tab
  inserts, Escape returns, Shift+Delete removes the address from the
  Address Book.
- Escape, Ctrl+W or Ctrl+F4: close, asking first if anything is
  unsaved.
- Alt+C: Compose menu. Alt with any menu's letter opens that menu, even
  from inside the message body.

### Formatting, while writing

- Ctrl+B: bold. Ctrl+I: italic. Ctrl+Shift+X: strikethrough.
- Ctrl+Shift+8: bulleted list. Ctrl+Shift+7: numbered list.
- Ctrl+Shift+9: quote. Ctrl+Shift+6: code. Ctrl+Alt+1: heading.
- Ctrl+K: insert a link.
- Ctrl+Shift+K: say what formatting is in force at the caret.
- Ctrl+Shift+M: Format menu, from anywhere, the message body
  included.

### Spelling, while writing

- Ctrl+Shift+F7: check spelling.
- Ctrl+Shift+F9: next misspelling.
- Ctrl+Shift+F8: add the word to the dictionary.

### Diagnostics

- Ctrl+Shift+F12: Hotkeys Diagnostic on or off. Writes each key
  pressed in a message being written to the debug log. Off by
  default.

</details>

## Interface languages

ZBox's interface is available in English and 49 translations: Afrikaans,
Amharic (አማርኛ), Arabic (العربية), Azerbaijani (Azərbaycanca), Bengali
(বাংলা), Burmese (မြန်မာ), Chinese Simplified (简体中文), Chinese
Traditional (繁體中文), Czech (Čeština), Danish (Dansk), Dutch (Nederlands),
French (Français), German (Deutsch), Greek (Ελληνικά), Gujarati
(ગુજરાતી), Hausa, Hindi (हिन्दी), Hungarian (Magyar), Indonesian (Bahasa
Indonesia), Italian (Italiano), Japanese (日本語), Kannada (ಕನ್ನಡ), Korean
(한국어), Malay (Bahasa Melayu), Malayalam (മലയാളം), Marathi (मराठी),
Norwegian Bokmal (Norsk bokmål), Norwegian Nynorsk (Norsk nynorsk),
Pashto (پښتو), Persian (فارسی), Polish (Polski), Portuguese Brazil
(Português (Brasil)), Portuguese Portugal (Português (Portugal)),
Romanian (Română), Russian (Русский), Somali (Soomaali), Spanish
(Español), Swahili (Kiswahili), Swedish (Svenska), Tamil (தமிழ்), Telugu
(తెలుగు), Thai (ไทย), Turkish (Türkçe), Ukrainian (Українська), Urdu
(اردو), Uzbek (O‘zbekcha), Vietnamese (Tiếng Việt), Yoruba (Yorùbá) and
Zulu (isiZulu).
Arabic, Pashto, Persian and Urdu are laid out right to left. Choose one
in Settings, General, Interface language.

The translations were made mainly with generative translation, not by
native translators, so they will have mistakes. Mail words such as
Inbox, Junk and Trash follow Thunderbird's own wording where it has one.
If you speak one of these languages, corrections are very welcome by
email: say which language, where the text appears, what it says now, and
what it should say.

## Privacy policy

The full ZBox privacy policy, word for word. The same text is in
[PRIVACY.md](PRIVACY.md).

Effective date: 16 November 2026

ZBox is an email client for Windows, made by ZAPPS SOFTWARE LTD (development team: Harith and Mesar). This policy explains what ZBox does with your information. In short: ZBox collects nothing. It has no analytics, no telemetry, no advertising and no user accounts with the developer. Your mail is between you and your mail provider.

### 1. What stays on your computer

Everything ZBox keeps is stored inside the ZBox folder on your own computer or drive: your account settings, the copies of your mail, your contacts, your settings, and your saved passwords and Microsoft sign-in tokens.

Passwords and sign-in tokens are encrypted with Windows' own protection, and also with your master password if you set one. They never leave your computer, except to sign you in to your own mail provider.

ZBox also keeps a small encrypted note of when this copy of ZBox was first used, when an account first received mail, and the date and time given in the replies to update checks. It is used only to decide which Pro features this copy offers, stays with ZBox's own files and is never sent anywhere.

ZBox checks its own program files for changes each time it starts. The check happens entirely on your computer and sends nothing.

Installation ID. For Pro licenses, ZBox can show a short Installation ID, a code of 25 letters and numbers. It is made from your Windows installation and your system drive and scrambled so that it cannot be turned back into either of them. It only lets a license work on this computer and no other. ZBox shows it to you and never sends it anywhere by itself.

The developer has no access to any of this, and none of it is sent anywhere unless you choose to, as described below.

### 2. Connections ZBox makes

ZBox connects to the internet only for the following purposes.

Your mail servers. To receive and send your mail, ZBox connects to the mail servers you set up, such as Gmail, Outlook.com or your own provider. What those providers do with your mail is covered by their own privacy policies.

Microsoft sign-in. For Outlook.com, Hotmail, Live and Microsoft 365 accounts, you sign in on Microsoft's own page, in your browser or with a code. ZBox receives a sign-in token from Microsoft and stores it encrypted on your computer. ZBox never sees your Microsoft password. Microsoft's privacy statement applies to the sign-in itself.

Update checks. ZBox can look for a newer version on the ZApps website (https://zapps.ltd) and, for now, on ZBox's public release page on GitHub (https://github.com/zapps-ltd/ZBox). This is off unless you turn it on, and ZBox asks once before its first check. It downloads nothing by itself: a newer version is shown with a link to where it lives. The websites receive only ZBox's version number and what any web request carries, such as your IP address. GitHub's privacy statement applies to its part. The Microsoft Store version is updated by the Microsoft Store.

Online Pro activation, only if you choose it. A Pro license normally comes as a license file that ZBox checks on your computer, with no connection at all. If you choose online activation instead, ZBox talks to the ZApps licensing server to confirm that your license is valid: once when you activate it, and after that only as your license's end date comes near. It never checks daily or in the background. It sends only your license number, your Installation ID and ZBox's version number, never anything about your accounts or your mail. If you never choose online activation, ZBox never contacts the licensing server.

Blocklist updates. ZBox's tracker, ad and phishing protection uses public blocklists. When blocklist updates are on, ZBox downloads newer copies of these lists from their publishers. This is optional and can be turned off in Settings. Nothing about you or your mail is sent.

Remote content in messages. Images and other content stored on the internet are blocked by default. If you choose to load them, for one message or for a sender, they load from that sender's servers. This can let the sender know you opened the message.

Links you open. A link you choose to open is opened in your web browser.

### 3. Debug logging

Debug logging is off by default. You can turn it on for a while to help solve a problem.

The log records what ZBox does, not what your mail says. It never contains your passwords, your sign-in tokens or the text of your messages. Names, the part of each email address before the @, and subjects are replaced with placeholders before anything is written. The log can still contain technical details: folder names and message counts, the domain part of email addresses, ZBox's internal account and message numbers, dates and times, and file paths on your computer, which may include your Windows user name.

The log stays in the ZBox folder on your computer. ZBox never sends it anywhere. If you decide to share it with the developer, you send it yourself, by email, and you can read it first. The developer uses it only to solve your problem and deletes it once the problem is solved. You can delete the log yourself at any time.

### 4. Contacting the developer

If you email the developer, your message and address are used only to reply to you and to help with your request. They are not shared with anyone.

When you ask for a Pro license from within ZBox, ZBox opens a new message to support@zapps.ltd with your Installation ID and the license period you chose already filled in. Nothing is sent until you press Send, and it goes from your own mail account like any other message. The developer uses your address, the Installation ID and any license details only to issue your license, keep a record of it and help you with it.

### 5. Removing your data

To remove an account, use Tools, Remove Account. This deletes its saved password or sign-in token and the copies of its mail on your computer.

To remove everything, delete the ZBox folder.

For a Microsoft account, you can also withdraw ZBox's access from the app permissions page of your Microsoft account.

To have your license record removed, email support@zapps.ltd.

### 6. Changes to this policy

Any change to this policy is published in ZBox's GitHub repository, with a new effective date.

### 7. Contact

ZAPPS SOFTWARE LTD
support@zapps.ltd

## Reporting a bug

Email **support@zapps.ltd**. Not GitHub issues.

What helps:

1. What you did, what you expected, what happened instead.
2. Your screen reader and its version, and your Windows version.
3. Whether it happens every time or once.

If a debug log is asked for: Settings has a debug logging switch, and
each launch writes its own log in `data\logs`, named for the time it
started. That log carries no message content by design. Subjects
appear only as numbers, bodies only as the words "text block",
attachments only by kind, and no complete email addresses: not those
of ZBox's users, and not those of the people their messages are from
or to. Only the email provider's domain, such as gmail.com, can
appear, because it is needed to find problems with a particular
provider. You can read the log before you send it.

## Licence

The full ZBox licence. The same text is in
`docs\LICENSE.txt`, and in ZBox on the License page that Help >
About ZBox links to.

Copyright (c) 2026 ZAPPS SOFTWARE LTD. All Rights Reserved.
Development team: Harith and Mesar.

Software: ZBox

### 1. Grant of personal license

Permission is hereby granted to individuals to download, install, and use
official builds of this software ("ZBox") published by the copyright
holder, including beta and pre-release builds published on the ZApps
website (https://zapps.ltd), free of charge, solely for personal, private,
non-commercial use on devices owned or controlled by the user. This free
grant covers the features that work without a license key (the Free
Edition); see Section 7 for Pro features. An individual may also take
part in beta testing and report problems.

Personal use includes an individual reading and sending mail from their
own accounts -- including a work account that an employer or a business
gave them -- on a device they own or control, for their own convenience.
It does not include business use: use by or on behalf of a business or
other organization, such as installing ZBox on devices an organization
owns or manages, deploying it to or requiring it of staff, or using it to
run shared or company mailboxes as part of an organization's work.
Business use requires a business license from the copyright holder (see
Section 7).

This is a grant to USE an official build, and nothing more. It does not
permit republishing or passing on that build to anyone else -- see
Section 2. ZBox is closed-source software: its source code is not
published, and no license to it is granted (see Sections 8 and 9). A beta
build is unfinished software offered for testing; see Section 4.

### 2. Public distribution and forking prohibition

You are expressly prohibited from:

1. Publishing, hosting, or distributing ZBox -- modified or unmodified,
   in whole or in part, in any form -- publicly or privately, to any
   third party.
2. Uploading ZBox, modified or unmodified, to public code repositories,
   forums, websites, or file-sharing services.
3. Making or distributing modified versions of ZBox, or works derived
   from it.
4. Using this software for any commercial, business, or enterprise
   purpose beyond the personal use Section 1 allows, without a
   business license from the copyright holder.

### 3. Reservation of rights

All rights not explicitly granted herein -- including the exclusive right
to publish, distribute, and license this software and its source code --
are reserved by the copyright holder.

### 4. No warranty

ZBOX IS PROVIDED "AS IS" AND "AS AVAILABLE", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, AND
NON-INFRINGEMENT. THE COPYRIGHT HOLDER DOES NOT WARRANT THAT ZBOX WILL BE
UNINTERRUPTED, TIMELY, SECURE, OR ERROR-FREE, THAT ANY DEFECT WILL BE
CORRECTED, OR THAT IT WILL SEND, RECEIVE, STORE, OR DELETE ANY MESSAGE
CORRECTLY OR AT ALL.

THIS APPLIES WITH PARTICULAR FORCE TO BETA AND PRE-RELEASE BUILDS, WHICH
ARE OFFERED FOR TESTING, ARE EXPECTED TO CONTAIN DEFECTS, AND MUST NOT BE
RELIED UPON FOR ANY MESSAGE, ACCOUNT, OR DATA YOU CANNOT AFFORD TO LOSE.
YOU ARE RESPONSIBLE FOR YOUR OWN BACKUPS.

### 5. Limitation of liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE COPYRIGHT HOLDER
SHALL NOT BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY -- WHETHER
IN CONTRACT, TORT, OR OTHERWISE -- ARISING FROM OR CONNECTED WITH ZBOX OR
ITS USE, INCLUDING WITHOUT LIMITATION LOST, CORRUPTED, UNSENT, OR
MISDELIVERED MESSAGES, LOSS OF ACCESS TO ANY MAIL ACCOUNT, LOSS OF DATA,
LOSS OF PROFITS, OR BUSINESS INTERRUPTION, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

NOTHING IN SECTIONS 4 AND 5 EXCLUDES OR LIMITS ANY LIABILITY THAT CANNOT
LAWFULLY BE EXCLUDED OR LIMITED.

### 6. Third-party services

ZBox connects to mail providers and downloads blocklist and phishing data
from third-party projects. Those services are not operated by the
copyright holder, are governed by their own terms, and may change or stop
without notice.

### 7. Free Edition, Pro features, and business use

ZBox is offered free of charge for personal, non-commercial use, limited
to the features available without a license key (the Free Edition). Some
features, now or in future versions, may require a paid license key (Pro
features); their use is governed by this license together with the terms
shown at the time of purchase. A license key is personal to the person
who bought it and may not be shared, sold, or published. The copyright
holder may change which features are free and which are Pro in future
versions. A version you have already obtained keeps the features it was
released with.

Business use, as Section 1 defines it, is not covered by the Free Edition
or by a personal Pro license key, and requires a business license from
the copyright holder, on the terms agreed at the time of purchase.

### 8. No decompiling, reverse engineering, or circumvention

You may not decompile, disassemble, or reverse engineer ZBox, extract or
reconstruct its source code, modify it, or remove, disable, or get around
any license key check or feature limit, except to the extent that
applicable law expressly permits it despite this restriction.

Exception for the LGPL components: ZBox includes the NVDA Controller
Client (GNU Lesser General Public License 2.1) and Sequoia PGP inside
PySequoia (GNU Library General Public License 2.0 or later), listed under
Credits and third-party components below. You may modify those components, or replace them with
your own versions, for your own use, and you may reverse engineer ZBox
only as far as is needed to debug such modifications. Their source code is
available at the addresses given there. Nothing in this license
limits the rights that any third-party component's own license gives you
in that component.

### 9. Earlier, source-published versions

Versions of ZBox up to and including testing beta 26.10.11 were published
together with their source code under the earlier terms of this license.
Copies of those versions already obtained remain governed by those earlier
terms, which never permitted redistribution or forks. Starting with the
version that carries this text, ZBox is closed source: new versions are
published as official builds only, and this license applies to them.

## Credits and third-party components

ZBox is built using these projects, with thanks. The terms in
Sections 1 to 3 and 7 to 9 of the licence above apply only to ZBox's
own code, never to these components, which keep their own licences.

### Bundled in every published build, used unmodified

1. [Himalaya](https://github.com/pimalaya/himalaya), the command-line
   email client that does ZBox's IMAP and SMTP work. A build carries
   himalaya.exe in its himalaya folder; ZBox runs it as a separate
   program and never changes it. Copyright Clement Douin and the
   Himalaya contributors. MIT License.
2. [Python](https://www.python.org), the language runtime. Python
   Software Foundation License.
3. [wxPython](https://wxpython.org) and wxWidgets, the user interface
   toolkit. wxWindows Library Licence.
4. [IMAPClient](https://github.com/mjs/imapclient), behind instant new
   mail and fast message loading. Copyright Menno Smits. BSD 3-Clause.
5. [pywin32](https://github.com/mhammond/pywin32), Windows password
   protection. Copyright Mark Hammond and contributors. PSF-style
   licence.
6. [accessible_output2](https://github.com/accessibleapps/accessible_output2),
   which hands announcements to your screen reader. MIT License. It
   carries the NVDA Controller Client, copyright NV Access Limited,
   GNU LGPL 2.1, and the client libraries of other screen readers,
   which belong to their vendors.
7. [PySequoia](https://github.com/wiktor-k/pysequoia), OpenPGP for
   Python. Copyright Wiktor Kwapisiewicz. Apache License 2.0.
8. [Sequoia PGP](https://sequoia-pgp.org) (sequoia-openpgp), the
   OpenPGP library compiled into PySequoia, with its pure Rust
   cryptography backend. By the Sequoia PGP authors. GNU Lesser General
   Public License 2.0 or later, used unmodified. Its source code is at
   https://gitlab.com/sequoia-pgp/sequoia.
9. [cryptography](https://github.com/pyca/cryptography), OpenPGP in
   the classic format and S/MIME. Apache License 2.0 or BSD 3-Clause.
   Its Windows package carries [OpenSSL](https://www.openssl.org),
   Apache License 2.0.
10. [Trix](https://github.com/basecamp/trix), the editor behind the
    message body. MIT License.
11. The SCOWL English word list, behind spell check. SCOWL licence,
    carried with the word list.
12. [keyring](https://github.com/jaraco/keyring), read only, to move a
    password from an older ZBox. Copyright Jason R. Coombs. MIT
    License.
13. [pywinrt](https://github.com/pywinrt/pywinrt), Windows Runtime
    access for the startup task, in the Microsoft Store build only.
    MIT License.
14. [pypstreader](https://github.com/justanyone/pypstreader), which
    reads Outlook data files (.pst) for Import Mail from Other
    Programs. MIT License.
15. [outlook-pst-rs](https://github.com/microsoft/outlook-pst-rs),
    Microsoft's reader for Outlook data files, from which parts of
    pypstreader are derived. Copyright Microsoft Corporation. MIT
    License.

### Downloaded while ZBox runs, never bundled

1. [StevenBlack unified hosts](https://github.com/StevenBlack/hosts),
   ad and tracker blocking. MIT License.
2. [EasyPrivacy](https://easylist.to/pages/licence.html), tracker
   blocking, by the EasyList authors. GNU GPL 3 or Creative Commons
   Attribution-ShareAlike 3.0.
3. [Phishing.Database](https://github.com/Phishing-Database/Phishing.Database),
   the phishing link check. Copyright Mitchell Krog, Nissar Chababy and
   the Phishing.Database contributors. MIT License.

### Already on your computer

1. Microsoft Edge WebView2 Runtime, for HTML mail. Microsoft Software
   License Terms.

Each component is also listed, with its licence and where it comes
from, in `docs\LICENSE.txt` and on the License page that Help >
About ZBox links to.
