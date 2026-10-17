# Le New Black — API Postman Collections

Official Postman collections for the [Le New Black](https://www.lenewblack.com) APIs.
Use these collections to explore, test and integrate LNB APIs directly from Postman.

> **Developer Portal:** [developer.lenewblack.com](https://developer.lenewblack.com)

---

## Available Collections

| Collection | Description | Status |
|---|---|---|
| **Wholesale v2 API** | Full access to your wholesale data — orders, products, buyers, catalogues, etc. | ✅ Available |
| **Wholesale v1 API** | Previous version of the Wholesale API — products, collections, inventory, orders, retailers, etc. | ✅ Available |
| **Retail API** | Read access for retailers — orders, appointments and selections | ✅ Available |
| More coming soon... | Additional LNB APIs will be added over time | 🔜 |

---

## Prerequisites

- [Postman](https://www.postman.com/downloads/) installed (desktop app recommended)
- A valid **Le New Black account**
- A **Client ID** and **Client Secret** obtained from [Le New Black](https://www.lenewblack.com)

---

## Getting Started

### 1. Download Postman

Download and install the Postman desktop app from [postman.com/downloads](https://www.postman.com/downloads/).

### 2. Import the Collection

1. Download the collection JSON file for the API you want to use (e.g. `wholesale-v2.json`)
2. Open Postman
3. Click **Import** (top left)
4. Drag and drop the JSON file, or browse to select it
5. The collection will appear in your left sidebar

### 3. Set Up Your Environment

1. In Postman, click **Environments** in the left sidebar
2. Create a new environment (e.g. `LNB Production`)
3. Add the following variables:

| Variable | Description | Example                                 |
|---|---|-----------------------------------------|
| `base_url` | LNB API base URL | `https://www.lenewblack.com/apis/<api>` |
| `client_id` | Your Client ID from the Developer Portal | `your-client-id`                        |
| `client_secret` | Your Client Secret from the Developer Portal | `your-client-secret`                    |
| `access_token` | Populated automatically after authentication | *(leave empty)*                         |

4. Save the environment and select it in the top-right dropdown

### 4. Authenticate

Run the **Authentication > Get Access Token** request in the collection.
This will automatically populate your `access_token` environment variable, which is used by all subsequent requests.

### 5. Make Your First Request

You're all set! Browse the collection and start making requests.
Each request includes a description, required parameters, and example responses.

---

## What You Can Do

With a valid LNB account and API credentials, these collections give you access to **read and write operations on your Le New Black data**, including:

- 📦 **Products** — list, create, update your product catalogue
- 🛒 **Orders** — retrieve and manage wholesale orders
- 👥 **Buyers** — access your buyer directory
- 📁 **Catalogues** — manage and share your collections
- And more, depending on your account permissions

For the full API reference, visit the [LNB Developer Portal](https://developer.lenewblack.com).

---

## Getting Your API Credentials

1. Log in to your Le New Black account: [Le New Black](https://www.lenewblack.com) or your private showroom URL
2. Navigate to **Settings** to get your credentials
3. Copy your **Client ID** and **Client Secret**
4. Add them to your Postman environment as described above

---

## Reporting Issues

If you encounter a bug or have a suggestion, please [open an issue](https://github.com/lenewblack/apis-postman-collections/issues) on this repository.

---

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for a history of changes to these collections.
