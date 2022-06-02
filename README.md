# qksms-notes
Notes about qksms tests

# regex builds

Builds can support regex, thanks to a commit that is merged.

Anyway that doesn't explain us a lot about how to block a sender by name, or doesn't offer an option to use case-sensitive or insesitive or allow body inspection like neko-sms.

https://regex101.com/ seems a very good site to test regex rules.

# case-scenario

A sms used to send us advertising will contain specific word like energy or a variation of it like Energy, either inside the body of sms or as sender.

# regex-ruls

From simple research seems these kind of regex is effective to block:

``(?i)(energy)``
