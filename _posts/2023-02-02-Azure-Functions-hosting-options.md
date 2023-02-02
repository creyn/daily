Azure Functions are the event-driven, serverless, Function as a Service
(FaaS) offer from Microsoft on the Azure cloud.

There are few options for hosting Functions, each has its own features,
limits and costs with different pricing models.

# Basic hosting options

## Consumption

Default plan. Has auto-scale and charges for resources usage while running

## Premium

Has the same scaling as **Consumption** and pre-warmed instances (so no
cold-start), more powerful machines and networking features. Allows for
higher limits and custom Linux image.

Better than **Consumption** for high execution scenarios (**no charges for
Execution Count**).

## Dedicated (App Service plan)

Can be used when there are underutilized App Service Plans already. Charges
as regular App Service Plans. Best for long running scenarios.

# Advanced hosting options

Give more control

## ASE (App Service Environment)

Fully isolated, secure networking and high scale and memory usage

## Kubernetes (direct or Azure Arc)

Fully isolated, on top of the Kubernetes platform. Best for custom hardware
requirements and hybrid, multi-cloud solutions. But does not auto-scale
like the basic options.

## IoT Edge

There is an option to run Functions in the IoT Edge device. This is free.

But there is an IoT Hub and other modules that have their own costs.

## Azure Stack

There is also an option to run the entire Azure stack on your local on-prem
or edge devices., offline devices. This also supports Functions.

---

You can learn more:
- [Azure Functions Hosting Options](
https://learn.microsoft.com/en-us/azure/azure-functions/functions-scale)
- [Deploy Functions as IoT Edge modules](
https://learn.microsoft.com/en-us/azure/iot-edge/tutorial-deploy-function)
- [App Service and Functions on Azure Stack](
https://azure.microsoft.com/en-us/blog/general-availability-of-app-service-and-functions-on-azure-stack
)


Paweł
