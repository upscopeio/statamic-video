# statamic-video

Statamic addon for videos from Vimeo

1. Add `VIMEO_ACCESS_TOKEN` to your `.env` file.
   - The token must be from the account owner of the video library you want to use. https://developer.vimeo.com/
2. Add the following code to `config/services.php`:

   'vimeo' => [
        'access_token' => env('VIMEO_ACCESS_TOKEN'),
    ],