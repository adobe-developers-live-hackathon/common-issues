# Common issues

### AIO CLI is outdated
Ensure your CLI and all plugins are up to date through `aio -v`. For this workshop we use version `8.1.0`. If your CLI is outdated, update it by running `npm install -g @adobe/aio-cli`. After that, you can simply run `aio update` to ensure all core plugins are updated.

### Unable to login via `aio login`
Go to https://account.adobe.com and click "Sign Out". Open terminal and type `aio logout`.
Then try to run `aio login` again.

### "Your connection is not private" in the browser
If you see this message when navigating to https://localhost:9080, click `Advanced` and `Proceed to localhost (unsafe)` to accept the certificate.
You may need to exit the current process and run aio app run again.

### Missing param error
If you see the following error, it is because you did not pass in required params to an action expecting one.
