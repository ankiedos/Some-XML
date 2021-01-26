# Some-XML
My DTDs

# List of DTDs
## Pricelist
`<!DOCTYPE pricelist PUBLIC "https://github.com/ankiedos/Some-XML/blob/main/pricelistDTD.dtd">`
1. Tags

- Root
:	`<pricelist>`, Type: `product*`

- Product
:	`<product>`, Type: `name,price,quantity,description`,
	- Attributes: `workinghours`, Type: `CDATA #IMPLIED`

- Name
:	`<name>`, Type: `PCDATA`

- Price
:	`<price>`, Type: `PCDATA`

- Quantity
:	`<quantity>`, Type: `PCDATA`

- Description
:	`<description>`, Type: `PCDATA`
