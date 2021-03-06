*****
Usage
*****

.. _Using product accounting categories:

Using product accounting categories
===================================

You set the accounting properties of a `Product <concept-product>` in the
product's accounting `Category <model-product.category>`.
You can only use product categories that have been specifically marked as
accounting categories for this.

How you decide to structure your accounting categories is very dependent on
what your products are, and how you want to group and manage them.

In a clothes company you may have some accounting categories for::

   Clothes
      Shirts
         Children
         Adults
   Shoes
      Children
      Adults

If you were using this structure then you could define different rates of
:abbr:`VAT (Value Added Tax)`, or :abbr:`GST (Goods and Services Tax)`,
for children's and adults' items.
It would also allow you to define different revenue
`Accounts <account:model-account.account>` for the revenue generated from the
sales of clothes and the revenue generated by selling shoes.
