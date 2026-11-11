# Deposit Check Prototype

Coded prototype for **CSC1058 User Interface Design and Implementation (DCU), Group Project D**.

**Live prototype:** https://marioemanciu.github.io/deposit-check/

## What it is
A redesign of a bank transfer flow that helps students avoid private accommodation deposit scams. When a student pays a new payee and selects *Private accommodation deposit*, the app makes risk visible before any money leaves their account:

- Progress bar showing each step of the check
- Live warnings while typing the rent and deposit (e.g. deposit above one month's rent)
- One safety question per screen, based on Garda advice
- Save and finish later, with the paused check shown on the home screen
- A summary of every warning sign before sending
- "Send when I've viewed it": the payment is set up but only sent once the student confirms the viewing, and it cancels automatically after 7 days

## How to use it for testing
1. Open the live link on a phone.
2. Tap **Reset saved progress**, then choose **Redesigned flow** or **Current flow (baseline)**.
3. Hand the phone to the participant on the scenario screen.

## Notes
- Student prototype only. No real money, banking or personal data is used.
- Built as a single HTML file (HTML, CSS, JavaScript), no install needed.
- Area rent figures used for the low-rent warning are illustrative, not real RTB data.
- Generative AI (Claude) was used to help build this prototype, as declared in our report.

**Team:** Mario Ciuciu, Emir Demirkol, Ibrahim Khan, Ilja Solovejs, Vasileios Papakostas
