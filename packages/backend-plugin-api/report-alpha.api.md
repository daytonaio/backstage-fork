## API Report File for "@backstage/backend-plugin-api"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { BackendFeature } from '@backstage/backend-plugin-api';
import { ServiceRef } from '@backstage/backend-plugin-api';

// @alpha (undocumented)
export interface FeatureDiscoveryService {
  // (undocumented)
  getBackendFeatures(): Promise<{
    features: Array<BackendFeature>;
  }>;
}

// @alpha @deprecated
export const featureDiscoveryServiceRef: ServiceRef<
  FeatureDiscoveryService,
  'root',
  'singleton'
>;

// Warnings were encountered during analysis:
//
// src/alpha.d.ts:3:1 - (ae-undocumented) Missing documentation for "FeatureDiscoveryService".
// src/alpha.d.ts:4:5 - (ae-undocumented) Missing documentation for "getBackendFeatures".

// (No @packageDocumentation comment for this package)
```