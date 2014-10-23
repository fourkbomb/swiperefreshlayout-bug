#SwipeRefreshLayout doesn't handle switching fragments nicely

Steps to reproduce:

1. Install app on device using the Android 5.0 SDK
2. Swipe to refresh, and then switch fragments using the navigation
   drawer
3. The planet _should_ change, but doesn't
