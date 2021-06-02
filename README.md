< ENHENCER - PURCHASE >

This is the template for Enhencer's GTM tag for "Purchase" event.

The tag has to fire after the visitor completes a purchase successfully. Only argument the list of the products that has been purchased. Each product is a JSON object and has 3 attributes: ID, quantity and unit price. An example list for the argument:

[{
  ID: 'mg-1162',
  quantity: 1,
  price: 59
},
{
  ID: 'ay-8315',
  quantity: 2,
  price: 25
}]


For more info, visit https://enhencer.com/resources