# Release notes

Installers for each version are available on the [Releases page](https://github.com/datacg/startstudio/releases). Installed copies can update through **Check for updates** in the application.

## 2.0.0 — November 2026

- **Sections inside a collection.** Split a collection's links under titles, such as "Documentation" and "Tools", without adding another level to click through. Use **New section** in an open collection, then drag links onto a section's title. The **Section** field in the link window and in **Move to…** does the same. Drag a section's title to reorder it, or use **Move up** and **Move down** in its ⋯ menu. Deleting a section keeps its links.
- **Command palette.** Press **Ctrl+K** and type part of a link's name, a collection, or an action, such as "New link". Choose with the arrow keys and press Enter. The **/** key now takes you to the page search.
- **Select several links at once.** Ctrl+click cards in the preview, or Shift+click to select a range, then move or delete them together from the bar at the bottom. **Select** is also in each link's ⋯ menu, and Esc clears the selection.
- **Duplicate links.** The link window tells you when an address is already somewhere else on the page, and **Duplicate links** in the command palette lists every repeated address so you can clean up.
- **Check links.** In the Windows app, **Check links** in the command palette opens each address and lists the links that no longer answer or that moved to a new address. One click switches a link to its new address.
- **Most used or recently opened.** Under **Options → List at the top of the page**, show your most used or most recently opened links above your collections. The count stays on your device, and nothing is sent anywhere.
- **A cleaner title inside a collection.** The collection's name is the page title, with the levels above it on the line below.
- Pages with sections need this version or later.

## 1.9.0 — November 2026

- **Drag cards to move them.** In the editor, drag a link or collection card in the preview to change its place. Drop it on a collection's card to put it inside, on a level of the breadcrumb to move it up, or on the edge of another card to change the order. The reorder arrows are gone from the cards and from the sidebar.
- **A ⋯ menu on every card.** **Move to…**, **Duplicate**, **Watch this page**, and **Delete** are one click away, and the menu works with the keyboard. **Move to…** puts a link or a collection anywhere in the tree without dragging. The link window (**Collection**) and the collection window (**Inside**) still move things too.
- **More room at the top.** Inside a collection, the breadcrumb is the page title (⌂ All collections › Work › Clients), and the welcome text steps aside, so your links start higher on the screen.
- **Undo, right in the notice.** Deleting a link no longer asks first: the notice that appears offers **Undo**. Deleting a collection still asks, and offers Undo too.
- **Clearer tabs.** The editor tabs are now **Appearance · Content · Options**. Updates and background checks moved to **App settings**, behind the gear at the top of the window.
- **Helpful tooltips.** Buttons explain themselves when you point at them or reach them with the keyboard. Press Esc to hide a tooltip.

## 1.8.0 — November 2026

- **Collections inside collections.** A collection can now hold other collections, as many levels deep as you need, so similar links stay together. Use **New subcollection** in an open collection, or choose **Inside** in the collection window. Cards show everything they hold, such as "2 subcollections · 14 links".
- **Always know where you are.** A clearer breadcrumb at the top shows every level (All collections › Work › Clients), and each level is one click away. **Back** goes up one level, and search looks through every level and shows where each result lives.
- **Collections and links as a tree.** In the editor's sidebar, expand a collection to see its subcollections and links. Drag by the handle to reorder, or drop an item on the middle of a collection to put it inside. The up and down arrows are still there, now larger and with tooltips. A filter finds any collection or link, and you can drag the sidebar's edge to make it wider.
- **A to Z, or Z to A.** Sort everything at once, at every level, with one click, and use Undo to go back. Or keep your top-level collections, or any collection, always in alphabetical order. Numbers sort the way you expect: 2 comes before 10.
- **Bookmark folders stay folders.** Importing bookmarks from your browser now keeps the folders inside folders as subcollections.
- **Watched links stand out.** Links you watch show a small bell. When you open a notification with **Show on page**, the link's card flashes so you see it right away.
- Pages with subcollections need this version or later.

## 1.7.0 — November 2026

- **My pages is always at hand.** In the editor, a highlighted **My pages** button sits next to the Start Studio logo, followed by the name of the page you're editing. One click takes you back to create, rename, delete, and reorder your pages. In the app's preview, **My pages** is in the page header.
- **Edit in Start Studio.** Your pages and start.html now open in the browser ready to use, with links, search, collections, and notifications. To change a page, select **Edit in Start Studio** at the top: the app opens on that same page. The first time, your browser asks for permission to open the app. Editing now happens only in the app, which has My pages, autosave, and link watching.

## 1.6.0 — November 2026

- **A notification bell.** The **Notifications** bell at the top of the app shows how many updates your watched links have, across all your pages. When news arrives, the app's taskbar button also flashes, so you won't miss it even if the Windows notification goes by.
- **All your notifications in one place.** The bell opens your notifications. Show all, new, or read ones; open the link or show it on its page; mark each one as read or unread; and delete them one by one or all at once. The **Watched links** tab lists every link you watch, with its rule, how often it's checked, and the last check, plus **Check now** and **Edit**.
- **Know when a term disappears.** Besides a page change or a term that appears, a link can now notify you when a term disappears from the page, such as "Applications open".
- **Easier to spot.** Collections show their updates as a badge in the corner of the card. On your start page in the browser, a bell in the header shows that page's news; marking it as read there applies to that browser only.
- Alerts from version 1.5.0 carry over as unread notifications.

## 1.5.0 — November 2026

- **Watch a page for updates.** Edit a link and turn on **Watch this page**. Start Studio can notify you when the page changes, or when a term appears on it, such as the number of the next version of a standard. Choose how often to check: every hour, every 6 hours, or once a day. **Test now** shows whether the term is already on the page.
- **Know what changed.** When there's news, Windows shows a notification, and the link gets a badge that also appears on your start page in the browser. Collections and My pages show how many updates are waiting. The link window lists earlier updates, and **Mark as seen** clears the alert.
- **Keep checking in the background (optional).** Under Settings → Windows application, **Check watched links in the background** keeps Start Studio in the notification area when you close the window and starts it with Windows. It's off by default.
- **Smarter search.** Search ignores accents and finds links that contain every word, in any order. Use quotes for an exact phrase, a hyphen to exclude a word, and `col:` to search specific collections. Results are grouped by collection.
- **Back and Forward work.** The page address remembers the open collection, so your browser's Back button returns you to it, including after you open a link.
- **Easier dialogs.** Dialogs open with the cursor in the first field, and clicking outside closes them. If you've typed something, Start Studio asks first.
- **Clearer arrows.** The arrows that reorder links now point left and right.

## 1.4.4 — November 2026

- **Fresh installations work again.** The installer no longer rejects a new folder at the **Your pages folder** step, including the suggested C:\startstudio. You can choose any writable folder outside the program folder, and the installer creates it for you.
- **Clearer folder checks.** Enter a full path, such as D:\startstudio. If a folder can't be used, the installer removes any empty folder it just created and asks you to choose another one.

## 1.4.3 — November 2026

- **A redesigned My pages.** Your pages now appear as cards, side by side, instead of one full-width row each. **Open**, **Rename page**, and **Delete page** sit at the bottom of each card.
- **Reorder your pages.** Drag a card, or use the arrow buttons, to change the order. The first page is marked **Opens first**, because it's the page start.html opens by default.
- **Transparent logos on My pages.** Logos now sit directly on the card, so transparent images stay transparent. A light or dark plate still appears if you chose one under **Logo background**.
- **A cleaner first screen.** The app version and **Check for updates** moved to the footer, and they stand out only when an update is available. **Browser setup** now sits next to the start.html tip.
- **Small screens.** The buttons for creating and importing pages stack neatly on narrow windows.

## 1.4.2 — November 2026

- **Update notifications.** When Start Studio opens, it checks for a new version. If one is available, it offers to download it and then to install it, after saving your changes.
- **You stay in control.** Choose **Not now** to keep working, or turn the startup check off under Settings → Windows application. **Check for updates** on My pages still works at any time.

## 1.4.1 — November 2026

- **Check for updates from My pages.** The first screen of the app shows the installed version and a **Check for updates** button. When a new version is available, you can download and install it from there. The button is still available under Settings → Windows application.
- **Version in the footer.** The credits now show the Start Studio version, including on exported pages.
- **Updated credits.** The footer notes that the app was developed with Codex and Claude Code.

## 1.4.0 — November 2026

- **Transparent logos.** PNG logos keep their transparent background. Under **Logo background**, choose Transparent, Light plate, or Dark plate; the plates take a light tint of the page's accent color.
- **SVG logos.** Logos can be SVG files up to 1 MB. Scripts and external references are removed on upload.
- **Maximum logo width.** Narrow logos no longer leave empty space before the text beside them. The preview shows transparent areas, and My pages displays each logo over its page's own background.
- **Large images scaled down.** Very large logos and background images are reduced on upload, which keeps pages lighter.
- **Dark mode in the editor.** The editor, dialogs, and My pages follow the Windows dark mode setting. The preview and your saved pages keep the theme you chose.
- **More consistent colors.** Missing or invalid colors now come from the page's own theme.
- **Safer pages.** Text typed into a page is always treated as text, never as code.
- **More reliable folder moves.** When an interrupted move of the data folder is resumed, the app recognizes the new folder even if Windows spells the same path differently.

## 1.3.1 — October 2026

- New collections start with the folder icon. The chosen symbol is kept when link favicons are downloaded.
- Pick a favicon for a collection card, or choose **None** to return to the symbol or emoji. Link images are kept.
- Local image and other-site options remain available, collapsed, under the collection icon settings.
- Detection of external changes, recovery of interrupted operations, and restoring backups as new pages.
- Optional batch favicon import and contrast checking for custom colors.
