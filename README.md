Privacy Policy for Fetch Deals

1. Purpose

	"Fetch Deals" is a personal learning project running locally on a single user's machine.

	Its sole purpose is to assist with retrieving current listings information in order to identify items selling below market value.

2. Data Collected

	The application only requests publicly available listing metadata, including:
	- Item titles, prices, and shipping costs
	- Condition and seller feedback scores
	- Public listing URLs and item IDs

	**No personally identifiable information, payment details, private messages, or account credentials are collected, stored, or transmitted.**

3. Data Usage & Processing

	All fetched data is processed exclusively on the user’s local machine. It is used solely for real-time price comparison. Data is never sold, shared, or sent to third-party servers, 	cloud services, or analytics platforms.

4. Storage & Retention

	Fetched data is temporarily stored in a local SQLite database on the user’s personal machine. All records are automatically purged after 30 days. No backups, cloud sync, or remote 	storage is performed.

5. Security & Transmission

	The application communicates only with eBay’s official APIs using OAuth 2.0 authentication. API keys are stored locally in a `.env` file and never transmitted. The tool runs entirely 	offline after data retrieval and does not collect IP addresses, device identifiers, or usage telemetry.

6. User Control

	As a desktop application, the user retains full control over their data. The local database can be manually deleted at any time. No user accounts or external services are required.

7. Contact
	
	For questions regarding this policy or data handling practices, contact: andy@pyle.org.uk
