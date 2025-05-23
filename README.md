<p align="center">
<img width="150" src=https://github.com/mickaphd/SimpleCookie/assets/25211018/64489133-ecae-435e-92d4-53cc79c9302c)>
</p>


<h3><i>SimpleCookie, a minimalist yet efficient cookie manager for Firefox</i></h3>
  
<i>SimpleCookie is the easiest and fastest way to view, learn about, and delete cookies. It also serves as a configurable cleaner. However, remember that cookies and related data are most of the time very useful so please, use this add-on with caution, read the description carefully, and report any bugs or feature requests on GitHub.</i>

<a href="https://addons.mozilla.org/firefox/addon/simplecookie/"><img src="https://blog.mozilla.org/addons/files/2015/11/get-the-addon.png" height=60px></a>

<h3>Main popup</h3>

<img width="200" alt="Popup_light" src="https://github.com/user-attachments/assets/3241e18c-01ee-4992-a974-8d820ad482d2">
<img width="200" alt="Popup_dark" src="https://github.com/user-attachments/assets/1626f4ad-b985-4242-9404-29a5d58a22f1">

<h3>Detailed table</h3>

<img width="350" alt="Table_light" src="https://github.com/user-attachments/assets/cee9e77e-de8c-4773-8db9-5487a894d4e7">
<img width="350" alt="Table_dark" src="https://github.com/user-attachments/assets/cd52b5d7-75e5-4683-8c9a-7a25c8bc4128">

<h3>Settings</h3>

<img width="350" alt="Settings_light_extensions-menu" src="https://github.com/user-attachments/assets/31b53b88-0631-4882-ae2f-956acad661aa">
<img width="350" alt="Settings_dark" src="https://github.com/user-attachments/assets/01096fa4-1e24-4221-b088-4be14cc63219">

<h3>Key features</h3>

1. <b>Cookie fetching:</b> SimpleCookie supports all cookie jars (containers) and partitioned cookies (3rd party, CHIPS) and displays a list of websites with the corresponding number of cookies.

1. <b>Domain aggregation:</b> SimpleCookie consolidates cookie subdomains under a main domain for clarity. It includes hundreds of exceptions for specific Second Level Domains (SLDs) used in various countries (e.g., .co.uk, .gouv.fr).

1. <b>Organized list:</b> Websites are sorted alphabetically for easy access. Sites storing cookies with an open tab are shown in green. The active tab's domain is highlighted, along with sites in special containers or with partitioned cookies.

1. <b>Detailed view:</b> Right-clicking on a listed website opens a table with detailed information about its associated cookies. Right-clicking additional sites consolidates this table with more cookies.

1. <b>Effortless cookie removal:</b> A single click on a website deletes all cookies associated with that domain. Clicking on a specific cookie line in the detailed table removes only that individual cookie.

1. <b>Safety first:</b> A 'star/favorite' icon allows you to protect cookies from being deleted. A 'backwards' icon appears in the Dock to undo the very last cookie deletion you triggered. A confirmation prompt also appears for the Dock shortcuts. An export/import function (JSON format) allows you to backup your cookies. Many footnotes have been added for educational purposes (icons, table headers, settings, etc.).

1. <b>Cookie editor:</b> An option in the settings allows you to create a new cookie from scratch. An edit option is available from the detailed table (in BETA).

1. <b>Dock shortcuts:</b> The 'broom' icon deletes all cookies from websites with closed tabs, while retaining cookies from open tabs (highlighted in green) and your favorites. The 'vacuum' icon deletes all cookies stored in Firefox except your favorites. The 'missile target' icon launches the myCleaner feature, allowing you to clear your selected browsing data. The 'gear' icon opens the settings.

1. <b>Tab switcher:</b> Hold Command (macOS) or Ctrl (PC) to enable the Tab Switcher feature so that a left click on one of the open tabs highlighted in green will switch to it.

1. <b>Tracker database:</b> SimpleCookie uses an internal tracking database derived from Ghostery (https://github.com/ghostery/trackerdb) to identify organizations/websites known to track behavior (ghost icon). While this does not confirm the collection of data in requests and cookies from these sites, they are known for their impact on user privacy.

1. <b>Theme options:</b> Light and Dark themes work seamlessly with Firefox's theme settings. The add-on also uses a system font that should be appropriate for the OS it runs on (macOS, Windows, Linux).

1. <b>Lightweight design:</b> Minimalist and efficient UI. No background scripts intentionally.

1. <b>Privacy policy:</b> SimpleCookie does not collect any data and there is no analytics or telemetry stuff in the code. This is just an open source hobby project by an indie dev (I'm not even a developer, I'm a researcher!) who is concerned about privacy. SimpleCookie uses the following permissions to work properly: 'all_urls' (for the domain aggregation), 'browsingData' (to clean up the dust!), 'cookies' (of course!), 'tabs' (to identify the active and closed tabs), 'contextualIdentities' (for the containers) and 'storage' (to store the settings).
