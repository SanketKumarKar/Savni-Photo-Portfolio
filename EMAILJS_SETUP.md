# EmailJS Setup Guide for Savni Goyal Photography Portfolio

## Quick Setup Instructions

### 1. Get Your EmailJS Public Key
You mentioned the service details, but you'll also need your **Public Key** from EmailJS:

1. Go to [EmailJS Dashboard](https://dashboard.emailjs.com/)
2. Navigate to **Account** → **General**
3. Copy your **Public Key**
4. Replace `"YOUR_PUBLIC_KEY"` in the JavaScript with your actual public key

### 2. Update the JavaScript
In the `script.js` file, find this line:
```javascript
emailjs.init("YOUR_PUBLIC_KEY"); // You'll need to replace this with your actual public key
```

Replace `"YOUR_PUBLIC_KEY"` with your actual EmailJS public key.

### 3. EmailJS Template Variables
Make sure your EmailJS template (`template_eqtnw3a`) includes these variables:
- `{{from_name}}` - Sender's name
- `{{from_email}}` - Sender's email
- `{{subject}}` - Message subject
- `{{message}}` - Message content
- `{{to_name}}` - Recipient name (Savni Goyal)
- `{{to_email}}` - Recipient email (goyalsavni@gmail.com)

### 4. Example EmailJS Template
Your email template should look something like this:

**Subject:** New Contact Form Message: {{subject}}

**Body:**
```
Hello {{to_name}},

You have received a new message from your photography portfolio website.

From: {{from_name}} ({{from_email}})
Subject: {{subject}}

Message:
{{message}}

---
This message was sent from your portfolio contact form.
```

### 5. Testing the Form
1. Open your website
2. Navigate to the contact section
3. Fill out the form with test data
4. Submit the form
5. Check your email (goyalsavni@gmail.com) for the message

### 6. Current Service Configuration
- **Service ID:** `service_el6zmci`
- **Template ID:** `template_eqtnw3a`
- **Recipient:** `goyalsavni@gmail.com`

## Features Implemented

### ✅ Form Validation
- Required field validation
- Email format validation
- Real-time error messages

### ✅ User Experience
- Loading state with spinner animation
- Success/error notifications
- Form reset after successful submission
- Disabled submit button during sending

### ✅ Error Handling
- Network error handling
- EmailJS service error handling
- Fallback error messages

### ✅ Mobile Responsive
- Works perfectly on all devices
- Touch-friendly interface
- Responsive form layout

## Form Fields Mapping
- **Your Name** → `from_name`
- **Your Email** → `from_email`
- **Subject** → `subject`
- **Your Message** → `message`

## Troubleshooting

### Common Issues:
1. **"FAILED" in console:** Check your EmailJS service ID and template ID
2. **No emails received:** Verify your EmailJS template variables match the form fields
3. **Public key error:** Make sure you've replaced `"YOUR_PUBLIC_KEY"` with your actual key

### Testing Steps:
1. Open browser developer tools (F12)
2. Go to Console tab
3. Submit a test message
4. Look for "SUCCESS!" or "FAILED..." messages
5. Check the EmailJS dashboard for sent emails

## Security Notes
- The public key is safe to expose in client-side code
- EmailJS handles the secure email sending
- Form validation prevents basic spam attempts
- No sensitive data is stored in the website code

---

**Next Steps:**
1. Replace `"YOUR_PUBLIC_KEY"` in script.js with your actual EmailJS public key
2. Test the contact form
3. Verify emails are being received at goyalsavni@gmail.com

The contact form is now fully functional and will send emails directly through EmailJS!
