# KutumbTree Legal & Policy Documents

Complete legal and policy documentation for KutumbTree family tree application.

## 📄 Documents Included

### 1. **index.html** - Policy Hub
Central landing page with navigation to all policy documents. Visitors can easily access any policy from this consolidated center.

- ✅ Professional design with gradients
- ✅ Mobile-responsive layout
- ✅ Easy navigation cards
- ✅ Contact information

### 2. **privacy-policy.html** - Privacy Policy
Comprehensive privacy policy covering:
- Information collection practices
- Data usage and retention
- Security measures (HTTPS, encryption, backups)
- User rights (access, correction, deletion)
- COPPA compliance (children's privacy)
- GDPR & CCPA compliance

**Key Sections:**
- Overview
- Information We Collect
- How We Use Data
- Data Retention
- Security Measures
- Information Sharing
- Your Privacy Rights
- COPPA Compliance
- Contact Us

### 3. **terms-of-service.html** - Terms of Service
Complete terms covering:
- License and usage rights
- User account responsibilities
- Content ownership
- Acceptable use policy
- Data and backups
- Sharing and collaboration
- Warranties and liability
- Third-party services
- Governing law

### 4. **data-safety.html** - Data Safety Statement
Detailed security and safety documentation including:
- Data collection overview
- Encryption (in-transit and at-rest)
- Password security (bcrypt)
- Authentication (JWT tokens)
- Data retention policies
- Backup procedures
- Compliance standards (GDPR, CCPA, COPPA)
- Security incident response

**Features:**
- Data collection table
- Security measures checklist
- Compliance standards listing
- Backup retention schedule

### 5. **cookie-policy.html** - Cookie Policy
Comprehensive cookie documentation:
- Types of cookies used
- Purpose of each cookie
- Cookie duration and lifecycle
- Analytics cookies (optional)
- Third-party cookies (minimal)
- User control and preferences
- Cookie consent management

**Included Cookies:**
- `auth_token` - Authentication (24 hours)
- `refresh_token` - Session renewal (7 days)
- `user_preferences` - UI preferences (1 year)
- `theme_preference` - Dark/light mode (1 year)
- `language_preference` - Language choice (1 year)

### 6. **acceptable-use.html** - Acceptable Use Policy
Guidelines for responsible platform use:
- Allowed activities
- Prohibited activities
- Content standards
- Consent and privacy requirements
- Account responsibility
- Violation enforcement
- Reporting mechanisms
- System use limits

### 7. **accessibility.html** - Accessibility Statement
Comprehensive accessibility documentation:
- Commitment to accessibility
- Features by disability type
  - Vision & sight (dark mode, screen readers, zoom)
  - Hearing & auditory (captions, visual feedback)
  - Motor & mobility (keyboard navigation, voice input)
  - Cognitive & neurological (simple design, clear language)
- WCAG 2.1 Level AA compliance
- Device-specific features (iOS, Android, Web)
- Known issues and remediation plans
- Accessibility testing practices
- User support and feedback

## 📋 Key Compliance Features

All documents include:
- ✅ **GDPR Compliance** - Right to access, rectification, deletion
- ✅ **CCPA Compliance** - California consumer privacy rights
- ✅ **COPPA Compliance** - Children's Online Privacy Protection
- ✅ **WCAG 2.1 Level AA** - Web accessibility standards
- ✅ **Mobile Responsive** - Works on all device sizes
- ✅ **Professional Styling** - Consistent branding throughout
- ✅ **Clear Language** - Easy to understand
- ✅ **Transparent** - Full disclosure of practices

## 🌐 Live Hosting

These documents should be hosted at:
```
https://kutumbtree.up.railway.app/
├── index.html (main hub)
├── privacy-policy
├── terms-of-service
├── data-safety
├── cookie-policy
├── acceptable-use
└── accessibility
```

For Google Play Store links:
- **Privacy Policy:** https://kutumbtree.up.railway.app/privacy-policy
- **Website:** https://kutumbtree.up.railway.app

## 🚀 Deployment Instructions

### Option 1: GitHub Pages (Recommended)
If using GitHub Pages for this repository:
1. Go to repository Settings → Pages
2. Select "main" branch as source
3. Documents will be available at: https://rubix-coder.github.io/kutumbtree-policy/

### Option 2: Railway Backend
Add to your Express backend:
```javascript
app.get('/privacy-policy', (req, res) => {
    res.sendFile(path.join(__dirname, 'public/policies/privacy-policy.html'));
});
// Repeat for other policies
```

### Option 3: Static Web Server
Host on any static web host (Netlify, Vercel, S3, etc.)

## 📱 Google Play Store Integration

For Google Play Store submission, use these URLs:
- **Privacy Policy URL:** https://kutumbtree.up.railway.app/privacy-policy
- **Website URL:** https://kutumbtree.up.railway.app

The Play Store will crawl these URLs to verify compliance.

## 🔒 Security Notes

- All documents use HTTPS only
- No sensitive information should be committed
- Documents are read-only and don't require authentication
- Update Last Modified dates when policies change
- Notify users of material policy changes

## 📝 Updating Policies

When updating policies:
1. Edit the relevant .html file
2. Update the "Last Updated" date
3. Commit with clear message
4. Push to GitHub
5. Wait for deployment to propagate (usually 1-2 minutes)

## 🔗 Cross-References

All documents link back to the main hub via the back button, creating a cohesive policy center.

## 📧 Contact Information

Support contact across all documents:
- **Email:** p.jesal.work@gmail.com
- **Support:** support@kutumbtree.com
- **Accessibility:** accessibility@kutumbtree.com
- **Website:** https://kutumbtree.up.railway.app

## ✨ Features

Each document includes:
- ✅ Table of Contents (where applicable)
- ✅ Professional styling
- ✅ Mobile-responsive design
- ✅ Easy navigation
- ✅ Contact information
- ✅ Last updated date
- ✅ Back to hub link
- ✅ Accessibility features

## 📊 Version History

- **1.0** (June 12, 2026) - Initial comprehensive policy suite
  - Privacy Policy
  - Terms of Service
  - Data Safety Statement
  - Cookie Policy
  - Acceptable Use Policy
  - Accessibility Statement
  - Consolidated Hub

## 📜 License

These documents are part of the KutumbTree application and are protected by copyright. They define the legal terms for using KutumbTree.

---

**Created:** June 12, 2026  
**Repository:** https://github.com/rubix-coder/kutumbtree-policy  
**Application:** KutumbTree Family Tree Management
