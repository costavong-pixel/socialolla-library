# SocialOlla Library — Product Specification

**Working product name:** SocialOlla Library

**Working description:** A creator content marketplace where people unlock practical recipes for making ads, images, and videos.
**Status:** Product definition only. No application functionality is implied by this document.

## 1. The product in one sentence

Creators publish a proven content result plus the recipe behind it; customers spend credits to unlock the recipe or upload a reference video for a private AI shot-by-shot breakdown.

The valuable thing is not the video alone. It is the knowledge needed to recreate the result: the hook, composition, shots, camera movement, edit, words, and assets.

## 2. What SocialOlla Library is — and is not

### It is

- A web-first, YouMind-style library of visual cards and collections.
- A content marketplace: approved creators can sell reusable content recipes.
- Pay-as-you-go: customers buy credits, rather than needing a monthly subscription to begin.
- A practical tool for people who want to make better social content without guessing how it was made.
- A related SocialOlla product, but with its own clear job: **learn or recreate content**.

### It is not

- An affiliate-video marketplace.
- A generic prompt library or a Notion replacement.
- A social-post scheduling product.
- A place that asks creators to produce artificial AI setup images for every step.
- A place where an uploaded private reference automatically becomes public content.

## 3. Core promise

> See a result you want. Open the card. Follow the recipe. Make your own version.

For private analysis:

> Upload a video. Receive a shot-by-shot explanation of how it was likely made.

## 4. People using the product

| Role | Main need | Main action |
|---|---|---|
| Buyer / learner | Make a better piece of content quickly | Browse, unlock, follow a card |
| Creator | Earn from a technique they created | Submit a result and its recipe |
| Admin | Protect quality, rights, and the customer experience | Approve, reject, price, and manage payouts |

At launch, creator access can be invitation-only or application-based. That keeps quality consistent while the library is small. It can become more open after the approval workflow is proven.

## 5. The common card framework

Every card follows the same base structure, even when the content type is different. This keeps browsing simple and allows the same card engine to support new categories.

| Card section | Purpose | Required in MVP? |
|---|---|---|
| Result preview | Show the finished outcome before a buyer spends credits | Yes |
| Title and goal | State what the card helps the buyer achieve | Yes |
| Recipe | Clear steps to recreate it | Yes |
| Assets needed | List the items, clips, tools, or copy needed | Yes |
| Creator, base price and total credit cost | Show who made it, the creator's price, and the total unlock cost | Yes |
| Notes / limits | State any rights, brand, or skill limitations | Yes |
| Save / collect | Let a buyer keep it in a personal collection | Later |

### Result previews

The preview must show the **finished result**, not an abstract setup diagram. A buyer should choose a card because they want that outcome.

For video cards, use the creator's real final clip or a short excerpt. For image cards, use the actual final image. AI-generated setup pictures are not part of the normal card workflow.

## 6. First card types

### A. Film technique card

For a visual technique such as a perfume reflection, a product-on-screen shot, or a talking-head setup.

Required recipe fields:

1. What you need
2. Exact setup
3. Film it
4. Edit / finishing steps, if relevant

The instructions should be short, plain, and beginner-friendly. When a visible measurement matters, include it in text. The creator's real result clip and optional real behind-the-scenes photo/video are the proof.

### B. Advertising card

For an ad concept that can be recreated for another product or business.

Required recipe fields:

1. Objective and target emotion
2. Hook
3. Scene sequence
4. On-screen text or spoken script
5. Call to action
6. Visual / filming notes

Example: a three-shot product ad whose first second creates curiosity, then demonstrates the benefit, then gives a purchase or follow action.

### C. Image card

For a reusable image concept, composition, or AI-image recipe.

Required recipe fields:

1. Result image
2. Use case
3. Composition and subject placement
4. Lighting, style, colours, and background
5. Prompt or manual production recipe
6. Negative constraints / things to avoid

### D. Video blueprint card

For a complete short-form content blueprint, not only a single filming technique.

Required recipe fields:

1. Final video preview
2. Duration and platform fit
3. Hook
4. Shot list in order
5. Script / text overlay
6. Editing rhythm, sound, and caption notes
7. Call to action

## 7. Library structure

The interface uses the simple YouMind idea: visual collections containing useful cards.

```
Home
├── Browse collections
│   ├── Film techniques
│   ├── Advertising ideas
│   ├── Image concepts
│   └── Video blueprints
├── Search and filters
├── My unlocked cards
├── Analyze my video
├── Creator area
└── Credit wallet
```

Useful filters in the first version:

- Content type: film, ad, image, video
- Goal: sell, explain, review, talk to camera, demonstrate
- Product category: beauty, food, technology, fashion, etc.
- Skill level: beginner, intermediate
- Production level: phone only, phone + basic light, studio

Do not add many filters until enough cards exist to make them useful.

## 8. Credits and payment

### Customer experience

1. A customer can browse all public previews without spending credits.
2. They buy a credit pack through Paddle.
3. They use credits to unlock a recipe or run private AI analysis.
4. Unlocked cards remain available in **My unlocked cards**.

### Credit rules

- A card displays its credit price before the customer unlocks it.
- A credit debit must be recorded once and be traceable to the exact card or analysis run.
- If an eligible technical failure prevents delivery, credits are restored automatically or by admin review.
- Purchased credits should have a stated expiry policy before public launch.
- AI analysis costs more than a normal card unlock because it has a variable processing cost.

### Creator-controlled pricing

Creators choose a **base price in credits** for each approved card. SocialOlla adds its marketplace fee on top, so the buyer sees the full credit total before unlocking.

| Buyer-facing amount | Rule |
|---|---|
| Creator base price | Chosen by the creator in credits |
| SocialOlla marketplace fee | Added on top of the creator base price |
| Total credits to unlock | Creator base price + SocialOlla marketplace fee |

Paddle's payment-processing fee applies when the customer buys a credit pack. It must be recovered in the credit-pack price and accounting; it is not charged a second time when the customer redeems prepaid credits for a card.

The exact marketplace fee, credit-pack prices, and price limits remain to be decided. The buyer must always see the total credit cost before unlocking.

## 9. Creator marketplace and earnings

### Creator submission

A creator submits:

1. Final result video or image
2. Card type and title
3. The recipe fields for that card type
4. Proof they have the right to publish and monetize the material
5. Optional real behind-the-scenes media where it improves clarity

The platform can help format the written card, but creators remain responsible for the truth of their recipe and their rights to the submitted material.

### Approval

An admin checks:

- The preview actually matches the recipe.
- The recipe is understandable and useful.
- The creator owns or has permission to use the media, music, products, logos, and people shown.
- The card is distinct enough to be worth a credit unlock.
- No misleading claims or copied work appear in the card.

Approved cards appear in the library. Rejected cards stay private with a reason for rejection.

### Earnings model

Creators do not earn for views. They earn when a customer spends credits on their approved content.

The creator sets a base price in credits. SocialOlla adds its marketplace fee on top for the buyer. The creator's earning is calculated from the creator base price under the approved revenue-share rule; refunds, chargebacks, and required taxes can reverse or reduce an eligible earning.

Paddle fees arise when credits are purchased, not when a prepaid credit is redeemed. The ledger must preserve the link between the original credit purchase, the card unlock, the marketplace fee, and the creator earning.

Every credit redemption should create an immutable ledger entry:

| Ledger entry | Needed fields |
|---|---|
| Customer unlock | customer, card, credits spent, time, status |
| Creator earning | creator, linked unlock, share amount, status |
| Refund / reversal | original transaction, reason, credits / earning reversed |
| Payout | creator, period, amount, payout status |

## 10. Private AI video analysis

### Customer flow

1. Customer uploads a finished reference video they are permitted to use.
2. The system detects scenes and extracts real frames from that video.
3. AI returns a shot-by-shot guide.
4. The customer can save the result privately or discard it.

### Analysis output

For each detected shot, the output may include:

- What is visibly shown
- Framing, camera angle, and camera movement
- Visible props, background, and lighting clues
- Editing / transition observations
- A recreate-it checklist
- Confidence labels: **observed** versus **likely setup**

The final video alone cannot prove hidden equipment, exact distances, lens settings, or an unseen lighting setup. The product must not present guesses as facts.

### Privacy and rights

Private uploads are not public marketplace submissions. They must never be shown to other users or added to the public library unless the uploader explicitly submits them as a creator card and the card is approved.

## 11. MVP — what to build first

The first release should prove that people will pay for a recipe, not try to complete every marketplace feature.

### MVP includes

- Public browse page with collections and result previews
- One shared card framework
- Film technique card and advertising card types
- Account and credit wallet
- Paddle credit-pack checkout
- Credit-gated unlock
- My unlocked cards
- Admin-created cards
- Admin approval for creator submissions
- Basic creator earning ledger
- Private video upload → shot breakdown using real extracted frames

### Later, after MVP proof

- Image and complete-video blueprint card creation flows
- Creator self-service pricing controls
- Creator dashboards and payout automation
- Subscription options
- Social posting/scheduling integration
- AI-generated setup imagery
- Public creator storefronts, follows, comments, and ratings

## 12. First proof test

Before aiming for hundreds or thousands of cards, create a small, high-quality set:

- 10 film technique cards
- 10 advertising cards
- A few distinct categories, not 20 versions of one product shot
- Real result previews on every card

Test whether people browse previews, unlock cards, follow the recipes, and return for another technique. This tells us whether the marketplace has a real transaction before expanding creator supply.

## 13. Success signals

Initial signals worth measuring:

- Preview-to-unlock conversion rate
- Credits spent per paying customer
- Number of buyers who unlock a second card
- Number of cards that earn at least one unlock
- Creator approval rate and rejection reasons
- Private analysis completion rate
- Refund or credit-restoration rate

## 14. Decisions needed before development

1. Marketplace fee: what percentage or fixed credit amount does SocialOlla add on top of a creator's base price?
2. What percentage of the creator base price goes to the creator for an unlocked card?
3. Are normal card unlocks permanent, or do credits buy temporary access?
4. Is private AI analysis initially allowed only for a customer's own videos, or also permitted reference videos they have rights to analyze?
5. Should the first release have both film technique and advertising cards, or launch with film technique cards first and add advertising next?

## 15. Immediate working decision

Build the library around one shared card framework. Creators choose each card's base price in credits; SocialOlla adds its marketplace fee on top. Start by proving the paid unlock flow with real final-result previews and clear recipes. Do not make AI-generated images a required part of publishing a card.
