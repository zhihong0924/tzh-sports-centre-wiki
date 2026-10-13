# MCP access and setup

[← MCP guides](README.md) · **Who:** Authorised administrators

1. Sign in as admin and open [MCP Access Tokens](https://tzhsports.vercel.app/admin/mcp-tokens).
2. Give the credential a descriptive name and choose its expiry and needed permissions. Create it, copy it once into the approved secure storage, and keep it out of chat, screenshots and Git.
3. Follow the [customer workspace setup](https://github.com/zhihong0924/tzh-sports-centre-mcp/blob/main/SETUP.md). Use that whole repository as the Codex project's main folder and configure the `tzh_sports_centre` connection.
4. Restart Codex as instructed. Confirm the server and relevant skills are discovered, then run the setup guide's read-only smoke test for your permission.
5. Try a read-only question from the task guides. Inspect a preview before authorising any change.

| Website permission | Enables |
|---|---|
| Student account | Student lookup and staged account audits |
| Member points | Member/policy lookup and positive point awards |
| Lesson management | Concrete lesson duration/price changes and attendance query/recording |
| Read admin attention | Read-only operational digest; other permissions do not imply it |
| Manual invoices | Already-paid member/non-member invoices after verified rollout |

**Expected:** Credentials are personal, expire when configured and can be revoked independently. Revocation stops clients using that token. A token does not bypass the active admin role or the approval required for each write.

For missing permissions, ask the centre for a replacement through the secure channel. Never paste the token into a support message. For updates, follow the customer repository's `git pull --ff-only` instructions without discarding local changes.

![Permission selection without creating a credential](../images/features/mcp-access.png)
