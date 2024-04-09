## Perquisites to read this document : 
1. Some idea of [Computer Vision]() (like Tesla Autopilot). PicKey uses this for authentication.
2. Some idea of how today's Password Managers work. Especially the Master Password that is used in all Password Managers of today.
3. Know what PicKey is.
	- Some resources to understand PicKey : 
		- https://youtu.be/KedRFg-Qg_Y?si=z_avMTKaUk7up-PI (2 min explainer video)
		- https://youtu.be/MY7DG6qOmg0 (50 sec explainer)
		- https://blog.pickey.ai/pickey-ai-the-future-of-password-management/ (Blog explainer)
		- https://pickey.ai/market/faq.html (faq page)
		- https://pickey.ai (website)
		- https://pickey.ai/market/market.html (3D, AR Keymoji Store)
## PicKey - Novel Features
1. PicKey leverages human photographic memory to transform visual and audiographic recall into a Master Password (Master Key) that is intuitively memorable.
2. PicKey harnesses real-world entropy, which is [significantly higher](https://blog.pickey.ai/defying-brute-force-the-unparalleled-strength-of-pickeys-master-key/) than what today's computer systems can achieve. This establishes PicKey’s Master Keys as the most robust Master Passwords available.
3. Users select a photo of anything significant around them as their Master Key. The unique, unpredictable nature of this choice, combined with the vast visual vocabulary and diverse environmental settings unique to each individual, ensures each Master Key is distinctive, personal, and easy to remember.
4. Any photo—whether of a nearby object, a cherished possession, or a familiar face—can be transformed into a Master Key. Photos can be captured using the camera or chosen from the phone's gallery.
5. The subject of the photo can be real (any physical object or scene) or digital (downloaded from the internet or a device). Since it remains private, only the user knows the true significance of the image.
6.  Master Keys are used to log in or sign up to PicKey. Once logged in, PicKey manages, saves, and autofills all other passwords using this single visual memory.
7. We recommend retaking photos live when logging in later to enhance security.
## PicKey - Convenience Features
1. Humans recall pictures [60,000 times faster than text](https://medtechintelligence.com/column/the-power-of-visuals/), making PicKey exponentially easier to use than traditional password managers.
2. PicKey converts the master password into a visual password that is naturally memorable.
3. Users can create multiple Master Keys, enabling flexible login options—from different locations or with different images—and serving as a self-recovery method.
## PicKey - Security Features
- [MagicPass](https://pickey.ai/#magicpass) - storage free passwords that are never stored anywhere and are recreated from the vision vector alone. AI *memorized* passwords. Prevents hacks as there is no data to hack.
- End-To-End Encryption on all devices.
- Zero Knowledge Proof architecture.
- Sensitive data is salted and hashed.
- Sensitive data is encrypted at rest with military-grade AES-256 Cypher (GCM/CBC).
- Sensitive data storage is access locked and cannot be accessed by anyone (including us).
- Role-based access control ([RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)) by design.
- All inter-module communication is encrypted over SSL.
- Quantum Proof identifiers (unique ids) generation.
- Multi-Factor Authentication for all account access.
- OAuth2.0 with stringent token control, roles and rotation.
- Delays are introduced randomly in executing critical operations to enhance security.
- Master Keys are totally anonymous. Only you know which picture and character is your key. Picture of anything around you or an online image or even a public social media post could be your vision secret that nobody knows about. This is unlike face unlock where everyone knows our face (you only have one).
- PicKey's entire tech-stack is built and deployed privately and does not depend on any external services like vector stores, AI model stores, AI model inference engines or DevOps/deploy pipelines.
## PicKey - Technical Features
1. Hot swappable model updates allow for seamless vision model upgrades with minimal downtime.
2. AI infrastructure is decoupled from cybersecurity measures to facilitate independent updates, scaling, and management.
3. State-of-the-art AI Vision Model framework, named "VisionAry," is trained to recognize natural changes in photos (e.g., aging, lighting, viewing angles).
4. Infrastructure is self-healing with autoscaling capabilities and independent DevOps pipelines.
5. Comprehensive support for all modern iOS and Android devices, and popular browsers for seamless password autofill and management.
6. QR based instant, passwordless login for browsers from an already logged-in device (iOS/Android)
7. Dynamic photo quality checks are performed during the creation or use of Master Keys to ensure optimal security and functionality.
## PicKey - Product Features
For detailed plans and pricing, visit: [PicKey Plans](https://pickey.ai/#plans)

For any other information, please email at info@pickey.ai . For partnership opportunities, visit our [affiliates page](https://pickey.ai/affiliates/affiliates.html) .
