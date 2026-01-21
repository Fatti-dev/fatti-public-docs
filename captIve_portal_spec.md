# Captive Portal Advertising Asset Specification
**Fatti Captive Portal**

This document outlines the creative assets and setup information required to configure a branded captive portal experience. Following these guidelines, and providing the items below will allow us to build, test, and deploy the portal efficiently while ensuring optimal performance and user engagement.

---
## Example of Portal

The portal generally has three pages: 
- a landing page (the first page that is shown when connecting to the Wifi). This page is optional.
- a account creation page (where questions can be asked). This page is optional.
- a success page (a page that is shown after an account is successfully created). This page is optional.

Examples of these are shown below:
<img width="1164" height="2306" alt="Screenshot 2026-01-21 at 18 42 19" src="https://gist.github.com/user-attachments/assets/ff253800-6434-4144-84ef-cb78e53a0a66" />
<img width="1164" height="972" alt="Screenshot 2026-01-21 at 18 42 49" src="https://gist.github.com/user-attachments/assets/7bb870af-ba2e-46b8-80d1-ee4ad5361864" />
<img width="1164" height="2092" alt="Screenshot 2026-01-21 at 18 42 57" src="https://gist.github.com/user-attachments/assets/be327979-9e39-4f3a-9cc5-46faeca43d91" />

---

## Assets required from client

### Primary Image (Static Visual/Primary visual)
This image will be used as the primary visual on the captive portal landing page, either alongside the promotional video or as a fallback visual on devices or connections where video playback is restricted.

#### Requirements
- **Recommended size:** 992 × 1366 pixels  
- **Format:** JPG or PNG  

#### Delivery options
- Email (as an attachment)

---

### Promotional Video
The promotional video is the most prominent element shown to users during the Wi-Fi login journey. Strong branding and a clear call-to-action in the opening seconds is recommended.

#### Requirements
- **Length:** 10–15 seconds - To keep user engagement high, we recommend a concise video that quickly conveys your message.
- **Format:** At present we can only use YouTube links. We’re unable to upload YouTube videos on your behalf due to licensing constraints, and we’re exploring support for additional formats in a future update. 
- **Orientation:** Landscape (16:9) 
- **Recommended resolution:** 1920 × 1080 
- **File size:** Ideally under 20–25 MB for fast loading on mobile networks

#### Delivery options
- Email (Just add the link to the body of the email)

---

### Captive Portal Banner (Static Visual)
This banner is used either alongside the primary image or video. We can have multiple banners that rotate on a set time to provide variety to users.

#### Requirements
- **Recommended size:** 1125 × 314 pixels
- **Format:** JPG or PNG
- **Orientation:** Landscape

#### Please include
- Final headline text  
- Preferred call-to-action (CTA) wording  
- Any specific branding elements (e.g., logos, colors) 

#### Delivery options
- Email (as an attachment)

---

### Survey Questions (Optional but Recommended)
Short surveys can significantly improve engagement while capturing valuable insight. We recommend no more than 3 questions to maintain a smooth login experience, but we can do up to 5 if needed.

#### Suggested structure
1. **Research question**  
   - Example: “How interested are you in attending Formula 1 events?”  

2. **Insight question**  
   - Example:  
     - “Have you attended an F1 event before?”  
     - “Where would you most likely travel from?”  

3. **Call-to-action / consent**  
   - Example:  
     - “Can we contact you to discuss tickets for the Miami F1 in 2026?”  

#### Please let us know
- The exact wording for each question
- Any specific data points you would like us to capture

#### Please note
- We currently support multiple-choice, free text, and dropdown(multiple answers) styled question types.

#### Delivery options
- Email

--- 

### Secondary Image (Optional)
Any official imagery you would like included in the portal experience. for example a different image on the success/login page, than on the landing page.

#### Usage
- Supporting visuals within the portal  
- Backup visuals where video cannot be displayed  

#### Requirements 
- **Minimum resolution:** 992 × 950  
- **Format:** JPG or PNG  

#### Delivery options
- Email (as an attachment)

---

### Link Destinations & Tracking
To ensure accurate measurement and attribution, please provide:
- Final destination URL(s) - where users will be directed after engaging with the portal
- We can provide tracking stats via the Connect dashboard, but if you have specific UTM parameters or tracking codes to be included in the URLs, please share those as well.

---

### Payment providers (Still in Development)

Monetization of the captive portal, or access to premium services, is a potential revenue source. Below is a list of payment providers we currently support, those that are still in development, and those that we know of but not currently developing.

We currently support:
- PayPal
    - Process flow
        1.	User clicks the same PayPal button
        2.	PayPal offers “Pay with card”
        3.	User enters card details
        4.	Payment completes
    - We require the following from the client:
        - **Client ID:** This can be obtained in the developer section of your paypal account.
        - **Login Details:** We can also set everything up for you on the PayPal side, if you provide us with login details for the PayPal account. 
- PayPal Wallet
    - Process flow
        1.	User clicks the PayPal button
        2.	PayPal detects an account (or user logs in)
        3.	User pays with:
            - PayPal balance
            - Linked bank account
            - Linked card
    - We require the following from the client:
        - **Client ID:** This can be obtained in the developer section of your paypal account.
        - **Login Details:** We can also set everything up for you on the PayPal side, if you provide us with login details for the PayPal account. 

We are currently investigating the following, but these are not available yet:
- Apple Pay via PayPal
    - Process flow
        1.	User clicks PayPal / or sees Apple Pay surface
        2.	On Safari + Apple device, PayPal may show Apple Pay
        3.	User authenticates with FaceID / TouchID
        4.	PayPal captures the payment
- Revolut


We are aware of other providers, and can do development if required:
- Stripe
- Adyen

---

## 8. Final Notes
- You may also build a landing page using a WYSIWYG editor (e.g., WordPress), and we’ll aim to match the layout as closely as possible.
- https://www.canva.com/photo-editor/ can be a useful tool for creating or resizing images if needed.
- All assets should be pre-approved by all parties to avoid delays and additional development costs.
- If you are unsure about formats or creative direction, we are happy to review drafts before final submission.  
- Once all assets are received, we will proceed with configuration, testing, and deployment.

---
Thank you for your collaboration! We look forward to creating an engaging captive portal experience for your users

