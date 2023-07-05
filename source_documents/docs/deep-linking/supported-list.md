---
title: Supported Domains & Schemes
navTitle: Supported Domains & Schemes
---

# Glass iOS Supported deep links, domains & schemes

This section lists all the supported deep links, domains & schemes in the app

**Note:** Names are to be kept in alphabetical order

## Deep Links

| Module Name         | Path pattern                                                 | Examples                                                     | Owned by                                                     |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Account             | account<br/>account/ccpa<br/>account/giftcards<br/>account/notifications<br/> | [walmart://account](walmart://account) <br/>[walmart://account/ccpa](walmart://account/ccpa) <br/>[walmart://account/giftcards](walmart://account/giftcards) <br/>[walmart://account/notifications](walmart://account/notifications) <br/> |                                                              |
| Add Items           | orders/:orderId/add<br/>                                     | [walmart://orders/2772221106239/add](walmart://orders/2772221106239/add) <br/> |                                                              |
| Ads                 | ads<br/>ads/redirect<br/>                                    | [walmart://ads](walmart://ads) <br/>[walmart://ads/redirect](walmart://ads/redirect) <br/> |                                                              |
| Authentication      | 3P Client Authentication<br/>account/login<br/><br/>account/signup<br/>signin<br/><br/>      | [walmart://account/login?client_id=12345&scope=offline_access&redirect_uri=https://www.walmart.com&nonce=john.smith](walmart://account/login?client_id=12345&scope=offline_access&redirect_uri=https://www.walmart.com&nonce=john.smith) <br/> [walmart://account/login](walmart://account/login) <br/>[walmart://account/login?sourcePage=foo&referrer=bar](walmart://account/login?sourcePage=foo&referrer=bar) <br/>[walmart://account/signup](walmart://account/signup) <br/>[walmart://signin](walmart://signin) <br/>[walmart://signin?sourcePage=foo&referrer=bar](walmart://signin?sourcePage=foo&referrer=bar) |                                                              |
| Auto Care Center    | acc<br/>acc/tracker/:keyTag/:storeId                         | [walmart://acc](walmart://acc) <br/>[walmart://acc/tracker/485700283333/5524](walmart://acc/tracker/485700283333/5524) <br/> |                                                              |
| Book Slot           | bookslot<br/>                                                | [walmart://bookslot](walmart://bookslot) <br/>               |                                                              |
| Cart                | cart<br/>mystore/cart/*<br/>addToCart/*<br/>buynow/*<br/>    | [walmart://cart](walmart://cart) <br/>[walmart://mystore/cart/*](walmart://mystore/cart/*) <br/>[walmart://addToCart?items=4ACS_12&deeplinkURL=https://affil.walmart.com](walmart://addToCart?items=4ACS_12&deeplinkURL=https://affil.walmart.com) <br/>[walmart://buyNow/cart?ap=4254e0&items=4DA49_13&offers=123%7C10&storeId=5435](walmart://buyNow/cart?ap=4254e0&items=4DA49_13&offers=123%7C10&storeId=5435) <br/> |                                                              |
| Checkout           | checkout<br/>                                                | [walmart://checkoutThankYou](walmart://checkoutThankYou) <br/>               |                                                              |
| Checkin             | checkin<br/>checkin/:storeId<br/>storePickup<br/>storePickup/:storeId<br/>mystore/checkin<br/>mystore/checkin/:storeId<br/>grocery/checkin<br/>grocery/checkin/:storeId<br/> | [walmart://checkin](walmart://checkin) <br/>[walmart://checkin/1234](walmart://checkin/1234) <br/>[walmart://storePickup](walmart://storePickup) <br/>[walmart://storePickup/1234](walmart://storePickup/1234) <br/>[walmart://mystore/checkin](walmart://mystore/checkin) <br/>[walmart://mystore/checkin/1234](walmart://mystore/checkin/1234) <br/>[walmart://grocery/checkin](walmart://grocery/checkin) <br/>[walmart://grocery/checkin/1234](walmart://grocery/checkin/1234) <br/> |                                                              |
| Content Page        | cp/:pageId<br/>cp/:pageName/:pageId<br/>                     | [walmart://cp/69810](walmart://cp/69810) <br/>[walmart://cp/electronics/69810](walmart://cp/electronics/69810) <br/> |                                                              |
| Converse             | converse/livechat                    | walmart://converse/livechat?receiverId=1234&firstName=name&lastName=lastname&avatarUrl=imageUrl&emailId=mailid&orderId=12345&purchaseOrderId=123 | [Voice](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-voice-ios) |
| Debug Panel         | debugPanel<br/>debugPanel/:type<br/>                         | [walmart://debugPanel](walmart://debugPanel) <br/>[walmart://debugPanel/deepLinking](walmart://debugPanel/deepLinking) <br/>[walmart://debugPanel/networkLog](walmart://debugPanel/networkLog) <br/>[walmart://debugPanel/liveOrderTrackingSettings](walmart://debugPanel/liveOrderTrackingSettings) <br/><br/>Supported types can be found [here](https://gecgithub01.walmart.com/walmart-ios/glass-app/blob/development/Plugins/DebugPanel/DebugPanel/Sources/Plugin/DebugPanelPluginAPI+Features.swift#L74-L305) | [Platform](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-platform-ios) |
| Delivery Address    | addresses<br/>addresses/add<br/>                             | [walmart://addresses](walmart://addresses) <br/>[walmart://addresses/add](walmart://addresses/add) <br/> |                                                              |
| DigitalFinance      | onedebitcard/landing                                         | [walmart://onedebitcard/landing](walmart://onedebitcard/landing) <br/>    |                                                             |
| DigitalRewards      | rewards-history                                              | [walmart://rewards-history](walmart://rewards-history) <br/>    |                                                             |
| Expo                | expo<br/>                                                    | [walmart://expo](walmart://expo) <br/>                       | [Platform](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-platform-ios) |
| Fuel                | fuel/fueling<br/>fuel/complete<br/>/fuel/qr/detect/*         | [walmart://fuel/fueling](walmart://fuel/fueling) <br/>[walmart://fuel/complete](walmart://fuel/complete) <br/>[walmart://fuel/qr/detect/&param=4816880](walmart://fuel/qr/detect/&param=4816880) <br/> |                                                              |
| Health & Wellness   | healthandwellness/dashboard<br/>healthandwellness/healthcenter<br/>healthandwellness/healthyliving<br/>healthandwellness/insurance<br/>healthandwellness/insurance/leadform<br/>healthandwellness/vision | [walmart://healthandwellness/dashboard](walmart://healthandwellness/dashboard)<br/>[walmart://healthandwellness/dashboard?deferred=pharmacy/transfer](walmart://healthandwellness/dashboard?deferred=pharmacy/transfer)<br/>[walmart://healthandwellness/healthcenter](walmart://healthandwellness/healthcenter)<br/>[walmart://healthandwellness/healthyliving](walmart://healthandwellness/healthyliving)<br/>[walmart://healthandwellness/insurance](walmart://healthandwellness/insurance)<br/>[walmart://healthandwellness/insurance/leadform](walmart://healthandwellness/insurance/leadform)<br/>[walmart://healthandwellness/vision](walmart://healthandwellness/vision) | [Wellness](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-wellness-ios) |
| Help                | help<br/>help/article/:articleTitle/:articleId<br/>help/thankyou | [walmart://help](walmart://help) <br/>[walmart://help/article/start-return-online/a760300a0bfb4cd4891e43f092c8bd18](walmart://help/article/start-return-online/a760300a0bfb4cd4891e43f092c8bd18) <br/>[walmart://help/thankyou](walmart://help/thankyou) <br/> |                                                              |
| Holiday Tab         | store/weekly-ads<br/>store/*/weekly-ads<br/>                 | [walmart://store/weekly-ads?flyer_run_id=788309](walmart://store/weekly-ads?flyer_run_id=788309) <br/>[walmart://store/2648-san-leandro-ca/weekly-ads](walmart://store/2648-san-leandro-ca/weekly-ads) <br/> |                                                              |
| Home                | home<br/>grocery<br/>                                        | [walmart://](walmart://) <br/>[walmart://home](walmart://home) <br/>[walmart://grocery](walmart://grocery) <br/> |                                                              |
| Item Details        | ip/:id<br/>item/:id<br/>grocery/ip/:id<br/>war/:id<br/>mystore/ip/:id<br/>ip/*/:id<br/>grocery/ip/*/:id | [walmart://ip/69810](walmart://ip/69810) <br/>[walmart://item/1234](walmart://item/1234) <br/>[walmart://grocery/ip/69810](walmart://grocery/ip/69810) <br/>[walmart://war/69810](walmart://war/69810) <br/>[walmart://mystore/ip/69810](walmart://mystore/ip/69810) <br/>[walmart://ip/electronics/69810](walmart://ip/electronics/69810) <br/>[walmart://grocery/ip/electronics/69810](walmart://grocery/ip/electronics/69810) <br/> |                                                              |
| Live Order Tracking | orders/:orderId/track-live<br/>orders/:orderId/track/:trackingNumber<br/> | [walmart://orders/12345/track-live](walmart://orders/12345/track-live) <br/>[walmart://orders/1234/track/5678](walmart://orders/1234/track/5678) <br/> |                                                              |
| Medications         | medications<br/>medications/details/:id                      | [walmart://medications](walmart://medications) <br/>[walmart://medications/details/1234](walmart://medications/details/1234)               | [Wellness](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-wellness-ios) |
| Medication Adherence| medication adherence<br/>medications/adherence               | [walmart://medications/adherence](walmart://medications/adherence) <br/>[walmart://medications/adherence](walmart://medications/adherence)               | [Wellness](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-wellness-ios) |
| My Items            | myitems<br/>my-registries<br/>lists<br/>lists/:permissionType/:listType/:listId<br/>lists/:listType/:listId<br/>lists/back-to-school/classes/:groupId<br/>BTS<br/>my-items | [walmart://myitems](walmart://myitems) <br/>[walmart://my-registries](walmart://my-registries) <br/>[walmart://lists](walmart://lists) <br/>[walmart://lists/back-to-school](walmart://lists/back-to-school)<br/>[walmart://lists/back-to-school/classes/79272](walmart://lists/back-to-school/classes/79272)<br/>[walmart://my-items?quickadd=true](walmart://my-items?quickadd=true) |                                                              |
| Order Details       | orders/:id<br/>grocery/orders/:id<br/>receipts/:id<br/>      | [walmart://orders/4742035227854](walmart://orders/4742035227854) <br/>[walmart://grocery/orders/7431210179547](walmart://grocery/orders/7431210179547) <br/>[walmart://receipts/10512813017369290333](walmart://receipts/10512813017369290333) <br/> |                                                              |
| Order Substitutions | orders/:orderId/edit<br/>                                    | [walmart://orders/2772221106239/edit?subfor=180816428](walmart://orders/2772221106239/edit?subfor=180816428) <br/> |                                                              |
| Payment Methods     | paymentmethods<br/>                                          | [walmart://paymentmethods](walmart://paymentmethods) <br/>   |                                                              |
| Pharmacy            | pharmacy/wellness<br/>pharmacy/scantorefill<br/>pharmacy/transfer<br/>pharmacy/refillhistory<br/>pharmacy/loggedinrefill<br/>pharmacy/refillsdue<br/>pharmacy/scantoimport<br/>pharmacy/createaccount<br/>pharmacy/secondaryauth<br/>pharmacy/orders/:orderId | [walmart://pharmacy/wellness](walmart://pharmacy/wellness) <br/>[walmart://pharmacy/scantorefill](walmart://pharmacy/scantorefill)<br/>[walmart://pharmacy/scantorefill?rxNo=1234&storeNo=1234](walmart://pharmacy/scantorefill?rxNo%3D1234%26storeNo%3D1234)<br/>[walmart://pharmacy/transfer](walmart://pharmacy/transfer) <br/>[walmart://pharmacy/refillhistory](walmart://pharmacy/refillhistory) <br/>[walmart://pharmacy/loggedinrefill](walmart://pharmacy/loggedinrefill) <br/>[walmart://pharmacy/refillsdue](walmart://pharmacy/refillsdue) <br/>[walmart://pharmacy/scantoimport](walmart://pharmacy/scantoimport)<br/>[walmart://pharmacy/createaccount](walmart://pharmacy/createaccount) <br/>[walmart://pharmacy/secondaryauth](walmart://pharmacy/secondaryauth)<br/>[walmart://pharmacy/orders/10384743272398191](walmart://pharmacy/orders/10384743272398191)<br/>[walmart://pharmacy/orders/10384743272398191?fillIds=123456789](walmart://pharmacy/orders/10384743272398191?fillIds=123456789)<br/>|                                                              |
| Purchase History    | orders<br/>grocery/orders<br/>                               | [walmart://orders](walmart://orders) <br/>[walmart://grocery/orders](walmart://grocery/orders) <br/> |                                                              |
| Scan And Go         | scanandgo                                                    | [walmart://scanandgo](walmart://scanandgo) <br/>             |                                                              |
| Scanner             | scanner<br/>                                                 | [walmart://scanner](walmart://scanner) <br/>                 | [Platform](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-platform-ios) |
| Search              | search/*<br/>browse/*<br/>grocery/search/*<br/>shop/*<br/>   | [walmart://search/tv](walmart://search/tv) <br/>[walmart://search/?query=tv](walmart://search/?query=tv) <br/>[walmart://search?query=tv&catId=3944](walmart://search?query=tv&catId=3944) <br/>[walmart://search/3944_1060825_2489948_7156390/?query=tv](walmart://search/3944_1060825_2489948_7156390/?query=tv) <br/>[walmart://search?query=tv](walmart://search?query=tv) <br/>[walmart://search?query=tv&facet=tv_screen_size_range_new%3A60%22%3A-%3A69%22&page=1&query=tv&sort=price_high](walmart://search?query=tv&facet=tv_screen_size_range_new%3A60%22%3A-%3A69%22&page=1&query=tv&sort=price_high) <br/> [walmart://browse](walmart://browse) <br/>[walmart://browse?catId=3944](walmart://browse?catId=3944) <br/>[walmart://browse/?catId=3944](walmart://browse/?catId=3944) <br/>[walmart://browse?catId=3944_5678&facet=tv_screen_size_range_new%3A60%22+-+69%22&page=1&query=tv&sort=price_high](walmart://browse?catId=3944_5678&facet=tv_screen_size_range_new%3A60%22+-+69%22&page=1&query=tv&sort=price_high) <br/>[walmart://browse/3944/electronics](walmart://browse/3944/electronics) <br/>[walmart://browse/3944_1060825/electronics](walmart://browse/3944_1060825/electronics) <br/>[walmart://browse/electronics/tv-video/general-electric/3944_1060825?cat_id=3944_1060825&facet=brand%3AGENERAL+ELECTRIC](walmart://browse/electronics/tv-video/general-electric/3944_1060825?cat_id=3944_1060825&facet=brand%3AGENERAL+ELECTRIC) <br/>[walmart://shop/savings](walmart://shop/savings) <br/>[walmart://shop/?deals_id=savings](walmart://shop/?deals_id=savings) <br/>[walmart://shop/dailyDeals](walmart://shop/dailyDeals) <br/>[walmart://shop/?deals_id=dailyDeals&cat_id=3944](walmart://shop/?deals_id=dailyDeals&cat_id=3944) <br/>[walmart://shop/deals/savings](walmart://shop/deals/savings) <br/>[walmart://shop/?deals_id=deals/savings](walmart://shop/?deals_id=deals/savings) <br/>[walmart://shop/?deals_id=deals/savings&cat_id=3944](walmart://shop/?deals_id=deals/savings&cat_id=3944) <br/>[walmart://shop?deals_id=deals/savings&cat_id=3944](walmart://shop?deals_id=deals/savings&cat_id=3944) <br/> | [Search](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-find-native-ios) |
| Search Landing      | department<br/>allDepartmentLanding<br/>                     | [walmart://department](walmart://department) <br/>[walmart://allDepartmentLanding](walmart://allDepartmentLanding) <br/> |                                                              |
| Spark Shopper       | orders/:id/shopper-substitutions<br/>                        | [walmart://orders/123/shopper-substitutions?pid=456](walmart://orders/123/shopper-substitutions?pid=456) <br/> |                                                              |
| Store Maps          | storemaps<br/>                                               | [walmart://storemaps](walmart://storemaps) <br/>             |                                                              |
| Subscriptions       | subscriptions/manage<br/>                                    | [walmart://subscriptions/manage](walmart://subscriptions/manage) <br/> |                                                              |
| Tempo               | tempo<br/>                                                   | [walmart://tempo](walmart://tempo) <br/>                     | [Platform](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-platform-ios) |
| Tipping Feedback    | orders/:orderId/tip/:shipmentId<br/>                         | [walmart://orders/1234/tip/5678](walmart://orders/1234/tip/5678) <br/> |                                                              |
| Tools               | tools<br/>                                                   | [walmart://tools](walmart://tools) <br/>                     |                                                              |
| VisionCenter        | visioncenter/select-prescription-lens<br/>visioncenter/add-prescription | [walmart://visioncenter/select-prescription-lens](walmart://visioncenter/select-prescription-lens) <br/>[walmart://visioncenter/add-prescription](walmart://visioncenter/add-prescription)
| Voice               | voice<br/>voice/addItemsWithSiri<br/>voice/bookSlotWithSiri<br/>voice/checkInWithSiri<br/>voice/shopWithSiri<br/>voice/shopWithGoogleAssistant | [walmart://voice](walmart://voice) <br/>[walmart://voice/addItemsWithSiri](walmart://voice/addItemsWithSiri) <br/>[walmart://voice/bookSlotWithSiri](walmart://voice/bookSlotWithSiri) <br/>[walmart://voice/checkInWithSiri](walmart://voice/checkInWithSiri) <br/>[walmart://voice/shopWithSiri](walmart://voice/shopWithSiri) <br/>[walmart://voice/shopWithGoogleAssistant](walmart://voice/shopWithGoogleAssistant) <br/> |[Voice](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-voice-ios)                                                              |
| Wallet              | wallet<br/>                                                  | [walmart://wallet](walmart://wallet) <br/>                   |                                                              |
| Walmart Credit Card | walmartcreditcard/landing<br/>walmartcreditcard/connect<br/>walmartcreditcard/external | [walmart://walmartcreditcard/landing](walmart://walmartcreditcard/landing) <br/>[walmart://walmartcreditcard/connect](walmart://walmartcreditcard/connect) <br/>[walmart://walmartcreditcard/external](walmart://walmartcreditcard/external) <br/> |                                                              |
| Walmart Pay         | walmartpay<br/>walmartpay/wcc/provision<br/>walmartpay/transaction/:transactionID | [walmart://walmartpay](walmart://walmartpay) <br/>[walmart://walmartpay/wcc/provision?sic=123465](walmart://walmartpay/wcc/provision?sic=123465) <br/>[walmart://walmartpay/transaction/51ca28a9-dc37-458a-901c-6076ac6648f8](walmart://walmartpay/transaction/51ca28a9-dc37-458a-901c-6076ac6648f8) <br/> |                                                              |
| Walmart Plus        | plus<br/>plus/extend<br/>plus/benefits<br/>plus/settings<br/>plus/address<br/>grocery/account/plus/overview<br/>grocery/account/plus/rx-benefit<br/>account/plus/overview<br/>plus/address/hub<br/>plus/redeem<br/>plus/express<br/>plus/learnmore<br/>plus/earlyaccess<br/>plus/plusups<br/>account/plus/rx-benefit<br/>plus/plans<br/>plus/referral<br/>plus/confirm<br/>account/plus/offers<br/>partner/plus<br/>plus/manageWeekly<br/>plus/wrs/benefits<br/>plus/signupoffers<br/>plus/offer-list | [walmart://plus](walmart://plus) <br/>[walmart://plus/extend](walmart://plus/extend)<br/>[walmart://plus/benefits](walmart://plus/benefits) <br/>[walmart://plus/settings](walmart://plus/settings) <br/>[walmart://plus/address](walmart://plus/address) <br/>[walmart://grocery/account/plus/overview](walmart://grocery/account/plus/overview) <br/>[walmart://grocery/account/plus/rx-benefit](walmart://grocery/account/plus/rx-benefit) <br/>[walmart://account/plus/overview](walmart://account/plus/overview) <br/>[walmart://plus/address/hub](walmart://plus/address/hub) <br/>[walmart://plus/redeem](walmart://plus/redeem) <br/>[walmart://plus/express](walmart://plus/express) <br/>[walmart://plus/learnmore](walmart://plus/learnmore) <br/>[walmart://plus/earlyaccess](walmart://plus/earlyaccess) <br/>[walmart://plus/plusups](walmart://plus/plusups) <br/>[walmart://account/plus/rx-benefit](walmart://account/plus/rx-benefit) <br/>[walmart://plus/plans](walmart://plus/plans) <br/>[walmart://plus/referral](walmart://plus/referral) <br/>[walmart://plus/confirm](walmart://plus/confirm) <br/>[walmart://account/plus/offers](walmart://account/plus/offers) <br/>[walmart:///partner/plus](walmart://partner/plus) <br/>[walmart://plus/manageWeekly](walmart://plus/manageWeekly) <br/>[walmart://plus/wrs/benefits](walmart://plus/wrs/benefits) <br/>[walmart://plus/signupoffers](walmart://plus/signupoffers) <br/>[walmart://plus/offer-list](walmart://plus/offer-list) | [WalmartPlus](https://gecgithub01.walmart.com/orgs/walmart-ios/teams/glass-walmart-plus-ios) |

## Registered Deep Link Redirects

|          From              |                To                     | Markets |  Notes   |
| :------------------------: | :-----------------------------------: | :-----: | :------: |
| walmart://cp/5431          | walmart://healthandwellness/dashboard | US      | Pharmacy |
| walmart://cp/pharmacy/5431 | walmart://healthandwellness/dashboard | US      | Pharmacy |
| walmart://cp/1078944       | walmart://healthandwellness/vision    | US      | Vision   |
| walmart://cp/walmart-credit-card/632402 | walmart://walmartcreditcard/landing | US      | Capitol One Credit Card |


## Universal Links

The paths to support universal links are added by following the process as outlined [here](https://engineering.walmart.com/docs/mobile/glass-ios/deep-linking#how-to-add-a-new-universal-link-route). All the supported paths for a particular domain can be found in its corresponding Apple App Site Association (AASA). In each AASA, we can find 2 or more entries which corresponds to different types of builds for a specific market.
For example, if we consider Walmart app for US market, AASA will have following bundle identifiers

- **App store/ Testflight** builds are identified by **74G6H8XY8B.com.walmart.electronics**
- **Debug/Nightly/Feature** builds which do not qualify above mentioned list are identified by **DXZ5VF8836.com.walmart.beta.electronics**

The entries under each identifier defines the supported path for a particular domain. If we consider, for example, the domain as www.walmart.com, looking at its supported paths in AASA, we can derive the complete URL as
https://www.walmart.com/browse*
https://www.walmart.com/plus/confirm
and so on.

|            Domain Name             |              Description              |                  Apple App Site Association                  |            Owned By            |                             Repo                             |
| :--------------------------------: | :-----------------------------------: | :----------------------------------------------------------: | :----------------------------: | :----------------------------------------------------------: |
|         `beta.walmart.com`         | Beta site of Walmart for Glass launch | [AASA](https://www.walmart.com/.well-known/apple-app-site-association) |        Mobile Platform         | [Link](https://gecgithub01.walmart.com/Torbit-Static-Origins/USGM-Static-Assets/blob/Prod/nativemobile/well-known/apple-app-site-association) |
|        `emlclk.walmart.com`        |         Email Click Marketing         | [AASA](https://emlclk.walmart.com/.well-known/apple-app-site-association) |              CRM               |                                                              |
|   `giftcards-locker.walmart.com`   |          Walmart Gift Cards           | [AASA](https://giftcards-locker.walmart.com/.well-known/apple-app-site-association) | Payment Methods & Item Details |                 Owned by Incomm (3P company)                 |
| `giftcards-locker-uat.walmart.com` |        Walmart Gift Cards UAT         | [AASA](https://giftcards-locker-uat.walmart.com/.well-known/apple-app-site-association) | Payment Methods & Item Details |                 Owned by Incomm (3P company)                 |
|         `goto.walmart.com`         |            Walmart Impact             | [AASA](https://goto.walmart.com/.well-known/apple-app-site-association) |                                |                                                              |
|     `goto.grocery.walmart.com`     |      Walmart Impact for Grocery       | [AASA](https://goto.grocery.walmart.com/.well-known/apple-app-site-association) |                                |                                                              |
|       `grocery.walmart.com`        |            Walmart Grocery            | [AASA](https://grocery.walmart.com/.well-known/apple-app-site-association) |        Mobile Platform         | [Link](https://gecgithub01.walmart.com/Torbit-Static-Origins/oneapp-mystore-Static-Assets/blob/master/mobile/well-known/apple-app-site-association) |
|       `links.em.walmart.com`       |           Braze Email Links           | [AASA](http://emlclk.walmart.com/.well-known/apple-app-site-association) |              CRM               | [Link](https://gecgithub01.walmart.com/growth-crm-comms/links.em.walmart.com/blob/master/.well-known/apple-app-site-association) |
|       `mystore.walmart.com`        |            Walmart Mystore            | [AASA](https://mystore.walmart.com/.well-known/apple-app-site-association) |        Mobile Platform         | [Link](https://gecgithub01.walmart.com/Torbit-Static-Origins/oneapp-mystore-Static-Assets/blob/master/mobile/well-known/apple-app-site-association) |
|       `rptrcks.walmart.com`        |             Click tracks              | [AASA](https://rptrcks.walmart.com/.well-known/apple-app-site-association) |             Comms              | AASA is managed at torbit config portal & not hosted in Git  |
|             `w-mt.co`              |              Short Links              | [AASA](https://w-mt.co/.well-known/apple-app-site-association) |             Comms              | AASA is managed at torbit config portal & not hosted in Git  |
|           `walmart.com`            |          Walmart Production           | [AASA](https://www.walmart.com/.well-known/apple-app-site-association) |        Mobile Platform         | [Link](https://gecgithub01.walmart.com/Torbit-Static-Origins/USGM-Static-Assets/blob/Prod/nativemobile/well-known/apple-app-site-association) |
|         `walmart.bttn.io`          |      Walmart button (Appsflyer)       | [AASA](https://walmart.bttn.io/.well-known/apple-app-site-association) |                                |                                                              |
|            `WMT02PAY.io`           |           Walmart Pay Fuel QR         | [AASA](https://wmt02pay.io/.well-known/apple-app-site-association) |         Mobile Pay       | [Link](https://gecgithub01.walmart.com/store-services/qr-code-redirector/blob/main/lib/static/apple-app-site-association.json) |
|            `WMT03PAY.io`           |           Walmart Pay Fuel QR         | [AASA](https://wmt03pay.io/.well-known/apple-app-site-association) |         Mobile Pay       | [Link](https://gecgithub01.walmart.com/store-services/qr-code-redirector/blob/main/lib/static/apple-app-site-association.json) |
| NOTE: The above two hosts (`WMT02PAY.io` and `WMT03PAY.io`) are intentionally above `walmart.onelink.me` and not following alphabetical order |||
|        `walmart.onelink.me`        |            Walmart Onelink            | [AASA](https://walmart.onelink.me/.well-known/apple-app-site-association) |                                |                                                              |
|       `www-e16.walmart.com`        |             Walmart Stage             | [AASA](https://www-e16.walmart.com/.well-known/apple-app-site-association) |                                |                                                              |
|      `www-teflon.walmart.com`      |            Walmart Teflon             | [AASA](https://www-teflon.walmart.com/.well-known/apple-app-site-association) |                                |                                                              |
|         `www.walmart.com`          |          Walmart Production           | [AASA](https://www.walmart.com/.well-known/apple-app-site-association) |        Mobile Platform         | [Link](https://gecgithub01.walmart.com/Torbit-Static-Origins/USGM-Static-Assets/blob/Prod/nativemobile/well-known/apple-app-site-association) |
|      `www.speedpassplus.info`      |            Exxon Fuel QR              | [AASA](https://speedpassplus.info/apple-app-site-association) |        Walmart+/Exxon         |                                                              |


## Schemes

|   Name    |     Description     |
| :-------: | :-----------------: |
|  walmart  |    Walmart Blue+    |
| walmart1h | Walmart One Hallway |


## External Schemes

|   Name    |                Description                |
| :-------: | :---------------------------------------: |
|    tel    |  To call a number, e.g. `tel:2063211212`  |


## Query Paramters


|              Value               |            Description             | Qualifies for tracking | Event Name |
| :------------------------------: | :--------------------------------: | :--------------------: | :--------: |
| walmartWidgets (To be finalised) | Query parameter of walmart widgets |         `true`         | `onClick`  |



## Allowed Domains

|            Domain Name             | Subdomains allowed? |              Description              | Owned By |
| :--------------------------------: | :-----------------: | :-----------------------------------: | :------: |
|         `beta.walmart.com`         | :heavy_check_mark:  | Beta site of Walmart for Glass launch |          |
|        `emlclk.walmart.com`        | :heavy_check_mark:  |         Email Click Marketing         |   CRM    |
|   `giftcards-locker.walmart.com`   | :heavy_check_mark:  |          Walmart Gift Cards           |          |
| `giftcards-locker-uat.walmart.com` | :heavy_check_mark:  |        Walmart Gift Cards UAT         |          |
|         `goto.walmart.com`         | :heavy_check_mark:  |            Walmart Impact             |          |
|     `goto.grocery.walmart.com`     | :heavy_check_mark:  |      Walmart Impact for Grocery       |          |
|       `grocery.walmart.com`        | :heavy_check_mark:  |            Walmart Grocery            |          |
|     `help.walmart-wellness.com`    | :heavy_check_mark:  |     Walmart Wellness Help Center      |   H&W    |
|       `i5.walmartimages.com`       | :heavy_check_mark:  |     Hosts assets, e.g. PDF files      |          |
|       `links.em.walmart.com`       | :heavy_check_mark:  |           Braze Email Links           |   CRM    |
|       `mystore.walmart.com`        | :heavy_check_mark:  |            Walmart Mystore            |          |
|       `rptrcks.walmart.com`        | :heavy_check_mark:  |             Click tracks              |  Comms   |
|             `w-mt.co`              | :heavy_check_mark:  |              Short Links              |  Comms   |
|           `walmart.com`            | :heavy_check_mark:  |          Walmart Production           |          |
|         `walmart.bttn.io`          | :heavy_check_mark:  |      Walmart button (Appsflyer)       |          |
|     `walmart.cesampling.com`       | :heavy_check_mark:  |       Walmart Baby Welcome Box        |          |
|        `walmart.onelink.me`        | :heavy_check_mark:  |            Walmart Onelink            |          |
|       `www-e16.walmart.com`        | :heavy_check_mark:  |             Walmart Stage             |          |
|      `www-teflon.walmart.com`      | :heavy_check_mark:  |            Walmart Teflon             |          |
|         `www.walmart.com`          | :heavy_check_mark:  |          Walmart Production           |          |
|     `www.speedpassplus.info`       | :heavy_check_mark:  |            Exxon Fuel QR              | Walmart+ |
|     `www.walmartpetrx.com`         | :heavy_check_mark:  |        Walmart PetRX Website          |          |