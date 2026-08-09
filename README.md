# Legal Document Templates

This folder contains ready-to-use HTML templates for Terms of Service and Privacy Policy documents required by TikTok (and other platforms).

## Files

- **[terms-of-service.html](terms-of-service.html)** - Terms of Service template
- **[privacy-policy.html](privacy-policy.html)** - Privacy Policy template

## How to Use

### Step 1: Customize the Templates

Edit the HTML files and replace these placeholders:

1. **Contact Email:**
   - Replace: `your-email@example.com`
   - With: Your actual email address

2. **GitHub URL (if applicable):**
   - Replace: `github.com/yourusername/video-maker`
   - With: Your GitHub repository URL
   - Or remove if not using GitHub

3. **Date:**
   - The templates use "August 9, 2026"
   - Update to current date if needed

### Step 2: Host the Files

You need to host these files publicly to get URLs for TikTok app registration.

#### Option A: GitHub Pages (Recommended - Free & Easy)

1. **Create a new GitHub repository:**
   ```bash
   # On GitHub.com, create new repo: "video-maker-legal"
   ```

2. **Upload the files:**
   ```bash
   git clone https://github.com/yourusername/video-maker-legal.git
   cd video-maker-legal
   
   # Copy the template files
   cp /path/to/templates/terms-of-service.html .
   cp /path/to/templates/privacy-policy.html .
   
   git add .
   git commit -m "Add legal documents"
   git push origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Select "main" branch
   - Click "Save"

4. **Your URLs will be:**
   ```
   https://yourusername.github.io/video-maker-legal/terms-of-service.html
   https://yourusername.github.io/video-maker-legal/privacy-policy.html
   ```

5. **Use these URLs in TikTok app registration**

#### Option B: Netlify Drop (Free - No Git Required)

1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop your HTML files
3. Get instant URLs like: `https://random-name-12345.netlify.app/terms-of-service.html`
4. Use these URLs in TikTok app registration

#### Option C: Vercel (Free - Git or Direct Upload)

1. Go to [Vercel](https://vercel.com)
2. Sign up with GitHub
3. Import your repository or drag files
4. Get URLs like: `https://video-maker-legal.vercel.app/terms-of-service.html`

### Step 3: Add URLs to TikTok App

When creating your TikTok app, enter:

- **Terms of Service URL:** `https://yourusername.github.io/video-maker-legal/terms-of-service.html`
- **Privacy Policy URL:** `https://yourusername.github.io/video-maker-legal/privacy-policy.html`

## Template Features

### Terms of Service Includes:
- ✅ Service description
- ✅ User responsibilities
- ✅ Content ownership
- ✅ API usage disclaimers
- ✅ Prohibited uses
- ✅ Limitation of liability
- ✅ Platform-specific terms

### Privacy Policy Includes:
- ✅ Data collection explanation
- ✅ Local storage emphasis
- ✅ Third-party services disclosure
- ✅ User rights (GDPR compliant)
- ✅ Children's privacy
- ✅ Data deletion instructions
- ✅ Security practices

## Important Notes

1. **Not Legal Advice:** These templates are provided as-is. For production use or business purposes, consult a lawyer.

2. **Customization Required:** The templates are generic. Customize them to match your specific use case.

3. **Keep Updated:** Review and update your legal documents regularly, especially when:
   - Adding new features
   - Integrating new services
   - Changing data practices
   - Laws change in your jurisdiction

4. **Platform Requirements:** Different platforms have different requirements:
   - **TikTok:** Requires both Terms and Privacy Policy URLs
   - **YouTube:** Privacy Policy link in app description
   - **Facebook:** Privacy Policy URL in app settings

## Testing

Before submitting to TikTok, test your URLs:

```bash
# Check if URLs are accessible
curl -I https://yourusername.github.io/video-maker-legal/terms-of-service.html
curl -I https://yourusername.github.io/video-maker-legal/privacy-policy.html

# Should return: HTTP/2 200
```

## Updating Documents

To update your documents after hosting:

1. Edit the HTML files
2. Update the "Last Updated" date
3. Push changes to GitHub (or re-upload to Netlify/Vercel)
4. Changes are live immediately

## Need Help?

See the main documentation:
- [TIKTOK_SETUP.md](../TIKTOK_SETUP.md) - Complete TikTok setup guide
- [COMMANDS.md](../COMMANDS.md) - All available commands

## License

These templates are provided for use with Video Maker App. Modify as needed for your use case.

---

**Created:** August 9, 2026
