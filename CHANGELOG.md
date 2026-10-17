# Changelog

All notable changes to the LNB API Postman Collections will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [Unreleased]

## [1.1.0] — 2026-10-17

### Changed
- **Wholesale v2 API** collection updated from API version 2.20.0 to 2.31.0
- The collection file is now an OpenAPI 3.1 document (previously Swagger 2.0); import it into Postman the same way

### Added
- Lines: `GET /lines`, `POST /lines`, `POST /multi/lines`
- Payment terms: `GET /payment_terms`, `POST /payment_terms`, `GET /payment_terms/{code}`
- Retailer lines: `GET /retailers_lines`, `POST /retailers_lines`, `POST /multi/retailers_lines`
- Retailer segments: `GET /retailers_segments`, `POST /multi/retailers_segments`
- Retailer additional reps: `GET /retailers_additional_reps`, `POST /multi/retailers_additional_reps`
- Rate limiting description and response headers

## [1.0.0] — 2026-03-23

### Added
- Initial release of the **Wholesale v2 API** Postman collection
- Authentication flow (Client ID / Client Secret → Access Token)
- Full coverage of read and write operations for products, orders, buyers, and catalogues
