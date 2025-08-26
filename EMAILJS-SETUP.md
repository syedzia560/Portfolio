# 📧 EmailJS Setup Instructions

To make your contact form send emails to **syed.zia560@gmail.com**, follow these steps:

## 🚀 Step 1: Create EmailJS Account

1. Go to [EmailJS.com](https://www.emailjs.com/)
2. Click **"Sign Up"** and create a free account
3. Verify your email address

## 🔧 Step 2: Create an Email Service

1. In your EmailJS dashboard, go to **"Email Services"**
2. Click **"Add New Service"**
3. Choose **"Gmail"** (recommended for Gmail users)
4. Click **"Connect Account"** and authorize with your Gmail account
5. **Service ID** will be generated (e.g., `service_xyz123`) - **COPY THIS**

## 📝 Step 3: Create an Email Template

1. Go to **"Email Templates"** in your dashboard
2. Click **"Create New Template"**
3. Set up your template with these variables:

### Template Content:
**Subject:** `New Portfolio Contact from {{from_name}}`

**Body:**
```
Hello Zia,

You have received a new message from your portfolio website:

From: {{from_name}}
Email: {{from_email}}

Message:
{{message}}

---
Sent from your portfolio contact form
```

4. **Template ID** will be generated (e.g., `template_abc456`) - **COPY THIS**

## 🔑 Step 4: Get Your Public Key

1. Go to **"Account"** → **"General"**
2. Find your **"Public Key"** - **COPY THIS**

## 💻 Step 5: Update Your Website Code

Open `js/script.js` and replace these placeholders:

```javascript
// Line 3: Replace YOUR_PUBLIC_KEY
emailjs.init("YOUR_ACTUAL_PUBLIC_KEY_HERE");

// Line 125: Replace YOUR_SERVICE_ID and YOUR_TEMPLATE_ID
emailjs.send('YOUR_ACTUAL_SERVICE_ID', 'YOUR_ACTUAL_TEMPLATE_ID', templateParams)
```

### Example:
```javascript
// Replace with your actual values
emailjs.init("user_abc123xyz789");
emailjs.send('service_gmail', 'template_contact', templateParams)
```

## ✅ Step 6: Test Your Contact Form

1. Open your portfolio website
2. Fill out the contact form
3. Click **"Send Message"**
4. Check **syed.zia560@gmail.com** for the email

## 🔒 Important Security Notes

- ✅ **Public Key is safe** to use in frontend code
- ✅ **Service ID and Template ID** are safe to use in frontend
- ✅ EmailJS handles the actual email sending securely
- ✅ Your Gmail password is never exposed

## 🎯 Features Already Implemented

- ✅ Form validation (name, email, message required)
- ✅ Email format validation
- ✅ Loading state ("Sending..." button)
- ✅ Success/error notifications
- ✅ Automatic form reset after successful send
- ✅ Professional email template
- ✅ Sends to: **syed.zia560@gmail.com**

## 🆓 EmailJS Free Plan

- ✅ **200 emails/month** for free
- ✅ Perfect for portfolio contact forms
- ✅ No credit card required for free plan

## 🚨 Troubleshooting

### Common Issues:

1. **"EmailJS is not defined" error:**
   - Make sure the EmailJS script is loading in `index.html`
   - Check browser console for script loading errors

2. **Emails not sending:**
   - Verify Service ID, Template ID, and Public Key are correct
   - Check EmailJS dashboard for error logs
   - Make sure Gmail service is properly connected

3. **Emails going to spam:**
   - Add your portfolio domain to trusted senders in Gmail
   - This is normal for new domains/services

## 📞 Support

If you have issues:
- Check EmailJS documentation: https://www.emailjs.com/docs/
- Contact EmailJS support through their dashboard
- The contact form will show success/error messages

## 🎉 Once Setup Complete

Your portfolio contact form will:
1. ✅ Send emails directly to **syed.zia560@gmail.com**
2. ✅ Include sender's name, email, and message
3. ✅ Show professional success notifications
4. ✅ Work from any device/browser
5. ✅ Be completely free (up to 200 emails/month)

---

**That's it! Your contact form will be fully functional once you complete these steps.** 🚀
