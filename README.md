# Mahjong Coach

A single-page Hong Kong mahjong game for learning, with a built-in coach.

- Hong Kong rules, 3 fan minimum, 1–3 AI opponents with different play styles
- Character tiles hide their Chinese numerals until hover, to help you learn them
- Coach panel: possible hands with probabilities, hints, table reading (danger of each discard)
- End-of-hand review that grades every move
- Gallery of all scoring hands, filtered by how close your tiles are
- Works on phones

Open `public/index.html` in a browser; there is no build step.

Hosted at https://mahjong.jamesridey.dev as a Cloudflare Worker with static assets. Deploy with `npx wrangler@4.40.0 deploy` (newer Wrangler 4.165 fails on this account after uploading, with "This Worker does not exist" [10007]).
