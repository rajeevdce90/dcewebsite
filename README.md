# DCE Infosec LLC Website

A professional website for DCE Infosec LLC, showcasing our cybersecurity, data engineering, and staffing services.

## Features

- Modern, responsive design
- Comprehensive service showcase
- Detailed capabilities section
- Contact form with email integration
- Professional branding and UI

## Setup Instructions

1. Clone this repository to your web server directory
2. Install PHP and required dependencies:
   ```bash
   composer install
   ```

3. Configure email settings:
   - Open `contactme.php`
   - Update the SMTP settings with your email server details:
     ```php
     $mail->Host = 'your-smtp-host';
     $mail->Username = 'your-email@domain.com';
     $mail->Password = 'your-password';
     ```

4. Update content:
   - Replace `images/logo.png` with your company logo
   - Replace `images/cyber-bg.jpg` with your preferred background image
   - Modify content in `index.html` as needed

## Requirements

- PHP 7.4 or higher
- Composer
- Web server (Apache/Nginx)
- SSL certificate (recommended for security)

## Contact

For any questions or support, please contact:
- Email: rajeev@dceinfosec.com
- Phone: (281) 851-4216

## License

Copyright © 2024 DCE Infosec LLC. All rights reserved.
