## Deployment
`arweave deploy www/index.html --key-file keychain.json`

### Checkout the multiple iterations

#### Iteration #1
- https://arweave.net/vAbXzjIojYgU_jma-LThvTyy1ceNdfc0bJhlKTdlhEw

Here we try to package the index.html with all the dependencies. The total package was more than 2MB so we firstly decided to deploy the plain `index.html`.

#### Iteration #2
- https://arweave.net/wgxjxPhttutyhZH2-Fw-GBft3Hjvqxm9bl8_t8xVVbE

 Here we included the styles inline and referenced the moneybutton library with an external link.


#### Iteration #3
- https://arweave.net/afqyL3YTn0sHO88m1ksSmLoSBMXCGopILn4-V-zQPLU

External files do not seem to be able to load (if they are js files) because they are block by the CORB policy. In this iteration we included the moneybutton code inline in the HTML.# kitten-adoption-rescue-society
