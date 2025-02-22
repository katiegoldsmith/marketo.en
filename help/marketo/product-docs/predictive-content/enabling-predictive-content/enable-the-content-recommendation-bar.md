---
unique-page-id: 4720108
description: Enable the Content Recommendation Bar - Marketo Docs - Product Documentation
title: Enable the Content Recommendation Bar
exl-id: f2244db1-51a9-4e26-9bf7-b2c79df25552
---
# Enable the Content Recommendation Bar {#enable-the-content-recommendation-bar}

The Content Recommendation Engine uses predictive analytics and machine learning algorithms to deliver relevant content to each web visitor. The recommendation engine predicts which content would perform best per visitor. The content for the engine is monitored and controlled under the Recommendations page, helping you optimize your content ROI.

>[!PREREQUISITES]
>
>Before enabling Predictive Content, you must:
>
>* **Prepare your Predictive Content**
>
>   * [Edit Predictive Content for Emails](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md) or
>   * [Edit Predictive Content for Rich Media](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md) or
>   * [Edit Predictive Content for the Recommendation Bar](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md)
>
>* [Approve a Title for Predictive Content](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md)

## Enable and Customize the Content Recommendation Bar {#enable-and-customize-the-content-recommendation-bar}

1. Go to **Content Settings**.

   ![](assets/settings-dropdown-hand.png)

1. Click **Bar**.

   ![](assets/content-settings-bar-hand.png)

1. To enable the Recommendation Bar for a URL, simply click **On** and then **Save**.

   ![](assets/bar-enable.png)

1. To customize a URL, select colors, style, format, arrows for the recommendation bar, and pages to include or exclude the bar. Customize to fit your website branding. Click **Save**.

   ![](assets/bar-customize-details-hands.png)

   >[!NOTE]
   >
   >**Include / Exclude Display URL**
   >
   >* Display URL should be the path of the domain
   >* Do not include https:// or https://
   >* Use &#42; for wildcards
   >* Use a semicolon as a separator
   >* Example: /contact_us&#42;; &#42;action=logout&#42;
   >* This field is case sensitive

## Recommendation Bar Considerations {#recommendation-bar-considerations}

* You need at least one content piece for the recommendation bar set to **On** on the Recommendations page for the Recommendation engine to work. If no content is enabled and the Bar is set to **On**, the Arrow effect will display on the bottom right of the webpage but no recommended content will appear.

* The more content running in the recommendation engine the better for the algorithm to test and learn which content works best. We recommend starting with 10 to 20 content pieces running and active and to keep adding new ones.
* The content piece you enable for recommendation should include the RTP Javascript tag. This helps the algorithm track and optimize recommended content.

>[!MORELIKETHIS]
>
>[Enable Predictive Content for Web Rich Media](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
