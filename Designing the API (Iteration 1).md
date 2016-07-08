# Designing the API (Iteration 1)
## Authentication
## Authorization
## IP Range Restrictions (with Logging/Alerting to Librato if rate gets too high)
## Rate Limiting
## Paging Data Queries
## Shaping Data (Mobile vs Web UI)
	^^^ Include the separation of the domain view from the api view via automapper or other means
## Metrics (Count and Call Timing)
## Metric Alerts (Count and Call Timing)
	^^^ Segway into setting up a Slack channel to receive alerts via Librato
## Error Handling
## Exception Management (Exceptionless)
## Exception Alerts
	^^ Also integrate via Slack
## Logging (Exceptionless)
## Identifying Bounded Contexts
### Api Gateway (From microservices book)
### Security Service (Authentication/Authorization/Ip Restrictions/etc)