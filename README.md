![Alt text](/.github/hamster_preview.png)

<div style="">
      <div style="display: flex; align-items: center">
        <img src="https://cdn.iconscout.com/icon/free/png-512/free-buymeacoffee-3521318-2944737.png?f=webp&w=256" width="17" height="17">
        <span style="padding-left: 15px"><strong>Like my bot? Buy me a coffee. Thanks for your support!</strong></span>
    </div>
    <div style="display: flex;margin-top: 5px; align-items: center">
        <img src="https://metamask.io/images/metamask-logo.png" width="17" height="17">
        <span style="padding-left: 15px"><strong>0x251d1EA8113549B6874cF30e32C2030f423BB655</strong></span>
    </div>
</div>


### 📜 **Script features**
- caching telegram web data for 24 hours to avoid flood ban
- real user agents (android)
- proxy binding to an account
- support running on multiple accounts (single-threaded execution in parallel mode)
---
### 🤖 **Automator functionality**
- buying upgrades at the best price/profit ratio
- auto-clicker
- use of daily energy recharger
- daily reward collection
- exchange selection
- ability to enable/disable auto-clicker
---
### 📝 Settings via .env file
| Property                 | Description                                                                             |
|--------------------------|-----------------------------------------------------------------------------------------|
| 🔑 **API_ID / API_HASH** | Telegram client app credentials ([FYI](https://core.telegram.org/api/obtaining_api_id)) |
| 🖱️ **TAP_MODE**         | OFF/ON auto clicker (**true / false**) - default **true**                               |
| 💰 **BUY_MODE**         | OFF/ON automatic buyer (**true / false**) - default **true**                               |
| 🔋 **MIN_ENERGY**            | Minimum energy level before triggering actions - default: **100**                         |
| ⚡ **TURBO_TAPS_COUNT**      | Number of taps in turbo mode - default: **2500**                                          |
| ⬆️ **MAX_UPGRADE_LVL**      | Maximum upgrade level for upgrades - default: **20**                                       |
| 🔄 **TAPS_COUNT_RANGE_MIN**  | Minimum number of taps in a range - default: **50**                                        |
| 🔄 **TAPS_COUNT_RANGE_MAX**  | Maximum number of taps in a range - default: **199**                                       |
| 💤 **SLEEP_BETWEEN_TAPS_MIN**| Minimum sleep time between taps in milliseconds - default: **10**                          |
| 💤 **SLEEP_BETWEEN_TAPS_MAX**| Maximum sleep time between taps in milliseconds - default: **15**                          |

---
### 📥 Installation

1. Download & install nodejs >= 16 [link](https://nodejs.org/en/download/package-manager/current)
2. Clone the repository
3. Create an .env file and insert your values (variables in .env-example)
4. `npm install`
5. `npm run build`

### 🚀 Startup
1. `npm run start`
2. Select **Add new account** and follow the instructions
3. `npm run start`
4. Select **Run automator** --> DONE!

### 🤝 For contributors
- to start in development mode, use `npm run dev`
- before creating a pull request, run the following commands and fix the errors if necessary:
  - `npm run type-check` (typescript typing check)
  - `npm run lint` (running eslint)
