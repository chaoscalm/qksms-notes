# qksms-notes
Notes about qksms tests

# regex builds

Builds can support regex, thanks to a commit that is merged.

Anyway that doesn't explain us a lot about how to block a sender by name, or doesn't offer an option to use case-sensitive or insensitive or allow body inspection like neko-sms.

https://regex101.com/ seems a very good site to test regex rules.

# case-scenario

A sms used to send us advertising will contain specific word like energy or a variation of it like Energy, either inside the body of sms or as sender.

# regex-rules

From simple research seems these kind of regex is effective to block:

``(?i)(energy)``

Both Energy and energy, but also variation of it, like enErgy.

# builds-size

Build based on kinng sources weight around 16 MB

Another build refactored to remove rtl stuff weight around 32 MB, and it is about this build that I want see until which point can be upgradable.
