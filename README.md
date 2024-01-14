# Workshop: Configuration as Code med IntuneCD

## Oppgave 1A: Lag et GitHub repository

## Oppgave 1B: Opprett en App Registration i DEV og PROD tenant

Opprett en App registration i DEV og PROD tenant med disse tilgangene:

> Legg til som Microsoft Graph Application Permissions

- DeviceManagementApps.ReadWrite.All
- DeviceManagementConfiguration.ReadWrite.All
- DeviceManagementServiceConfig.ReadWrite.All
- DeviceManagementManagedDevices.ReadWrite.All
- Group.Read.All
- Policy.Read.All
- Policy.ReadWrite.ConditionalAccess
- Application.Read.All

> Ta vare på følgende verdier fra App Registrations:
- Client Secret
- Application (client) ID
- Directory (tenant) ID

## Oppgave 2A: Opprett en workflow som tar backup av DEV miljøet og pusher til en egen branch

> Test at den virker med å gjøre endringer i en policy eller lage nye policier i Intune DEV tenant

## Oppgave 2B: Opprett en workflow som pusher konfigurasjon fra repoet til PROD

> Test at den virker ved at policier blir replikert fra DEV til PROD
