# CropSlot: farmer app prototype (Smart India Hackathon 2026)

Clickable prototype of the **farmer side** of Kisan CropSlot, built for Smart India Hackathon 2026, problem statement **SIH26032** (Ministry of Consumer Affairs, Food & Public Distribution).

**The problem:** at MSP procurement centres, farmers wait in long queues without knowing when their produce will be weighed or what its status is.

**The idea:** farmers book a time slot or take a walk-in token, see where they are in the live queue, and show a QR code at the gate. The commission agent (arhtiya) runs the queue from a dashboard.

## What's in the prototype

- Pick a mandi and a time window, then confirm the booking (screens in English and Hindi)
- A QR pass to show at the gate
- Booking status updates as the produce moves through the centre
- Every screen inside an Android phone frame, so it can be demoed in a browser

## Run it

No build step. Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Related

- [kisan-cropslot-arhtiya-dashboard](https://github.com/i-varunsharma/kisan-cropslot-arhtiya-dashboard): the arhtiya (commission agent) side

**Status:** design prototype with no backend. The full product, with a real queue backend, is being rebuilt from scratch.

## Author

[Varun Sharma](https://github.com/i-varunsharma), team lead of team MandiMitra.
