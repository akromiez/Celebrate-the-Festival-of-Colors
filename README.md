# Celebrate The Festival Of Colors

Professional invitation for the Festival of Colors celebration, ideal for travel agencies and event organizers.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Travel & Tourism, Events
- **Message Type:** Events
- **Tags:** celebration, holi, festival, color

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/Celebrate-the-Festival-of-Colors.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/Celebrate-the-Festival-of-Colors/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.Celebrate-the-Festival-of-Colors',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
