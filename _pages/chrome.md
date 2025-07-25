---
title: "ChromeOS"
permalink: /chrome/
author_profile: true
sidebar:
  nav: "nav-chrome"
header:
  overlay_color: "#333"
---
# Chromebook Setup

__Let's get your ChromeOS device set up!__

* Press the __power__ button at the top-right corner of the keyboard: 

{% include figure url="/assets/images/pixelbookgo-power.jpg" image_path="/assets/images/pixelbookgo-power.jpg" caption="(if you have a ChromeBox the power button is on the device and not the keyboard)" %}

* Connect your device to a wireless network (either your home WiFi or the Block office) with Internet access.

* Your device should indicate that it is __Managed by squareup.com__:

{% include figure url="/assets/images/chrome-01-login.jpg" image_path="/assets/images/chrome-01-login.jpg" caption="(if you do not see &quot;Managed by squareup.com&quot; ask for [help](/help))" %}

* Enter your full email address and click [Next](#duo){: .btn .btn--inverse .btn--small}

{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" %}

* Enter your username, click [Next](#next){: .btn .btn--inverse .btn--small} then enter your newly created password, and click [Verify](#verify){: .btn .btn--inverse .btn--small}

Since you have already set up __Okta Verify__ on your mobile device, you can now use it to authenticate in the next step: 

{% include figure url="/assets/images/security-key-setup.png" image_path="/assets/images/security-key-setup.png" %}

* Click __Set Up__ when asked to set up a Security Key or Biometric Authenticator. 

You should have received a YubiKey with your laptop. Insert it into your laptop now. 

{% include figure url="/assets/images/yubikey-5c-nfc.png" image_path="/assets/images/yubikey-5c-nfc.png" caption="(If you didn't get a Yubikey, file a go/IT ticket)" %}

* Click Set Up, then choose __USB Security Key__
**USB-security-key**

When prompted, insert the Yubikey, and touch the gold sensor. 

* Select __Allow__ when asked if the site can use your YubiKey.
{% include figure url="/assets/images/security-key-allow.png" image_path="/assets/images/security-key-allow.png" %}


Once logged in, you should see this message:

{% include figure url="/assets/images/chrome-02-signin.jpg" image_path="/assets/images/chrome-02-signin.jpg" caption="(you may review the sync options after setup)" %}

* Click [Accept and Continue](#ready){: .btn .btn--inverse .btn--small}. You may hear the _Google Assistant_ announce that it has been disabled. To silence the device audio, press the mute button (above the “0” key in the top row of your keyboard). 

[Next Step &rarr;](/chrome-browser/){: .btn .btn--success .btn--large}
