We're the creators of PicKey.ai ([site](https://PicKey.ai), [subreddit](https://www.reddit.com/r/PicKeyAI)) - a new kind of Password Manager that uses memorable objects, places, and faces around you to manage all your passwords.
### Why ?
Our goal with PicKey (Picture + Key) is to remove the barriers to cybersecurity and make the user experience fun by providing access to military-grade security in a natural, gamefied way.

The main reasons we created PicKey are :

1. Passwords are often forcibly memorized.  The requirement to remember numbers, uppercase and lowercase letters, and special characters is more of an obligation as websites demand it. This leads to an unnatural experience where people forget, repeat, or give up on their passwords.  Some even forget their master passwords in traditional password managers, despite their technical savvy, because it feels more like a chore than a positive experience.

2. There is currently no solution for the most vulnerable internet users. With [24% internet users](https://webtribunal.net/blog/password-stats) using passwords like "password123", "123456", its challenging to teach mom, pops and grandma about cybersecurity. Being cybersecure is hard and for a sizable chunk of internet users, it comes at a heavy price of convenience. It is almost unthinkable that such users would be able to get access to, or practice top notch cybersecurity.
#### But what about Password Managers?
Password manager apps rely on a master password. Remember this single, long master password, and the app will save, manage, and autofill all your other passwords. There are several problems here :

- Master passwords inherit all traditional password problems, such as vulnerability to keyloggers and brute force attacks.
- They still feel like an obligation.
- The user experience is lacking; no one is excited about entering passwords.
- They can be complex (in terms of resetting and platform restrictions)
- Hacks
### How Does PicKey Solve This ?
PicKey creates a new kind of a Master Password (called the Master Key) from a combination of :
1. Your favorite picture (leveraging adaptive picture memory)
2. An animated 3D character (often has music & sound)

This combination creates a Master Key that you use to login/signup to PicKey. Once in, PicKey manages, saves and autofills all your passwords.

Imagine creating a Master Key with a picture of your room featuring a roaring virtual dinosaur, or managing all your passwords with a photo of your favorite teddy bear and a dancing robot beside it, or turning that favorite painting on the wall with a hummingbird hovering in front, into a password vault.

The possibilities are endless, private, personalized, fun and most importantly .. random (your choices for master key, will be naturally unpredictable than mine).

Humans are [visual beings](https://www.sciencedirect.com/science/article/abs/pii/S0885201409000471) and remember visuals [60,000 times](https://oit.williams.edu/files/2010/02/using-images-effectively.pdf) better than text. PicKey's Master Key is not only 60,000 easier to remember than any password or master password, but is so randomly different between individuals (extremely high starting [entropy](https://en.wikipedia.org/wiki/Entropy_(computing))), that it becomes [resistant to quantum computing attacks](https://blog.pickey.ai/defying-brute-force-the-unparalleled-strength-of-pickeys-master-key/).
### Details

#### Tech & Misc
- The favorite picture is processed by vision neural networks that are trained to understand physical changes (age, light, view angle etc) and recognize your choice again when you take the picture of the same thing for master login next time. In PicKey, your picture is called as the "Vision Secret" as it is a visual secret between you and PicKey and mimics human photographic memory.
- The 3D character is called the Keymoji secret. Augmented reality view is default for iPhones and supported Android devices. Else we switch to a 3D view.
- PicKey Supports iPhones > iOS 14, Android > 7, Chrome, Firefox, Edge and Safari on desktops
- Biometrics on mobile, QR based passwordless login on desktop via browser plugins
- PicKey has a comprehensive free plan that should be enough for most users.
#### Security
- End to end encryption, AES-256 cypher, Salting/Hashing, RBAC
- Quantum proof identifiers
- MFA, Oauth2, all communication encrypted over ssl
- Zero Knowledge Proof architecture
- [MagicPass](https://pickey.ai/#magicpass) - Storage free passwords, never stored anywhere, regenerated from the vision vector alone (AI *remembered* passwords)
- Master Keys are totally anonymous. Only you know which picture and character is your key. Picture of anything around you or an online image or even a public social media post could be your vision secret that nobody knows about. This is unlike face unlock where everyone knows our face (you only have one)
- PicKey's entire tech-stack is built and deployed privately and does not depend on any external services like vector stores, AI model stores, AI model inference engines or DevOps/deploy pipelines.
#### Privacy
- PicKey or anyone else.. never shares/exposes/sees any of your data
- You can delete all of your data at any time (currently via iOS)
#### Links
- Website : https://PicKey.ai
- More on Master Key : [link](https://pickey.ai/market/faq.html#faq4)
- Blog : https://blog.PicKey.ai
- Forums : https://forums.PicKey.ai
- Keymoji Store : https://pickey.ai/market/market.html
- Founder : [Twitter/X](https://twitter.com/garyiskidding) 
