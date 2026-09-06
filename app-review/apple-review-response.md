# Reply to App Review — Guideline 2.1

Hello App Review Team,

Thank you for your message. We have attached a physical-device screen recording named `Zhetysu-Go-App-Review.mp4`. It was recorded on an iPhone 14 Pro Max running iOS 26.6.1 and begins with launching the app. The recording demonstrates registration, Telegram phone verification, login, account deletion, location permission, taxi ordering and completion, courier delivery, food ordering and delivery, intercity booking, chat, and trip completion.

1. **Test devices and operating systems**

- iPhone 14 Pro Max — iOS 26.6.1

2. **Functions, target audience, and value**

Zhetysu Go is a local transportation and delivery marketplace for residents, visitors, drivers, couriers, and local venues in Usharal and the Alakol District of Kazakhstan. It lets passengers request local taxi rides, create courier-delivery requests, order food from participating local venues, and reserve seats for intercity trips. Drivers, couriers, and venues receive and manage the corresponding physical-service orders. The app replaces fragmented phone calls and messaging with order status, driver location, notifications, and in-app chat in one place. The app does not sell digital content.

3. **Setup and access instructions**

The production backend will remain available during review. No sample files or special device configuration are required. Reviewers may deny location access and enter addresses manually.

Use the following dedicated review accounts. All three use the password supplied in the Password field of App Review Information:

- Passenger: `+77000000001`
- Driver/Courier: `+77000000002`
- Venue/Merchant: `+77000000003`

Passenger flow: sign in, choose Taxi, Courier, Food, or Intercity, and create an order or booking.

Driver/Courier flow: sign in, select the relevant work mode, go online where applicable, accept an available request, and update its status. Background location is requested only after a driver explicitly goes online.

Venue flow: sign in, review incoming food orders, accept an order, start preparation, mark it ready, and request a delivery driver.

Account deletion is available at the bottom of the profile screen. In a chat, press and hold another user's message to access reporting and blocking actions.

4. **External services and platforms**

- Render: application API hosting, PostgreSQL database, Redis realtime infrastructure, and public support/legal pages
- Google Maps Platform / native iOS mapping services: maps, address lookup, routes, and location-based functionality
- Telegram Bot API: phone-number verification for ordinary customer registration
- Apple Push Notification service, through Expo notification tooling: order and trip notifications
- Expo EAS: mobile build and distribution tooling

There is no AI service and no third-party payment processor. Payments for physical services are made directly by cash or Kaspi transfer; no payment is processed inside the app.

5. **Regional differences**

The service is currently intended for Usharal and the Alakol District in Kazakhstan, with intercity routes offered by participating drivers. The app itself does not provide different feature sets based on the user's App Store region. Actual service and venue availability depends on participating local drivers, couriers, routes, and venues.

6. **Regulated industries and third-party material**

The app does not provide healthcare, financial, gambling, or other highly regulated services. It facilitates local physical transportation and delivery services. Venue names, menus, prices, and images are supplied or authorized by the participating venues. The app does not provide protected third-party streaming or digital media content.

7. **Additional information**

The attached recording also shows the permission prompt for foreground location. User-generated content is limited to order/trip chat; reporting and blocking are available by pressing and holding another user's message. There are no subscriptions or in-app purchases.

Support: `zhetysugo@internet.ru`

Privacy Policy: https://taxivillage-docs-xp2f.onrender.com/privacy-policy.html

Account Deletion: https://taxivillage-docs-xp2f.onrender.com/delete-account.html

Thank you.

## Before sending

1. Attach `Zhetysu-Go-App-Review.mp4` to the reply.
2. Put `+77000000001` in the App Review username field and the real shared review password in the password field.
3. Copy the same information into App Review Information > Notes for future submissions.
4. Do not replace the placeholder by committing a real password to this repository.
