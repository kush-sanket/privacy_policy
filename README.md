# Privacy Policy Page

A single-page HTML privacy policy template for Google Play Console app publishing.

## Features

- **Comprehensive Coverage**: Includes all standard privacy policy sections required for app store submissions
- **Mobile Responsive**: Fully responsive design that works on all devices
- **Clean Design**: Professional styling with Google's blue color scheme (#1a73e8)
- **Easy to Customize**: Simple HTML structure with inline CSS for easy modifications
- **No Dependencies**: Pure HTML and CSS, no external libraries required

## Usage

### For Google Play Console

1. **Host the page**: Upload `index.html` to your web hosting service
2. **Get the URL**: Copy the public URL of your hosted page
3. **Add to Play Console**: 
   - Go to your app in Google Play Console
   - Navigate to "App content" section
   - Under "Privacy policy", paste your privacy policy URL
   - Save changes

### Customization

Edit the `index.html` file to customize:

- **Last Updated Date**: Change the date in the `.last-updated` paragraph
- **Contact Information**: Update email, address, and website in the "Contact Us" section
- **Company Details**: Replace placeholder text like "[Your Company Address]"
- **Content**: Modify any section to match your app's specific data practices
- **Colors**: Change the `#1a73e8` color values to match your brand

### Local Preview

Open `index.html` directly in your web browser, or use a local web server:

```bash
# Using Python 3
python3 -m http.server 8080

# Using PHP
php -S localhost:8080

# Then visit http://localhost:8080/index.html
```

## Privacy Policy Sections

The template includes all essential sections:

1. Information We Collect
2. How We Use Your Information
3. Information Sharing and Disclosure
4. Data Security
5. Data Retention
6. Your Rights and Choices
7. Children's Privacy
8. Third-Party Services
9. International Data Transfers
10. Changes to This Privacy Policy
11. Contact Us

## Requirements for Google Play

Google Play requires apps to have a privacy policy if they:
- Handle personal or sensitive user data
- Are targeted at children
- Are available in certain regions (like EU/EEA)

This template covers all common requirements, but please review Google's current policies and consult with legal counsel to ensure compliance with your specific situation.

## License

This is a template provided as-is. Please modify it according to your needs and have it reviewed by legal counsel before publication.