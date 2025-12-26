Update Log
New Features
Added config option revive_limit to control how many times a player can be revived (set to 0 for unlimited revives).
Added config option extra_head_hearts to set how many extra hearts a player gets when wearing the head after the first death.
Changes
After the first death, wearing the head only grants extra hearts once. On further deaths, the head is only decorative and gives no extra hearts.
Revive logic now respects the revive_limit from the config.
Bugfixes & Improvements
Improved config structure and flexibility.
Minor code optimizations and better null safety.
