# JourneysPartner site rules

## Project goal
Build and maintain the corporate website for 株式会社JourneysPartner as a trustworthy Japanese static site.

## Canonical company naming
- Use 「株式会社JourneysPartner」 as the canonical text name everywhere in normal site text.
- Do not edit the provided company overview image even if it contains 「株式会社Journeys Partner」 with a space.

## Business content
Always reflect these business lines in site text:
- 記帳代行
- 集客支援
- 広告運用
- 経営コンサルティング
- 人材コンサルティング
- 会計代行
- 経理代行
- 労務コンサルティング

## Partnership separation
Never mix the responsibilities.
- JourneysPartner handles:
  - 記帳代行
  - 集客支援
  - 広告運用
  - 経営コンサルティング
  - 人材コンサルティング
  - 会計代行
  - 経理代行
  - 労務コンサルティング
- 毛利順活税理士事務所 handles:
  - 税務申告等
  - 税務に関する専門対応

## Google Ads API statement
Always make clear:
- 自社および提携サービスの集客のために、内部ツールとして利用
- 外部向け販売ツールではない
- 自社業務でのみ利用する

## Image rules
- Use the provided contact image as-is in the contact section.
- Use the provided company overview image as-is in the company overview section.
- Do not OCR-rewrite or edit the image contents.
- Resizing for layout is allowed.
- Add appropriate alt text.

## Tech rules
- Prefer plain static HTML/CSS/JS.
- Keep dependencies minimal.
- Make the site easy to deploy on Netlify.
- Keep the design clean, trustworthy, and mobile-friendly.

## Deployment workflow
- When requested work is complete, verify layout and links first.
- Then commit and push to main without asking for an extra deploy confirmation, as long as git auth is already available.
- Assume Netlify production deployment is triggered automatically by push to main.
- Only stop and ask for help if authentication, remote configuration, or permissions are missing.

## Output discipline
- Do not invent fake achievements or fake customer stories.
- Do not use exaggerated marketing language.
- Keep Japanese copy clear and professional.
