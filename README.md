# Bellar Presale Landing Page

Professional presale website for Bellar luxury collapsible hat.

## 📋 Features

- **Presale Landing Page** (`index.html`) - Hero section with countdown, features, FAQs
- **Product Selection Page** (`product.html`) - Color/size variants, cart, checkout
- Responsive design for mobile, tablet, desktop
- Interactive FAQ sections
- Live countdown timer to launch date
- Stripe payment integration ready

## 🚀 Quick Deploy to Vercel

1. **Create Vercel Account**
   - Go to [vercel.com](https://vercel.com)
   - Sign up (free)

2. **Upload Project**
   - Click "New Project"
   - Choose "Import Git Repository" or drag and drop folder
   - Select this `bellar-presale` folder

3. **Deploy**
   - Click "Deploy"
   - Your site is live in seconds!

4. **Custom Domain**
   - In Vercel dashboard, go to "Settings" → "Domains"
   - Add your custom domain (e.g., `presale.bellar.co`)
   - Follow instructions to update DNS

## 🎨 Customization

### Update Copy/Text
- **index.html** - Edit text in the presale landing page
- **product.html** - Edit product page copy
- Search and replace to update any messaging

### Change Images
- Open `index.html` or `product.html`
- Find image URLs (starting with `https://images.unsplash.com...`)
- Replace with your own image URLs
- Or upload images to Vercel and reference them

### Add Videos
- Replace video source URLs with your actual video links
- Make sure videos are hosted and publicly accessible

### Update Pricing
- Search for `$135` (presale) and `$170` (retail)
- Change numbers as needed
- Update in both HTML files

### Modify FAQ
- Open `product.html`
- Find `<div class="faq-item">` sections
- Edit questions and answers
- Duplicate sections to add more questions

## 💳 Stripe Integration

When ready to accept payments:

1. **Get Stripe Key**
   - Log in to [stripe.com](https://stripe.com)
   - Go to Developers → API Keys
   - Copy "Publishable Key"

2. **Setup Product in Stripe**
   - Create product "Bellar Hat Presale"
   - Set price to $135
   - Copy product ID

3. **Wire Up Checkout**
   - Replace `STRIPE_PLACEHOLDER_KEY` in code with your actual key
   - Update payment form to use Stripe Checkout

## 📱 Pages

### Page 1: Presale Landing (index.html)
- Presale headline
- Video/3D model showcase
- Live countdown
- Features section
- FAQ section
- CTA buttons link to product page

### Page 2: Product Selection (product.html)
- Color selector (White, Beige, Pink)
- Size selector (S/M, L/XL)
- Product gallery
- Quantity selector
- Cart summary
- Stripe checkout button
- FAQ section

## 🔧 File Structure

```
bellar-presale/
├── index.html          (Presale landing)
├── product.html        (Product selection)
├── vercel.json         (Vercel config)
└── README.md           (This file)
```

## 📊 Support

Need to make changes after launch?
- Edit HTML files and push/upload to Vercel
- Changes deploy automatically
- No downtime

## ✅ Next Steps

1. Deploy to Vercel
2. Test both pages
3. Make any design/copy changes
4. Get Stripe account ready
5. Add real product images
6. Launch! 🚀

---

Built with ❤️ for ambitious travelers.
