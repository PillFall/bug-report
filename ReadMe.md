# Bug Report (laravel/vite-plugin#209)

This is the configuration I use for the bug to show.

You can change anything in the [`resources/js/pages/home.vue`](resources/js/pages/home.vue), and the changes are not reflected until you reload the server, unless you deactivate the `refresh` option in [`vite.config.js`](resources/vite.config.js).



### Possible cause

I believe that the problem arises because of the symlinks, but I do not know why it only shows after you enables the refresh option.

But I need those links as the resources folder is a submodule in my project, and I do not know other way to keep the app with the same workflow as if the symlinks where not there.
