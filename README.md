Contact Form with Multiple Attachments Using AJAX and PHPMailer
============

This is very simple contact form with multiple attachments using AJAX and PHPMailer v6.5

This form will work for PHP 7 or higher

Installation
============

You have to clone this repository

```
git clone https://github.com/alltimehasan/contact-form-with-multiple-attachments-using-ajax-and-phpmailer.git
```

You have to install PHPMailer using composer in the root directory

```
composer install
```

Usage
=====

You have to add your google reCaptcha V2 site key in the index.html file at line No. 21

```html

<div class="g-recaptcha" data-theme="light" data-sitekey="site_key"></div>

```

You have to add your google reCaptcha V2 secret key in the process/process-contact.php file at line No. 54

```php

$secret = 'secret_key';

```

You have to add your domain name in the process/process-contact.php file at line No. 115

```php

$mail->setFrom('noreply@yourdomain.com', 'Company Name');

```

You have to add a email address where the form data will go, in the process/process-contact.php file at line No. 119

```php

$mail->addAddress('youremail@domain.com');

```