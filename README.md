# Canadian Municipalities

```typescript
interface municipality {
    name: string;
    id: {
      dguid: string; // See https://www150.statcan.gc.ca/n1/pub/92f0138m/92f0138m2019001-eng.htm for details
      vintage: string;
      type: "A";
      schema: "2021";
      geouid: string; // 7 digit Geographic Unique Identifier
      pruid: string; // 2 digit province code
      cduid: string; // 2 digit census division code
      csduid: string; // 3 digit census subdivision code
    };
    province: {
      abbr: "AB" | "BC" | "MB" | "NB" | "NL" | "NS" | "ON" | "PE" | "QC" | "SK" | "NT" | "NU" | "YT";
      en: "Alberta" | "British Columbia" | "Manitoba" | "New Brunswick" | "Newfoundland and Labrador" | "Nova Scotia" | "Ontario" | "Prince Edward Island" | "Quebec" | "Saskatchewan" | "Northwest Territories" | "Nunavut" | "Yukon";
      fr: "Alberta" | "Colombie-Britannique" | "Manitoba" | "Nouveau-Brunswick" | "Terre-Neuve-et-Labrador" | "Nouvelle-Écosse" | "Ontario" | "Île-du-Prince-Édouard" | "Québec" | "Saskatchewan" | "Territoires du Nord-Ouest" | "Nunavut" | "Yukon";
    };
  }
```
