# Workshop: Configuration as Code med IntuneCD

Under finner dere oppgavene til workshop. Oppgavene viser ikke mye, så bruk alle ressurser dere kan for å løse dem.

Mye av informasjonen dere trenger ligger i IntuneCD repo: https://github.com/almenscorner/IntuneCD

En mulig løsning av oppgaven befinner seg i dette repoet. Aller helst forsøk å løse oppgavene uten å se på løsning i dette repo.

## Oppgave 1A: Lag et GitHub repository

## Oppgave 1B: Opprett en App Registration i DEV og PROD tenant

Opprett en App registration i DEV og PROD tenant med disse tilgangene:

> Legg til som Microsoft Graph Application Permissions

| Application Permission |
| --- |
| DeviceManagementApps.ReadWrite.All |
| DeviceManagementConfiguration.ReadWrite.All |
| DeviceManagementServiceConfig.ReadWrite.All | 
| DeviceManagementManagedDevices.ReadWrite.All |
| Group.Read.All | 
| Policy.Read.All | 
| Policy.ReadWrite.ConditionalAccess | 
| Application.Read.All | 


#### Ta vare på følgende verdier fra App Registrations:
- Client Secret
- Application (client) ID
- Directory (tenant) ID

## Oppgave 2A: Opprett en workflow som tar backup av DEV miljøet og pusher til en egen branch

> Test at den virker med å gjøre endringer i en policy eller lage nye policier i Intune DEV tenant

## Oppgave 2B: Opprett en workflow som pusher konfigurasjon fra repoet til PROD

> Test at den virker ved at policier blir replikert fra DEV til PROD
