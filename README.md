# Utilities Translation Bug

1. Log in with `admin@example.com` and `password`
2. See that the admin panel is in English (as per the users preferences)
3. Go to Utilities page and see that it is in Swedish (as per the app config)

*Note: Individual utility pages are still in English*

## Settings

- `config/app.php` has `locale => 'sv'`
- `users/admin@example.com.yaml` has `preferences: locale: en`
