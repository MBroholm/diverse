# Third-party application access policy i Github-organisationer
Denne guide beskriver, hvordan man kan give tredjepartsapplikationer adgang til en GitHub-organisation's data.

Når man opretter en organisation på GitHub følger de tredjepartapplikationer, som man har giv tilladelse til at tilgå sin personlige konto, ikke automatisk med. Ønsker man at gøre brug af tredjepartsapplikationer, som f.eks. IntelliJ, i organisationen, kræver det derfor følgende:

Fra organisations forside, gå til 'Settings'.

<img src="assets/01-go-to-organization-settings.png" alt="Go to organization settings" width="900">

Lokaliser og gå til 'OAuth app policy' i venstre side.

<img src="assets/02-go-to-oauth-app-policy.png" alt="Go to OAuth app policy" width="900">

Herfra er der to muligheder. I kan,
1. fjerne alle restriktioner, hvilket giver adgang for alle trejdepartsapllikationer som organisationens medlemmer har givet adgang til deres egne konti.
2. giv specifikt adgang til de applikationer, der skal kunne tilgå organisationens data.

## Option 1
Tryk 'Remove restrictions'. 

<img src="assets/11-remove-restrictions.png" alt="Remove restrictions" width="900">

Siden prompter jer til at bekræfte valget. Bekræft hvis I ønsker at fortsætte.

<img src="assets/12-confirm-removal.png" alt="Confirm removal" width="900">

Restriktionerne er herefter fjernet.

<img src="assets/13-restrictions-removed.png" alt="Restrictions removed" width="900">

## Option 2
Følg linket til jeres egne autoriserede tredjepartsapplikationer.

<img src="assets/21-go-to-your-authorized-applications.png" alt="Go to your authorized applications" width="900">

Lokaliser og gå til den applikation I ønsker at autorisere.

<img src="assets/22-locate-application.png" alt="Locate application" width="900">

Tryk 'Grant' ud for den den organisation I ønsker at give adgang til.

<img src="assets/23-grant-app-access.png" alt="Grant application access" width="900">


