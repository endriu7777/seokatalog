

# ZAMKNIĘTY MINI - SEO WEB CATALOG + PAYPAL + STRIPE <img width="1408" height="595" alt="zamkniety mini 1 2" src="https://github.com/user-attachments/assets/c1a44861-6524-4028-9073-481509189c16" />

SEO KATALOG - ZAMKNIĘTY MINI.
DEMO: http://demo.ma7.eu

  ===>  Zamkniety Mini v1.2 — Installation Instructions <==
  Version PL and ENG

REQUIREMENTS:
  - PHP 8.4+
  - MySQL 5.7+ or MariaDB 10.3+
  - PHP extensions: pdo, pdo_mysql, gd, mbstring

DIRECTORY STRUCTURE:
  zamkniety_admin/   — admin panel
  zamkniety_disp/    — display files (front-end)
  zamkniety_img/     — PNG images 
  zamkniety_inc/     — configuration files and installer
  zamkniety_tpl/     — templates (fonts)
  lp_cache/          — cache (requires 777 permissions)

INSTALLATION:
  1. Upload the entire package contents to the server
  2. Set permissions 777 for the lp_cache/ directory
  3. Set permissions 777 for the zamkniety_inc/ directory
     (only for the installation time)
  4. Open in your browser:
        http://yourdomain.com/zamkniety_inc/zamkniety_install.php
  5. Fill in the installation form:
     - database credentials
     - disk path to the script root directory
     - administrator login and password
  6. Click "Install"
  7. After installation DELETE the file:
        zamkniety_inc/zamkniety_install.php
  8. Change permissions of zamkniety_inc/ back to 755
  9. Paste the contents of the "htaccess" file into ".htaccess"
     (rename htaccess to .htaccess)
 10. Admin panel:
        http://yourdomain.com/zamkniety_admin/
	 
	 ADDITIONAL:
	- Set permissions 755 for the [lp_cache] directory — collects link popularity sessions
    - Set permissions 755 for rob_pl.db and rob.db files — collect search engine bot visit data
	
	If you don't know the path to your domain (when installing the script), open:
    yourdomain.com/sciezka.php

CHANGES COMPARED TO THE ORIGINAL:
  ✓ SQL Injection protection — all queries via PDO
    with prepared statements
  ✓ XSS protection — htmlspecialchars() on all output data
  ✓ CSRF protection — tokens on all POST forms
  ✓ PHP 8.4 — removed all deprecated functions:
    mysql_*   → PDO
    eregi()   → preg_match()
    each()    → foreach
    eregi_replace() → preg_replace()
  ✓ UTF-8 encoding (instead of ISO-8859-2)
  ✓ All images as PNG (no .gif, no .jpg)
  ✓ New design: light blue + transparency + shades
    of blue, gray, white, and sand
	
Update: if you want to upgrade to a newer version, overwrite all files, run the installer, click on Update, and delete the installer file (follow the instructions).

**************************************************************************
Keywords:
SEO directory,SEO tools,link building,SEO optimization,online business directory,website database,SEO for businesses,list of websites,web directory,content optimization,company database,list of companies,enterprise directory,company register,services directory,local business,industry directory,company search,local business directory,company listing,B2B business directory
