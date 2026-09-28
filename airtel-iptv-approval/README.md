# IPTV channel approval (Airtel Thanks)

An interactive mobile prototype showing how an account owner approves or declines a paid channel added on their Airtel IPTV connection. It works like a MyGate approval request.

Open `index.html` in a browser. The homepage layer is `home.png`, the production Airtel Thanks screenshot, left unchanged. Only the push notification and the approval bottom sheet are new. `sony-sports.webp` is the channel logo. The Airtel mark in the notification icon comes from Simple Icons.

## Flow

1. **Push notification**: "Channel addition request" from Airtel Thanks on the lock screen. Tap it.
2. **Approval sheet**: the homepage opens, dims, and the IPTV request sheet slides up. The Sony Sports HD logo sits centred, half outside the sheet, above the request, ₹22/month and the bill impact, all centre-aligned.
3. **Mid-swipe**: drag the red handle. The track fills, and past about 60% the label changes to "Release to approve". Letting go early springs it back.
4. **Channel approved**: the swipe completes into a checkmark with a haptic pulse, and a red tick lands on the channel logo and the confirmation shows inside the sheet. It closes by itself.
5. **Request declined**: tapping Decline shows a calm, neutral confirmation, then closes.

The left panel jumps to any state. **All 5 frames** shows the static frames side by side.
