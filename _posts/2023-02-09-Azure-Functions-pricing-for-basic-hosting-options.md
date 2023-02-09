Azure Functions are the event-driven, serverless, Function as a Service
(FaaS) offer from Microsoft on the Azure cloud.

The three basic, most popular, hosting options for Azure Functions, have
different pricing models. Prices are for the UK South region on 2022-02-09.

# Consumption

Per second usage and number of executions.

Meters:
- Execution Time: this is actually both time and memory, time is affected
by CPU utilization: **£0.000013 per GB-s**
- Total Executions: how many times all Functions are triggered: **£0.162
per million executions**

Free: 400,000 GB-s and 1 million executions

# Premium

Per second usage. 1 year and 3 years savings plans available (saves about
17%).

Meters:
- vCPU duration: **£109.29 vCPU/month**
- Memory duration: **£7.798 GB/month**

# Dedicated (App Service plan)

Regular pricing for App Service. 5 tiers (for both Linux and Windows).
Linux options are cheaper. Windows options gives 1 more: Shared between
different tenants. For top options there are savings plans available.

- Free (play around): £0/month
- Shared (dev, Windows only): £7.680/month
- Basic (dev, test): £10.634/month
- Standard (production): £59.074/month
- Premium: £66.753/month
- Isolated: £224.480/month

To choose the best one, all the features should be compared.

---

Read more:
- [Azure Functions Pricing](
https://azure.microsoft.com/en-us/pricing/details/functions/)
- [Azure App Service Pricing](
https://azure.microsoft.com/en-us/pricing/details/app-service/linux/)
- [Azure Calculator functions](
https://azure.microsoft.com/en-us/pricing/calculator/?service=functions)
- [Azure Calculator app services](
https://azure.microsoft.com/en-us/pricing/calculator/?service=app-service)

Paweł
