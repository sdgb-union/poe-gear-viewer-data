# Privacy Policy for PoE gear-viewer

Effective date: February 27, 2026

PoE gear-viewer ("the Extension") is a Chrome extension that detects supported live stream pages, maps stream channels to Path of Exile accounts, and shows an in-page inventory overlay.

## 1. Data We Process

The Extension processes only the data needed to provide its feature:

- Current tab context on supported hosts (platform, channel identifier, live status)
- Path of Exile public/account API response data required for overlay display
- Local extension settings and cache values stored in browser local storage

The Extension uses Chrome `storage` to store:

- UI preferences (for example, language and display options)
- Temporary cache data (for example, mapping and league/character lookup cache)

## 2. Data We Do Not Sell

- We do not sell personal data.
- We do not use data for advertising.
- We do not run third-party analytics SDKs inside the Extension.

## 3. Data Sharing

Data is requested directly from the following services only as needed for functionality:

- `youtube.com` / `m.youtube.com` / `chzzk.naver.com` (stream context)
- `pathofexile.com` / `poe.game.daum.net` / `api.pathofexile.com` (game data)
- `cdn.jsdelivr.net` (mapping JSON source)

No separate backend server operated by this project is required for normal extension operation.

## 4. Permissions and Why They Are Needed

- `storage`: Save local settings and cache for performance and usability.
- Host permissions:
  - YouTube / CHZZK: Detect supported stream pages and render overlay.
  - Path of Exile domains: Fetch character, league, and item data.
  - jsDelivr: Fetch mapping JSON configuration.

## 5. Retention and Control

- Data stored via Chrome `storage` remains on the user's browser profile until removed.
- Users can remove stored data by uninstalling the Extension or clearing extension storage in browser settings.

## 6. Security

- The Extension requests only the minimum permissions required for its purpose.
- The Extension does not intentionally execute remote code.

## 7. Changes to This Policy

This policy may be updated when functionality or data handling changes.
The updated version will be published in this repository with a new effective date.

## 8. Contact

For questions about this policy, contact the maintainer through the repository issue tracker where this policy is hosted.

