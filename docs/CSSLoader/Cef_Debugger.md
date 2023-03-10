# 🌐 CEF Debugger

![Debugger](img/Debugger.png)

The Chromium Embedded Framework (CEF) debugger is very useful for creating themes, as it allows you to play around directly with the style of the Steam Deck UI.

The debugger allows you to access tabs that are used for the UI. The main ones are listed below.

- `SP` - The main UI of the Steam Deck
- `QuickAccess` - The Quick Access overlay
- `MainMenu` - The Steam menu overlay

## 🧰 Recommended Setup

1. Turn on the "Allow Remote CEF Debugging" setting in the Decky settings.
1. Open a Chromium-based browser (ex. Google Chrome, Microsoft Edge, Brave).
1. Go to the inspect page of your browser (ex. chrome://inspect, edge://inspect, brave://inspect).
1. Under "Discover network targets", click "Configure", and enter "{DECK_IP}:8081".
   - You need to be on the same network as your Steam Deck.
   - You can find the IP of your Steam Deck by going into your internet settings, selecting the currently connected network, and looking at the "IP Address" field.
1. Wait a few seconds, and you will see multiple tabs appear under "Remote Target"
   - After selecting a tab, you should be able to see the HTML and CSS used for that specific tab, like the screenshot above.

## 🧰 Legacy Setup

1. Turn on the "Allow Remote CEF Debugging" setting in the Decky settings.
1. Open a Chromium-based browser (ex. Google Chrome, Microsoft Edge, Brave).
1. Enter "{DECK_IP}:8081" in the browser.
   - You need to be on the same network as your Steam Deck.
   - You can find the IP of your Steam Deck by going into your internet settings, selecting the currently connected network, and looking at the "IP Address" field.
1. Select a tab.
   - After selecting a tab, you should be able to see the HTML and CSS used for that specific tab, like the screenshot above.