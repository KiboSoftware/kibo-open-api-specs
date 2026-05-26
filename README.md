# Kibo Open API Specs

This repository contains OpenAPI specifications for the **Kibo Composable Commerce Platform**, enabling developers to integrate with Kibo's APIs for e-commerce, catalog management, order fulfillment, customer management, and more.

## Overview

Kibo provides a comprehensive set of REST APIs that power modern composable commerce operations. All OpenAPI specifications are published on the Kibo Documentation site and can be accessed programmatically for code generation, SDK development, and integration planning.

**Documentation:** [https://docs.kibocommerce.com](https://docs.kibocommerce.com)

---

## API Categories & OpenAPI Specifications

### Getting Started
- **Getting Started with Your API** – Learn how to authenticate and make your first API calls to the Kibo platform.
  - Docs: https://docs.kibocommerce.com/api-overviews/getting-started.md

---

### Application Development
- **App Development** – Manage installed applications, authentication tickets, and application packages for your tenant.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_appdevelopement_overview.json

---

### Catalog Management

#### Catalog Administration
- **Catalog Administration** – Configure catalogs, products, categories, discounts, price lists, and search settings for your storefront.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_catalog_admin_overview.json

#### Catalog Storefront
- **Catalog Storefront** – Retrieve product categories, pricing, and search results for the shopper-facing storefront experience.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_catalog_storefront_overview.json

---

### Commerce Operations

- **Commerce** – Manage shopping carts, checkouts, orders, returns, wishlists, and B2B quotes for your commerce operations.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_commerce_overview.json

---

### Content Management

- **Content** – Organize site content into document hierarchies and manage publishing workflows for your storefront.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_content_overview.json

---

### Customer Management

- **Customer** – Manage customer accounts, contacts, segments, credits, B2B hierarchies, and authentication for shoppers.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_customer_overview.json

---

### Data & Entities

- **Entities** – Store and query custom JSON data with indexed properties for large, filterable datasets.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_entities_overview.json

---

### Events & Subscriptions

- **Events** – Subscribe to push notifications for CRUD operations and query event history for your applications.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_event_overview.json

---

### Fulfillment & Logistics

- **Fulfillment** – Manage shipments, packages, pick waves, and manifests throughout the order fulfillment workflow.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_fulfillment_overview.json

---

### Inventory Management

- **Inventory** – Retrieve and adjust inventory levels, manage allocations, and segment stock with tags across fulfillment locations.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_inventory_overview.json

- **Reservations** – Create and manage inventory reservations for items, quantities, and fulfillment methods.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_reservation_overview.json

---

### Location Management

#### Location Administration
- **Location Administration** – Create and manage fulfillment locations, location groups, and location types for inventory and pickup.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_location_admin_overview.json

#### Location Storefront
- **Location Storefront** – Retrieve fulfillment location details for the shopper-facing storefront experience.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_location_storefront_overview.json

---

### Order Management

- **Order Routing** – Configure routing filters, location groups, and rules to determine optimal fulfillers for orders.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_orderrouting_overview.json

---

### Import/Export

- **Import/Export** – Bulk import and export Kibo resources using CSV files for efficient data management.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_importexport_overview.json

---

### Settings & Configuration

- **Site Settings** – Configure site, checkout, payment, and application settings for your tenant and storefronts.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_settings_overview.json

---

### Subscriptions & Recurring Orders

- **Subscriptions** – Manage recurring order subscriptions, including items, frequencies, and subscription lifecycle.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_subscription_overview.json

---

### Compliance & Data Management

- **GDPR** – Handle personal data requests and compliance with GDPR regulations.
  - OpenAPI: https://docs.kibocommerce.com/openapi/openapi_gdpr.json

---

## Using the OpenAPI Specifications

### Download & Access

All OpenAPI specifications are available in JSON format from the URLs listed above. You can:

1. **Download directly** – Use the JSON download links to get the specification files
2. **Integrate with tools** – Use specifications with Swagger UI, Postman, OpenAPI generators, or IDE plugins
3. **Generate SDKs** – Use OpenAPI generator tools to create client SDKs in your language of choice
4. **API Documentation** – Import specs into documentation platforms for interactive API references

### Example: Using the Specifications

```bash
# Download a specification
curl -o catalog_admin.json https://docs.kibocommerce.com/openapi/openapi_catalog_admin_overview.json

# Generate a TypeScript client (using openapi-generator-cli)
openapi-generator-cli generate \
  -i catalog_admin.json \
  -g typescript-fetch \
  -o ./generated-client
```

---

## Additional Resources

- **API Documentation:** https://docs.kibocommerce.com
- **SDKs & Toolkits:** https://docs.kibocommerce.com/api-overviews/sdks-and-toolkits.md
- **Authentication:** https://docs.kibocommerce.com/api-overviews/getting-started.md

---

## Contributing

To report issues with the OpenAPI specifications or suggest improvements, please contact Kibo support or submit feedback through the documentation site.

---

## License

These OpenAPI specifications are provided by Kibo Software as part of the Kibo Composable Commerce Platform documentation.
