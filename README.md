# Contract terms

Adds a contract terms object to the tender and lot objects, to describe the terms governing the future contract.

## Guidance

## Legal context

In the European Union, this extension's fields correspond to [eForms BG-711 (Contract Terms)](https://github.com/eForms/eForms), although not all the fields have been implemented yet. See [OCDS for the European Union](http://standard.open-contracting.org/profiles/eu/master/en/) for the correspondences to Tenders Electronic Daily (TED).

## Example


```json

{
  "tender": {
    "contractTerms": {
      "hasElectronicPayment": true,
      "hasElectronicOrdering": false,
      "electronicInvoicingPolicy": "required",
      "hasReservedExecution": false,
      "termsPerformance": "A set of KPIs will be developed for this contract and the successful contractor will be measured against these for the duration of the contract. Please refer to briefing document for further details."
    }
  }
}

```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.
