# Homeassistent gas usage alert for the P1 smart meter
This is an automation script to check when you go above your set daily limit of gas usage.
You will then be notified via Ntfy.

## Important!
This automation is tested with the HomeWizard P1 smart meter.
Other meters might have variying success.

## Usage
The script makes use of the following environment variables:
- HA-HOST: the Homeassistent API url to your gas meter.
- HA-ALERT-AFTER: After what amount of gas usage to alert.
- NTFY-URL: The Ntfy url including the topic to which to send the alert.
