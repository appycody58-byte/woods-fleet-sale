# WOODS FLEET CLEARANCE

**Owner / Full Credit:** [@appycody58-byte](https://github.com/appycody58-byte)  
**Email for offers:** appycody58@gmail.com  
**Phone / WhatsApp:** +1 (712) 250-1219  

**Live Public Site:** https://woods-fleet-sale-appycatcherbot-s-projects.vercel.app  
**Dealer / Wholesaler Version:** https://woods-fleet-sale-appycatcherbot-s-projects.vercel.app/dealer.html

## What This Is
Aggressive cash-sale landing page for 6 abandoned / project vehicles.

### Vehicles
1. Dodge Ramcharger (classic square-body)
2. Black GMC Yukon Denali
3. Maroon GMC Yukon XL
4. Ford Windstar / Freestar minivan
5. Older Dodge Ram pickup
6. Custom red/purple short-bed street truck

## Features Live Now
- Bulk "Entire Fleet" package deal
- Floating Call + WhatsApp buttons (+1 712 250-1219)
- Real form that emails offers to **appycody58@gmail.com** (Formspree)
- Photo placeholder slots with exact file names to drop real pictures
- Ready-to-copy Facebook Marketplace & Craigslist ads
- Separate Dealer / Wholesaler pricing page with lower numbers
- Expanded list of fast cash buyers (CarBuyerUSA, Clunker.pro, EZGo, CarBrain, Gateway, TruckFleetBuyer, etc.)

## How to Add Real Truck Photos
1. Create a folder in the repo called `images/`
2. Upload your photos with these exact names:
   - `ramcharger.jpg`
   - `denali.jpg`
   - `yukon-xl.jpg`
   - `windstar.jpg`
   - `ram-pickup.jpg`
   - `custom-truck.jpg`
3. In `index.html`, replace each photo-slot div with:
   ```html
   <img src="/images/ramcharger.jpg" alt="Dodge Ramcharger">
   ```
   (repeat for each)

## Form Backend
The form currently points to a Formspree endpoint and is set to notify **appycody58@gmail.com**.  
If it ever hits free-tier limits, go to https://formspree.io (free), create a new form, and replace the `action` URL in the form. Takes 2 minutes.

Alternative free options: Web3Forms, FormBold, SplitForms.

## Ready-to-Copy Ads
Already included on the live site under the form. Just copy-paste into Marketplace or Craigslist.

## Deploy
- Linked to Vercel
- Every push to `main` auto-redeploys

Built for pure velocity. Credit locked to **@appycody58-byte**.
