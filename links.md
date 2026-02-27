# Links & Emails Found in Documentation

All URLs and email addresses discovered across the Transcrypts SDK documentation, organized by category.

---

## API & Platform URLs

| URL | Found In | Context |
|-----|----------|---------|
| `https://prod.transcrypts.com/v1/` | `overview/introduction.mdx`, `user-flow-endpoints/bridge-token-create.mdx`, `user-flow-endpoints/users-create.mdx`, `user-flow-endpoints/users-update.mdx`, `user-flow-endpoints/users-list.mdx`, `user-flow-endpoints/users-read.mdx`, `user-flow-endpoints/users-delete.mdx`, `user-flow-endpoints/providers-list.mdx`, `user-flow-endpoints/providers-detail.mdx`, `user-flow-endpoints/company-autocomplete-search.mdx`, `user-flow-endpoints/company-info.mdx`, `user-flow-endpoints/company-mapping.mdx`, `document-processing/collections-list.mdx`, `document-processing/document-collections.mdx`, `orders/orders-read.mdx`, `orders/orders-create.mdx`, `orders/orders-list-lookup.mdx`, `orders/orders-update.mdx`, `orders/orders-cancel.mdx`, `orders/orders-invoice.mdx`, `orders/orders-refresh.mdx`, `orders/orders-certifications.mdx`, `orders/orders-add-employer.mdx`, `orders/orders-events.mdx` | Base URL for all Transcrypts API requests; environment is determined by Access secret, not the URL. |
| `https://prod.transcrypts.com/v1/users/` | `user-flow-endpoints/users-create.mdx`, `user-flow-endpoints/users-list.mdx` | API endpoint for creating and listing users. |
| `https://prod.transcrypts.com/v1/users/{user_id}/` | `user-flow-endpoints/users-read.mdx`, `user-flow-endpoints/users-update.mdx`, `user-flow-endpoints/users-delete.mdx` | API endpoint for reading, updating, and deleting a specific user. |
| `https://prod.transcrypts.com/v1/users/{user_id}/tokens/` | `user-flow-endpoints/bridge-token-create.mdx` | API endpoint for generating bridge tokens to launch the Transcrypts Bridge UI. |
| `https://prod.transcrypts.com/v1/providers/` | `user-flow-endpoints/providers-list.mdx` | API endpoint for listing all supported payroll providers. |
| `https://prod.transcrypts.com/v1/providers/{id}/` | `user-flow-endpoints/providers-detail.mdx` | API endpoint for retrieving details of a specific provider. |
| `https://prod.transcrypts.com/v1/companies/` | `user-flow-endpoints/company-autocomplete-search.mdx` | API endpoint for company autocomplete search. |
| `https://prod.transcrypts.com/v1/companies/{company_mapping_id}/` | `user-flow-endpoints/company-info.mdx` | API endpoint for retrieving detailed company information. |
| `https://prod.transcrypts.com/v1/company-mappings-search/` | `user-flow-endpoints/company-mapping.mdx` | API endpoint for searching company mappings by name or domain. |
| `https://prod.transcrypts.com/v1/documents/collections/` | `document-processing/collections-list.mdx`, `document-processing/document-collections.mdx` | API endpoint for listing and managing document collections. |
| `https://prod.transcrypts.com/v1/documents/collections/?page=2` | `document-processing/collections-list.mdx` | Example of paginated document collections request. |
| `https://prod.transcrypts.com/v1/orders/` | `orders/orders-create.mdx`, `orders/orders-list-lookup.mdx` | API endpoint for creating and listing verification orders. |
| `https://prod.transcrypts.com/v1/orders/{id}/` | `orders/orders-read.mdx`, `orders/orders-update.mdx` | API endpoint for reading and updating a specific order. |
| `https://prod.transcrypts.com/v1/orders/{id}/cancel/` | `orders/orders-cancel.mdx` | API endpoint for canceling a verification order. |
| `https://prod.transcrypts.com/v1/orders/{id}/certifications/` | `orders/orders-certifications.mdx` | API endpoint for retrieving order certifications. |
| `https://prod.transcrypts.com/v1/orders/{id}/employers/` | `orders/orders-add-employer.mdx` | API endpoint for adding employers to an order. |
| `https://prod.transcrypts.com/v1/orders/{id}/events/` | `orders/orders-events.mdx` | API endpoint for listing events associated with an order. |
| `https://prod.transcrypts.com/v1/orders/{id}/invoice/` | `orders/orders-invoice.mdx` | API endpoint for retrieving the invoice for an order. |
| `https://prod.transcrypts.com/v1/orders/lookup/` | `orders/orders-list-lookup.mdx` | API endpoint for looking up orders by reference number. |

---

## Dashboard URLs

| URL | Found In | Context |
|-----|----------|---------|
| `https://app.transcrypts.com` | `docs.json` | Link to the Transcrypts Dashboard in the site navigation. |
| `https://app.transcrypts.com/app/development/keys` | `document-processing/collections-create.mdx` | Link to obtain API credentials from the Dashboard. |
| `https://app.transcrypts.com/app/development/keys` | `overview/api-keys-rotation.mdx` | Link to generate fresh API keys during key rotation. |

---

## External Service & Resource URLs

| URL | Found In | Context |
|-----|----------|---------|
| `https://www.postman.com/downloads/` | `overview/postman-collection.mdx` | Link to download Postman for importing the Transcrypts API collection. |
| `https://www.npmjs.com/package/transcrypts` | `docs.json` | Link to the Transcrypts npm package in the site navigation. |
| `https://mintlify.com/docs.json` | `docs.json` | JSON schema reference for the Mintlify documentation configuration. |

---

## Example / Placeholder URLs

| URL | Found In | Context |
|-----|----------|---------|
| `http://example.com/` | `user-flow-endpoints/webhook-endpoints.mdx`, `user-flow-endpoints/webhooks-read.mdx` | Placeholder webhook URL used in API request/response examples. |
| `https://example.com/webhooks/transcrypts` | `user-flow-endpoints/webhook-requests-list.mdx`, `user-flow-endpoints/webhook-endpoints.mdx` | Example webhook endpoint URL in webhook configuration examples. |
| `https://example.com/files/file123xyz789.pdf` | `document-processing/collections-file-retrieve.mdx` | Example pre-signed file URL in document collection file retrieval response. |

---

## S3 / CDN Asset URLs

| URL | Found In | Context |
|-----|----------|---------|
| `https://citadelid-resources.s3-us-west-2.amazonaws.com/facebook.png` | `user-flow-endpoints/company-autocomplete-search.mdx`, `user-flow-endpoints/company-mapping.mdx`, `user-flow-endpoints/companies-and-data-providers.mdx` | Company logo URL returned in API response examples (legacy S3 bucket). |
| `https://citadelid-resources.s3.us-west-2.amazonaws.com/doc_upload/w2.pdf` | `document-processing/uploaded-documents.mdx` | Sample uploaded document file URL in API response example (legacy S3 bucket). |

---

## Email Addresses

| Email | Found In | Context |
|-------|----------|---------|
| `support@transcrypts.com` | `overview/introduction.mdx` | Official support contact for inquiries and requesting rate limit increases. |
| `john.doe@example.com` | `user-flow-endpoints/users.mdx`, `user-flow-endpoints/users-create.mdx`, `user-flow-endpoints/users-update.mdx`, `user-flow-endpoints/users-list.mdx`, `user-flow-endpoints/users-read.mdx`, `financial-accounts/income-report.mdx`, `user-reports/income-insights-reports.mdx` | Placeholder email used in user object and report API response examples. |
| `john.doe@gmail.com` | `income-and-employment/identity.mdx` | Placeholder email in identity verification API response example. |

---

## mTLS Domain References

| Domain | Found In | Context |
|--------|----------|---------|
| `api-mtls.transcrypts.com` | `platform-management/advanced-security-and-mtls.mdx` | mTLS production endpoint for mutual TLS API connections. |
| `mtls-prod.transcrypts.com` | `platform-management/advanced-security-and-mtls.mdx` | Domain for Transcrypts's public certificate used in webhook mTLS authentication. |

---

## SVG Namespace URLs (Non-browsable)

| URL | Found In | Context |
|-----|----------|---------|
| `http://www.w3.org/2000/svg` | `favicon.svg`, `logo/dark.svg`, `logo/light.svg` | Standard XML namespace declaration in SVG files. |

