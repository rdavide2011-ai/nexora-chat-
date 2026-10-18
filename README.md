
# Nexora Chat

Test delle notifiche Web Push per la PWA.

## File del sito

- `index.html`: interfaccia e registrazione push.
- `service-worker.js`: ricezione delle notifiche in background.

## Backend

La Edge Function `schedule-test-notification` è ospitata su Supabase.

Secrets richiesti:
- `VAPID_PUBLIC_KEY`
- `VAPID_PRIVATE_KEY`

Non inserire mai la chiave privata VAPID nel codice pubblico.

## Pubblicazione

Il sito viene pubblicato da Vercel quando viene aggiornato il branch
main di GitHub.
