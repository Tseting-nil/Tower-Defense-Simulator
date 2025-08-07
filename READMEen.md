### English | [中文](README.md)

!! USE -> claude.ai -< To Translate !!
# Tower Defense Simulator Map Script Submission Guide

Welcome to **Tower Defense Auto Scripts**! Please read the following guidelines!

You can submit your custom scripts here. After review, I will add them to the public script library for all players to use. Please follow the format and steps below to ensure your script can be properly validated and included.

---

## 📌 How to Submit Scripts

### 1️⃣ Create a New Issue
Please go to the following link to open a new issue:  
👉 [Submit Script](https://github.com/Tseting-nil/Tower-Defense-Simulator/issues)

---

### 2️⃣ Title Naming Convention
When creating an issue, please **label the following three pieces of information in the title**:

### Mode: Regular / Special / Hardcore  
### Difficulty: Easy / Casual / Intermediate / Molten / Fallen  
### Map: Please fill in the correct map name

❌ **If the title does not provide complete information or has incorrect format (missing mode or map, or missing difficulty in Regular mode), it will be considered an invalid submission and will not be reviewed.**

---

### 3️⃣ Paste Your Script Data (Format Below)
Please paste your script according to the following format (do not fill in random data):

👉 [Example Format Reference](https://raw.githubusercontent.com/Tseting-nil/Tower-Defense-Simulator/refs/heads/main/MapscriptURL/Four%20Seasons/Easy/Script.lua)

```lua
{
	Name = "Display Name",
	Title = "Display Title",
	Author = "Your Name or Nickname",
	Time = "Clear Time (can be empty)",
	Tower = {" ", " ", " ", " ", " "},
	Script = "Raw format or complete process script content (recommended)"
}
```

### ℹ️ Additional Notes

- **Tower Field**: Please fill in 1 to 5 tower names, ensuring they match the in-game tower names. If you want to use golden towers, just add "Gold" or "Golden" before the tower name, for example: ("GoldSoldier", "DJ Booth", "ACC"). --ACC = Accelerator

- **Script Field**: Only supports "raw" format script content. You can choose one of the following two submission methods:
  - **Direct URL Provision**: Please ensure the URL points to a publicly accessible "raw" format script file (such as GitHub's Raw link). The URL must be valid and stable, avoiding temporary or easily expired links.
  - **Complete Auto Process Script (Recommended)**: Directly paste the complete script content **tools will be provided later**.
  👉 [Complete Process Script Content Reference](https://raw.githubusercontent.com/Tseting-nil/Tower-Defense-Simulator/refs/heads/main/MapscriptURL/Four%20Seasons/Easy/Four_Seasons_1.lua)

- **Script Submission Recommendations**:
  - Ensure the script has been thoroughly tested and can stably clear the specified map and mode.
  - If providing a URL, it's recommended to use reliable hosting platforms (such as GitHub, GitLab, or Pastebin Raw links), and check that the link is publicly accessible.
  - Avoid submitting untested or incorrectly formatted scripts, as this may result in review rejection.

### 🔐 Key System Usage Instructions (If Applicable)

To provide more stable and fair service, **the main loading script will require key verification in the game lobby**.

The key system has undergone over 6 months of stable testing and is currently running well. Please use with confidence.

#### 📋 Key System Rules

- Each time you re-enter the game, **you may need to re-enter the key**.
- Currently providing a **Public Key** system:
  - Everyone shares the same set of keys.
  - Some users may be able to use the full 3 days, while others may only be able to use for several hours.
- **Key Update Time**: Every **three days, reset at 00:00 UTC+8**.

#### ⚠️ Notes

- If you cannot pass key verification, please go to the GitHub Issue section to leave a message for help.
- Please **attach error message screenshots** to help confirm the problem and respond.

### ⚠️ Privacy Policy

- Please **do not provide your real name** inside the script. Only use nicknames or anonymous identifiers.
- **Rights you can exercise**:
  - Request me to **delete** scripts related to you.
  - Request me to **modify** scripts you provided (**limited to once per day**).
- **Rights I (Tseting-nil) can exercise**:
  - Manage the entire script library.
  - **Delete non-compliant** or **incorrectly formatted** script content.
  - Merge, refactor, or organize scripts you submit to make them more suitable for public use.
  - Choose to **not display** certain scripts based on circumstances (e.g., high error rate "you can mention in the title that it's not 100% complete").

### ⚠️ Game Security / Precautions

1. **This script is for academic research and learning purposes only**. Do not use it for violating game rules or malicious behavior.
2. Using any script may involve risks, including but not limited to account bans, data anomalies, etc. **The author is not responsible for any losses**.
3. **The game may crash**. This is due to certain script characteristics; the game may crash and does not require special feedback unless very serious.
4. Some functions may depend on current server status. If you encounter anomalies, please try switching servers or wait for updates.
5. If scripts are not updated in time or become ineffective, please wait patiently for maintenance, or report in Issues to help improve.
6. It is strictly forbidden to distribute malicious variants, encrypted, or backdoor-inserted scripts. Violators will be permanently banned from submission privileges.