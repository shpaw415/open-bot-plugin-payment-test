# Payment Test

A deliberately useless plugin whose only purpose is to test the open-bot
marketplace **paid listing** flow at the minimum price ($0.99):

1. Buy it from its marketplace page (Stripe test checkout).
2. Install it — the artifact download is gated on the license.
3. Refund it from the admin Purchases panel and watch the license block
   reinstall/update while installed copies keep running.

It ships one payload file (`hello.txt`) and nothing else.
