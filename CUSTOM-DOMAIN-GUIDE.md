# Custom Domain Setup Guide

## Recommended Domain Names for Adam Gibrine

### 1. Primary Recommendations:
- `adamgibrine.com` ⭐ **Best Choice**
- `adamgibrine.dev` ⭐ **Developer-focused**
- `adamgibrine.me` ⭐ **Personal branding**

### 2. Creative Options:
- `adam.codes`
- `adamg.dev`
- `gibrine.dev`
- `adamgibrine.tech`

### 3. Ghana-Specific:
- `adamgibrine.gh`
- `adamgibrine.com.gh`

## Domain Registrar Comparison

### Namecheap (Recommended):
- `.com`: $8.88/year first year, $13.98/year renewal
- `.dev`: $12.98/year
- `.me`: $8.88/year first year
- Pros: Great prices, free privacy protection
- Cons: None major

### Google Domains:
- `.com`: $12/year
- `.dev`: $12/year
- Pros: Simple interface, Google integration
- Cons: Slightly more expensive

### Cloudflare:
- `.com`: $8.57/year (at cost pricing)
- `.dev`: $9.95/year
- Pros: No markup, great performance
- Cons: Requires Cloudflare account

## Setup Steps

### GitHub Pages + Custom Domain:

1. **Buy Domain**:
   - Go to Namecheap.com
   - Search for your domain
   - Purchase with privacy protection

2. **Configure GitHub**:
   - Repository → Settings → Pages
   - Custom domain: enter your domain
   - Enforce HTTPS: ✅ Enable

3. **Configure DNS**:
   At your domain registrar, add these DNS records:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   
   Type: A
   Host: @
   Value: 185.199.109.153
   
   Type: A
   Host: @
   Value: 185.199.110.153
   
   Type: A
   Host: @
   Value: 185.199.111.153
   
   Type: CNAME
   Host: www
   Value: yourusername.github.io
   ```

### Netlify + Custom Domain:

1. **Buy Domain**
2. **Netlify Setup**:
   - Dashboard → Domain management
   - Add custom domain
   - Follow DNS instructions

## Cost Breakdown (Annual)

### Free Options:
- `yourusername.github.io`: **$0**
- `yoursite.netlify.app`: **$0**

### Paid Options:
- `.com` domain: **$10-15/year**
- `.dev` domain: **$12-20/year**
- `.me` domain: **$8-15/year**
- `.gh` domain: **$25-35/year**

## Professional Email Setup

With custom domain, you can also get:
- `adam@adamgibrine.com`
- `contact@adamgibrine.com`
- `hello@adamgibrine.com`

### Email Providers:
- **Google Workspace**: $6/month
- **Microsoft 365**: $6/month
- **Zoho Mail**: Free for 1 user
- **ProtonMail**: $4/month

## LinkedIn Benefits

Custom domain on LinkedIn profile:
- Shows professionalism
- Easy to remember
- Builds personal brand
- Better for networking

Example LinkedIn about section:
```
💻 Full-Stack Developer from Ghana
🌐 Portfolio: adamgibrine.com
📧 Contact: adam@adamgibrine.com
```

## Next Steps

1. **Choose domain name**
2. **Buy from registrar**
3. **Configure DNS**
4. **Update portfolio links**
5. **Update LinkedIn profile**
6. **Update resume/CV**

## Pro Tips

- Buy for 2+ years to save money
- Enable privacy protection
- Set up email forwarding
- Use subdomain for testing (test.adamgibrine.com)
- Monitor domain expiration
- Consider buying multiple variations (.com, .dev, .me)

## Backup Plan

If your preferred domain is taken:
- Add middle initial: `adamsgibrine.com`
- Use profession: `adamgibrinedev.com`
- Use location: `adamgibringh.com`
- Try different TLD: `adamgibrine.dev`

Good luck with your domain selection! 🚀
