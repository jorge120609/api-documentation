Zettle Go API Glossary
=============

<!-- Add the corresponding section if any term start with the heading letter. Add numbers before letters if there are glossary items that start with numbers.-->
<!-- Order: numbers, then A–Z. For example, 3GPP is placed before glossary items started with letter a. --<
<!-- Write full sentences when explaining acronyms and concepts. -->
<!-- For syntax reference, see https://www.markdownguide.org/extended-syntax/. -->

## A
<dl>
  <dt>Acquiring bank</dt>
  <dd>Also known as acquirer. An acquiring bank is a financial institution that authenticates the card holder and authorises the transaction. It ensures that the card is valid and the card has sufficient funds to complete the transaction.</dd>
</dl>

## E
<dl>
  <dt>Exchange</dt>
  <dd>Instead of returning a payment, a seller can use an exchange with different goods than what was in the original sale, to refund a buyer.</dd>
</dl>

<dl>
  <dt>Extra amount tipping flow</dt>
  <dd>This flow prompts customers with a question before entering the tip amount. This tipping flow can be used when taking card payments using the Zettle SDK. See Total amount tipping flow.</dd>
</dl>

## I
<dl>
  <dt>Inventory balance</dt>
  <dd>The sum of all product items available at a specific location. The inventory balance for the store location type is usually the most important for integrations. See Location.</dd>
</dl>

<dl>
  <dt>Issuing bank</dt>
  <dd>Also known as issuer. An issuing bank is a bank or financial institution that offers payment cards. For example, credit and debit cards.</dd>
</dl>

## L
<dl>
  <dt>Liquid account</dt>
  <dd>A Zettle merchant account. It's used to hold funds that are ready to be paid out to merchants. After a transaction happens, the funds are recorded in the preliminary account while Zettle is checking whether the funds should be paid out. After that, the funds will be moved to and recorded in the liquid account while waiting to be paid out.</dd>
</dl>

<dl>
  <dt>Location</dt>
  <dd>The Inventory service keeps track of inventory balances by moving products between locations. These are created automatically when tracking is enabled for a product. A location can be a physical "Store", or virtual like "Sold", "Bin" (discarded products), or "Supplier" (for stock replenishment).</dd>
</dl>

<dl>
  <dt>Low stock threshold</dt>
  <dd>This is the minimum amount of inventory a merchant wants to have on hand. You can set the low stock threshold value through the Inventory API to help merchants manage their inventory.</dd>
</dl>

## M
<dl>
  <dt>Minor currency unit</dt>
  <dd>Also known as minor unit. A minor currency unit is the smallest unit of a currency. For example, for two-decimal currencies like US dollars, 199 with currency USD means $1.99 at Zettle. For zero-decimal currencies like Japanese Yen, 1095 with currency JPY means ¥1095 at Zettle.</dd>
</dl>

## P
<dl>
  <dt>Partial return</dt>
  <dd>A partial return means that goods that are part of an original sale are being returned. In such a case, an amount is normally resolved and refunded from the original payment. See Refund.</dd>
</dl>

<dl>
  <dt>Payment</dt>
  <dd>Corresponds to money being exchanged between seller and buyer as part of a sale. Can also be a “return of sale”, in which case payment is often referred to as refund.</dd>
</dl>

<dl>
  <dt>Preliminary account</dt>
  <dd>A Zettle merchant account. It's used to hold funds that are being checked by Zettle. After a transaction happens, the funds are recorded in the preliminary account while Zettle is checking whether the funds should be paid out. After that, the funds will be moved to and recorded in the liquid account while waiting to be paid out.</dd>
</dl>

<dl>
  <dt>Purchase</dt>
  <dd>The acquisition of an item or service that is typically paid for through an exchange of money or other asset.</dd>
</dl>

## R
<dl>
  <dt>Refund</dt>
  <dd>Money being exchanged as the result of a returned sale. Items or services from the sale are being returned, and money is transferred from the seller back to the buyer.</dd>
</dl>

<dl>
  <dt>Return</dt>
  <dd>When a customer sends an item back to your store or warehouse. Customers must usually return an item before they get a refund.</dd>
</dl>

## S
<dl>
  <dt>Sale</dt>
  <dd>A business event between a seller and a buyer. Normally means giving out some goods or services to a buyer, who in turn promises to somehow fund the seller.</dd>
</dl>

<dl>
  <dt>SKU</dt>
  <dd>A stock keeping unit (SKU) is a unique code for identifying and tracking products in the inventory or stock.</dd>
</dl>

<dl>
  <dt>Stock level</dt>
  <dd>The number of products a merchant needs to have at hand to fulfill customer orders and delivery expectations. Inventory management helps maintain the stock level as low as possible, and at the same time make products available when required. </dd>
</dl>

## T
<dl>
  <dt>Tipping rate limit</dt>
  <dd>Prevents entering of incorrect tipping amount in the Zettle card reader. Validation against the limit ensures that the tipping amount is not too high, for example if a customer enters their pin code by mistake. The validation also ensures that the tipping amount entered is higher than the total amount.</dd>
</dl>

<dl>
  <dt>Total amount tipping flow</dt>
  <dd>This lets customers enter the total amount, including tip, directly. This tipping flow can be used when taking card payments using the Zettle SDK. See Extra amount tipping flow.</dd>
</dl>

<dl>
  <dt>Tracking</dt>
  <dd>The Inventory service provides tracking of items in the product library. Tracking is applied to products for inventory balance calculations. This lets a merchant know how many items are available for selling, and if stock replenishment is needed. If tracking is enabled for a product, sales through the POS system are automatically tracked, and the inventory is updated accordingly.</dd>
</dl>

## V
<dl>
  <dt>VAT</dt>
  <dd>Value-added tax.</dd>
  <dt>Void</dt>
  <dd>If a payout or a transaction is made void, it means that they failed and therefore are not processed. </dd>
</dl>
