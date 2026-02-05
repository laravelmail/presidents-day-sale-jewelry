# Presidents Day Sale Jewelry

Professional email template for a Presidents Day Sale on Jewelry products in the Retail industry.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Retail
- **Message Type:** E-commerce
- **Tags:** discount, presidentsdaysale, jewelry

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/presidents-day-sale-jewelry.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/presidents-day-sale-jewelry/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.presidents-day-sale-jewelry',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
