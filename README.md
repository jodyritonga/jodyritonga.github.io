# Arc Search for Android — tab origin attribution PoC (VICTIM origin)

Security research proof-of-concept for a report to The Browser Company.
"Victim Bank" is fictional; no real service is impersonated and no credentials
are collected by any server (the attacker page echoes what you type back onto
the screen so the cross-origin delivery is visible).

- This origin (`https://jodyritonga.github.io`) is the **top-level page**.
- It embeds third-party content from a **different** origin,
  `https://victimjodyritonga-create.github.io`, in an iframe.

Open this page in Arc Search for Android and tap inside the bordered box.
