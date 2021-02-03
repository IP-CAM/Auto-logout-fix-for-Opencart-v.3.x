# Opencart 3 Auto Logout Fix

This fixes Opencart 3 issue when user returns to your opencart website and got automatically logged out, even though they did not clear their cookies manually.

This usually happens for Payment checkouts with returning POST request instead of GET request.


# Installation

1. Go to Admin
2. Upload session-modify-oc3.ocmod in Extensions > Installer
3. Go to Extensions > modifications > click on refresh
4. All should be fine, see log if there's any issue.