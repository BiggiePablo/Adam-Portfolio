# DNS Configuration Fix for adamgibrine.com

## GitHub Pages DNS Setup (Alternative Method)

### Option 1: A Records (Recommended)

Instead of TXT verification, use A records directly:

```
Type: A
Host: @ (or root/blank)
Value: 185.199.108.153
TTL: 300

Type: A  
Host: @ (or root/blank)
Value: 185.199.109.153
TTL: 300

Type: A
Host: @ (or root/blank) 
Value: 185.199.110.153
TTL: 300

Type: A
Host: @ (or root/blank)
Value: 185.199.111.153
TTL: 300

Type: CNAME
Host: www
Value: yourusername.github.io
TTL: 300
```

### Option 2: CNAME Method (Easier)

If A records don't work, try CNAME:

```
Type: CNAME
Host: @ (or root/blank)
Value: yourusername.github.io
TTL: 300
```

## Step-by-Step Fix

### 1. Clear Current Settings
- Remove custom domain from GitHub Pages
- Wait 5 minutes
- Delete any existing DNS records for your domain

### 2. Add New DNS Records
Based on your registrar, add the A records above

### 3. Wait for Propagation
- DNS changes take 10 minutes to 24 hours
- Check status: https://whatsmydns.net

### 4. Re-add Domain to GitHub
- Go back to GitHub Pages settings
- Add adamgibrine.com again
- Check "Enforce HTTPS" after verification

## Common Issues & Solutions

### "We couldn't find the TXT record"
- Make sure Host field is exactly: _github-challenge-yourusername-org
- Some registrars need @ instead of blank
- Wait 2-4 hours for DNS propagation

### "Domain already taken"
- Someone else might have verified this domain
- Make sure you own the domain
- Contact GitHub support if needed

### "DNS_PROBE_FINISHED_NXDOMAIN" 
- Domain not pointing to GitHub yet
- Double-check A record values
- Wait for propagation

## Quick DNS Test

Test if your DNS is working:
```bash
nslookup adamgibrine.com
```

Should return GitHub's IP addresses:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

## Registrar-Specific Instructions

### Namecheap:
1. Login → Domain List → Manage
2. Advanced DNS tab
3. Delete existing records
4. Add A records from above
5. Save changes

### GoDaddy:
1. Login → My Products → DNS
2. Delete existing A/CNAME records
3. Add new A records
4. Save

### Cloudflare (if using):
1. DNS tab
2. Delete existing records
3. Add A records (turn OFF proxy - gray cloud)
4. Save

## Verification Timeline

- DNS changes: 10 minutes - 4 hours
- GitHub verification: 5-30 minutes after DNS propagates
- SSL certificate: 1-24 hours after verification

## If Still Not Working

### Try Netlify Instead:
1. Export your files from GitHub
2. Drag to netlify.com
3. Add custom domain
4. Much easier DNS setup

### Contact Domain Registrar:
- Some registrars have specific requirements
- Ask support for "GitHub Pages DNS setup"
- They can help configure records

## Success Indicators

✅ GitHub shows green checkmark
✅ adamgibrine.com loads your portfolio  
✅ www.adamgibrine.com also works
✅ HTTPS is working
✅ No browser warnings

## Quick Fix Commands

If you have access to command line:
```bash
# Test DNS propagation
dig adamgibrine.com

# Test from different DNS servers  
nslookup adamgibrine.com 8.8.8.8
nslookup adamgibrine.com 1.1.1.1
```

## Next Steps After Success

1. Update LinkedIn profile
2. Update resume/CV
3. Share on social media
4. Add to email signature
5. Update business cards

Need help with any specific registrar? Let me know which one you're using!
