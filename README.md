# Moteino RTC shield

This is an RTC Shield for Moteino based on Maxim DS3234. Recommended library to use: https://github.com/OSBSS/DS3234lib3

To force interrupts in backup battery/low power mode (~1uA), don’t solder the 10K resistor, enable Arduino internal pullups
on pin 4 instead and pin-power the RTC when needed by turning pin 3 on. Backup battery should last 1-2 years @ 30 second alarm intervals depending on temperature variations.
