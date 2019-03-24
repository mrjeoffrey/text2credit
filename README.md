# xp

## For Experian Text4Credit
[Design](https://jeoffreybatangan.design/experian-bis-text4credit)

## The vision for the product
1. Customizable white-label B2C template that can be configured client brand and requirements.
2. Structure the Sass to easily add new clients without affecting shared components. Also to be able to add new products to this template.

## Goals with code samples
* Redesign and develop landing page to incorporate bootstrap sass file structure. [code sample](https://github.com/mrjeoffrey/xp/tree/master/template/clients/loanme/sass)
* Modify bootstrap v.4.3.2 node-module file structure to import specific sass for angular components. [code sample](https://github.com/mrjeoffrey/xp/blob/master/template/clients/loanme/styles.scss)
* Utilize bootstrap v.4.3.2 variables and added custom client specific variables using the bootstrap naming convention. [code sample](https://github.com/mrjeoffrey/xp/blob/master/template/clients/loanme/sass/variables.scss)
* Organized client specific components shared in Angular. Separated from bootstrap node_modules and imported per client need. [code sample](https://github.com/mrjeoffrey/xp/tree/master/template/sass-global/components)
* Included a product add-on category to add new products without interrupting the basic prequalification flow. [code sample](https://github.com/mrjeoffrey/xp/tree/master/template/sass-global/addons)
