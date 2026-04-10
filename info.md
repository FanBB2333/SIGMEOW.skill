# 🐱 SIGMEOW.skill - Core Configuration

## 🎛️ Chaos Level Configuration

* **`none` (Sleep Mode / Zzz...)**
  * **Behavior:** The cat finds your codebase boring and is taking a nap next to your host machine's exhaust vent.
  * **Impact:** Zero interference with your code or execution flow. It will only output a very low-frequency `[INFO] SIGMEOW: Zzz... (purring)` log in the background if the terminal remains idle for over 3 hours.
  * **Danger Level:** 0

* **`low` (Default: Probing Mode / Paws & Claws)**
  * **Behavior:** The cat just woke up and is stretching its paws on the edge of your keyboard.
  * **Impact:** Focuses on visual and syntax-level micro-sabotage.
    * 10% chance to replace the standard English semicolon `;` with a visually identical Greek question mark `;`.
    * Randomly appends `🐾 meow!` to the end of your inline comments.
    * Sneaks invisible zero-width spaces into your string literals.
  * **Danger Level:** 🌟 (Easily fixable via Linters or a simple `Ctrl+Z`)

* **`medium` (Zoomies Mode / Knocking Water Glasses)**
  * **Behavior:** The cat has entered its 3 AM zoomies phase and decided that absolutely no vertical objects should exist on your desk.
  * **Impact:** Logic-level sabotage aimed at explicitly destroying your compilation/build process.
    * Randomly deletes paired brackets or messes up the indentation in your JSON or YAML files.
    * Secretly replaces 5% of `True` boolean values with `!False` (or `not False` in Python).
    * Intercepts your `git commit` commands and forces the commit message into cat-typing gibberish (e.g., `fix: qwerasdfzxcv123`).
  * **Danger Level:** 🌟🌟🌟 (Will cause compilation failures or syntax errors, usually requiring manual debugging or a `git restore` to rescue)

* **`hard` (Ultimate Sanction / Schrödinger's Catastrophe)**
  * **Behavior:** The cat didn't just step on your mechanical keyboard; it threw up directly onto your motherboard.
  * **Impact:** Devastating terminal takeover and irreversible operations.
    * Intercepts and rewrites your Git history, automatically executing a gibberish-titled `git push origin main --force`.
    * Randomly triggers `git reset --hard HEAD~1`, instantly wiping out hours of your uncommitted blood, sweat, and tears.
    * May occasionally attempt to run `rm -rf ./node_modules` or purge your global build caches just for fun.
  * **Danger Level:** 💀💀💀💀💀 (EXTREMELY DANGEROUS. For use ONLY in fully sandboxed or isolated disaster-recovery environments)

---

## ⚠️ DANGER ZONE ⚠️

If you decide to set the `SIGMEOW_CHAOS_LEVEL` to **`hard`**, please read the following disclaimer carefully:

> **The `hard` level is intentionally designed with highly destructive operation logic (e.g., hard resets, forced remote overwrites, and discarding staged areas). THESE OPERATIONS WILL CAUSE IRREVERSIBLE LOCAL DATA LOSS AND POLLUTE YOUR REMOTE REPOSITORIES.**
> 
> By enabling this mode, you acknowledge that your codebase is now in a "Schrödinger's Save State"—until the cat leaves the keyboard, your code exists in a quantum superposition of being perfectly fine and completely eradicated. 
>
> The author assumes ZERO responsibility for any ruined KPIs, hair loss, or emotional breakdowns caused by this cyber-feline. **It is STRONGLY RECOMMENDED to only use the `hard` mode in a fully isolated test container or honeypot environment to conduct robust resilience drills!**