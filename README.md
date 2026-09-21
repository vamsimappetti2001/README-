<h1 align="center">Hi, I'm Vamsi Mappetti 👋</h1>
<h3 align="center">QA / Test Automation Engineer &nbsp;|&nbsp; Playwright · TypeScript · AI-Assisted Testing</h3>
<p align="center">Based in Bengaluru, India 🇮🇳 &nbsp;·&nbsp; Open to QA / SDET roles</p>

<p align="center">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
</p>

---

### 🧭 Summary

QA engineer specializing in **automated end-to-end testing with Playwright and TypeScript**, with hands-on range across three distinct automation styles: a structured Page Object Model framework, direct Copilot/MCP-driven AI test generation and self-healing, and classic real-world UI suites. I write tests that survive past the first green run — organized, documented, and CI-wired — and I'm actively pushing into where AI agents fit into the QA workflow rather than just using them to autocomplete code.

Looking for a **QA / SDET / Automation Engineer** role where I can own test strategy for a real product.

---

### 🧰 Technical Skills

**Automation:** Playwright · TypeScript · Page Object Model (POM) · Locator strategies · Visual regression testing · CAPTCHA handling (`2captcha-nodejs`)
**AI-Assisted QA:** GitHub Copilot test agents (planner / generator / healer) · Playwright MCP Server · Claude API
**CI/CD & Reporting:** GitHub Actions · Allure Report · Playwright HTML reports
**Languages/Tooling:** TypeScript · JavaScript · Node.js · Git/GitHub · VS Code
**Currently deepening:** API testing, auth/storage-state reuse, cross-browser & mobile viewport coverage

---

### 🛠️ Project Portfolio

#### 🏦 [Playwright-automation-Framework-POC](https://github.com/vamsimappetti2001/Playwright-automation-Framework-POC)
A **Page Object Model** framework built against a banking demo site — the project that demonstrates production-shaped structure, not just working scripts.
- Clean `BasePage` → `LoginPage`/`HomePage`/`QuickTransactionPage`/`TransactionHistoryPage` class hierarchy with reusable role-based locator helpers
- Data-driven transfer flow using external JSON test data (`Transfer_TestData.json`)
- Config-driven runs via `config.json` (target URL, credentials, app name) instead of hardcoded values
- Covers a full user journey: login → quick transaction transfer → verify entry in transaction history

`Playwright` `TypeScript` `Page Object Model` `Data-Driven Testing`

#### 🤖 [Playwright-AI-Agents-Project](https://github.com/vamsimappetti2001/Playwright-AI-Agents-Project)
An exploration of **AI agents driving the test lifecycle** — planning, generating, and self-healing Playwright tests via the Playwright MCP server and GitHub Copilot.
- Three custom agents: a **planner** that explores a live site and writes a structured test plan, a **generator** that turns a plan into an executable spec, and a **healer** that runs failing tests and patches them by inspecting console/network/locator state
- Live example against the OrangeHRM demo app: an AI-generated test plan (`orangehrm-dashboard-test-plan.md`) turned into a working spec
- All three agents connect through one local MCP server exposing browser and test-runner actions as callable tools

`Playwright` `TypeScript` `MCP` `GitHub Copilot Agents` `Self-Healing Tests`

#### 🎓 [Playwright-Automation-typescript](https://github.com/vamsimappetti2001/Playwright-Automation-typescript)
A structured, chapter-by-chapter learning framework covering the breadth of Playwright's feature set against real-world sites (Google, YouTube, GitHub, DemoQA).
- 5 chapters progressing from first tests → locators/hooks/interactions → test organization (tags, retries, visual regression) → browser context & reporting → environment config via `.env`
- Dual reporting: Playwright's native HTML report **and** Allure for richer output
- CAPTCHA-solving dependency (`2captcha-nodejs`) already scaffolded for advanced scenarios

`Playwright` `TypeScript` `Allure` `GitHub Actions CI`

#### 💰 [Expense-Tracker-Automation-Playwright](https://github.com/vamsimappetti2001/Expense-Tracker-Automation-Playwright-)
End-to-end UI suite against a live deployed app (Nest.js Expense Tracker), covering real authentication and CRUD flows.
- Tests sign-in, navigation, and full add/delete-expense flow with amount, description, and category fields
- Configured for visible-browser runs with full trace, screenshot, and video capture on every run — built for debuggability, not just pass/fail

`Playwright` `TypeScript` `E2E Testing`

---

### 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=vamsimappetti2001&show_icons=true&theme=default&hide_border=true"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vamsimappetti2001&layout=compact&hide_border=true"/>
</p>

---

### 🎯 What I'm Looking For

- QA Engineer / SDET / Automation Engineer roles (fresher–early career)
- Teams that value maintainable, well-structured test code — POM, config-driven runs, documented suites — over raw test count
- A seat where AI-assisted QA tooling (agents, self-healing tests) is part of how the team already works, or wants to start

---

### 📫 Reach Me

<p align="left">
  <!-- Replace with your real links -->
  <a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<p align="center"><i>Always open to QA/SDET opportunities and interesting automation problems.</i></p>
