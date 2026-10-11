# OpenLabel for Hyvä (bundle)

One Composer package that installs [OpenLabel](https://github.com/iranimij/openlabel), product labels for Magento 2
and Hyvä, with everything a Hyvä shop needs:

| Package | Purpose |
|---|---|
| [`iranimij/openlabel`](https://github.com/iranimij/openlabel) | Core: labels, designs, conditions, indexer, admin, GraphQL, CLI |
| [`iranimij/openlabel-hyva`](https://github.com/iranimij/openlabel-hyva) | Hyvä render package |
| [`iranimij/module-base`](https://github.com/iranimij/module-base) | Shared config tab. No license checks, no phone-home. |

```bash
composer require iranimij/openlabel-hyva-bundle
bin/magento setup:upgrade
bin/magento openlabel:reindex
```

Installation, quick start and documentation: [OpenLabel README](https://github.com/iranimij/openlabel#readme).
Issues go to [iranimij/openlabel](https://github.com/iranimij/openlabel/issues).

OpenLabel is an independent open-source project, not affiliated with Hyvä Themes B.V. or Adobe Inc. MIT licence.
