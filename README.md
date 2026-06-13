# Conduit Communicator
Reimplements a UI containing your mail, calendar, tasks, and online chats such as IRC, XMPP, and Matrix. Also allows for isntant messaging on the Fediverse. Adds a customizable Speed Dial-styel home page with widget support which can be made to fit your needs.

## Sidebar
The sidebar provides a panel showing an overview of your online communications. Inboxes will be sorted by accounts, with each accont having nested entries for mailbox folders, IM servers, or chat rooms. A "Favorites" section will exist for quick access to your favorite channels. 

## Toolbar buttons
- Mail
- Calendar & Tasks
- Matrix, IRC, and XMPP
- Messages
  - Fediverse IMs
  - Direct messages from IRC, Matrix, or XMPP

## Loading in Firefox

1. Open `about:debugging`.
2. Choose **This Firefox**.
3. Choose **Load Temporary Add-on**.
4. Select the root `manifest.json`.

## Proposed features
- Side panel websites (mobile layout) - doesn't seem feasible due to iframe limitations and only one sidebar per extension
- IMAP/POP3 client
  - Autodiscover support
  - Side panel mail list, opens mail client
  - Multi account support
- Calendar and to-do functionality
- Chat client featuring XMPP, IRC, and Matrix support
- RSS/Atom support integrated into email client UI
- Maybe some sort of fediverse integration?
- Firefox Home widget support
  - Speed dial widget
  - RSS/feed widget
  - Calendar widget
  - Mail summary widget
  - Chat notifications widget
