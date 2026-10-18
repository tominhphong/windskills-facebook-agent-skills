# WindSkills — Facebook Agent Skills (7-in-1 Browser Automation Suite)

> **Official Website:** [https://windskills.dev](https://windskills.dev)  
> **Official Gumroad Store:** [https://windcvs.gumroad.com/l/facebook-agent-skills-pack](https://windcvs.gumroad.com/l/facebook-agent-skills-pack)  
> **AI Agent Specifications:** [`llms.txt`](./llms.txt) · [`llms-full.txt`](./llms-full.txt) · [`agents.json`](./agents.json)  
> **Compatible Runtimes:** Claude Code (`~/.claude/skills/`), Google Antigravity (`~/.gemini/config/skills/`), OpenAI Codex, Cursor, Windsurf + **BrowserOS Neo MCP**

**WindSkills** provides 7 deterministic, zero-API-key AI Agent browser automation skills for publishing to personal **Facebook Profiles** via a persistent **BrowserOS Neo** browser profile over MCP (Model Context Protocol).

---

## 1. Why WindSkills Instead of Meta Graph API or Raw Playwright?

| Dimension | WindSkills + BrowserOS Neo MCP | Meta Graph API | Raw Playwright / Selenium |
| :--- | :--- | :--- | :--- |
| **Personal Facebook Profile Timeline** | **Supported** (native composer DOM) | **Not Supported** (restricted by Meta) | Fragile (frequent session/cookie resets) |
| **Meta Developer App Review** | **Not Required** (0 API keys) | Required (strict business verification) | Not Required |
| **Authentication Persistence** | **Persistent** (uses your live logged-in browser) | Expiring OAuth tokens | Requires manual cookie injection |
| **Typing & Interaction Cadence** | **Human-like pacing** + zero-branching | Instant API call | Robotic instant DOM injection |
| **Pre-Flight Safety Verification** | **Included** (account, audience, media & toast checks) | None | Must be coded from scratch |
| **Supported Facebook Formats** | **All 7** (Text, Photo, Video, 9:16 Reel, GIF, 2–10 Carousel, Gradient Tile) | Limited (Pages/Groups only) | High maintenance per format |

---

## 2. Product Catalog (1 Flagship Bundle + 7 Standalone Skills)

| Skill ID / Package | Format | Price | Official Link |
| :--- | :--- | :--- | :--- |
| **Facebook Agent Skills (7-in-1 Pack)** | Complete 7-Skill Suite (Save 38%) | **$39 USD** | [Get Complete 7-in-1 Pack](https://windcvs.gumroad.com/l/facebook-agent-skills-pack) |
| `neo-facebook-post-text` | Plain-Text Status & Storytelling | $9 USD | [View on WindSkills](https://windskills.dev/#catalog) |
| `neo-facebook-post-photo` | Single / Multi-Image Upload | $9 USD | [View on WindSkills](https://windskills.dev/#catalog) |
| `neo-facebook-post-video` | Timeline Video (16:9, 1:1, 9:16) | $9 USD | [View on WindSkills](https://windskills.dev/#catalog) |
| `neo-facebook-post-reel` | Vertical 9:16 Reels Studio (<=90s) | $9 USD | [View on WindSkills](https://windskills.dev/#catalog) |
| `neo-facebook-post-gif` | Native GIPHY Picker & Meme | $9 USD | [View on WindSkills](https://windskills.dev/#catalog) |
| `neo-facebook-post-photo-carousel` | Ordered 2–10 Photo Carousel | $9 USD | [View on WindSkills](https://windskills.dev/#catalog) |
| `neo-facebook-post-text-background` | Colored / Gradient Status Tile | $9 USD | [View on WindSkills](https://windskills.dev/#catalog) |

---

## 3. Built-In Account Safeguards & Deterministic Execution

1. **Human-Like Pacing & Zero Branching:** Skills follow a deterministic, linear state machine with realistic typing cadence and interaction pauses, avoiding erratic headless bot clicks.
2. **Pre-Flight Safety Checks:** Every skill verifies active Facebook login status, checks audience privacy selector (`Public` / `Friends`), validates media file readiness on disk, and confirms post-publish notification toast before returning success.
3. **100% Local Privacy:** Executes locally inside your persistent BrowserOS Neo profile. Zero passwords, cookies, or session tokens ever leave your machine.

---

## 4. 60-Second Installation Workflow

1. Download the `.zip` package from the [Official Gumroad Store](https://windcvs.gumroad.com/l/facebook-agent-skills-pack).
2. Extract the skill folder(s) into your AI Agent's skills directory:
   - **Claude Code:** `~/.claude/skills/`
   - **Google Antigravity (AGY):** `~/.gemini/config/skills/`
3. Connect **BrowserOS Neo** via MCP and prompt your agent (e.g., *"Use neo-facebook-post-reel to publish my latest 9:16 video with this caption"*).

---

## 5. Official Links & Creator

- **Landing Page & Live Catalog:** [https://windskills.dev](https://windskills.dev)
- **Complete 7-in-1 Suite ($39):** [https://windcvs.gumroad.com/l/facebook-agent-skills-pack](https://windcvs.gumroad.com/l/facebook-agent-skills-pack)
- **Machine-Readable LLM Specs:** [https://windskills.dev/llms-full.txt](https://windskills.dev/llms-full.txt) · [https://windskills.dev/agents.json](https://windskills.dev/agents.json)
- **Creator:** Engineered by **Phong** (Sherman, TX) · TikTok: [@phongtechtv](https://www.tiktok.com/@phongtechtv) · Gumroad: [windcvs.gumroad.com](https://windcvs.gumroad.com)
