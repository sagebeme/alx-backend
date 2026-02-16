0x02. i18n (Internationalization)
=================================

This project practices **internationalization (i18n)** and **localization**: detecting or selecting the user's locale and returning translated strings (e.g. with Flask-Babel or gettext) so the API or app can support multiple languages.

Tasks
-----

### 0. i18n / locale and translations

mandatory

Implement locale selection (e.g. from Accept-Language header or query param) and translated messages: use a translation catalog (e.g. Babel) to return strings in the correct language. Run: start the app and send requests with different Accept-Language values to see different translations.

**Repo:**

-   GitHub repository: `alx-backend`
-   Directory: `0x02-i18n`
-   File: (i18n config and views as per project)

---

**How to run / test**

1. Install Flask-Babel (or project deps) and extract/compile translations.
2. Run the app and call endpoints with different locale headers; verify the response language changes.
