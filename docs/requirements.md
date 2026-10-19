# Requirements

## Functional requirements (what the system must DO)
1. The system shall let the cashier open a sign language recognition option from the POS screen.
2. The system shall turn on the webcam connected to the POS only after the cashier selects this option, and turn it off when the cashier closes it.
3. The system shall detect the customer's hand in the live camera video.
4. The system shall recognise a set of BIM signs used at checkout (for example 10 to 20 signs such as price, cash, card, bag, receipt, yes, no, thank you, wait and help).
5. The system shall show each recognised sign as text on the cashier's POS screen.
6. The system shall let the cashier clear the recognised text.
7. The system shall show a message when no hand is detected or a sign is not recognised.

## Non-functional requirements (how the system must PERFORM)
1. The system shall show a recognised sign on the POS screen within 1 second after the customer holds it steady.
2. The system shall correctly recognise at least 90% of the supported signs in tests with at least 3 people who were not in the training data.
3. The system shall process the camera video in the browser on the POS computer and shall not store or send any video or images.
4. The system shall only display the recognised text and shall not change the cart, prices or payment by itself.
5. A new cashier shall be able to start the sign language option within 5 minutes without help