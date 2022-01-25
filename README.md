# UW SSO Login (Chromium)
Chrome extension for automatic UW SSO login

> :warning: **Warning**: This extension stores your password unencrypted. It may be possible for people or other extensions to access it. I would recommend reading through the full source code before installing (it isn't that long). Please use with caution.

For some additional features, see [kaedenbrinkman/uw-autofill](https://github.com/kaedenbrinkman/uw-autofill)

## Setup
Install the extension
- Enable developer mode
- "Load unpacked"
- Select the `src` directory

You may need to edit the extension ID on [this line](https://github.com/kaedenbrinkman/uw-sso-login/blob/c94e9b42e9d9be08c03a68bc49bbecaebbc54ada/src/autofill.js#L22) first.

## Usage
Click the extension icon

Enter your UW NetID and password

Click Save

Every time you visit https://idp.u.washington.edu/idp/profile/SAML2/Redirect/SSO, your credentials will be autofilled. If you check the "Auto-submit" checkbox, it will automatically press the Login button and you will be logged in instantly.
