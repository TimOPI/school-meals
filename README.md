# school-meals
Application for free/reduced [school meals](http://www.fns.usda.gov/school-meals/child-nutrition-programs).

## Developing

1. Install [Node.js](https://nodejs.org)
2. `npm install`
3. `npm start`

Should you encounter an error with `uswds` and `politespace`, it might be necessary to run `npm update` in the `node_modules/uswds` directory. IE:

1. `cd node_modules/uswds`
2. `npm update`

To run eslint:

1. `cd node_modules/.bin`
2. `eslint --fix --ext .js --ext .jsx "[complete file path to /src]"`

To update translation file copy the altered file from `./translations` to `./docs/translations`

## Roadmap
```
Welcome.jsx
BeforeYouBegin.jsx
Attestation.jsx
Students.jsx
AssistancePrograms.jsx
Foster.jsx
OtherPrograms.jsx
IncomeElection.jsx
OtherChildren.jsx
ChildIncome.jsx
└── ChildIncomeSlide.jsx
Adults.jsx
AdultIncomeOverview.jsx
├── MilitaryIncome.jsx
├── PublicAssistanceIncome.jsx
├── SpousalIncome.jsx
├── UnemploymentIncome.jsx
├── RetirementIncome.jsx
└── OtherIncome.jsx
Signature.jsx
Contact.jsx
Demographics.jsx
LegalStatements.jsx
Summary.jsx
ThankYou.jsx
```

## Public domain

As stated in [CONTRIBUTING](CONTRIBUTING.md):

> With the exceptions noted in [LICENSE](LICENSE.md), this project is in the worldwide public domain (in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/)).

> All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.
