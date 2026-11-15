# Resonanz X-Ray

Investment performance, risk and comparisons for business and professional use.

This Claude plugin bundles the Resonanz investment guide with a connection to the
hosted Resonanz X-Ray analytics service. Broad questions start with a focused
walkthrough; specific analytical requests go directly to the relevant tools.

## Get started

Install the plugin through a supported Claude plugin installation flow and connect
to Resonanz X-Ray when prompted. Sign in to your Resonanz account, or create one
and verify your email. No API key or manually supplied OAuth client secret is
included or required by this package.

Try:

- "What can Resonanz X-Ray help me do?"
- "Walk me through a synthetic example."
- "Analyze this uploaded fund history and explain its performance and drawdowns."

Access is currently free. Historical analysis does not predict future returns.
The service does not execute trades.

## Contents

- `.claude-plugin/plugin.json`: plugin identity and version.
- `.mcp.json`: connection to `https://ensemble.resonanzcapital.com/mcp`.
- `skills/resonanz-fund-research/`: the guide and its supporting references.

The analytics service is hosted separately. Changes to this repository update the
plugin and guide; they do not deploy the service or change access permissions.
Directory publication is subject to review; this repository is not evidence of
approval or availability in the directory.

## Product and support

- [Usage](https://resonanzcapital.com/mcp/resonanz-x-ray-usage)
- [Support](https://resonanzcapital.com/mcp/x-ray-support)
- [Privacy policy](https://resonanzcapital.com/mcp/resonaz-x-ray-privacy-policy)
- [Terms](https://resonanzcapital.com/mcp/resonanz-x-ray-terms)

## Maintaining the bundle

Version 0.1.13 was imported from the reviewed Claude distribution archive.
Keep the plugin manifest and guide together when releasing updates. Validate the
package and test its connection and guide in Claude before submitting a new
version. Never commit credentials, user uploads or deployment configuration.

## License

This plugin is proprietary. The [LICENSE](LICENSE) permits use with Resonanz
X-Ray and authorized platform distribution; it does not grant general reuse,
modification or redistribution rights. The hosted service is governed by its
separate terms.

Claude bundle 0.1.14 adds the license, supplied logo and explicit listing links
to the 0.1.13 bundle. Its guide and MCP connection are unchanged.

## Guide update 0.1.16

This version synchronizes the guide with the application repository at commit
`120b2d8`. It keeps confirmed upload details, asks only for missing information
that affects the next step, and continues with the retained original instead of
asking for another upload. An update-versus-new question is asked only when the
app reports a matching investment; replacement details follow the user's choice.

The guide source is maintained in `Analytics-service-AI/skills/resonanz-fund-research/`.
Synchronize that directory here when releasing guide changes; application commits
do not automatically update this repository. Version 0.1.15 was used by the separate
application release bundle; this update uses a new version for the revised guide.

After pushing a release commit, use **Check for new commits** in the Anthropic
submission portal and check which commit was reviewed. A successful local package
check does not establish directory approval. Privacy-policy publication and hosted
service updates are separate from this guide update.

## Publication preparation 0.1.21

This candidate synchronizes the current guide and packaged listing assets with
Analytics-service-AI. The proprietary license, 512-pixel supplied logo, four
listing links and published-host-identity sign-in configuration are preserved.
The guide starts broad fund requests with general performance and risk, keeps
confirmations concise and preserves the user's confirmed data conventions.

The 0.1.16 notes above describe the previous release. Candidate 0.1.21 also
normalizes packaged license line endings for reproducible builds. This candidate has not been
pushed or checked by the directory as part of local preparation. Public privacy
and terms completion, approved retention enforcement, reviewer access and hosted
acceptance remain separate publication requirements. A successful local package
check is not a claim of directory approval. Do not submit until those checks pass.
