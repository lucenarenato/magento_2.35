"{"product":{"name":"gamettt","custom_attributes":[{"attribute_code":"url_key","value":"5f5b74e03710495bd329bb57"},{"attribute_code":"description","value":"<p>jogo"}]}}"



Problem 1
    - magento/product-community-edition 2.3.5 requires msp/twofactorauth 3.1.2 -> satisfiable by msp/twofactorauth[3.1.2].
    - Installation request for magento/product-community-edition 2.3.5 -> satisfiable by magento/product-community-edition[2.3.5].
    - Conclusion: don't install spomky-labs/otphp v8.3.3
    - Conclusion: don't install spomky-labs/otphp v8.3.2
    - magento/magento2-functional-testing-framework 3.0.0 requires spomky-labs/otphp ^10.0 -> satisfiable by spomky-labs/otphp[v10.0.0, v10.0.1].
    - magento/magento2-functional-testing-framework 3.1.0 requires spomky-labs/otphp ^10.0 -> satisfiable by spomky-labs/otphp[v10.0.0, v10.0.1].
    - Can only install one of: spomky-labs/otphp[v8.3.0, v10.0.0].
    - Can only install one of: spomky-labs/otphp[v8.3.0, v10.0.1].
    - msp/twofactorauth 3.1.2 requires spomky-labs/otphp ~8.3 -> satisfiable by spomky-labs/otphp[v8.3.0, v8.3.1, v8.3.2, v8.3.3].
    - Conclusion: don't install spomky-labs/otphp v8.3.1
    - Installation request for magento/magento2-functional-testing-framework ^3.0 -> satisfiable by magento/magento2-functional-testing-framework[3.0.0, 3.1.0].


phpunit/phpunit: ~6.5.0 || ~7.0.0

codeception/phpunit-wrapper ^6.0.9|^7.0.6

codeception/phpunit-wrapper 7.8.0 requires phpunit/phpunit 7.5.*

magento/magento2-functional-testing-framework 2.6.5 requires codeception/codeception ~2.4.5 -> satisfiable by codeception/codeception[2.4.5].

{
    "id": 10,
    "sku": "5f5bb1cfe1b84f25b02e44c2",
    "name": "Ecang-twaaepdkp123",
    "attribute_set_id": 4,
    "price": 0,
    "status": 1,
    "visibility": 4,
    "type_id": "simple",
    "created_at": "2020-09-11 17:20:17",
    "updated_at": "2020-09-11 18:00:19",
    "extension_attributes": {
        "website_ids": [
            1
        ],
        "stock_item": {
            "item_id": 10,
            "product_id": 10,
            "stock_id": 1,
            "qty": 0,
            "is_in_stock": false,
            "is_qty_decimal": false,
            "show_default_notification_message": false,
            "use_config_min_qty": true,
            "min_qty": 0,
            "use_config_min_sale_qty": 1,
            "min_sale_qty": 1,
            "use_config_max_sale_qty": true,
            "max_sale_qty": 10000,
            "use_config_backorders": true,
            "backorders": 0,
            "use_config_notify_stock_qty": true,
            "notify_stock_qty": 1,
            "use_config_qty_increments": true,
            "qty_increments": 0,
            "use_config_enable_qty_inc": true,
            "enable_qty_increments": false,
            "use_config_manage_stock": true,
            "manage_stock": true,
            "low_stock_date": "2020-09-11 18:00:19",
            "is_decimal_divided": false,
            "stock_status_changed_auto": 1
        }
    },
    "product_links": [],
    "options": [
        {
            "product_sku": "5f5bb1cfe1b84f25b02e44c2",
            "option_id": 10,
            "title": "Prices",
            "type": "radio",
            "sort_order": 1,
            "is_require": true,
            "max_characters": 0,
            "image_size_x": 0,
            "image_size_y": 0,
            "values": [
                {
                    "title": "2048 × 1080",
                    "sort_order": 1,
                    "price": 40,
                    "price_type": "fixed",
                    "sku": "2K",
                    "option_type_id": 28
                },
                {
                    "title": "7680 × 4320",
                    "sort_order": 2,
                    "price": 60,
                    "price_type": "fixed",
                    "sku": "4K",
                    "option_type_id": 29
                },
                {
                    "title": "7680x4320",
                    "sort_order": 3,
                    "price": 75,
                    "price_type": "fixed",
                    "sku": "8K",
                    "option_type_id": 30
                }
            ]
        }
    ],
    "media_gallery_entries": [],
    "tier_prices": [],
    "custom_attributes": [
        {
            "attribute_code": "options_container",
            "value": "container2"
        },
        {
            "attribute_code": "url_key",
            "value": "5f5bb1cfe1b84f25b02e44c2"
        },
        {
            "attribute_code": "msrp_display_actual_price_type",
            "value": "0"
        },
        {
            "attribute_code": "gift_message_available",
            "value": "0"
        },
        {
            "attribute_code": "required_options",
            "value": "1"
        },
        {
            "attribute_code": "has_options",
            "value": "1"
        },
        {
            "attribute_code": "tax_class_id",
            "value": "2"
        },
        {
            "attribute_code": "category_ids",
            "value": []
        },
        {
            "attribute_code": "description",
            "value": "<p>jogo"
        }
    ]
}


[2020-09-11 19:08:56] main.CRITICAL: if tag was never closed [] []
[2020-09-11 19:08:56] main.CRITICAL: if tag was never closed [] []


[2020-09-11 19:10:09] main.DEBUG: cache_invalidate:  {"method":"PUT","url":"http://localhost/rest/V1/products/5f5bb1cfe1b84f25b02e44c2","invalidateInfo":{"tags":["cat_p_10"],"mode":"matchingAnyTag"}} []
[2020-09-11 19:10:09] main.DEBUG: cache_invalidate:  {"method":"PUT","url":"http://localhost/rest/V1/products/5f5bb1cfe1b84f25b02e44c2","invalidateInfo":{"tags":["cat_p_10"],"mode":"matchingAnyTag"}} []

